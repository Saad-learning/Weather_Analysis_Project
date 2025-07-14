
##  Weather Data Analysis with Python

This project presents an exploratory data analysis (EDA) of a weather dataset using Python and Pandas. The analysis covers general data profiling and answers to specific analytical questions regarding weather conditions, wind speed, humidity, visibility, and more.

---

###  Key Objectives

- Understand the structure and properties of weather data
- Perform exploratory data analysis using Pandas
- Answer specific business questions using filtering, grouping, and aggregation
- Extract insights related to weather patterns

---

###  Tools & Libraries Used

- **Python** 
- **Pandas** for data manipulation and analysis
- **Jupyter Notebook** for interactive coding

---

###  Dataset Columns

- `Date/Time`
- `Temp_C`
- `Dew Point Temp_C`
- `Rel Hum_%`
- `Wind Speed_km/h`
- `Visibility_km`
- `Press_kPa`
- `Weather`

---

###  Key Questions Answered

1. **Find all unique wind speed values**
2. **Find number of times when weather is exactly clear**
3. **Find number of times wind speed was exactly 4 km/h**
4. **Find all null values in the dataset**
5. **Rename column `Weather` to `Weather Conditions`**
6. **Find the mean visibility**
7. **Find standard deviation of pressure**
8. **Find variance of relative humidity**
9. **Find all instances when snow was recorded**
10. **Find records when wind speed > 24 and visibility = 25**
11. **Find mean of each column grouped by weather condition**

---

###  How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Saad-learning/weather-data-analysis.git
   ```
2. Place your dataset at the specified path or update the path in the notebook:
   ```python
   data = pd.read_csv(r'F:\Porfolio Project\Python\Weather\file.csv)
   ```
3. Run the `Weather_analysis.ipynb` notebook in Jupyter.

---

###  Future Enhancements

- Add visualizations using Matplotlib or Seaborn
- Handle missing values and outliers more deeply
- Build predictive models for forecasting temperature or weather events

---

###  Author

**Saad Attia**  
Aspiring Data Analyst | Passionate about weather data and analytics  
[LinkedIn](https://www.linkedin.com/in/saad-attia-302433246/) • [GitHub](https://github.com/Saad-learning)
