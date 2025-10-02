

## Project Overview

[cite_start]This is a **data analysis project** focused on the **Netflix content catalog** (`netflix1.csv`)[cite: 3, 4]. [cite_start]The project aims to provide valuable insights into content strategy, audience demographics, and production trends[cite: 3].

[cite_start]The core goal is to analyze the content catalog to uncover key trends in content type, production, and distribution over time[cite: 4]. [cite_start]This analysis will ultimately provide **strategic recommendations** for content investment and geographical expansion[cite: 5]. [cite_start]The final analysis dataset contains **8,790 rows and 10 columns**[cite: 12, 25].

---

## Tools and Techniques

The project uses a mix of tools for the complete data pipeline:

* [cite_start]**Power BI / Excel:** Used for data cleaning, modeling, and creating the final **Dashboard**[cite: 7].
* [cite_start]**SQL:** Used for **querying and aggregating data**[cite: 8].
* [cite_start]**Python (Pandas):** Employed for **Deeper Exploratory Data Analysis (EDA)** and forecasting[cite: 9].

---

## Process

The project is executed in three main phases:

### [cite_start]1. Data Cleaning and Pre-processing [cite: 11]

[cite_start]The initial steps revealed a clean structure but required several transformations for effective analysis[cite: 12]. Key cleaning actions include:

* [cite_start]**Handling Missing Values:** Replacing 'Not Given' with 'Missing' in the `director` column and 'Unknown' in the `country` column[cite: 13].
* [cite_start]**Splitting Columns:** Splitting multi-country entries (e.g., 'United States, Canada') to count each country individually[cite: 13].
* [cite_start]**Date Transformation:** Converting `date_added` to `datetime` objects and extracting `add_year` and `add_month` for time-series analysis[cite: 13, 26].
* [cite_start]**Duration Parsing:** Splitting the `duration` column into `Duration_Value` (numeric) and `Duration_Unit` ('min' or 'Season')[cite: 13, 26].
* [cite_start]**Genre Expansion:** Splitting the comma-separated `listed_in` (genre) entries into individual rows for genre-level analysis[cite: 13, 27].

### [cite_start]2. Data Analysis and Visualization [cite: 14]

[cite_start]The analysis focuses on five key areas to generate impactful visualizations[cite: 15, 16]:

| Focus Area | Metric/Analysis | Insight Goal |
| :--- | :--- | :--- |
| **Content Mix** | Ratio of Movies vs. TV Shows and their trend over time. | [cite_start]Understand the platform's primary content focus and recent changes[cite: 17]. |
| **Geographic Focus** | Top 10 Content Producing Countries. | [cite_start]Identify key markets for production and assess geographical diversity[cite: 17]. |
| **Content Growth** | Number of Titles Added to Netflix by Year. | [cite_start]Visualize the platform's expansion and growth rate[cite: 17]. |
| **Genre Popularity** | Top 10 Most Popular Genres. | [cite_start]Guide future investment in high-demand genres[cite: 17]. |
| **Movie Duration** | Distribution of Movie Durations (in minutes). | [cite_start]Find the optimal/most common movie runtime[cite: 17]. |

### [cite_start]3. Project Report Structure [cite: 18]

[cite_start]The final output is a comprehensive report structured to deliver maximum strategic value to stakeholders[cite: 19]. The structure includes:

* [cite_start]**Executive Summary:** Objective, Key Finding Snapshot, and Actionable Recommendations[cite: 20, 21, 22, 23].
* [cite_start]**Data Overview:** Description, Cleaning Summary, and Initial Observations[cite: 24, 25, 26, 27].
* [cite_start]**Key Visualizations:** Presentation of the 5 charts with captions[cite: 28, 29, 30].
* [cite_start]**Analytical Findings:** Detailed discussion on Content Strategy, Geographical Concentration, Audience Segmentation (via Ratings), and Genre Deep Dive[cite: 31, 32, 33, 34, 35, 36].
* [cite_start]**Strategic Recommendations:** Business actions derived from the analysis, covering Content Focus, Market Expansion, Genre Investment, and Content Length Optimization[cite: 37, 38, 39, 40, 41, 42].
* [cite_start]**Conclusion:** Summarizing the achievement of the objective and confirming the primary findings[cite: 43, 44, 45, 46, 47, 48].

---

## Key Insights

The analysis confirmed several critical points about the Netflix catalog:

* [cite_start]**Content Focus:** Netflix remains **primarily a movie platform**, with films constituting the majority of the total catalog[cite: 45].
* [cite_start]**Expansion Phase:** The **aggressive increase in titles added yearly**, especially in recent years, signals a decisive expansion phase[cite: 46].
* [cite_start]**Geographical Concentration:** Content sourcing is **highly concentrated**, with the **United States and India** serving as the indisputable production leaders[cite: 47].
* [cite_start]**Genre Popularity:** The high prevalence of **International TV Shows, Dramas, and Comedies** highlights the core genres driving current audience engagement[cite: 48].

---

## Strategic Recommendations

The analytical findings translate into specific business actions for content stakeholders:

* [cite_start]**Content Focus:** Recommend a target ratio for future investment (e.g., shifting from a 70/30 Movie/TV Show ratio to 60/40) to capitalize on the success of TV series[cite: 39].
* [cite_start]**Market Expansion:** Suggest specific countries (e.g., **Brazil, Turkey, Mexico**) as high-potential targets for original content co-production[cite: 40].
* [cite_start]**Genre Investment:** Advise on prioritizing investment in high-performing genres like **'International TV Shows' or 'Documentaries'** while exploring potential gaps in underrepresented categories[cite: 41].
* [cite_start]**Content Length Optimization:** Based on the Movie Duration Histogram, recommend an **ideal runtime** for future movie acquisitions or productions[cite: 42].
