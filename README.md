# Carbon-Emissions-Prediction
Carbon emissions prediction involves forecasting greenhouse gas emissions to inform decision-making and reduce climate change impacts. It uses data and machine learning to predict emissions trends, enabling proactive measures for sustainability.

# Description of The Project:
Business Objective of the project

The primary objective of the project is to develop a model that can accurately predict CO2 emissions based on different engine features of cars.

The goal is to estimate the amount of CO2 a car will emit using the provided data.

# Tools and Technologies:
The project was developed using various tools and technologies, including:

Python programming language

Libraries such as NumPy, Matplotlib, SciPy, scikit-learn, and Streamlit

Linear Regression, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Regression (SVR) models for prediction

Deployment on the cloud using Streamlit
# How to install these libraries?
You can install these libraries by using the command.

You can install all the libraries in your system which I have used in my project by using only one command.

You will need Python in your system to use this command. You can use this given link to install Python in your system : Python

After installation of Python, you need to run this command in your command prompt.

pip install -r requirements.txt 

# Running the Project:
To run the project locally, one can install the required libraries using the provided command in the command prompt. Use the below Streamlit command to launch the application.
streamlit run app.py 


# ✅ Week 1 Milestone Completed: Stage 1 – Data Cleaning & Preparation 

Used the original Excel dataset (Dataset.xlsx) without converting to CSV

Loaded different sheets directly using pandas.read_excel() @@ -27,8 +27,29 @@ The goal is to explore and prepare a climate dataset (CO₂ emissions & other gr
Pandas

Jupyter Notebook

# 🚀 Ready for Week 2

The dataset is now cleaned and prepared, ready for:

Visualization
Machine Learning model building (Regression, Forecasting, etc.)

# ✅ Week 2 Milestone Completed: Stage 2 – Data Exploration & Visualization

Imported Cleaned Dataset: Used data_clean.csv generated in Stage 1.

Visualized Global Trends: Plotted relationships between CO₂ emission and country-specific indicators.

Explored Columns and Units: Identified key columns and decoded abbreviations from the dataset.

Feature Engineering: Selected relevant features and removed unnecessary ones.

Created Visualizations:

  Correlation matrix heatmap for feature dependencies
  Scatterplots to examine distribution
  
Histograms for pattern discovery

Outlier detection using visual tools

Detected Dependencies & Trends: Observed connections and trends in the data based on the visualizations.

# 📁 Files Included

data_exploration.ipynb → Jupyter Notebook for EDA, feature analysis, and plots

# 🛠 Tools Used

Pandas

Matplotlib

Seaborn

numpy

Jupyter Notebook
