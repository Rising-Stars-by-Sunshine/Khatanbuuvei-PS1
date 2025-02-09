# Khatanbuuvei-PS1
# Netflix vs Disney Data Analysis
Data Analysis Setup for Netflix vs Disney Subscriber Growth and Retention
Overview
This repository contains the data analysis for examining how the content offerings (original programming, genre diversity, and franchise presence) and pricing strategies of Netflix and Disney influence subscriber growth and retention across various demographic groups (age, region, and income) from 2018 to 2024.

System Configuration
Local Environment Setup
To run the data analysis on your local machine, you need to have the following dependencies installed:

Python: Ensure that Python (preferably version 3.8 or later) is installed. You can download it from python.org.

Package Manager: If you don’t have pip installed, you can install it by running:

bash
Copy
Edit
python -m ensurepip --upgrade
Required Libraries:

Pandas: For data manipulation and analysis.
Matplotlib: For plotting graphs and visualizations.
Seaborn: For statistical data visualization.
NumPy: For numerical operations.
Scikit-learn: For machine learning models and evaluation.
Install these libraries by running:

bash
Copy
Edit
pip install pandas matplotlib seaborn numpy scikit-learn
Dataset: Download the dataset from the repository. Ensure that all data files are in the correct directory structure as described in the repository.

Cloud Environment Setup
To run the analysis in the cloud, you can use services such as Google Colab or Microsoft Azure Notebooks. Here’s a guide for setting it up in Google Colab:

Google Colab Setup:

Go to Google Colab and create a new notebook.
Mount your Google Drive (if necessary) to upload and access the data.
Use the following code snippet to install the necessary libraries:
python
Copy
Edit
!pip install pandas matplotlib seaborn numpy scikit-learn
Data Files: Upload the dataset from the GitHub repository into your Colab environment by running:

python
Copy
Edit
from google.colab import files
uploaded = files.upload()
Running the Analysis: After setting up the environment, import the required libraries and execute the analysis steps as shown in the notebook.

