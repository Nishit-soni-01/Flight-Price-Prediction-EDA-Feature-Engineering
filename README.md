# Flight Price Prediction: EDA & Feature Engineering ✈️

## 📌 Project Overview
As a Data Analyst, I conducted an in-depth Exploratory Data Analysis (EDA) and Feature Engineering on flight booking data. This project transforms raw categorical and temporal flight data into a machine-learning-ready format to predict ticket prices across major Indian cities.

## 🎓 About the Author
* **Name:** Nishit Soni
* **Education:** 3rd Year B.Tech in Electrical and Computer Science Engineering
* **Certification:** Certified Data Analyst (Udemy)
* **Specialization:** Data Analysis, Machine Learning, and Competitive Programming

## 📊 Dataset Features
The dataset includes information on 6 airlines and 6 unique cities:
* **Temporal:** Departure Time, Arrival Time, Days Left.
* **Categorical:** Airline, Source/Destination City, Seat Class, Total Stops.
* **Target:** Ticket Price.

## 🛠️ Data Engineering Steps
In this project, I performed the following technical transformations:
1. **Handling Missing Values:** Imputed missing values in the `Total_Stops` and `Route` columns.
2. **Temporal Extraction:** Split `Date_of_Journey` into Date, Month, and Year (Integer format).
3. **Time Normalization:** Converted `Arrival_Time` and `Dep_Time` into Hours and Minutes.
4. **Categorical Encoding:** Applied **OneHotEncoder** to transform Airlines, Source, and Destination into numerical vectors.
5. **Feature Mapping:** Manually mapped `Total_Stops` (e.g., 'non-stop' to 0) to preserve ordinal relationships.

