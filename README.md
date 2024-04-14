YouTube Data Harvesting and Warehousing Using SQL
Overview
This project aims to harvest data from YouTube using the YouTube Data API and store it in a SQL database for further analysis and reporting. By leveraging the YouTube API, we can collect various data points such as video metadata, channel information, comments, likes/dislikes, and view counts.

Prerequisites
Before running the scripts, make sure you have the following:

Google Cloud Platform (GCP) account with access to the YouTube Data API.
API key obtained from GCP for accessing the YouTube Data API.
Python environment with necessary packages (e.g., google-api-python-client, pandas, sqlalchemy).
SQL database (e.g., MySQL, PostgreSQL) set up and accessible.
Setup
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/youtube-data-warehouse.git
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Obtain an API key from the Google Cloud Platform (GCP) Console for accessing the YouTube Data API.

Configure your API key in the config.py file:

python
Copy code
API_KEY = 'YOUR_API_KEY_HERE'
Set up your SQL database and configure the connection details in config.py.

Usage
Run the data harvesting scripts to fetch data from the YouTube Data API:

bash
Copy code
python harvest_data.py
Run the ETL (Extract, Transform, Load) process to store the harvested data in the SQL database:

bash
Copy code
python etl_process.py
Perform data analysis and reporting using SQL queries on the stored data.

Project Structure
harvest_data.py: Python script to fetch data from the YouTube Data API.
etl_process.py: Python script for the ETL process to transform and load data into the SQL database.
config.py: Configuration file for API keys and database connection details.
sql_queries/: Directory containing SQL queries for creating tables and performing data analysis.
requirements.txt: List of Python packages required for the project.
Contributing
Contributions are welcome! If you have suggestions or encounter issues, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.


