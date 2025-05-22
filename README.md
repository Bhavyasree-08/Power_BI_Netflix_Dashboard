# Power_BI_Netflix_Dashboard
# 🎬 Netflix Data Analysis & Visualization Project

This repository contains the complete data analysis pipeline, datasets, and visualizations for a deep dive into Netflix’s content library. The goal was to understand *streaming content trends, **audience patterns, and **catalog structure* using real-world data.

---

## 📌 Project Overview

This project demonstrates the full data lifecycle from cleaning raw Netflix data to generating dynamic, business-driven insights using *Python* and *Power BI*.

### 🔍 Objectives
- Analyze the distribution of content types (Movies vs TV Shows)
- Identify most active countries and directors
- Explore relationships between cast members, content ratings, and durations
- Visualize global content production and viewer-targeted categorization

---

## 🧱 Dataset Pipeline

### 📁 Raw & Cleaned Files
| File | Description |
|------|-------------|
| Netflix_data.csv | Original raw dataset |
| Netflix_data_cleaned.csv | Null values handled, standardized columns |
| Netflix_data_cleaned_final.csv | Final cleaned version with engineered features |
| netflix_data_normalized.csv | Exploded fields for multi-label columns like genre, country |

### 🧪 Derived / Analysis DataFrames
| File | Purpose |
|------|---------|
| type_data.csv | Movie vs TV Show count |
| tv_shows_by_country.csv | Distribution of content by country |
| top_directors.csv | Release count by director |
| avg_duration_by_rating.csv | Average duration grouped by rating |
| cast_data.csv | Exploded and normalized cast data |
| frequent_cast_members.csv | Most recurring actors |
| content_by_country_and_category.csv | Country-category mapping |
| most_common_types.csv, movies.csv | Filtered type-specific datasets |
| dynamic_derived_columns.csv | Auto-generated columns via Python logic |

---

## 📊 Visualizations (Power BI)

- *Pie Charts* for:
  - Content type distribution
  - Director-wise release volume
  - Title-wise cumulative release metrics

- *Filters & Slicers*:
  - Country, Year, Genre, Cast, Murder Mystery flag

- *Custom Metrics*:
  - Dynamic average durations by rating
  - Cross-tab country × category views

<details>
<summary>🔎 Sample Visuals</summary>

![Screenshot 2025-05-22 141149](https://github.com/user-attachments/assets/717982d9-9edc-4478-95a2-f4a81b6c8add)
![Screenshot 2025-05-22 141342](https://github.com/user-attachments/assets/7764a0c6-c256-47dc-a602-f81adc3f5626)
![Screenshot 2025-05-22 141425](https://github.com/user-attachments/assets/4f613eda-f534-431b-8574-00886970b4c9)

</details>

---

## 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| *Python (Pandas, NumPy)* | Data cleaning, transformation, analysis |
| *Power BI* | Visualization and dashboarding |
| *Jupyter Notebook* | Scripting, EDA |
| *VS Code* | Development environment |
| *Excel* | Initial sanity checks |

---

## 💡 Key Insights

- 🎞 *Movies dominate* the platform (69.6%), with TV Shows at ~30%
- 🌍 *Multi-country productions* are prevalent (e.g., Argentina, France, Germany)
- 🎬 *Rajiv Chilaka* leads in total releases (50% of summed years)
- ⏱ *Rating vs Duration* trends show target-audience-based content planning
- 👥 Frequent cast analysis reveals *patterns in actor collaborations*

---

:)
