# Cinematic-Data-Exploration
This repository contains a Python script for analyzing a dataset containing information about top movies. The dataset is loaded from a CSV file, and various data analysis tasks are performed using popular libraries such as Pandas, Matplotlib, Seaborn, and NumPy.

Getting Started
To use the script and perform movie data analysis on your local machine, follow the instructions below:

Prerequisites
Python 3.x
Jupyter Notebook or any Python IDE (Integrated Development Environment)
Installation
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/your-repository.git
Install the required libraries by running:
Copy code
pip install pandas matplotlib seaborn scipy
Place the top_movies.csv dataset file in the same directory as the Python script.
Analysis Steps
The following analysis steps are performed in the script:

Import the required libraries.
Load the movie dataset from the CSV file and view the first few rows.
Check the total number of rows and columns in the dataset and display the column names.
Get detailed information about the dataset, including column names, non-null count in each column, data types of each column, and memory usage.
Convert the "release_date" column's data type to a datetime type and extract the year from it.
Calculate statistical information such as mean, median, mode, minimum, maximum, etc. for the dataset.
Identify and handle duplicate values in the dataset.
Identify and handle null values in the dataset.
Delete unnecessary columns from the dataset.
Visualize the data using box plots, distribution plots, pair plots, histograms, and a correlation heatmap.
Calculate and remove outliers from the "vote_average" column.
Usage
Open the Python script using Jupyter Notebook or your preferred Python IDE.
Run the script step by step to perform the movie data analysis.
Observe the generated visualizations and explore the analyzed data.
Contribution
Contributions to the project are welcome. If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
