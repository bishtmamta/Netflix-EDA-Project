# 🎬 Netflix Exploration & Sentiment Analysis – EDA Project

## 📌 Project Overview

This project focuses on a comprehensive framework for Exploratory Data Analysis (EDA) and Sentiment Analysis of Netflix content. Based on academic literature research, it maps out how key performance indicators like IMDb ratings, genres, and regional distributions impact structural audience trends.

The workflow translates these research guidelines into practical Python data setups, handling data structures, analyzing missing profiles, and plotting categorical distributions.

---

# 🔍 Key Hypotheses & Framework
*Based on the research paper framework included in the analysis:*

1. **IMDb Rating vs. Netflix Popularity:** Higher-rated titles see an exponential spike in audience traction and engagement.
2. **Genre Dominance:** Core genres like *Drama* and *Comedy* secure significantly higher user engagement.
3. **Volume Breakdown:** Movies are hypothesized to vastly outnumber TV Shows/web series within the active platform inventory.
4. **Sentiment Impact:** Positive qualitative review sentiments create a statistically significant boost to structural content success.
5. **Geographical Skew:** Production data is heavily centralized, with a few dominant regional countries contributing the major share.

---

# 🛠️ Tech Stack & Libraries Used

* **Language:** Python 3.x
* **Data Processing:** pandas, numpy
* **Data Visualization:** matplotlib, seaborn
* **Statistical Logic:** scipy.stats
* **Deep Learning Framework:** tensorflow.keras (For planned sentiment classification & tokenization workflow)

---

# 📂 Project Workflow

## 1. Literature Review & Matrix Mapping
* Detailed analysis of the paper *"Exploratory and Sentiment Analysis of Netflix Data"*.
* Established a **Key Determinant Factors Matrix** mapping variables (IMDb Ratings, Reviews, Votes, Country) to their impact on platform popularity.

## 2. Data Understanding & Structural Inspection
* Loading and reading the core dataset (`netflix_titles.csv`).
* Inspecting structural profiles, tracking active features, and checking total instances (8,807 rows and 12 columns).
* Identifying missing value columns (`director`, `cast`, `country`) to prepare for data cleaning pipelines.

## 3. Categorical Distribution & Visualization
* Building initial data plots using `seaborn` and `matplotlib`.
* Visualizing the absolute distribution gaps between **Movies** vs. **TV Shows** to verify the core volume hypotheses.

---

# 📈 Visualizations Included / Planned

* **Countplots:** Categorical frequency distribution of content types (Movies vs. TV Shows).
* **Geospatial & Country Distribution:** Mapping the concentration of international production hubs.
* **Correlation Maps:** Evaluating interactions between ratings, metrics, and sentiment trends.
* **Word Clouds:** Visualizing positive vs. negative audience feedback based on text data.

---

# 📊 Conclusion

The project effectively demonstrates that a streaming platform's success is highly data-driven rather than spontaneous. Audience engagement is deeply influenced by regional preferences, genre dominance (Drama/Comedy), and metric baselines like IMDb ratings. Ultimately, integrating advanced Sentiment Analysis with Exploratory Data Analytics acts as a potent tool for content acquisition, allowing platforms to strategically fill library gaps and optimize viewer retention.

  
