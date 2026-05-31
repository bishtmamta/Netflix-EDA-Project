# 🎬 Netflix Exploration & Sentiment Analysis – EDA Project

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and Sentiment Analysis of Netflix data to understand the factors that influence content popularity and audience reception.

The analysis explores how content types (movies vs. TV shows), genres, country of origin, IMDb ratings, and viewer reviews impact overall engagement. The workflow includes data cleaning, feature engineering, statistical hypothesis testing, and natural language processing (NLP) for sentiment evaluation.

---

# 🔍 Key Findings

### 1. Sentiment heavily drives popularity
Positive viewer reviews and high qualitative sentiment scores create a statistically significant boost to overall content success.

### 2. Movies dominate the platform volume
The available inventory shows that movies significantly outnumber TV shows/web series on Netflix[cite: 1].

### 3. Genre preferences are highly centralized
Drama and Comedy are verified as the most frequently watched and dominant genres across the entire platform[cite: 1].

### 4. Higher ratings yield massive traction
Titles with strong IMDb ratings display consistently higher user engagement levels and viewer retention[cite: 1].

### 5. Production distribution is skewed
Regional content analysis highlights that title distribution is heavily centralized, with a few top countries producing the majority of the content[cite: 1].

---

# 🛠️ Tech Stack & Libraries Used

* **Language:** Python 3.x
* **Data Processing:** pandas, numpy[cite: 1]
* **Data Visualization:** matplotlib, seaborn[cite: 1]
* **Statistical Logic:** scipy.stats[cite: 1]
* **Deep Learning / NLP:** tensorflow.keras (Tokenization & Sequence Alignment)[cite: 1]

---

# 📂 Project Workflow

## 1. Data Understanding
* Dataset structure analysis (8,807 rows, 12 features)[cite: 1]
* Data types inspection & missing value profiling (`director`, `cast`, `country` gaps)[cite: 1]

## 2. Data Cleaning
* Handling missing strings by categorizing them as `"Unknown"` or `"Not Available"`[cite: 1]
* Imputing missing values in numerical/categorical metrics using statistical Mode (`.mode()[0]`)[cite: 1]

## 3. Feature Engineering
Created new features to unlock temporal and structural insights:

### Content Age
Calculated to evaluate old vs. new content trends relative to the baseline year:
$$\text{Content Age} = 2026 - \text{release\_year}$$

### Movie Indicator (Is Movie)
Binarized categorical content type into a machine-learning-ready format:
$$\text{Is Movie} = \begin{cases} 1, & \text{if Type} = \text{'Movie'} \\ 0, & \text{otherwise} \end{cases}$$

### Temporal Demographics
Extracted `year_added` and `month_added` from raw date strings to map seasonal release patterns[cite: 1].

---

# 📈 Visualizations Included

* **Bar Charts & Countplots:** Content type distribution and top producing countries[cite: 1].
* **Histograms & KDE Plots:** Distribution of content age and rating patterns[cite: 1].
* **Correlation Heatmaps:** Relationships between IMDb ratings, vote counts, and sentiment scores[cite: 1].
* **Word Clouds / Sentiment Trends:** Visualizing positive vs. negative audience feedback[cite: 1].

These visualizations help analyze:
* Growth of content over the years[cite: 1]
* Dominant genres and their audience engagement[cite: 1]
* Global distribution of Netflix content[cite: 1]
* Impact of user sentiment on a title's baseline success[cite: 1]

---

# 📊 Conclusion

The project demonstrates that a title's success and presence on Netflix are strongly influenced by:
* Content type and genre alignment[cite: 1]
* User sentiment and active review feedback[cite: 1]
* Geographic and regional production hubs[cite: 1]
* Critical reception (IMDb ratings and vote counts)[cite: 1]

The analysis highlights how data-driven insights and sentiment markers can be leveraged to optimize content acquisition and recommendation systems[cite: 1].
