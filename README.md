
# Global Cities, Countries & Languages Analysis

## Project Overview
This project explores global demographics, population trends, economic indicators, urbanization, and linguistic diversity using a structured dataset of **cities, countries, and languages**.  
The dataset is derived from the classic **World Database** (SQL → CSV), making it beginner-friendly while also powerful for data storytelling and visualization.

## Goal
To perform **Exploratory Data Analysis (EDA)** and generate insights about:
- Global population distribution
- Country-level demographics and economic indicators
- Urbanization patterns across major cities
- Linguistic and cultural diversity

This project is designed as a **portfolio piece** to demonstrate skills in **Python, Pandas, Data Cleaning, Data Visualization, and Storytelling**.

---

## Dataset
The dataset consists of **three relational tables**:

1. **city.csv**
   - `ID` → Unique city identifier  
   - `Name` → City name  
   - `CountryCode` → Links to country  
   - `District` → Administrative division  
   - `Population` → City population  

2. **country.csv**
   - `Code` → Unique country code  
   - `Name` → Country name  
   - `Continent`, `Region` → Geographic classification  
   - `SurfaceArea` → Area in square kilometers  
   - `Population` → Country’s population  
   - `LifeExpectancy`, `GNP`, `GovernmentForm`, `HeadOfState`, etc.  

3. **countrylanguage.csv**
   - `CountryCode` → Links to country  
   - `Language` → Language name  
   - `IsOfficial` → Whether the language is official  
   - `Percentage` → % of speakers in population  

---

##  Tech Stack
- **Python**
- **Pandas / NumPy** → Data wrangling  
- **Matplotlib / Seaborn** → Data visualization  
- **Missingno** → Missing value visualization  
- **Jupyter Notebook** → Analysis & reporting  

---

## Exploratory Data Analysis (EDA)
The analysis is divided into sections:

### A. Global Overview
- Population distribution by continent  
- Number of countries per continent  
- Life expectancy comparison  
- GNP distribution  

### B. Country-Level Insights
- Top 10 most populated countries  
- Population density ranking  
- Correlation between population & GNP  
- Richest countries (per capita GNP)  

### C. City-Level Insights
- Top 10 most populated cities  
- Contribution of cities to their national population  

### D. Language & Culture
- Most spoken global languages  
- Countries with the highest number of official languages  

---

## Key Insights
### Global Demographics
- Asia is home to the majority of the world’s population, while Africa is politically diverse with the largest number of countries.  
- Europe and Oceania lead in life expectancy, while Africa has the lowest median values.  

### Economic Landscape
- Global GNP is concentrated in **Asia and North America**, despite Africa’s large population.  
- Smaller high-income countries (e.g., Luxembourg, Switzerland) dominate **per-capita wealth**, showing wealth ≠ population size.  

### Population Distribution
- China and India together account for **over a third** of global population.  
- Tiny nations like Singapore and Bangladesh have **extreme population densities** compared to much larger nations.  

### Urbanization Trends
- Mega-cities such as **Shanghai, Mumbai, and São Paulo** dominate urban populations.  
- Cities like Dhaka and Singapore contribute a **disproportionately high share** to national populations.  

### Linguistic & Cultural Diversity
- **English, French, and Arabic** are the most globally widespread languages.  
- Countries such as **India and Switzerland** recognize multiple official languages, reflecting **cultural pluralism**.  

---

## Data Cleaning Strategy
- Filled missing categorical values with `"Unknown"` / `"NA"`.  
- Replaced missing **Life Expectancy** with continent medians.  
- Dropped irrelevant column (`GNPOld`).  

---

## Dataset Source
This dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/adilshamim8/world-cities-countries-and-languages-dataset/data):  
**“World Cities, Countries & Languages Dataset”** by *adilshamim8*.  

---

## Licensing & Usage
- Please ensure you comply with Kaggle’s terms of service and any license specified on the dataset page.  
- If you share or publish results, cite this dataset properly.  
- Any modifications to the data (cleaning, imputation) are my own.  

---

## Acknowledgements
Thanks to *adilshamim8* for creating and sharing the dataset.  
