# 🎬 Netflix Movie Recommendation System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📌 Project Overview

This project implements a comprehensive **movie recommendation system** for Netflix by analyzing a dataset of **8,807 titles** including both movies and TV shows. The system leverages advanced machine learning techniques and statistical analysis to provide personalized content recommendations and extract meaningful insights about content preferences and trends.

**Key Features:**
- 🔍 **Comprehensive EDA** with interactive visualizations
- 🤖 **Content-Based Filtering** using TF-IDF and cosine similarity
- 📊 **Statistical Analysis** including PCA and clustering
- 📈 **Temporal Trend Analysis** across different time periods
- 🌍 **Geographic Content Analysis** by region and country

---

## 🎯 Project Objectives

- **🔍 Exploratory Data Analysis**: Conduct comprehensive analysis to identify trends, patterns, and insights from the Netflix dataset
- **🎯 Recommendation System Development**: Build and implement content-based filtering algorithms using TF-IDF vectorization and cosine similarity
- **📊 Statistical Modeling**: Apply advanced statistical techniques including PCA, clustering, and correlation analysis
- **📈 Temporal Analysis**: Analyze how content preferences, genres, and ratings have evolved over different time periods
- **🌍 Geographic Insights**: Examine content distribution and preferences across different countries and regions
- **🎨 Data Visualization**: Create interactive visualizations to communicate findings and insights effectively

---

## 📊 Dataset Information
- **Dataset Source**: Kaggle - Netflix Movies and TV Shows Dataset
- **Total Entries**: **8,807 titles**
- **Key Features**:
  - **Title**: Name of the movie or TV show.
  - **Type**: Whether it's a **Movie** or a **TV Show**.
  - **Director**: Name of the director(s).
  - **Cast**: List of main actors.
  - **Rating**: Age certification (e.g., PG-13, TV-MA).
  - **Listed_in**: Genre of the content.
  - **Release_Year**: Year when the movie/show was released.
  - **Duration**: Movie length or TV show seasons.
  - **IMDB Scores**: User ratings.
  - **TMDB Popularity**: Popularity score from TMDB.

---

## 🏗 Methodology & Implementation

### 🔹 Data Preprocessing
- **Handling Missing Values**: Imputed or removed missing values in key attributes.
- **Removing Duplicates**: Ensured dataset consistency by filtering duplicate entries.
- **Fixing Data Inconsistencies**: Standardized genre names and rating formats.

### 🔹 Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Analyzed **release years, duration, and ratings**.
- **Bivariate Analysis**: Explored relationships between **release year, content type, and duration**.
- **Multivariate Analysis**: Used **correlation analysis, PCA, and clustering techniques**.

### 🔹 Recommendation System
- **Content-Based Filtering**: Utilized **cosine similarity** to recommend movies based on genre and description.
- **Similarity Measures**: Calculated **text similarity** between movie descriptions.
- **Feature Engineering**: Extracted important attributes for recommendations.

---

## 📌 Key Insights from the Project
- **📊 Content Distribution**:
  - **69.6% Movies** and **30.4% TV Shows**.
  - Netflix has focused more on movies than TV series.

- **🎬 Most Popular Genres**:
  - **International Movies and Dramas** dominate the platform.
  - Stand-up comedy and documentaries are also gaining traction.

- **📅 Release Year Trends**:
  - A **spike in content releases** from **2015 onwards**.
  - Older movies (pre-2000) are fewer, with most content being recent.

- **📈 User Preferences**:
  - **Mature content (TV-MA, TV-14) dominates Netflix**.
  - **United States and India** are the top content-producing countries.

---
