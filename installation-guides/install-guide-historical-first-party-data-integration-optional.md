# Install Guide: Historical first-party data integration (optional)

Often our partners license their first-party data to outside partners. This process never actually shares your data with an outside party. It merely allows you to match your first-party data to their existing Identity Graphs and validate activity.&#x20;

All new customer registrations and newsletter signups will be automatically logged, and data will be encrypted (hashed) and stored with the customer record. However, GrowthCode needs a record for historical customers and asks that you provide a complete list of all email addresses (hashed or plain text) of any customer currently registered and/or receiving a newsletter. In turn, GrowthCode will identify those customers when they return to your site and utilize this information to increase monetization.&#x20;

Please provide this historical customer information as a file (excel, CSV, Gsheet, etc.).  Please include the following column headers:

|                                                                                       |          |
| ------------------------------------------------------------------------------------- | -------- |
| Hashed Sha 256 preferred but any format is acceptable) or Plain Text Email (REQUIRED) | REQUIRED |
| Registered User (OPTIONAL)                                                            | Yes/No   |
| Newsletter recipient (OPTIONAL)                                                       | Yes/No   |
| Original Registration Date (OPTIONAL)                                                 | MM/DD/YR |
| Last Registration Date (OPTIONAL)                                                     | MM/DD/YR |
| Last newsletter send date (OPTIONAL)                                                  | MM/DD/YR |
| Last Newsletter open date (OPTIONAL)                                                  | MM/DD/YR |

Complete your installation by inserting the provided Partner ID within the ‘pid’ variable and all the other parameters and placing it into your tag manager.
