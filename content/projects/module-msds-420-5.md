---
title: "Yelp Business Graph Analysis with EdgeDB"
date: 2025-06-08
draft: false
weight: 14
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project uses EdgeDB to explore graph-relational modeling and querying on a Yelp business and review dataset from Chicago. It focuses on modeling relationships among users, businesses, and reviews to uncover insights about customer sentiment and local engagement patterns.

<!--more-->

Developed as part of the MSDS 420 course at Northwestern University, this work demonstrates practical graph-based querying strategies and evaluates EdgeDB’s expressiveness compared to traditional relational and document databases.

⸻

### 🔧 Features

- **Schema Design:** Defines a normalized graph schema using `Link` and `Multi-Link` types in EdgeDB.
- **Data Ingestion:** Loads CSV data into EdgeDB, transforming flat rows into a connected object model.
- **Graph Queries:** Retrieves insights such as most-reviewed businesses, average ratings, and reviewer activity.
- **Comparison Discussion:** Reflects on the benefits of EdgeDB’s graph-relational structure over traditional SQL and NoSQL models.

⸻

### 💡 Key Insight

> Graph-relational databases like EdgeDB blend the structure of SQL with the expressiveness of graph queries, enabling deeper insights from naturally connected datasets such as customer reviews.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
