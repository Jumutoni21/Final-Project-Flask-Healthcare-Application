Final-Project-Flask-Healthcare-Application
This project is a Flask web application designed to collect user data, store it in MongoDB, and perform data analysis using Python. The data is then processed, visualized, and the Flask app is deployed on AWS.

Features
Web Development with Flask:
A simple web application built using Flask for user data collection.
Data Storage with MongoDB:
Stores user details like age, gender, income, and expenses in a MongoDB database.
Data Processing with Python:
A Python class User processes the user data and stores it in a CSV file.
Data Visualization:
Data is visualized using Python and Matplotlib.
AWS Deployment:
Flask application is deployed on Amazon Web Services (AWS).
Project Structure
index.py: The main Flask application that collects user data and stores it in MongoDB.
processing.py: A file containing a class which create a csv file.
user_data.csv: The CSV file that contains user data exported from the MongoDB database.
data_analysis.ipynb: A Jupyter notebook used for loading the CSV data, performing data analysis, and creating visualizations.
Instructions
1. Flask Web Application
Create a simple webpage using Flask that collects the following data from users:

Age
Gender
Total Income
Expenses (utilities, entertainment, school fees, shopping, healthcare)
The expense categories are selected using checkboxes.

2. Data Storage with MongoDB
MongoDB is used as the database for storing the collected data. The structure of each entry includes:
Age
Gender
Total Income
Expenses (an array of different expense categories)
3. Data Processing with Python
A User class in Python processes the collected data. Each User object is created with attributes such as age, gender, income, and expenses.
The data is looped through, and each entry is written to a CSV file (user_data.csv).
4. Data Visualization
The CSV data is loaded into a Jupyter notebook for analysis and visualization.
Visualizations include:
Total Income by Age: A bar chart showing the age groups with the highest income.
Gender Distribution Across Spending Categories: A stacked bar chart showing how different genders distribute their spending across the provided categories.
5. Deployment
link to the deployed version

Setup and Installation
Clone the repository:

git clone this repo
cd to "Survey to collect participants data"
Install dependencies: Create a virtual environment and install the required packages:

pip install flask
pip install pymongo
Run the Flask application:

python index.py
Launch the Jupyter notebook: Open the data_analysis.ipynb notebook to run the data analysis and visualizations.

