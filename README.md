# 🎵 Analysis of Music Listening Behavior on Spotify in Thai Weather Conditions

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Scikit--Learn-orange)
![University](https://img.shields.io/badge/KMUTT-CPE232-red)

## 📌 Project Overview
This project is part of the **CPE232 Data Model** course at **King Mongkut's University of Technology Thonburi (KMUTT)**. 

The objective is to study the relationship between **Thai weather conditions** (Temperature, Rain) and **Spotify music preferences** (Audio features like Danceability, Energy, Valence). We aim to analyze whether weather patterns influence the type of music people listen to and build a machine learning model to predict weather context based on song features.

**Research Question:** *Does the weather affect the mood of the music we choose to listen to?*

## 👥 Team Members (Group "ต้าวอ้วน")
- Mr. Tharatorn Prakotkla
- Mr. Assadavut Hodmontade
- Mr. Nutthanun Jarukornkul
- Mr. Thiti Tiyachaipanich
- Mr. Ratchanon Tiptamoon
- Mr. Saksit Vetchawittayaklang
- Mr. Thammaphon Changpathee

## ⚙️ Methodology

### 1. Data Preparation
- Collected music data using **Spotify API** (features: valence, energy, danceability, acousticness, etc.).
- Collected weather data (Temperature, Rain status) corresponding to the listening timestamps.
- Cleaned and merged datasets using `Pandas`.

### 2. Exploratory Data Analysis (EDA)
- Analyzed correlations between audio features and weather conditions.
- Visualized distributions of song attributes across different weather types.

### 3. Machine Learning Modeling
- **Task:** Multi-output Classification/Regression (Predicting `average_temp` and `rain`).
- **Model Used:** Random Forest (optimized using `GridSearchCV`).
- **Best Parameters:** - `max_depth`: 10
  - `min_samples_split`: 5
  - `n_estimators`: 58
- **Evaluation:** Accuracy Score.

## 📊 Results & Insights
*(You can add a summary of your findings here, e.g., "We found that people tend to listen to high-energy music when it rains...")*

- **Model Accuracy:** [Insert your final accuracy score here]

## 🛠️ Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/spotify-weather-analysis.git](https://github.com/YOUR_USERNAME/spotify-weather-analysis.git)
