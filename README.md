# Bank Loan Analysis

**Project Description:**

The project's primary objective was to conduct Exploratory Data Analysis (EDA) on a dataset from a finance company specializing in lending loans to urban customers. The goal was to identify patterns and factors that indicate whether a customer might have difficulty paying their loan installments, thereby assisting the company in making informed decisions about loan approvals. The project aimed to address the risks of rejecting capable applicants or approving high-risk ones. This involved tasks such as handling missing data, identifying outliers, analyzing data imbalance, and conducting univariate, segmented univariate, and bivariate analyses.

**Approach:**

To achieve the project's objectives, the following approach was followed:

I went through the risk analytics process step by step, task after task. The project outcomes are as follows:
**Overall Method to Analysis:** The bank’s problem statement is to identify the major causes of bank loan default. The knowledge will be used for risk assessment by the company. We have provided two enormous data sets here.
  - ‘application data.csv’ contains all of the client’s information at the time of application. The information pertains to whether or not a client is having financial issues.
  - ‘previous application.csv’ provides data from the client’s previous loans. It indicates if the prior application was Accepted, Cancelled, Refused, or Unused.
    
**Data Collection:** The dataset provided by the finance company was imported into Microsoft Excel 2022, which served as the primary tool for data analysis.

**Data Cleaning:**
- Identifying Missing Data: Excel functions such as COUNT, ISBLANK, and IF were used to identify missing data in the dataset.
- Handling Missing Data: Missing data was appropriately handled through imputation using Excel's AVERAGE and MEDIAN functions or by removing rows with missing values.

**Outlier Detection:**
- Identifying Outliers: Excel's statistical functions like QUARTILE and IQR were employed to identify potential outliers in numerical variables.
- Outlier Treatment: Thresholds and business rules were applied to determine whether outliers were valid data points or required further investigation.

**Data Imbalance Analysis:**
Detecting Data Imbalance: Excel functions like COUNTIF and SUM were used to calculate the proportions of each class (e.g., payment difficulties vs. other cases).
Visualizing Data Imbalance: Pie charts and bar charts were created to visualize the distribution of the target variable and highlight class imbalance.

**Exploratory Data Analysis:**
- Univariate Analysis: Excel functions such as COUNT, AVERAGE, MEDIAN, and pivot tables were used to understand the distribution of individual variables.
- Segmented Univariate Analysis: Excel features like filters, sorting, and pivot tables were employed to compare variable distributions for different scenarios (e.g., payment difficulties vs. other cases).
- Bivariate Analysis: Scatter plots, heatmaps, and other visualizations were created to explore relationships between variables and the target variable.


**Correlation Analysis:**
- Segmenting the Dataset: The dataset was segmented based on different scenarios (e.g., payment difficulties and other cases).
- Calculating Correlations: Excel's CORREL function was used to calculate correlation coefficients between variables and the target variable within each segment.

**Our Technology Stack:**
- Software: Microsoft Excel 2019
- Purpose: Microsoft Excel was chosen for its robust data analysis and visualization capabilities, making it suitable for tasks like data cleaning, analysis, and visualization.
