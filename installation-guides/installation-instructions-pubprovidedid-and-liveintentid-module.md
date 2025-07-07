# Installation Instructions: PubProvidedID & LiveIntentID Module

The PubProvidedId module supports the GrowthCode on-page script (above). This module provides real-time capabilities for segmenting audiences based on context (using IAB Taxonomy 2.2, cattax: 6). It also offers HEMs (Header Enrichment Modules) that can smoothly integrate with your existing Prebid setup, making it simple to optimize your advertising strategies. The LiveIntentId module provides the functionality of LiveIntent’s Connect ID system. LiveIntent requires their module to be locally installed, unlike other modules that support a server-to-server environment.

### <mark style="color:orange;">PreBid Module Requirements</mark>

* Prebid <= Version 8.00.0
* GrowthCode HEM Resolution Sync Installed

#### <mark style="color:orange;">Building Prebid with PubProvided Id Support</mark>

Compile the PubProvided ID module into your Prebid build:

{% code overflow="wrap" %}
```
$ gulp serve --modules=userId,pubProvidedIdSystem,liveIntentIdSystem,<Any other Bid Adapters>
```
{% endcode %}

#### <mark style="color:orange;">Code in your Prebid Config</mark>&#x20;

| <p>pbjs.setConfig(</p><p>    . . .</p><p>    userSync: {</p><p>       . . .</p><p>       "syncsPerBidder": 5,</p><p>       "syncDelay": 3000,</p><p>       "auctionDelay": 0,</p><p>       . . .</p><p>      </p><p>       userIds: [</p><p>         . . .</p><p>         {</p><p>             name: "pubProvidedId",</p><p>             params: {</p><p>                 eidsFunction: growthCodeEids,</p><p>             }</p><p>         },</p><p>         . . .</p><p>       ]</p><p>    }</p><p>    . . .</p><p> }</p> |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

#### <mark style="color:orange;">LiveIntendId Prebid Config</mark>&#x20;

There is no prebid config for LiveIntent in prebid, the integrated LiveIntent script will take care of the config in prebid. If you have your own Publisher ID or Distributor ID please let Growthcode know. \
\
[This link](https://content.zetaglobal.com/i/gAjk___54O50JWernIjQ8CrnIMMyH6vwjofmA6HZPLUSSIGNf7utPLUSSIGNeMBkYTi3WzEuAEa388EKRFH7le14J6PNJYP5lHRRDEgFFge92suPLUSSIGN8xYhT1VwZqyUfyrI___2KWm3NcfpClDErA) contains all the most up-to-date information about installing LiveIntent
