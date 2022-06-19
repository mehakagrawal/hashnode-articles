## What is Recommendation System, How Does It Work, and What Are Its Types?

## Introduction

Hello, I'm [Mehak](mehakagrawal.bio.link) and in this article, I'll be explaining the recommendation system along with its types and how does it work for better understanding.

Not only e-commerce and retail enterprises but media, banking, and telecom industries are also harnessing the power of data to increase sales through the use of recommender systems integrated into their websites. These systems' use cases have been steadily rising. There is no better time than today to go further into this amazing machine learning technology.

## What is a recommendation system?

Recommender systems are systems that recommend things to the user based on a variety of factors. These systems predict the most likely product that users are likely to purchase and are interested in. Companies such as Netflix and Amazon use recommender systems to assist their users in identifying the best product or movie for them.

## How does a recommendation system work?

A recommendation system makes use of data and machine learning technology. Data is essential in the development of a recommendation system because it is the foundation from which patterns are derived. The more data it has, the better it will be at making relevant suggestions.

A recommendation system processes data in four stages, which are as follows:

1. Data Collection - This is the first and most critical step in developing a recommendation engine. Data collection might be explicit (product evaluations and comments) or implicit (page views, order history, etc.).

2. Storing - Once the data has been collected, it must be stored. The amount of data will become massive overtime. This necessitates the availability of enough scalable storage. Various methods of storage are available depending on the sort of data collected like NoSQL database, object storage, or standard SQL database.

3. Analyzing - The data must then be drilled down into and examined in order to be utilized. Data can be analyzed in a variety of ways. Among these are Real-time analysis, Batch analysis, and Near-real-time analysis.

4. Filtering - Data Filtering is the last stage. Depending on whether collaborative, content-based, or hybrid model recommendation filtering is employed, various matrixes or mathematical rules and formulas are applied to the data. The recommendations are the outcome of this filtering.

## Types of Recommendation System

There are three main types of recommendation systems –

### 1. Collaborative Filtering

This method is based on collecting and evaluating user behavior data. This includes anticipating what the user will like based on similarities with other users' online activity.

For example, if user A likes Shimla, Manali, and Goa and user B likes Shimla, Manali, and Coorg, they have comparable tastes. As a result, it is quite likely that A will like Coorg and B will like Goa. This is how collaborative filtering works.

There are two types of collaborative filtering techniques used:

- Item-based collaborative filtering - The recommendation rating of an item for a user is derived based on the ratings of that item by other similar users. The ratings are anticipated based on the ratings of nearby users.

- User-based collaborative filtering - The rating of an item is projected based on how that user has rated similar goods. The user's ratings on neighboring products are used to anticipate the ratings.

Advantages:
- The user might be introduced to new products.
- Business can grow and new items can be popularised.

Disadvantages:
- Depending on the sort of collaborative approach employed, the user's previous history or product data is necessary.
- If no one has purchased or rated the new item, it cannot be suggested.


### 2. Content-Based Filtering

This method is based on a product description and a profile of the user's preferred selections. Products are specified using keywords in this recommendation system, and a user profile is created to reflect the type of thing this user prefers.

For example, if a user enjoys watching movies like Captain America, the recommender system will suggest movies in the action genre or films about Chris Evans.

The key assumption of content-based filtering is that if you like one item, you will enjoy another.

Advantages:
- The user is recommended goods that they enjoy.
- The type of recommendation satisfies the user.
- New items can be suggested; all that is required is data for that item.

Disadvantages:
- The consumer will never be advised to purchase further things.
- Because the user does not try a different sorts of goods, the business cannot grow.
- The cosine similarity matrix must be generated again whenever the user matrix or item matrix is modified.

### 3. Hybrid Recommendation System

To offer a greater choice of products to clients, hybrid recommendation systems use both content-based and collaborative filtering simultaneously. This recommendation system is new and is believed to deliver more accurate recommendations than existing recommender systems.

Netflix is a good example of a hybrid recommendation system. It provides recommendations by comparing users' viewing and browsing behaviors and locating comparable people on that platform. Netflix employs collaborative filtering in this manner.

Netflix employs content-based filtering by proposing shows/movies that share characteristics with those that the user has rated highly. They can also veto common difficulties in recommendation systems, such as cold start and data inadequacy.

### Wrapping Up

In today's digital world, adding recommendations to systems is a worthwhile investment. Recommendation systems not only improve user experience and engagement but also increase income for organizations.

