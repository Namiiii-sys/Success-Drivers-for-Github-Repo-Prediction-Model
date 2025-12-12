# GitHub Trending Data Analysis & Growth Prediction 📈

This project analyzes the factors that drive virality in open-source GitHub repositories.  
By scraping weekly snapshots of the **top 100 trending repositories** across multiple programming languages, the project explores trends in **stars growth**, **contributor engagement**, **commit frequency**, and **topic relevance**.  
A machine learning model is then used to **predict whether a repository is likely to become viral** and identify the **key attributes influencing its visibility**.

---

## 🚀 Features

- 🔍 **Web scraping** of weekly top-100 trending GitHub repositories  
- 🧹 **Data preprocessing** and cleaning  
- 🧩 **Feature engineering** (stars velocity, contributor activity, commit frequency, topics, etc.)  
- 📊 **Exploratory Data Analysis (EDA)** with visualizations  
- 🤖 **ML model to predict viral potential** of repositories  
- ⭐ Identification of the **top factors driving repository visibility**  

---

## 📂 Dataset

The dataset is created by scraping GitHub Trending:

- Trending repositories for multiple languages  
- Weekly snapshots  
- Attributes include:
  - Stars & stars gained this week  
  - Forks  
  - Number of contributors  
  - Recent commit activity  
  - Repository description & topics  
  - Release/update timestamps  

The scraping script collects and converts this data into a structured, analysis-ready format.

---

## 🛠️ Tech Stack

- **Python**
- **pandas, numpy** — Data manipulation  
- **matplotlib, seaborn, plotly** — Visualizations  
- **requests** — Scraping GitHub Trending  
- **scikit-learn** — ML modeling (classification)  
- **GitHub API (optional)** — For deeper metadata extraction  

---

## 📊 Project Workflow

1. **Web Scraping**  
   - Weekly trending repositories scraped using `requests`  
   - Structured into a consistent tabular format

2. **Preprocessing & Feature Engineering**  
   - Cleaning missing values  
   - Extracting stars velocity  
   - Counting contributors  
   - Commit-based growth metrics  
   - Topic encoding

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of stars  
   - Correlation of features  
   - Activity patterns across languages  
   - Time-based trends

4. **ML Modeling**  
   - Classification model predicting whether a repository will become **viral**  
   - Feature importance ranking to highlight key drivers

5. **Insight Generation**  
   - Which repos grow fastest?  
   - What patterns do viral repos share?  
   - Which languages trend more easily?

---

## 📈 Visualizations (Examples)

(Add your graphs here once generated)

