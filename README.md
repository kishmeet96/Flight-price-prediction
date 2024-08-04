# Flight Price Prediction

## Business Problem :-
To know how unexpectedly the prices vary. The cheapest available ticket on a given flight 
gets more and less expensive over time. This usually happens as an attempt to maximize 
revenue based on. 

(1) Time of purchase patterns (making sure last-minute purchases are expensive.

(2) Keeping the flight as full as they want it (raising prices on a flight which is filling up in 
order to reduce sales and hold back inventory for those expensive last-minute expensive 
purchases)


## Project Summary
This project investigates the fluctuations in flight ticket prices over time, leveraging data scraped from the MakeMyTrip website. By employing web scraping techniques and various machine learning models, the study aims to understand price dynamics and customer preferences for airlines. The analysis involves detailed data preprocessing, exploratory data analysis (EDA), and regression modeling to forecast flight prices and reveal trends in customer choices.

## Key Highlights 

### • Business Problem Framing:

Investigated price variability of flight tickets, focusing on how prices increase or decrease over time.
Analyzed revenue optimization strategies such as pricing for last-minute purchases and managing flight occupancy.

### • Data Collection and Preprocessing:

#### • Data Collection: 

Utilized Selenium for web scraping to gather flight information from MakeMyTrip.

#### • Data Preprocessing:

• Cleaned data by removing currency symbols and extra spaces.

• Converted and separated "Departure Time" and "Arrival Time".

• Parsed flight duration into hours and minutes.

• Created dummy variables for "Airline_Name" and converted "Total_stops" into binary values.

• Applied concatenation methods for data integration.

### • Analytical Techniques:

• Exploratory Data Analysis (EDA): Employed statistical and visual methods including swarm plots, box plots, and count plots to explore data patterns.

• Data Visualization: Used Matplotlib and Seaborn for comprehensive data visualization.

### • Model Development and Evaluation:

• Regression Models Applied:

K-Nearest Neighbors Regressor (98% accuracy)

Decision Tree Regressor (98% accuracy)

Random Forest Regressor (98% accuracy)

• Analyzed the preference for airlines, highlighting IndiGo as the most preferred and AirAsia as the least, with non-stop flights favored over one-stop flights.

### • Tools and Technologies:

• Programming Languages: Python

• Libraries and Frameworks: Selenium, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

• Techniques Used: Web scraping, data cleaning, exploratory data analysis, regression modeling

### • Learning Outcomes:

• Gained practical experience in data scraping, preprocessing, and machine learning model application.

• Enhanced skills in statistical analysis and data visualization to derive actionable insights from complex datasets.

## Snapshots

![image](https://github.com/user-attachments/assets/57eecfd4-57f1-4451-a0c8-1f22dd98b6dc)

![image](https://github.com/user-attachments/assets/484f12e4-96e0-453e-9d20-6af3f0606b02)

![image](https://github.com/user-attachments/assets/88ae53f4-bacd-42e4-8d64-fb6bea35aae3)

![image](https://github.com/user-attachments/assets/3e00ae00-4389-4643-9c98-9aeea34328f7)
