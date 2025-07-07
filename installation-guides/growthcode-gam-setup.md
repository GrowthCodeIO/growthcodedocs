# GrowthCode GAM Setup

### <mark style="color:orange;">Key/Value Pair Setup</mark>

Publishers should configure a new key-value item in Google Ad Manager in their Google

Ad Manager reporting. The configuration in Google Ad Manager for Key-Value items can

be found under the section ‘Inventory -> Key Values.’

### <mark style="color:orange;">Create a custom dimension key-value pair using GAM.</mark>

This key value will track the GrowthCode Bid Enrichment Switchboard's performance compared to the control group. Its value must be isolated and independent, not shared or combined with other reporting purposes or features. Only the GrowthCode measurement script should set the values for this key-value item to ensure accurate reporting.\


1. The new key-value item will be named: ‘gc\_test’.&#x20;
2.  The following values should be copied and pasted into the Google Ad Manager UI for the new key/value item. (These values can all be pasted into the box as one batch):&#x20;

    true

    false
3. It should be marked as: "Predefined"\
   It should include:  "Include values in reporting & add key as custom dimension”

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdhV3l3s3S-smzynSQ4DdGZqjKRI08T437qrJV8xBT-KTDXhyiorDCGXHU3RzcuX9S3et30sjU16rjVI7dROt-gKF774yknUv1-ByZIx5QGaEq946z0uUNcCYGVIj0bUKtVBK3MfA?key=2xusgCVybLeo_m09_IN-TA" alt=""><figcaption></figcaption></figure>

## GrowthCode Reporting Setup

The final step is to configure automatically delivered reporting that breaks down the required metrics across the expected dimensions.\
&#xNAN;_**Note: Granting the GrowthCode team (adops@growthcode.net) access to your GAM allows us to handle the reporting aspect independently, and it is the preferred way to move forward.**_&#x20;

### <mark style="color:orange;">GrowthCode Bid Enrichment Report:</mark>

Alternatively, select the reporting options shown for the Eastern Time Zone, with a dynamic date range of yesterday, reporting in US Dollars as a flat report with a custom dimension containing gc\_test.&#x20;

<mark style="color:blue;">**Report 1:**</mark> \
**Email Subject:** GrowthCode Dashboard (PID:PARTNER\_ID,GAM:GAM\_ID) - Bidder Report (T7D)\
**Date range:** Last seven days\
**Dimensions:** gc\_test, Browser category, Date, Country\
**Metrics:** Total impressions, Total CPM and CPC revenue, Total ad requests\
**Filters:**\
&#xNAN;_&#x42;rowser category (is any of):_\
Chrome\
Microsoft Edge\
Firefox \
Safari

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdvJhQKYvXpBXlwyBvF3eF3fCm3-S05gZbkIv69CwY-0YIHhevXt6O7uBFLUT1a_p-8tH7sAlg9c7pqMSVzHAuPP2hmY6n5x1qyGi3M96lUnG_s-E-3FrK-u-wXYKcStOB8MFQs9Q?key=2xusgCVybLeo_m09_IN-TA" alt=""><figcaption></figcaption></figure>

<mark style="color:blue;">**Report 2:**</mark> \
**Email Subject:** GrowthCode Dashboard (PID:PARTNER\_ID,GAM:GAM\_ID) - Bidder Report (LI-T7D)\
**Date range:** Last seven days\
**Dimensions**: gc\_test, Line item type, Browser category, Date, Country\
**Metrics**: Total impressions, Total CPM and CPC revenue\
**Filters:**\
&#xNAN;_&#x42;rowser category (is any of):_\
Chrome\
Microsoft Edge\
Firefox\
Safari

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXecBLoL2KVDsV1B6qLt2sQYIEuPFakXWdKpqyMcqNnr0fUvxD60L0Q5h5naV3AHBcnXjz_JWDav646Z6LZ7bxy8eiUq32kaA6dgdf4GpHA7kPtD5WoBaMyEa1X5WoyaG4JWSIs7?key=2xusgCVybLeo_m09_IN-TA" alt=""><figcaption></figcaption></figure>

Then schedule the report to be automatically delivered daily as a .csv file:

* Cadence: Daily
* Send to: [adops@growthcode.net](mailto:adops@growthcode.net)
* Date range: a year from now
* **Important**: Include **Header** and **Include IDs**

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeLnj5mfH5RSwwFAxS6TJaNAUevHy4ASiI5zLP9P_LT2DHO0F319aOClYknAYYZpKR2P4fpeGM52ioEVuE86Y5UFuMZgaBwum20kPVS_skORyagLG-oE-m1ZpDoB-Ly54pkpICg?key=2xusgCVybLeo_m09_IN-TA" alt=""><figcaption></figcaption></figure>



