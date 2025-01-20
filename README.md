# Algerian Forest Fire Weather Index (FWI) Prediction
### Project Overview
This project aims to predict the Fire Weather Index (FWI) using various weather-related attributes from the Algerian Forest Fires Dataset. The dataset includes observations from two regions in Algeria (Bejaia and Sidi Bel-abbes) over the period from June 2012 to September 2012.

### Dataset Information
The dataset contains 244 instances with 11 attributes and 1 output attribute (class). It has been classified into two classes: fire (138 instances) and not fire (106 instances). ... (pack the attributes info into a neat block)

### Prediction Models
Several machine learning models were used to predict the FWI, including:

Linear Regression

Lasso Regression

Elastic Net Regression

### Deployment
The final model was deployed using Flask, allowing for easy and efficient prediction of FWI based on input attributes such as temperature, relative humidity (RH), wind speed (Ws), and rain. Additionally, I have learned how to deploy the project on Amazon Web Services (AWS) to ensure scalability and accessibility.
### Clone the repository.

Install the necessary dependencies listed in requirements.txt.

Run the Flask application by executing python app.py.

Access the web application and input the required attributes to predict the Fire Weather Index (FWI).
