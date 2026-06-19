# Educational Data Mining of Learning Strategies and Programming Concept Comprehension

## Research Question
Which learning strategies are associated with better comprehension of programming concepts in introductory programming courses?

## Overview
This repository contains the analysis code for my BSc AI thesis. The study combines question-level exam data with self-reported survey data from two cohorts of the Programming 1 course at Radboud University (2024/2025 and 2025/2026) to investigate how learning strategies relate to concept-level exam performance.

The analysis pipeline includes:
- Data preprocessing and concept score computation
- Exploratory data analysis
- Multiple Correspondence Analysis (MCA)
- Logistic regression (pass/fail per concept)
- Linear regression (continuous concept score)

## Repository Structure
bsc-thesis-edm/

├── Code_BSc_Thesis_s1088428.ipynb   # Full analysis notebook

└── README.md

## How to Run
The notebook was developed in **Google Colab**. To reproduce the analysis:
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells in order
3. When prompted, upload the four data files:
   - `P1_2425_C1_Answers_Anon.csv`
   - `P1_2425_C1_Points_Anon.csv`
   - `P1_2526_C1_Answers_Anon.csv`
   - `P1_2526_C1_Points_Anon.csv`
>**Note:** The data files are not included in this repository as they contain anonymised student data. 

## Dependencies
The notebook installs `prince` automatically. All other libraries are available in the standard Colab environment:
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `statsmodels`
- `scipy`
- `prince`
