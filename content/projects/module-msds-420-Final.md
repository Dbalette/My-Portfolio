---
title: "Database-Driven Yelp Analytics"
date: 2025-06-08
draft: false
weight: 20
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

This project uses EdgeDB to construct a graph-relational schema over Yelp’s business and review data, enabling advanced queries and structured analytics. Built for the MSDS 420-3 course, it highlights database design, data modeling, and query optimization.

<!--more-->

Yelp’s raw data is transformed into a semantic knowledge graph that connects businesses, users, and reviews through typed relationships. From here, advanced queries reveal spatial patterns, user preferences, and categorical trends across Chicago’s business ecosystem.

⸻

### Features

- **Graph-Relational Modeling:** Implements a hybrid data model using EdgeDB to connect relational tables with graph relationships.
- **Normalized Schema:** Structures Yelp data into entities like `Business`, `User`, and `Review`, with integrity constraints and indexes.
- **Advanced Querying:** Demonstrates queries using EdgeQL to extract insights like top-rated categories, prolific reviewers, and spatial outliers.
- **Chicago-Focused Analytics:** Filters the dataset to spotlight insights from Yelp businesses located in Chicago, IL.
- **Visualization:** Exports data to CSV for visualization of review patterns, business clusters, and user sentiment analysis.

⸻

### Key Insight

> Database-first AI products require intentional design. This project shows how structuring and enriching data upfront leads to faster, deeper insights, with less reliance on LLM guesswork.

[View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
