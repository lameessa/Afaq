# Afaq | آفاق

Afaq is a data science and machine learning project that explores tourism engagement across Saudi Arabia through publicly available Flickr photos.

The project analyzes photo engagement, visual content, geographic regions, seasons, time of day, and audience sentiment to uncover patterns in how Saudi destinations are represented and received online.

**Developed at King Saud University (KSU), Riyadh, Saudi Arabia (SA).**

🏆 **1st Place at the KSU IT Fair**

---

## About Afaq

Afaq was developed to explore how data can support tourism promotion in Saudi Arabia.

Using tourism-related photos collected through the Flickr API, we analyzed engagement metrics alongside visual and contextual characteristics to understand what contributes to photo popularity and how engagement differs across regions.

The project covers the five regions of Saudi Arabia — North, South, Central, East, and West — and combines data analysis, computer vision, natural language processing, and machine learning.

---

## Project Workflow

### 1. Data Collection

Public photo data was collected through the **Flickr API**, including:

- Views
- Favorites
- Comments
- Upload dates
- Photo locations
- Images and their metadata

The data collection process began on **January 25, 2025**.

### 2. Image & Text Analysis

The collected data was enriched using several AI and computer vision techniques:

- **CLIP** was used to classify landscape types and identify visual elements within each image.
- **OpenCV** was used to classify photos as day or night based on image brightness.
- **Hugging Face Transformers** were used to perform sentiment analysis on photo comments.

Visual elements included features such as mountains, buildings, trees, water, sand, roads, rocks, and mosques.

### 3. Popularity Analysis

A **Popularity Score** was created to measure photo engagement using favorites, comments, normalized views, and sentiment.

Exploratory data analysis was then used to examine differences in popularity across:

- Saudi regions
- Seasons
- Time of day
- Landscape types
- Visual elements
- Engagement patterns over time

### 4. Machine Learning

The processed data was split into **80% training and 20% testing data**.

Three regression models were evaluated:

- Linear Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)

The **Random Forest Regressor** achieved the strongest performance with an **R² of approximately 0.93**, compared with approximately **0.88** for Linear Regression, while SVR produced a negative R².

---

## Key Insights

The analysis revealed several patterns in the collected Flickr data:

- The **Eastern region** achieved the highest overall Popularity Score, followed by the Northern region.
- The **Southern region** had the lowest overall engagement in the dataset, highlighting an opportunity for greater visibility and further analysis.
- **Autumn** showed particularly strong engagement across several regions, while the South showed its strongest engagement during spring.
- **Daytime photos** generally performed better, although nighttime photos showed stronger engagement in the Western region.
- Visual elements such as **sand, roads, and rocks** were associated with higher average Popularity Scores.
- Engagement patterns and the types of landscapes represented differed considerably across Saudi regions.

These findings reflect patterns within the collected Flickr dataset and may not represent tourism activity as a whole.

---

## Technologies & Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- OpenCV
- OpenAI CLIP
- Hugging Face Transformers
- Flickr API
- Matplotlib
- Seaborn
- Google Colab

---

## Repository Contents

This repository contains the main materials produced for Afaq:

- **Afaq Notebook** — data collection, preprocessing, analysis, visualizations, and machine learning
- **Project Report** — full documentation of the project and findings
- **Project Poster** — visual summary of Afaq
- **Project Presentation** — presentation of the project, methodology, and results

---

## Team

- Lamees Alghamdi
- Norah Almadhi
- Maha Alruwais
- Ghadeer Alnuwaysir
- Rana Albridi

**Supervisor:** Dr. Mashael Sultan Aldayel

---

## Affiliation

**King Saud University (KSU)**  
Riyadh, Saudi Arabia (SA)

Developed as part of **IT362 – Data Science**.
