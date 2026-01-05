# building-damage-eda
Exploratory Data Analysis of Earthquake Building Damage Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on an earthquake building damage dataset.
The analysis explores damage distribution, building materials, location-based damage patterns,
and the relationship between building age and damage severity.

## Dataset
Source: Kaggle  
Link: [https://www.kaggle.com/](https://www.kaggle.com/code/ar89dsl/predicting-building-damage-from-earthquakes/notebook)

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Visual Studio Code

## Key Analyses
- Damage class distribution
- Damage vs building material
- Damage by district
- Relationship between building age and damage
- Relationship between floor count and damage

## Key Findings 

Here are the main insights discovered from the earthquake building damage dataset:

1. **Damage Class Distribution**
   - Buildings are classified from **Grade 1 to Grade 5**, with **Grade 5 (most severe damage) being the most common**, estimated at around 265–270 buildings.
   - Lower damage classes (Grades 1–4) have smaller counts, ranging approximately from 75,000 to 180,000 buildings.

2. **Damage vs Building Material**
   - **Mud mortar stone** structures showed the **highest damage**, indicating this material is less resilient during earthquakes.

3. **Damage by District**
   - **District 23** stands out with noticeably higher severe damage (**Grade 5**), estimated at ~70,000 buildings.
   - Other districts have moderate counts for Grade 5 damage (~40,000), and relatively lower counts for Grades 1–4.

4. **Relationship between Building Age and Damage**
   - Older buildings tend to experience slightly more damage.
   - Average ages per grade:
     - Grade 1: 14.96 years  
     - Grade 2: 19.52 years  
     - Grade 3: 24.83 years  
     - Grade 4: 26.99 years  
     - Grade 5: 26.5 years  
   - Overall, the trend shows a mild increase in damage with age, but it is not strongly pronounced.

5. **Relationship between Floor Count and Damage**
   - Damage does **not increase with the number of floors**.
   - Buildings with **2 floors** have the highest number of damaged buildings, while taller buildings do not necessarily experience higher damage.

## Files
- `eda.ipynb` – main analysis notebook

## Notes
This project was created as part of a beginner data science learning journey, with the goal of practicing fundamental data analysis concepts such as data cleaning, exploration, and visualization using real-world data.
