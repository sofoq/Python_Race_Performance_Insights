# Race Performance Insights 🏃‍♂️🏃‍♀️

This project involves analyzing a dataset of races spanning two centuries, focusing on the 50km and 50mi races in USA in the year 2020. The analysis includes athlete performance, speed, age, gender, and race season trends.

## Key Steps in the Analysis 🧮

### 1. Data Loading and Exploration 📂
- The dataset `TWO_CENTURIES_OF_UM_RACES.csv` is loaded and the first 10 rows are examined.
- Data types and shape are checked to understand the structure of the data.

### 2. Data Cleaning 🧹
- The data is filtered for **USA athletes** competing in **50km and 50mi** races in **2020**.
- Columns such as `Athlete club`, `Athlete country`, `Athlete year of birth`, and `Athlete age category` are dropped.
- Missing values and duplicates are removed, and data types are fixed where necessary (e.g., converting age to integer, average speed to float).

### 3. Feature Engineering 🔧
- **Athlete Age** is calculated by subtracting the athlete's year of birth from the event year.
- **Athlete Performance Time** is cleaned to keep only the numeric part of the time.
- Column names are renamed for better clarity (e.g., `Event name` to `race_name`).
- New features such as `race_month` and `race_season` are derived from the `race_day`.

### 4. Data Analysis 📊
- Visualizations are created using `seaborn` and `matplotlib` to explore different aspects of the data:
  - Distribution of race lengths and gender-based analysis.
  - Comparison of average speed for **50km vs. 50mi** races by gender.
  - Age group performance for the **50mi** race.
  - Speed comparison across different seasons (Winter, Spring, Summer, Fall).

### 6. Visualizations 🎨
- **Histograms** for race length distribution and average speed by gender.
- **Violin Plot** comparing speed by gender for different race lengths.
- **Line Chart** comparing mean average speed across seasons.

## Libraries Used 📚
- `pandas` for data manipulation.
- `seaborn` for data visualization.
- `matplotlib` for creating line charts.



**Sofo Qaadze**
  - 📧 [sqaadze2000@gmail.com](mailto:sqaadze2000@gmail.com)
  - 🔗 [LinkedIn Profile](https://www.linkedin.com/in/sofo-qaadze-ba7895205/)
