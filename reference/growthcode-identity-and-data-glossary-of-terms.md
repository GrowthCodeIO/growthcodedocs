---
description: >-
  A quick outline of the key terms in the ecosystem as it relates to first-party
  data
---

# GrowthCode Identity & Data Glossary of Terms

## <mark style="color:orange;">Identity Graph/Identity Spine</mark>

***

### <mark style="color:orange;">Identity Spine</mark>

An identity spine is a term used in advertising and marketing to describe a comprehensive database of user profiles. This database includes various data points such as email addresses, phone numbers, device IDs, and other identifiers that can track users across different devices and platforms. Collecting and consolidating this data enables publishers and marketers to understand better and engage their audience.

#### <mark style="color:orange;">Value of an Identity Spine</mark>

* **Audience Understanding and Targeting:** The primary value of an identity spine lies in its ability to help publishers understand their audience more comprehensively. By tracking user behavior across multiple devices and platforms, publishers can build a complete picture of their audience, allowing for more relevant content and advertising.
* **Personalized User Experience:** An identity spine offers publishers a seamless and personalized experience across their platforms. Users benefit from features such as personalized recommendations, saved preferences, and customized content, which are consistent across different devices.
* **Enhanced User Engagement:** Utilizing an identity spine enables publishers better to understand user behaviors, interests, and preferences. This data can be used to deliver targeted and relevant content, increasing user engagement and satisfaction.

#### <mark style="color:orange;">Monetization Opportunities:</mark>&#x20;

The valuable user data collected through an identity spine can attract advertisers looking to reach specific audience segments. This precise targeting can lead to higher advertising revenues for publishers.

* **Reduced Friction:** Users can navigate different services and features within a publisher’s ecosystem more quickly, without needing separate logins or repeated authentication, providing a smoother user experience.
* **Data Consolidation and Insights:** An identity spine consolidates user data from various sources, providing valuable insights into user behavior, content preferences, and engagement patterns. Publishers can use these insights to optimize content strategies and make data-driven decisions.
* **Increased Security:** Implementing robust authentication and authorization protocols within an identity spine enhances security measures, protecting user data and mitigating risks of unauthorized access or data breaches.
* **CrossPlatform Reach:** Publishers can extend their reach across multiple platforms and devices. Users can access content and services seamlessly, whether on desktops, mobile devices, smart TVs, or other connected devices, ensuring a consistent experience.

By integrating and utilizing an identity spine, publishers can significantly enhance their capabilities in understanding and engaging with their audience. This will lead to more effective content delivery and increased monetization potential.\


## <mark style="color:orange;">Deterministic vs Probabilistic Identity</mark>

***

### <mark style="color:orange;">Deterministic Identity:</mark>

Deterministic identity graphs use explicit, verified data points such as email addresses, login information, or phone numbers to match and recognize individuals across devices and platforms accurately. These data points provide a high degree of certainty in user identification. Deterministic methods prioritize accuracy and recency, making them highly reliable but often limited in scale due to the requirement for direct user-provided information.

### <mark style="color:orange;">Probabilistic Identity:</mark>

Probabilistic identity graphs rely on algorithms to make educated guesses about user identities based on patterns and behaviors. These algorithms analyze data points like device types, IP addresses, and browsing habits to infer connections between devices and users. While probabilistic methods can create extensive identity graphs and scale efficiently, they risk inaccuracies as they deal with probabilities rather than certainties.

### <mark style="color:orange;">Key Differences:</mark>

#### <mark style="color:blue;">Accuracy vs. Scale:</mark>

* Deterministic methods are highly accurate because they use direct, verifiable data but may cover fewer users.
* Probabilistic methods can cover a broader audience by inferring connections, though they may sometimes need to be more accurate.

#### <mark style="color:blue;">Data Requirements:</mark>

* Deterministic identity requires explicit user data like email addresses or log in details.
* Probabilistic identity leverages indirect data like device characteristics and browsing patterns.

#### <mark style="color:blue;">Use Cases:</mark>

* Deterministic identity is preferred when high accuracy is crucial, such as in personalized marketing and secure user authentication.
* Probabilistic identity is useful for broad audience targeting and when deterministic data is unavailable.

### <mark style="color:orange;">Integration of Both Methods:</mark>

Many identity solutions integrate deterministic and probabilistic elements to balance accuracy and scale. For instance, a deterministic core might be expanded with probabilistic links to enhance the reach while maintaining a base level of accuracy.

### <mark style="color:orange;">Conclusion:</mark>

The choice between deterministic and probabilistic identity methods depends on the application's specific needs, the importance of accuracy versus scale, and the available data. Both approaches have advantages and can be effectively combined to optimize user identification and targeting strategies.\


## <mark style="color:orange;">Offline Data</mark>

***

"Offline data" refers to information collected from sources outside the online or digital environment. In the context of online advertising targeting, offline data typically includes data gathered from physical stores, customer surveys, loyalty programs, and other nondigital interactions.

This offline data can encompass various types of information, such as demographic details, purchase history, geographic location, preferences, and other relevant customer attributes. Marketers and advertisers utilize offline data to enhance their understanding of consumer behavior, create more accurate customer profiles, and improve the effectiveness of targeted advertising campaigns.

Advertisers can develop a more comprehensive view of their target audience by combining offline data with online data—such as website browsing behavior, online purchases, or social media interactions. This integrated approach allows them to deliver more relevant and personalized advertisements to consumers based on their offline activities, interests, and preferences.

## <mark style="color:orange;">PII, or Personally Identifiable Information</mark>

***

**Personally Identifiable Information (PII)** refers to any data that can be used to identify a specific individual. This information can include a variety of details that, either alone or in combination with other data, can uniquely distinguish one person from another. Common examples of PII include:

* &#x20;Full name
* &#x20;Social Security number
* &#x20;Email address
* &#x20;Home address
* &#x20;Phone number
* &#x20;Date of birth
* &#x20;Passport number
* &#x20;Driver's license number
* &#x20;Credit card information
* &#x20;Biometric data (such as fingerprints or facial recognition data)

In digital advertising and data management, PII is highly sensitive and subject to stringent regulations and privacy standards, such as the General Data Protection Regulation (GDPR) in Europe and the California Consumer Privacy Act (CCPA) in the United States. These regulations protect individuals' privacy rights and ensure their data is handled responsibly.

When handling PII, companies must implement robust security measures to protect this information from unauthorized access, breaches, and misuse. Additionally, they must obtain explicit consent from individuals before collecting, storing, or using their PII for any purpose, including advertising and marketing activities.

Protecting PII is crucial for maintaining consumer trust and compliance with legal requirements. Failure to adequately protect PII can lead to significant legal penalties, reputational damage, and loss of customer trust.\


## <mark style="color:orange;">Universal Identifiers and First-Party Data</mark>

***

Universal Identifiers (UIDs): Imagine a VIP card that grants access to exclusive areas across different websites. That's like a UID. However, there's a twist - these cards can be either:

* Salted: Each website creates a unique version of the card for a user. exclamation: Imagine the VIP card having a special flavor specific to each club (e.g., RampID, ID5).
* Unsalted: The card remains the same across websites, allowing for consistent user identification (e.g., Panorama ID, Xandr ID).exclamation

### <mark style="color:orange;">First-Party Data: The Treasure Trove of User Insights</mark>

This is the gold mine for online publishers! They gather all the information directly from users who visit their website or platform. Think of it as a detailed user profile built with various pieces:

* Demographic Data: Age, gender, location - the basics that paint a picture of who your audience is.
* Behavioral Data: This tracks a user's journey - what pages they visit, what they click on, how long they stay. It reveals their interests and how they interact with your content.
* Transactional Data: If a user makes a purchase, this data captures what they bought, how much they spent, and their purchase history.
* Preference Data: This unveils a user's likes and dislikes. What kind of content do they subscribe to? What topics keep them engaged?
* Contact Information: Email addresses and phone numbers (with permission, of course) are direct communication channels.

### <mark style="color:orange;">Why First-Party Data Matters</mark>

Imagine having a direct line to your audience, knowing their preferences and behavior. First-party data empowers publishers to:

* Personalize Content: Show users content they're likely interested in, keeping them engaged.
* Target Ads Effectively: Tailor advertisements to specific user profiles, leading to better conversions.
* Craft Stellar User Experiences: Understand user behavior to optimize website navigation and features.
* Develop Winning Marketing Strategies: Leverage data insights to create targeted campaigns that resonate with your audience.

The best part? First-party data is collected directly from users, making it more reliable and trustworthy than data from external sources.expand\_more It's a win-win for publishers who gain valuable audience insights and users who receive a more personalized experience.

### <mark style="color:orange;">First-Party Cookie:</mark>

A first-party cookie is a small text file that a website or online publisher creates and stores on a user's device when they visit their website. It's an HTTP cookie associated with the domain of the website being visited. Here are some key points about first-party cookies:

* **Purpose:** It is primarily used to remember user information and interactions with the website, enhancing the user experience and providing personalized services.
* **Information Stored:** This can store various data types, including login credentials, language preferences, shopping cart items, user settings, and other relevant data for website functionality or customization.
* **Duration:** This may have different expiration periods, such as expiring when the browser is closed (session cookies) or lasting for a specified time (persistent cookies) until manually cleared by the user.
* **Data Ownership:** This is created and controlled by the website or online publisher, giving them ownership and control over the stored data and its usage.
* **Privacy Considerations:** While less intrusive than third-party cookies, privacy concerns remain. Websites must inform users about cookie usage through privacy policies and provide options to manage or disable cookies.
* **Regulatory Compliance:** Compliance with data protection regulations like GDPR and CCPA is essential when collecting and processing data through first-party cookies.

First-party cookies are crucial in delivering personalized experiences, maintaining user preferences, and adhering to privacy regulations.

## <mark style="color:orange;">Third-Party Cookie:</mark>

***

A third-party cookie is a small text file created by a website other than the one the user is visiting. It's primarily used to track and collect user data across multiple websites for online advertising purposes. Here are some key points about third-party cookies:

* **Purpose:** Used to track user behavior across websites for advertising, targeting, and performance measurement.
* **Information Collected:** Includes user preferences, browsing history, demographics, and behavioral data.
* **Usage:** It is commonly used by advertising networks, analytics providers, and marketing companies to create personalized ads and target audiences.
* **Privacy Concerns:** Third-party cookies face scrutiny due to privacy concerns and user consent issues, leading to measures to limit or block them.
* **Alternatives:** Promotes privacy-centric alternatives like first-party cookies, contextual targeting, and other technologies for personalized content delivery without extensive user tracking.

## <mark style="color:orange;">Third-party Data</mark>

***

Third-party data refers to information collected by entities other than online publishers themselves. Here are some key points about third-party data:

* **Source**: Collected by external sources like data brokers, advertising networks, or platforms, then shared with publishers for various purposes.
* **Data Types:** Includes demographic information, browsing behavior, purchase history, social media activity, and other relevant data points for audience insights and targeting.
* **Usage:** Helps publishers understand their audience, target ads effectively, personalize content, and optimize user experiences.
* **Regulation:** Subject to privacy regulations like GDPR, impacting the availability and usage of third-party data.

Third-party data provides publishers with valuable insights but requires compliance with privacy regulations and evolving industry practices.



## <mark style="color:orange;">Contextual Advertising:</mark>

***

Contextual advertising in online marketing is a strategy advertisers use to deliver targeted ads based on the context or content of a webpage. Instead of relying on specific user data like demographics or browsing history, contextual targeting focuses on analyzing the keywords, themes, and overall context of the page viewed by a user in real time.

Here's an overview of how contextual targeting typically operates:

* **Content Analysis:** Sophisticated algorithms and natural language processing (NLP) techniques examine the text, images, and other relevant elements on a webpage to understand its topic, tone, and context.
* **Keyword Matching:** The algorithm identifies keywords and phrases pertinent to the advertising campaign or the target audience.
* **Ad Placement:** Based on the content analysis and keyword matching, the system selects and displays advertisements that are most relevant to the page's context, aiming to capture the interest of users visiting that page.

### <mark style="color:orange;">Contextual targeting offers several advantages for online advertisers:</mark>

* **Relevance**: By presenting ads aligned with the content of a webpage, contextual targeting increases the likelihood of reaching users already engaged with or interested in a particular topic or theme.
* **Brand Safety:** Advertisers can avoid specific content types or websites that do not align with their brand image, ensuring their ads are placed in suitable and secure environments.
* **Privacy-Friendly:** Unlike other targeting methods, which rely on individual user data, contextual targeting focuses on the content itself, minimizing concerns related to privacy and data protection.
* **Real-Time Adaptability:** Because contextual targeting operates in real time, ads can be dynamically matched to evolving content, enabling more timely and relevant ad placements.

Overall, contextual targeting empowers advertisers to deliver more precise and relevant ads to users based on the context of the web pages they visit, thereby enhancing the effectiveness of online advertising campaigns.



## <mark style="color:orange;">Data Segment</mark>

**Audience Segment:** In online advertising, an "audience segment" refers to a specific group of individuals who share similar characteristics or interests and are targeted for advertising campaigns. These segments are created based on various data points, such as demographics, behavior, interests, location, or any other relevant attributes.

By dividing the larger audience into smaller segments, advertisers can tailor their marketing messages and deliver more personalized and relevant ads to specific groups. Audience segments enable advertisers to focus their efforts on reaching the most relevant users, increasing the effectiveness and efficiency of their advertising campaigns.

Here are a few examples of audience segments commonly used in online advertising:

1. **Demographic segments:** These segments categorize users based on demographic information such as age, gender, income, education level, or marital status.
2. **Behavioral Segments:** Based on user behavior and actions, such as websites visited, search queries, content consumed, purchase history, or engagement with specific ads or campaigns.
3. &#x20;**Interest segments:** These segments group users based on their interests and preferences, which can be determined from their online activities, social media engagement, or interactions with specific content categories.
4. **Geographic segments:** These segments target users based on their location, which can be as broad as a country or as specific as a neighborhood or zip code.

Advertisers use audience segments to optimize their ad targeting strategies, allocate their budgets effectively, and maximize their advertising efforts' return on investment (ROI). By reaching the right audience with the right message at the right time, advertisers can increase the likelihood of engagement, conversions, and, ultimately, business success.



## <mark style="color:orange;">IAB Taxonomy</mark>

***

IAB stands for Interactive Advertising Bureau, an industry organization developing standards and guidelines for online advertising. The Interactive Advertising Bureau's IAB Taxonomy is a hierarchical classification system developed to categorize and organize digital advertising content.

The IAB Taxonomy provides a standardized framework for classifying and organizing digital advertising content, making it easier for advertisers, publishers, and ad tech platforms to understand and work with different types of online advertising. It helps organize and structure digital advertising inventory and also facilitates targeting and delivering ads to specific audiences.

The taxonomy includes a hierarchical structure with multiple levels of categories and subcategories. It covers various aspects of digital advertising, including ad formats, industry sectors, content types, and targeting methods. Each category within the taxonomy represents a specific aspect or attribute of digital advertising.

By using the IAB Taxonomy, advertisers and publishers can ensure that their ads are properly classified and aligned with relevant content. This can improve the targeting, relevance, and effectiveness of advertising campaigns. Additionally, it enables better data analysis and reporting, as the taxonomy provides a consistent and standardized way of categorizing digital advertising content across different platforms and systems.\


## <mark style="color:orange;">Wrapper (Header Bidding Wrapper, Wrapper Tag)</mark>

***

A prebid wrapper, also known as a header bidding wrapper or wrapper tag, is code implemented on a website to facilitate the execution of header bidding.&#x20;

Header bidding is an advertising technology that allows multiple ad exchanges to compete for ad impressions simultaneously before the webpage loads. Traditionally, publishers used a waterfall model, where ad networks bid one after another, resulting in suboptimal revenue and slower page load times. With header bidding, publishers can receive bids from multiple demand partners simultaneously and choose the highest bid in real-time.

A prebid wrapper is a container for all the header bidding codes from various demand partners or ad exchanges. It is placed in the header section of a webpage and makes requests to different ad exchanges, allowing them to participate in the bidding process. The wrapper collects bids from these exchanges and passes them to the publisher's ad server, selecting the winning bid to serve the ad.

The advantage of using a prebid wrapper is that it simplifies the implementation and management of header bidding. Rather than individually integrating the code of each demand partner, the publisher only needs to implement a single wrapper tag. The wrapper communicates with the exchanges, collects bids, and passes them to the ad server. Additionally, wrappers often provide features like bid caching, timeout management, and analytics, further enhancing the efficiency and effectiveness of header bidding.

Overall, a prebid wrapper streamlines the header bidding process, improves competition among demand partners, and helps publishers maximize their advertising revenue.\


## <mark style="color:orange;">Prebid (prebid.org)</mark>

***

Prebid.org is a project that supports digital advertising by offering free tools and resources to publishers and advertisers. It focuses on header bidding, a technology that allows websites and apps to get the best value for their ad space.

Think of it as a virtual auction where multiple advertisers bid to show their ads on a website or app. This creates healthy competition and ensures publishers can profit more from their advertising inventory.

Prebid.org provides software solutions that publishers can use to implement header bidding on their websites or apps. These tools help publishers take control of their advertising and maximize their revenue potential.

By using Prebid.org's tools, publishers can increase their chances of getting higher bids for their ad space. This means more revenue for them, which can support creating great content or improving their services.

The project also fosters collaboration and knowledge sharing among industry participants, promoting fairness and transparency in the digital advertising ecosystem. It helps advertisers and publishers work together more effectively to create a better online advertising experience for users.

In summary, Prebid.org is a project that offers free tools and resources to help websites and apps earn more money from their advertising. It does this by implementing header bidding, which allows advertisers to compete for ad space, resulting in better revenue for publishers.



## <mark style="color:orange;">RTD (Real Time Data) Wrapper/Module</mark>

***

An RTD prebid module is software used in programmatic advertising to improve the bidding process. It works within real-time bidding systems, where advertisers and publishers participate in auctions to buy and sell ad space.

The module focuses on using real-time data to make bidding decisions. It is part of a prebid framework publishers use to manage their advertising inventory.

The main job of an RTD prebid module is to collect and analyze real-time data about the ad inventory being auctioned. This data includes user behavior, demographics, device information, and other relevant details. Using this data, advertisers can make smarter bidding choices, leading to better targeting and campaign performance.

The RTD prebid module connects with data providers, demand side platforms, and ad exchanges to exchange data and bidding information. It accesses real-time data streams, applies algorithms and rules, and generates optimized bid responses based on available inventory and advertiser preferences.

In summary, an RTD prebid module is software that uses real-time data to improve the efficiency and effectiveness of bidding in programmatic advertising. It helps advertisers make informed decisions and achieve better results in their campaigns.\


## <mark style="color:orange;">Bid Enrichment / Bid Enhancement / Bid Decoration</mark>

***

Bid enrichment enhances bid requests with additional information linked to impressions, users, or contextual cues. This incremental data provides additional signals and valuable insights to demand partners (SSPs and DSPs), elevating the advertising experience for both advertisers and consumers and thereby increasing the impression value for the publisher. Critical elements in decorating the bid include universal IDs, IAB categories, and other acceptable data points.

Universal IDs, in particular, are becoming crucial components of bid decoration. With over fortyfive potential UIDs available, focusing on the most relevant ones is essential. Among the myriad options, around two dozen universal IDs stand out due to their high importance and frequent usage. Some commonly utilized universal IDs include ID5, Ramp ID, Panorama ID, Shared ID, Criteo ID, Hadron ID, 33Across, Transunion's Fabrik ID, Yahoo Connect ID, and several others.

Moreover, bid decoration can lead to higher ad viewability and clickthrough rates, as users are likelier to engage with relevant ads. This, in turn, can attract more advertisers to bid for your ad inventory, resulting in increased competition and potentially higher CPMs (cost per thousand impressions).

By embracing Bid Decoration, publishers can create a winwin situation. Advertisers benefit from better targeting capabilities, which increases their ad performance, while publishers can attract premium advertisers and generate higher revenue from their ad space.

It is important to ensure that the bid decoration process respects user privacy and adheres to applicable regulations and guidelines. Transparency and user consent are crucial to maintaining trust and providing a positive user experience.

In summary, bid decoration empowers publishers by enhancing the value of their ad inventory. It enables you to offer advertisers valuable insights about your audience, leading to more effective ad campaigns, increased revenue, and a better overall advertising experience for your users.

<figure><img src="https://lirp.cdn-website.com/0554e939/dms3rep/multi/opt/Screenshot-2023-10-13-at-10.44.33-AM-1920w.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:orange;">Linkage Data</mark>

***

Linkage data refers to the process of connecting or associating different pieces of information from various sources, typically to identify and link user profiles or data points across multiple platforms or systems. In the context of digital marketing and advertising, linkage data often involves the linking of a third-party cookie and a hashed email.

A third-party cookie is a small text file stored on a user's device by a website they visit, but a different domain manages it than the one being visited. Third-party cookies are commonly used for tracking and targeting purposes, allowing advertisers and marketers to collect information about a user's browsing behavior and interests across multiple websites

On the other hand, a hashed email refers to an email address that has been converted into a unique string of characters using a cryptographic hashing algorithm. Hashing is a one-way process that cannot be reversed to obtain the original email address. Hashed emails are often used as a privacy measure to pseudonymize or anonymize personal information.

When linking a third-party cookie and a hashed email, the process typically involves the following steps:

1. **Collection**: A user's email address is collected through a specific interaction or opt-in process on a website or application. The email address is then hashed using a hashing algorithm, generating a unique string of characters.
2. **Storage**: The hashed email and any other relevant user data or preferences are stored in a secure database or data management platform (DMP).
3. **Linking**: As the user interacts with different platforms or websites that utilize thirdparty cookies, the cookie data is collected and associated with the corresponding hashed email in the database. This linkage allows for aggregating user behavior and interests across multiple touch points.
4. **Analysis and Targeting:** The linked data can be used for analysis, segmentation, and targeting purposes in advertising and marketing campaigns. Advertisers can deliver more relevant and personalized content or advertisements by understanding the user's behavior and interests.

It's important to note that with increasing privacy concerns and regulatory changes, such as the General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA), the use of third-party cookies and hashed emails for linking user data is subject to compliance with applicable laws and regulations, as well as obtaining proper user consent and providing transparency regarding data usage and privacy practices.



## <mark style="color:orange;">Audience Curation</mark>

***

Audience curation refers to identifying, segmenting, and selecting a specific target audience for a digital advertising campaign. It involves analyzing various data points, such as demographics, interests, behaviors, and past interactions, to create a highly defined audience profile.

Audience curation aims to ensure that the advertising message reaches the most relevant and receptive audience, maximizing the campaign's effectiveness. By curating the audience, advertisers can deliver personalized and tailored content that resonates with the specific characteristics and preferences of the target audience, increasing the likelihood of engagement, conversions, and, ultimately, a higher return on investment (ROI).

Audience curation often involves using various tools and technologies, such as data management platforms (DMPs), customer relationship management (CRM) systems, and thirdparty data providers. These resources help advertisers collect, analyze, and leverage data to create audience segments or personas that align with their campaign objectives and messaging strategies.

Overall, audience curation plays a crucial role in optimizing digital advertising efforts. It ensures that the right message is delivered to the right people at the right time, leading to improved campaign performance and better overall results.

\
