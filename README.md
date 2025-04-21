# 🚔Patrol-check-post Analysis
  📖 Project Description
        > This project is a data analysis tool designed to gain insights from police check post activity data. It uses a combination of Python, Pandas, SQL queries       trends, and insights from the dataset. The analysis is presented in a user-friendly web interface built using Streamlit.The system is designed to assist            police officers in managing vehicle checks, recording incidents at check posts more effectively. It replaces manual record-keeping with a streamlined, secure       digital interfaceand system developed to enhance the security and efficiency of police check posts by enabling digital monitoring and real-time data logging.
**✨ Features**
        Data exploration and visualization of check post activities
        SQL query integration for flexible data querying
        Interactive Streamlit dashboard
**🛠 Tech Stack**
    This project was built using:
      * Python – for data handling and backend logic
      * Pandas – for data manipulation and analysis
      * MySQL –  to query the dataset
      * Streamlit – for building an interactive web interface
**Tools used**
     Installed:-
            pip install pandas
            pip install openpyxl
            pip install mysql-connector-python
            pip install tabulate
            !streamlit run app.py
      imported:-
            import pandas as pd 
            import mysql.connector
            from tabulate import tabulate            
            import streamlit as st
            import matplotlib.pyplot as plt
            import seaborn as sns
**Data cleaning process**
            Handled the missing values/Null values in the traffic_dataset using mode function for categorical values.Used python code in Jupyter notebook to process the data.
**Database design and Explaination**
        Created the database and Table in mysql workbench.
        Inserted the values as a list to the table from the cleaned dataset.
        Written the query in python to connect Mysql through mysql-connector-python.
        Fetched the output of query in python as the table in a grid form using tabulate.
        Created the interactive Streamlite dashboard to visualise the given data by getting the input from the user.used different tools to show the 
        data in the form of line graph,bar graph,...
        Predicated the stop outcome by providing the different selectbox to choose the category such as country name,stop time,..and display the predication in the         attractive way. 






