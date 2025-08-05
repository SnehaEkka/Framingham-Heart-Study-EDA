# Framingham Heart Study EDA

A data-driven exploration of cardiovascular risk and lifestyle factors in the landmark Framingham Heart Study. Developed as a self-guided project for BA780 (Fall 2024 – Spring 2025), this repository showcases a deep dive into the medical, demographic, and behavioral data collected over decades in the town of Framingham, Massachusetts.

## Project Motivation

What shapes heart health? This project takes the open Framingham dataset and investigates key predictors of cardiovascular disease, focusing especially on the interplay between smoking habits, demographics (age, gender, education), and core health measures like BMI, blood pressure, and cholesterol.

## Dataset

- **Source:** [Framingham Heart Study](https://www.kaggle.com/datasets/soltaniehha/intro-to-data-analytics-framingham) ([see original](https://www.framinghamheartstudy.org/))
- **Rows:** 4,240  
- **Features:** 16 (including demographics, smoking status, medical history, biometric indicators)  
- **Target:** Ten-year coronary heart disease (TenYearCHD, binary outcome)

## Technologies Used

- **Python:** pandas, numpy, matplotlib, seaborn
- **Notebook Environment:** Jupyter, Google Colab

## The Journey: From Questions to Insights

The analysis began with foundational questions: who smokes, how much, and how do these patterns vary across the age and education spectrum? Demographic profiling revealed that nearly half of the study’s participants were smokers, with younger adults and men smoking most intensively (median ≈ 20 cigarettes/day among smokers).

Curiosity drove deeper explorations. Visualizing smoking intensity and prevalence brought out clear contrasts, while health metrics showed that current smokers had a lower mean BMI but higher systolic and diastolic blood pressures than non-smokers. Across the board, about 15% of the cohort suffered a ten-year CHD event, with risk peaking among older, hypertensive, and smoking individuals.

Correlation heatmaps and focused pairplots told the next chapter: BMI, blood pressure, and cholesterol form tightly linked clusters, while smoking status is modestly but meaningfully tied to higher cholesterol and elevated heart risk.

The project emphasized rigorous data cleaning, strong reporting practices, and clear, impactful visualizations—ensuring all insights rest on a robust analytical foundation. The goal throughout: not just to present numbers, but to illuminate the human stories and actionable trends behind them.

## Reflections

Beyond the statistics, this project underscores how lifestyle choices, early intervention, and equitable health strategies remain central to reducing cardiovascular risk. It illustrates the value of data-driven insights for public health, clinical analytics, and practical decision-making, showcasing transferable skills in EDA, reporting, and communication.

For a closer look at methods, visualizations, and additional insights, explore the full code notebook. 
For comments or collaboration, feel free to reach out via this repo.
