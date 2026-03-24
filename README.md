# 🎬 Netflix Movies Data Analysis(Internship project)

This project focuses on analyzing Netflix movies data using Python to uncover trends, patterns, and insights from the dataset.

---

## 📌 Project Overview

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on Netflix movies dataset and answer key questions such as:

- How movie duration has changed over time  
- Distribution of movies across years  
- Trends in content production  
- Insights from movie duration and release patterns  

Netflix dataset contains thousands of records of movies and shows, making it ideal for data analysis practice 0  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## 📂 Dataset

- Source: Kaggle Netflix Dataset  
- File used: `netflix_titles.csv`  
- Contains information like:
  - Title  
  - Release Year  
  - Duration  
  - Genre  
  - Country  

---

## 🔍 Key Steps Performed

### 1. Data Loading
- Loaded CSV data using Pandas  

### 2. Data Cleaning
- Removed null values  
- Filtered only movies  
- Cleaned duration column  

(Data cleaning is important because raw datasets often contain missing or inconsistent values 1)

---

### 3. Data Analysis

- Analyzed movie durations over years  
- Compared trends from 2011–2020  
- Created dictionaries and structured data  

Example insight:
- Average movie duration shows a decreasing trend over time 2  

---

### 4. Data Visualization

- Line plots for duration trends  
- Histograms for distribution  
- Color-based classification  

---

## 📊 Key Insights

- 📉 Movie duration is decreasing over time  
- 🎬 Netflix has diverse content across years  
- 📈 Recent years show higher content production  

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/AnshulKumar001/Internship_projects.git

# Go to project folder
cd Internship_projects/1.NETFLIX

# Open notebook
jupyter notebook NETFLIX_MOVIES.ipynb
