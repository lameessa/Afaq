# Afaq | آفاق

Afaq is a data science and machine learning project that analyzes **Saudi landscape photos** to explore the factors associated with higher online engagement and identify destinations that may deserve greater visibility.

Using public images and metadata collected through the Flickr API, the project combines data analysis, computer vision, natural language processing, and machine learning to uncover patterns across Saudi regions, seasons, visual elements, and audience engagement.

**Developed at King Saud University (KSU), Riyadh, Saudi Arabia (SA).**

🏆 **1st Place at the KSU IT Fair**

---

## About the Project

Afaq was developed to explore how data can support tourism promotion in Saudi Arabia.

The project analyzes Saudi landscape photos and their engagement data to investigate how factors such as geographic region, season, time of day, visual content, and audience sentiment relate to photo popularity.

The analysis covers five regions of Saudi Arabia: **Central, West, North, South, and East**.

---

## Methodology

The project follows an end-to-end data science workflow:

1. **Data Collection**  
   Public Saudi landscape photos and their metadata were collected using the **Flickr API**, including views, favorites, comments, and upload information.

2. **Image & Text Analysis**
   - **CLIP** was used to classify landscape types and detect visual elements.
   - **OpenCV** was used to classify images as day or night based on brightness.
   - **Hugging Face Transformers** were used for sentiment analysis of photo comments.

3. **Data Analysis**  
   Engagement patterns were explored across regions, seasons, time of day, landscape types, and visual elements.

4. **Machine Learning**  
   Linear Regression, Random Forest Regressor, and Support Vector Regressor (SVR) were evaluated to predict a custom **Popularity Score**.

The project collected **200 Saudi landscape images**, with **199 retained in the final processed dataset across 33 features**.

---

## Model Performance

The **Random Forest Regressor** achieved the strongest performance:

- **R² Score:** 0.9288
- **RMSE:** 576.70

The model explained approximately **93% of the variance in Popularity Score** within the project dataset.

---

## Key Findings

- The **East** had the highest overall Popularity Score, followed by the **North**.
- The **South** showed the lowest overall engagement in the collected dataset.
- **Autumn** emerged as a high-engagement season across multiple regions.
- **Daytime photos** generally showed higher average popularity.
- **Sand, roads, and rocks** were among the visual elements associated with higher average Popularity Scores.
- Engagement and landscape patterns varied across Saudi regions.

---

## Technologies & Tools

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `OpenCV` · `CLIP` · `Hugging Face Transformers` · `Flickr API` · `Matplotlib` · `Seaborn` · `Google Colab`

---

## Repository Contents

- **Afaq-Notebook.ipynb** — Data collection, preprocessing, analysis, visualizations, and machine learning
- **Afaq-Report.pdf** — Full project methodology, results, and discussion
- **Afaq-Poster.pdf** — Visual overview of the project
- **Afaq-Presentation.pdf** — Project presentation and findings

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
College of Computer and Information Sciences  
Department of Information Technology  
Riyadh, Saudi Arabia (SA)

Developed as part of **IT362 – Data Science**.

