# SCT_DS_02
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
# ------------------------------------------------------------
# PROJECT: DATA CLEANING & EXPLORATORY DATA ANALYSIS (EDA)
# DATASET: TITANIC DATASET (FROM KAGGLE)
# ------------------------------------------------------------

# 1. Import Required Libraries
#    - pandas: for data manipulation
#    - numpy: for numerical operations
#    - matplotlib & seaborn: for data visualization
# ------------------------------------------------------------

# 2. Load the Dataset
#    - Read the CSV file using pandas
#    - Display first few rows to understand the structure
#    - Check the shape of the dataset (rows, columns)

# 3. Inspect the Data
#    - Use df.info() to view data types and non-null counts
#    - Use df.describe() for basic statistical summary
#    - Identify categorical and numerical features

# 4. Check for Missing Values
#    - Use df.isnull().sum() to count missing values per column
#    - Decide how to handle missing data:
#         * Drop columns/rows with too many missing values
#         * Fill missing numerical values with mean or median
#         * Fill missing categorical values with mode (most frequent value)

# 5. Data Cleaning
#    - Handle missing values appropriately (e.g., fill or drop)
#    - Convert data types if necessary (e.g., object to category)
#    - Remove duplicates if any using df.drop_duplicates()
#    - Rename columns for consistency and clarity
#    - Handle outliers if they affect the analysis

# 6. Univariate Analysis (Single Variable)
#    - Analyze one feature at a time
#    - For numerical columns:
#         * Plot histograms and boxplots to check distributions
#    - For categorical columns:
#         * Use countplots or pie charts to view frequency of categories

# 7. Bivariate Analysis (Two Variables)
#    - Explore relationships between independent and dependent variables
#    - Examples:
#         * Survival vs Gender (sns.countplot)
#         * Survival vs Passenger Class
#         * Age vs Survival (using boxplot)
#    - Observe how variables affect the target (Survived)

# 8. Multivariate Analysis (More than Two Variables)
#    - Use grouped plots or pairplots to explore combined effects
#    - Example: Survival rate by Gender and Class together
#    - Helps identify patterns and complex relationships

# 9. Correlation Analysis
#    - Use df.corr() to compute correlation between numeric columns
#    - Plot a heatmap using seaborn to visualize correlations
#    - Identify which variables have strong or weak relationships

# 10. Identify Patterns and Trends
#     - Women and children had higher survival rates
#     - Passengers in higher classes (Pclass 1) survived more often
#     - Younger passengers were more likely to survive
#     - Fare tends to be higher for survivors (indicating class/facility difference)

# 11. Data Visualization
#     - Use histograms, bar plots, box plots, and heatmaps to represent insights
#     - Customize charts with titles, labels, and colors for clarity

# 12. Summary of Findings
#     - Summarize key observations and insights found during EDA
#     - Mention any assumptions, patterns, or anomalies detected
#     - Prepare the cleaned dataset for further modeling (if needed)

# ------------------------------------------------------------
# END OF DATA CLEANING & EDA PROCESS
# ------------------------------------------------------------
