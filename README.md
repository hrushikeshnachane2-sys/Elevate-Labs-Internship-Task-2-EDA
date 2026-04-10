# Elevate-Labs-Internship-Task-2-EDA
# Task 2: Exploratory Data Analysis (EDA)
**Internship:** AI & ML Internship at Elevate Labs

## Objective
The goal of this task is to understand the Titanic dataset using descriptive statistics and data visualization tools like Pandas, Seaborn, and Matplotlib.

## Tools Used
* **Pandas:** Data manipulation and summary statistics.
* **Matplotlib & Seaborn:** Static visualizations (Histograms, Boxplots, Heatmaps).
* **Plotly:** Interactive data exploration.

## Steps Performed
1. **Data Loading:** Loaded the Titanic dataset from a public URL.
2. **Descriptive Statistics:** Generated mean, median, and standard deviation for numeric features.
3. **Data Visualization:** - Created Histograms for age distribution.
   - Used Boxplots to identify outliers in ticket fares.
   - Generated a Correlation Matrix to see relationships between features.
4. **Pattern Recognition:** Identified survival trends based on Passenger Class and Age.

## Key Inferences
1. **Survival by Passenger Class:** There is a strong correlation between socio-economic status and survival. Passengers in 1st Class had a survival rate of approximately 63%, while those in 3rd Class had the lowest survival rate at roughly 24%.

2. **Fare Anomalies:** The ticket fare distribution is highly right-skewed with a skewness coefficient of approximately 4.79. Significant outliers exist (fares above 100), representing a small number of elite passengers who paid significantly more than the average fare of ~32.

3. **Missing Data Impact:** The Cabin feature has over 77% missing values, making it unsuitable for direct modeling without significant imputation or transformation. The Age column also has about 20% missing values, which could bias age-based survival analysis if not addressed.

4. **Age Demographics:** The passenger population was primarily composed of young adults. The distribution peaks between the ages of 20 and 40, with a noticeable "infant" peak, indicating a priority for saving children during the evacuation.

5. **Correlation Findings:** Fare and Survived show a positive correlation, confirming that higher-paying passengers were more likely to survive. Conversely, Pclass and Survived show a negative correlation, confirming that survival chances decreased as the class number increased.
