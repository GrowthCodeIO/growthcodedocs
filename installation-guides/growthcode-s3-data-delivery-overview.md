---
description: >-
  Introduction: GrowthCode provides high-quality, actionable data to clients.
  Data is delivered daily to an AWS S3 bucket, enabling clients to access
  updated insights regularly. This document outlines o
---

# GrowthCode S3 Data Delivery Overview

***

**Delivery Methodology:** Data is delivered daily to a designated AWS S3 bucket in a structured format. This ensures:

* **Timeliness**: Data is refreshed daily (it can be provided more frequently for an additional fee).&#x20;
* **Consistency**: All datasets follow a standard partitioning structure (year/month/day).
* **Flexibility**: Clients can easily integrate data into their existing systems for analysis and decision-making.

***

### <mark style="color:orange;">Data Types and Structure</mark>

**Event** **Data**

* **Description**: Detailed records of user interactions, typically page views.
* **Partitioning**: Organized by year/month/day.
* **S3 Bucket Path**: s3://\<bucket-name>/type=event/
*   **Fields**:

    * time\_stamp: Timestamp of the event
    * partner\_id: Publisher partner ID
    * gcid: GrowthCode ID
    * uid: Publisher user ID
    * aa: User agent
    * ip: IP address
    * url: URL of the event
    * domain: Domain of the URL
    * referrer: Referring URL
    * region: GEO region
    * country: GEO country



**Audience Data**

* **Description**: Aggregated insights into audience segments.
* **Partitioning**: Organized by year/month/day.
* **S3 Bucket Path:** s3://\<bucket-name>/type=audience/
* **Fields**:
  * gcid: GrowthCode ID
  * id: Category ID
  * taxonomy: Taxonomy of the ID (IAB 2.2)
  * hits: Number of times the user is observed in the category

**IDs Data**

* **Description**: Comprehensive list of user IDs across various platforms.
* **Partitioning**: Organized by year/month/day.
* **S3 Bucket Path:** s3://\<bucket-name>/type=ids/
* **Fields**:
  * gcid: GrowthCode ID
  * uid: Publisher user ID
  * hem\_md5: MD5 HEM
  * hem\_sha1: HEM SHA-1
  * hem\_sha256: HEM SHA-256
  * panoramaid: Panorama ID
  * hadronid: Hadron ID
  * xandrid: Xandr ID
  * amxid: Adapt MX ID
  * liveintentid: LiveIntent ID
  * fabrickid: Fabrick ID
  * id5id: ID5
  * trackdeskid: TradeDesk UID1
  * sharedid: Shared ID
  * teadsid: Teads ID
  * ttacrossid: 33 Across ID
  * epsilonid: Epsilon ID

***

### <mark style="color:orange;">How to Utilize the Data</mark>

* Event Data: Analyze user behavior and interactions to optimize content strategies and user experiences.
* Audience Data: Build and refine audience profiles to enhance campaign targeting.
* IDs Data: Leverage cross-platform identifiers for advanced audience insights and personalization.

For additional support or inquiries about the data delivery process, please contact the GrowthCode team at support@growthcode.io.

### <mark style="color:orange;">Best Practices</mark>

* Regularly monitor your S3 bucket for new data updates.
* Implement automated data ingestion pipelines to streamline analysis.
* Use appropriate security measures to protect the integrity and confidentiality of the data.

***

### <mark style="color:orange;">Benefits of GrowthCode S3 Data Delivery</mark>

**Enhanced Insights**

* Access to granular event-level data for detailed analysis.
* Audience data enables precise targeting and segmentation.
* Comprehensive ID mapping supports multi-platform user tracking.

**Seamless Integration:**

* Data is delivered in a standardized format, making it easy to incorporate into existing workflows.
* S3 compatibility ensures smooth data ingestion into analytics and visualization tools.

**Scalability**

* Partitioned structure supports efficient data management and scalability as data volumes grow.

**Transparency and Consistency**

* Clearly defined fields and taxonomies ensure consistency across datasets, facilitating reliable analysis.
