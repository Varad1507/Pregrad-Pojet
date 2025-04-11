# Pregrad-Project

Zomato Bangalore Restaurants Analysis
This project analyzes the Zomato Bangalore restaurant dataset to gain insights into the food and dining preferences of the city. It includes data cleaning, exploratory data analysis (EDA), and preprocessing to prepare the data for potential machine learning applications.

📁 Dataset
The dataset used is a CSV file named zomato.csv, which contains information about restaurants in Bangalore including:

Name, location, cuisines

Ratings and votes

Cost for two people

Online delivery and table booking availability

Restaurant type and listed-in categories

📊 Workflow Summary
1. Importing Libraries
Standard Python libraries are used:

pandas, numpy for data manipulation

matplotlib, seaborn for visualization

sklearn for potential modeling tasks

2. Data Cleaning
Dropped irrelevant columns: url, dish_liked, phone

Removed duplicate rows

Handled missing values by dropping them

Renamed columns for simplicity: e.g., 'approx_cost(for two people)' → 'cost'

Converted the cost column from string (with commas) to float

3. Data Exploration
Analyzed unique values in important features like rate, cost, cuisines, etc.

Explored distribution of ratings and votes

Investigated relationships between cost, rating, and other features

Visualized data using histograms, bar plots, and count plots

4. Feature Engineering
Transformed and encoded categorical variables

Prepared data for modeling by cleaning and structuring

5. (Optional/Planned) Model Building
While the notebook mainly focuses on data analysis and cleaning, logistic regression and other sklearn modules are imported, suggesting plans to build a prediction model (possibly for rating or online delivery).

📈 Key Insights (To Add)
Distribution of restaurant costs across the city

Correlation between rating and cost

Most popular cuisines and locations

Influence of online delivery and table booking on restaurant ratings
