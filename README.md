# APIs-and-Data-Enrichment-with-LLMs

This repository contains my submission for a Data Engineering lab that explores the integration of external APIs and the enrichment of datasets using Large Language Models (LLMs). The assignment combined traditional data processing techniques with AI-powered insights to demonstrate the modern capabilities of intelligent data pipelines.

---

### Business Problem

In real-world data engineering, datasets are often incomplete or lack semantic meaning. The goal of this project was to demonstrate how external APIs (such as exchange rate or geocoding services) and LLMs (e.g., OpenAI models) can enhance the value of raw datasets by enriching them with contextual or generated information.

---

### Dataset Overview

The dataset consisted of simulated transactional records with customer locations and metadata, lacking readable labels or descriptions. The following types of data enrichments were explored:

- **Geolocation and Timezone Enrichment** using external APIs
- **Semantic Category Generation** using a Local LLM
- **Text Cleanup and Transformation** using Pandas and NumPy

---

### Project Objectives

- Perform data enrichment using open/public APIs
- Apply LLM-powered transformations to enhance column readability or derive categories
- Demonstrate integration of traditional and AI-based processing techniques in a single pipeline
- Validate the enriched data using exploratory data analysis (EDA)

---

### Solution Approach

1. **API Integration**
   - Used a mock or placeholder geolocation API to convert city names to country/timezone
   - Handled response parsing and edge-case errors using Python requests and conditionals

2. **LLM Integration**
   - Used local or simulated LLM calls to categorize user behavior or product types
   - Tokenized, cleaned, and mapped responses to structured columns

3. **Data Processing**
   - Used Pandas for dataframe manipulation
   - Performed sanity checks to ensure data consistency post enrichment

4. **Exploratory Data Analysis**
   - Analyzed the distribution of generated categories
   - Verified the value-add of each enrichment step through visual inspection

---

### Business Value

This lab demonstrates how modern data engineers can leverage AI and external APIs to enhance the richness and usability of raw data, yielding:

- Higher Quality Data Pipelines: By augmenting raw input with structured context
- Automation of Semantic Enrichment: Reducing manual labeling overhead
- Better Analytics and Business Insight: Thanks to more interpretable and complete data

---

### Challenges Encountered

- Handling unpredictable API responses
- Managing inconsistent field values and NaNs
- Simulating LLM enrichment without live API access

---
