# PRODIGY_DS_02

# ✅ Task 2 – Data Cleaning and Exploratory Data Analysis on the Titanic Dataset

# 📊 Description:

In this task, we perform data cleaning and exploratory data analysis (EDA) on the Titanic test dataset using Python. The primary goal is to understand the structure, detect and handle missing values, and analyze the distribution and relationships of various features such as Age, Fare, Pclass, Sex, and Embarked.

Through visualizations like histograms, count plots, and scatter plots, we uncover trends and insights about the passengers aboard the Titanic. Although this test set does not include survival information, the analysis provides a foundation for understanding passenger demographics and potential survival patterns.

# 🧑‍💻 Technologies Used:

Python

Pandas – Data loading, cleaning, and preprocessing

NumPy – Handling numerical data

Matplotlib & Seaborn – Visualization and statistical graphics

# 🚀 Key Features Implemented:

Loaded Titanic dataset (test.csv) and reviewed structure with .info() and .describe()

Identified and handled missing values in:

Age: filled with mean age

Fare: filled with mean fare

Cabin: filled with "Unknown"

Dropped rows with critical missing values (if any)

Verified for and confirmed absence of duplicate entries

Visualized data to identify patterns:

Histogram for age distribution

Count plot for gender distribution

Scatter plot of age vs fare

Used descriptive statistics to summarize numeric features

# 📌 Visual Outputs:

Age Distribution: Histogram with KDE overlay

Gender Distribution: Count plot showing number of male vs female passengers

Scatter Plot: Age vs Fare with hue by age

Optional: bar plots and box plots for further insights (e.g., by class or embarkation port)

# 📁 Dataset Used:

test.csv – The test portion of the Titanic dataset from Kaggle, containing information on passengers excluding the target variable Survived.
