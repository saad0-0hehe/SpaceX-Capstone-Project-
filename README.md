SpaceX Launch Analysis 🚀

This project analyzes SpaceX Falcon 9 launch records using data science and machine learning techniques. The goal is to predict the likelihood of a successful first-stage landing and explore the factors that influence launch outcomes.

📂 Project Structure
.
├── spacex_launch_dash.csv     # Dataset
├── spacex_dash_app.py         # Dash web application
├── spacex_folium_map.ipynb    # Folium mapping notebook
├── spacex_ml.ipynb            # Machine learning models
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation

📊 Features

Exploratory Data Analysis (EDA):

Payload distribution

Success rates by launch site

Booster version analysis

Interactive Dashboard (Plotly Dash):

Dropdown to filter by launch site

Pie chart of success/failure

Scatter plot of payload vs. success

Geospatial Analysis (Folium):

Launch site locations

Proximity to railways, highways, coastlines, and cities

Distance calculations with markers and polylines

Machine Learning Models:

Logistic Regression

Support Vector Machines (SVM)

Decision Trees

K-Nearest Neighbors (KNN)

Hyperparameter tuning with GridSearchCV

Evaluation with confusion matrix & accuracy scores



📈 Results

Logistic Regression achieved good accuracy but showed false positives.

SVM and Decision Trees improved classification performance.

Launch site and payload mass are key predictors of success.

Launch sites are generally close to coastlines but away from major cities.

📚 Dataset

The dataset was collected from SpaceX API and additional sources. It includes:

Launch Site

Payload Mass (kg)

Booster Version Category

Landing Outcome (success/failure)

🙌 Acknowledgments

IBM Data Science Capstone Project (Coursera)

SpaceX open data

Folium, Plotly Dash, Scikit-learn
