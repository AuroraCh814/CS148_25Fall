# CS148_25Fall - Student Performance Analysis

**Team LMAO** | CS M148 Fall 2025 | UCLA

This is the Team LMAO, together with Micheal Ji, Chong Han, Songyou Yang, Kevin Zheng, Deysi Chen Li, Ovin; We are here working together for the course CS M148 in 2025 Fall at UCLA

## Overview

Analyzing student performance factors using machine learning to understand what drives academic success.

**Dataset:** [Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors) (6,607 students, 20 features)

## Dataset

The dataset includes 19 features and 1 target variable (`Exam_Score`):

**Academic Factors:** Hours_Studied, Attendance, Previous_Scores, Motivation_Level, Tutoring_Sessions
**Family Factors:** Parental_Involvement, Parental_Education_Level, Family_Income
**Resources:** Access_to_Resources, Internet_Access, School_Type, Teacher_Quality
**Lifestyle:** Sleep_Hours, Extracurricular_Activities, Physical_Activity, Learning_Disabilities
**Environmental:** Distance_from_Home, Peer_Influence, Gender

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook notebooks/
```

## Project Structure

```
├── data/                  # StudentPerformanceFactors.csv
├── notebooks/             # Analysis notebooks
├── src/                   # Python modules
├── models/                # Saved models
└── reports/               # Visualizations
```

## Goals

1. Identify key factors affecting student performance
2. Build predictive models (Linear Regression, Random Forest, XGBoost)
3. Provide actionable insights for educational interventions

## License

Dataset: CC0 Public Domain | Course Project 2025
