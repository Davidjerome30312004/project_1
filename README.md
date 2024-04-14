# YouTube Data Harvesting and Warehousing

This project is  harvest data from YouTube using the YouTube Data API in  google developer console, process it using Pandas, store it in a SQL database, and visualize it using Streamlit.

## Overview

This project aims to harvest data from YouTube using the YouTube Data API and store it in a SQL database for further analysis and reporting. By leveraging the YouTube API, we can collect various data points such as video metadata, channel information, comments, likes/dislikes, and view counts.

## Prerequisites
Before running the scripts, make sure you have the following:

 - Google Cloud Platform (GCP) -create an account to access to the YouTube Data API from google developer console.
 - API key obtained from GCP for accessing the YouTube Data API to the scripts.
 - Install Python environment with necessary packages like, google-api-python-client, pandas, sqlalchemy etc..).
 - SQL database (e.g., MySQL, PostgreSQL) set up and accessible.
 - Setup
 - Clone this repository to your local machine:

## modules
  - import os
  - import googleapiclient.discovery
  - import googleapiclient.errors
  - import mysql.connector as db
  - import streamlit as st
  - import pandas as pd 
  - rom streamlit_option_menu import option_menu
  - import mysql.connector

## step by step
-  Create account-Create account in google developer console to retrive the apikey from GCP copy that and paste in api section.
-  Script-Write the scripts by installing the libraries and modules to extract the details.
-  Extraction-extract the channel info,videos id,videos info and comment info and convert into DataFrames.
-  SQL- create a database in sql and give connection followed by create required tables to show in streamlit
-  Streamlit-Crete a navigation  bar and call all datas and visulaize in streamlit 

## REFERENCE
1. repository:

    ```
    git clone https://github.com/Davidjerome30312004/Youtube-data-harvesting-and-warehousing-using-SQL.git
    ```
2. install the packages as in the instalation:

    ```
    pip install -r requirements.txt
    ```




## License
This project is licensed under the MIT License.


