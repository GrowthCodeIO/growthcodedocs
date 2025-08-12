# Installation Instructions: GrowthCode Universal ID Module (UIM)

### <mark style="color:orange;">Installation of Resolution Sync Tag</mark>&#x20;

This guide provides step-by-step instructions for integrating the GrowthCode script into your website. Proper installation ensures accurate data collection and audience segmentation for optimized monetization.

#### Step 1: Add the GrowthCode Script to Your Website

1. Copy the GrowthCode script provided to you.
2. Replace **PARTNER\_ID** with the unique ID provided by GrowthCode.
3. Paste the script **as high as possible** in the \<head> section of every page of your site.
4. Alternatively, insert the script using a **tag manager** (e.g., Google Tag Manager).

```
<script type="text/javascript"> 
var _gcio = window._gcio = window._gcio || []; 
var pid = "PARTNER_ID"; 
var uid = "YOUR USER ID";    // Optional
var tcf = "USER TCF STRING"; // Optional 
var nl = true; 
(function() { 
var u="//p.gcprivacy.com/t/"; 
_gcio.push(['pid', pid]); 
_gcio.push(['uid', uid]);        // Optional
_gcio.push(['tcf', tcf]);        // Optional
var d=document, g=d.createElement('script'), 
s=d.getElementsByTagName('script')[0]; 
g.type='text/javascript'; g.async=true; g.src=u+'gcid_s.min.js'; s.parentNode.insertBefore(g,s); 
})(); 
</script>
```

#### Step 2: Compatibility with CMPs and CAPTCHA Systems

* If your site uses a Consent Management Platform (CMP) or CAPTCHA system, you must whitelist the User-Agent below to allow proper tracking

```
FirstParty.id Contextual (https://firstparty.id)
```

#### Step 3: Passing Hashed Email Data (h1, h2, h3 Parameters)

Publishers with a CDP, DMP, or proprietary identity system can enhance their audience matching by passing hashed email values to GrowthCode using the H1, H2, and H3 parameters.

These parameters allow you to send hashed emails using industry-standard encryption methods:

* h1: MD5
* h2: SHA-1 (No longer used)
* h3: SHA-256



**How It Works:**

* Suppose a publisher can access user emails via a customer data platform (CDP), data management platform (DMP), or other proprietary system. In that case, they can hash those emails before passing them through the GrowthCode script.
* GrowthCode will use these values to match users across the ecosystem without relying on third-party cookies.
* This improves identity resolution and enables better audience segmentation, monetization, and targeting across programmatic channels.

**Implementation Example:**

When implementing the script, modify it to include the hashed email values where applicable:

```
<script type="text/javascript"> 
var _gcio = window._gcio = window._gcio || []; 
var pid = "PARTNER_ID"; 
var uid = "YOUR USER ID";    // Optional
var tcf = "USER TCF STRING"; // Optional 
var nl = true; 
(function() { 
var u="//p.gcprivacy.com/t/"; 
_gcio.push(['pid', pid]); 
_gcio.push(['uid', uid]);        // Optional
_gcio.push(['tcf', tcf]);        // Optional
_gcio.push(['h1', ‘hashed email’]);        // Optional (Email Hash - MD5)
_gcio.push(['h3', ‘hashed email’]);        // Optional (Email Hash - SHA-256)
var d=document, g=d.createElement('script'), 
s=d.getElementsByTagName('script')[0]; 
g.type='text/javascript'; g.async=true; g.src=u+'gcid_s.min.js'; s.parentNode.insertBefore(g,s); 
})(); 
</script>
```

#### <mark style="color:blue;">Resolution Sync Parameters</mark>&#x20;

| **Parameter**  | **Description**                                  |          |
| -------------- | ------------------------------------------------ | -------- |
| pid            | Partner ID (Provided by GrowthCode)              | required |
| uid            | Partner User ID (Your User ID)                   | optional |
| tcf            | GPP IAB TCF Version 2.0 String (EU) - Specs      | optional |
| tcfca          | GPP IAB TCF Version 1.0 String (Canada) - Specs  | optional |
| usprivacy      | GPP IAB CCPA/USP v1 - Specs                      | optional |
| nl             | Newsletter Processing (true/false)               | optional |
| h1             | Hashed email - MD5                               | optional |
| h3             | Hashed email - SHA256                            | optional |

More information about IAB Global Privacy Platform (GPP) at [https://github.com/InteractiveAdvertisingBureau/Global-Privacy-Platform](https://github.com/InteractiveAdvertisingBureau/Global-Privacy-Platform)

#### <mark style="color:blue;">Example Code for Tag Installation</mark>

**NOTE:  Google Tag Manager or placement of the native script on all pages.**

