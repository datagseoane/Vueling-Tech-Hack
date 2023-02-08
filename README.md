# Vueling Tech Hack
This repository contains the solution to the [VUELING TECH HACK](https://nuwe.io/dev/competitions/vueling-tech-hack/dashboard-datascience-challenge).  
My name is [Guillermo Seoane](https://www.linkedin.com/in/guilleseoane/) and I'm a **#DataScience** student at the **IT Academy de Barcelona Activa**.

## Dashboard-Data Science Challenge

✈️ Context:
At the last Annual General Assembly of IATA, the zero net CO₂ emissions in 2050 (aviation sector) resolution finally got approved. That lets us be one step closer to the Paris Agreement of 2015, accomplishing not exceeding 1.5 ºC the Earth's temperature.

🦾 Overview:

**Dataset Dictionary:**

* **Date:** Flight date.
* **Origin_Country :** Country of origin.
* **Origin_Continent :** Continent of origin.
* **Destination_Country:** Country of destination. Target variable.
* **Destination_Continent:** Destination continent.
* **Total_flights:** Total number of flights.
* **Total_seats:** Total number of seats.
* **Total_ASKs:** (Available Seat Kilometer). Total seat numbers available by the total number of km these seats have flown.

**Archives:**  
The data has been split into two groups:

* The **training set** has been used to build the machine learning models. [Download 'train.csv'](https://github.com/datagseoane/Vueling_Hack/blob/main/data/train.csv)
* The **test set** has been used to see how well our model performs on unseen data. For the test set, the *Destination Country* variable is not provided. [Download 'test.csv'](https://github.com/datagseoane/Vueling_Hack/blob/main/data/test.csv)

In the repository you can also find:
* **Exploratory_analysis** of the data,that allows you to understand it better and find insights (ex: flights per month, most used routes, etc.) based on "Mapping Destination Countries". [Download 'Mapping Destination Countries'](https://github.com/datagseoane/Vueling_Hack/blob/main/encode_countries.json)
* **Model:** model used for prediction.
* A **ppt** explaining how I have reach the solution

📚 **Evaluation:**
The metric used to evaluate the predictive algorithm has been **F1 Score Macro**. 
* **f1-SCORE: 0.97**
* **Model:** RandomForestClassifier

✅ Submission:

* [Download 'JSON'](https://github.com/datagseoane/Vueling_Hack/blob/main/target.json)

Date: 08/02/2023
