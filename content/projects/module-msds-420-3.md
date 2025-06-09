---
title: "Chicago Yelp Graph Database Analysis"
date: 2025-06-08
draft: false
weight: 12
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project explores the use of EdgeDB to model and analyze a real-world graph-relational dataset — Yelp businesses and reviews from the Chicago metro area. Built for the MSDS 420-3 Databases course at Northwestern University, the notebook walks through schema design, data loading, and analytical queries over a semi-structured dataset.

<!--more-->

By adopting EdgeDB, the project illustrates how flexible, queryable schemas can unlock new dimensions of insight — blending the rigor of relational databases with the adaptability of graph systems. Business metadata, category tags, and review sentiment are cross-linked to enable multi-hop queries that mimic human curiosity.

⸻

### 🔧 Features

- **Graph Schema Design:** Models Yelp businesses, users, reviews, and locations as typed relations and links in EdgeDB.
- **Data Ingestion:** Loads cleaned JSON data into EdgeDB and validates schema integrity.
- **Query Language Mastery:** Uses EdgeQL for pattern-matching and filtering — including aggregates, conditional expressions, and nested structures.
- **Review Sentiment & Trends:** Analyzes how review scores and comment patterns shift across neighborhoods and categories.
- **Graph Navigation:** Demonstrates multi-hop joins between users → reviews → businesses → locations.

⸻

### 💡 Key Insight

> SQL-based tools dominate enterprise analytics, but graph-relational platforms like EdgeDB offer a more natural fit for richly connected data. This project shows how the right data model can turn flat tables into exploratory engines for user and business insight.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
