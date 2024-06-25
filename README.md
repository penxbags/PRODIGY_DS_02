# PRODIGY_DS_02
**DATA CLEANING AND EDA**

### Data Loading and Initial Exploration
1. **Loading the Dataset**: The dataset was loaded using `pd.read_csv()` into a DataFrame named `train`.
2. **Shape and Columns**: The shape of the dataset was displayed to show the number of rows and columns. The column names were displayed in both array and list formats.
3. **Head and Tail**: The first and last few rows of the dataset were displayed to understand the structure and sample data.
4. **Subsetting Data**: Specific rows and columns were selected and displayed using `.head()`, `.tail()`, and `.iloc[]`.

### Data Cleaning
5. **Removing Columns**: Unnecessary columns were identified and removed from the dataset. For example, the 'User_ID' column was dropped as it might not contribute to the analysis.
6. **Handling Missing Values**: The number of missing values in each column was calculated. Rows with missing values in the 'Product_Category_2' column were dropped.
7. **Removing Duplicates**: Duplicate rows were removed while keeping the first occurrence.
8. **Dealing with Missing Values**: Specific columns with missing values, such as 'Product_Category_3', were addressed by counting the number of missing entries.

### Exploratory Data Analysis (EDA)
9. **Descriptive Statistics**: The `describe()` method was used to obtain statistical data like mean, standard deviation, percentiles, etc.
10. **Skewness and Kurtosis**: The skewness and kurtosis of numeric columns were calculated to assess the normality of data. It was concluded that most of the data followed a normal distribution as skewness < |2| and kurtosis < |7|.

### Additional EDA Tasks
11. **Gender Distribution**: The count of males in the dataset was calculated.
12. **Subsetting by Data Type**: Columns were selected based on their data types (numerical and categorical).
13. **Mode Calculation**: The mode of each column was calculated to find the most frequent values.

### Data Visualization
14. **Bar Chart for Car Origins**: A bar chart was created to visualize the distribution of car origins using Seaborn. The 'origin' column's value counts were plotted to show the frequency of each category.

### Conclusion
The analysis revealed that the dataset predominantly consisted of cars from the USA. The cleaning steps ensured the dataset was free from missing values and duplicates, making it suitable for further analysis. The EDA provided insights into the distribution, central tendency, and dispersion of the data.
