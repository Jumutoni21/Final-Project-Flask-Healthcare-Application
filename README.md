**Final Project: Flask Healthcare Application**

**Overview**

This project is a web application built with Flask, designed to gather user data, store it in MongoDB, and conduct data analysis using Python. The processed data is visualized, and the Flask app is hosted on AWS.

**Features**

1. Web Development with Flask

- A user-friendly web application that collects data through a simple interface.

2. Data Storage with MongoDB

- User information, including age, gender, income, and expenses, is stored in a MongoDB database.

3. Data Processing with Python

- A Python class, User, processes the collected data and saves it in a CSV format.

4. Data Visualization

- Data is visualized using Python libraries, particularly Matplotlib.

5. AWS Deployment

- The Flask application is deployed on Amazon Web Services (AWS).

**Project Structure**

- index.py: The main Flask application responsible for collecting user data and storing it in MongoDB.
- processing.py: A module containing a class that generates a CSV file from the collected data.
- user_data.csv: The CSV file that holds user data exported from the MongoDB database.
- data_analysis.ipynb: A Jupyter notebook used for importing the CSV data, performing analysis, and creating visualizations.

**Instructions**

**Flask Web Application**

Create a straightforward webpage using Flask to collect the following user information:

- Age
- Gender
- Total Income
- Expenses (categories: utilities, entertainment, school fees, shopping, healthcare)
Users can select expense categories using checkboxes.

**Data Storage with MongoDB**

Utilize MongoDB as the database for storing the collected data. Each entry will include:

- Age
- Gender
- Total Income
- Expenses (represented as an array of various categories)

**Data Processing with Python**

Implement a User class in Python to handle the collected data. Each User object will have attributes such as age, gender, income, and expenses. The data will be iterated over, and each entry will be written to a CSV file (user_data.csv).

**Data Visualization**

Load the CSV data into a Jupyter notebook for analysis and visualization. The visualizations will include:

- Total Income by Age: A bar chart illustrating which age groups have the highest income.
  
- Gender Distribution Across Spending Categories: A stacked bar chart depicting how different genders allocate their spending across the specified categories.

**Deployment**

[Link to the deployed version of the application](http://51.20.109.173:8080/)

Setup and Installation
Clone the Repository:

git clone [repository-url]
cd "final project flask healthcare application"

Install Dependencies:
Create a virtual environment and install the necessary packages:

pip install flask
pip install pymongo

Run the Flask Application:

python index.py

Launch the Jupyter Notebook:
Open the data_analysis.ipynb notebook to execute data analysis and visualizations.

