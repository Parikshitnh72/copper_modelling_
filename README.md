# Industrial Copper Modeling

This project, titled "Industrial Copper Modeling," is an application of data analysis and machine learning techniques to address challenges in the copper industry. It involves building predictive models for both regression (predicting Selling Price) and classification (predicting the success or failure of leads), as well as creating an interactive web application using Streamlit for model deployment
# Approach
Data Understanding:
Identify variable types (continuous, categorical) and their distributions.
Handle categorical variables with '00000' values and treat reference
columns as categorical.
Data preprocessing, including handling missing values and skewness.

# EDA
Visualize outliers and skewness using Seaborn's boxplot, distplot, violinplot.
Feature engineering and identifying highly correlated columns.

#Model Building and Evaluation
Create an interactive Streamlit web application.
Accept input data and perform necessary feature engineering.
Display predictions for Selling Price or Status (Won/Lost).

# Dependencies To run this project, you'll need: Colab Notebook 

Install the dependencies using pip: pip install -r requirements.txt

Usage Clone this repository: git clone https://github.com/yourusername/industrial-copper-modeling.git cd industrial-copper-modeling Place your dataset files in the data/ directory.

Explore the Colab notebook in the  directory for data analysis and model development.

To run the Streamlit app: !streamlit run app.py &>/content/logs.txt & npx localtunnel --port 8501 & curl ipv4.icanhazip.com

Interact with the Streamlit app to make predictions and visualize results.

