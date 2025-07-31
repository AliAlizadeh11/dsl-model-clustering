# DSL for Data Clustering

## Overview

In today's fast-paced digital world, **data** is one of the most valuable assets for organizations and businesses. Extracting insights from data through analysis and processing is critical for intelligent decision-making. Among various data analysis techniques, **clustering** stands out as a powerful unsupervised learning method used to group similar data points into clusters.

This project introduces a **Domain-Specific Language (DSL)** tailored specifically for data clustering tasks. The DSL is designed to simplify the process of defining, executing, and analyzing clustering algorithms using a human-readable syntax.

---

## Features

- ✅ **User-friendly DSL** for clustering operations  
- 🧠 Supports popular clustering algorithms:
  - `K-Means`
  - `DBSCAN`
  - `Agglomerative Clustering`
  - `Spectral Clustering`
- 📊 Load and visualize datasets easily
- ⚙️ Customize algorithm parameters through simple DSL commands
- 📈 Graphical representation of clustering results
- 🛠️ Built using [ANTLR](https://www.antlr.org/) for grammar parsing and AST generation
- 🧩 Includes a **Custom Listener** to generate and traverse Abstract Syntax Trees (AST)
- 🚀 High extensibility for researchers, data scientists, and students

---

## Motivation

Due to the complexity and diversity of clustering algorithms, using a DSL provides a powerful abstraction layer. Users can define clustering workflows without deep knowledge of programming or machine learning internals.
