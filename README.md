📌 Project Title: Flight Price Prediction & Data Analysis
📝 Project Description

This project focuses on analyzing historical flight price data to understand key factors influencing airfare and prepare the dataset for predictive modeling. The dataset contains 10,683 records with 11 features, including airline name, travel route, duration, number of stops, departure time, and ticket price.

The process involves data cleaning, preprocessing, exploratory data analysis (EDA), and feature engineering to derive meaningful insights from the dataset.

🔍 Key Steps & Analysis
✔️ 1. Data Loading & Inspection

The dataset was imported and inspected for structure, column types, shape, and missing values.

Initial observation showed multiple columns stored as object type requiring conversion to proper formats (dates, numerics, categories).

✔️ 2. Handling Missing Values

A systematic approach was used:

Numerical columns: Filled using median to handle skewness.

Categorical columns: Filled using mode to retain the most frequent value.

🧹 Data Cleaning & Feature Engineering

Date columns converted to datetime format.

New meaningful features extracted, such as:

Day of Journey

Month & Year of Journey

Categorical features prepared for model compatibility.

📊 Exploratory Data Analysis (EDA)
Univariate & Distribution Study

A histogram of airline ticket prices revealed that most ticket prices fall in a lower price range.

Distribution is right-skewed, showing the presence of premium-priced outliers such as business or last-minute tickets.

📈 Insights

Flight prices vary significantly depending on:

Airline

Number of stops

Travel duration

Travel month or season

Departure and arrival time patterns

Presence of outliers indicates a clear distinction between budget travel and premium class bookings.
