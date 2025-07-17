---
description: >-
  This guide outlines how GrowthCode and its partners measure Uplift when they
  enrich bids using their first-party graph
cover: >-
  https://images.unsplash.com/photo-1708607487609-45758252b5ee?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MTIxNjM3NDZ8&ixlib=rb-4.0.3&q=85
coverY: 0
---

# GrowthCode Bid Enrichment Uplift Measurement with Prebid Analytics

### OVERVIEW&#x20;

Publishers use GrowthCode’s Addressability Management Platform to increase revenue by enriching bid requests with Universal IDs and SSP IDs.

To evaluate Graph & Enrich performance, GrowthCode measures uplift and bid density, providing a clear understanding of the impact of bid enrichment and the incremental revenue it produces.

### A/B TESTING FOR UPLIFT

**What is A/B Testing?**

A/B testing (split testing) compares two groups to determine a variable's impact. GrowthCode uses this methodology to quantify the effect of Signal+ enhancements.

**GrowthCode’s Testing Methodology**

GrowthCode assigns users to audience cohorts and maintains their grouping for the duration of the test:

* **Control Cohort (10%):** No Universal IDs are injected into bid requests.
* **Active Cohort (90%):** Universal IDs are dynamically injected to enhance bid competitiveness.

### UPLIFT CALCULATION METHODOLOGY

GrowthCode calculates uplift using a straightforward and structured method:

1. Determine the total number of impressions in the **Control Cohort**.
2. Calculate the **eCPM of the Control Cohort** by dividing total revenue by total impressions.
3. Apply the same process to the **Test Cohort** to calculate its **eCPM**.
4. Measure the difference between the **eCPM values** of the Test and Control Cohorts to find the incremental revenue per thousand impressions.
5. Multiply the **incremental eCPM** by the total impressions in the Test Cohort to determine the **total uplift.**\


### MEASUREMENT & DASHBOARD

GrowthCode provides a dashboard for publishers to track:

* **Total Programmatic Revenue**
* **CPM**
* **Revenue Per Session (RPS)**
* **Bid Density**

Publishers can filter results by:

* **Time period**
* **SSP**
* **Browser**
* **Geography**

### BENEFITS OF USING PREBID ANALYTICS

* **Standardized Measurement:** Industry-consistent, bid-level insights.
* **Faster Insights:** Real-time auction performance analysis.
* **Publisher Control:** No reliance on GAM data.

### IMPLEMENTATION TIMELINE

Results typically stabilize within **14-21 days**. Publishers will have access to the updated dashboard and reporting tools as Prebid-based measurement rolls out.

For details or support, contact your GrowthCode representative.

\


_<mark style="color:orange;">NOTE: The Prebid “Asteroid” identity measurement module will be available shortly, and GrowthCode will add this testing tool to our services.</mark>_  &#x20;

\
