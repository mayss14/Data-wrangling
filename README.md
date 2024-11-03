# Data Wrangling Project
This project demonstrates essential data wrangling techniques, converting raw data into a structured format suitable for analysis. This is a step-by-step guide using Python's pandas library for reading, cleaning, and preparing data, specifically for automobile data analysis.

### Table of Contents
Project Overview
Dataset
Requirements
Key Steps
Usage
Results

## Project Overview
The goal of this notebook is to clean and organize a raw dataset containing information about various cars, making it ready for further analysis. The project covers basic data wrangling techniques such as:

Importing data
Handling missing values
Renaming columns
Data type conversions
Exploratory Data Analysis (EDA)

## Dataset
The dataset used in this project contains various attributes of cars, including specifications and performance data. The dataset is loaded from an external URL:

Source: Auto.csv
Attributes: symboling, normalized-losses, make, fuel-type, aspiration, num-of-doors, body-style, drive-wheels, engine-location, wheel-base, length, width, height, curb-weight, engine-type, num-of-cylinders, engine-size, fuel-system, bore, stroke, compression-ratio, horsepower, peak-rpm, city-mpg, highway-mpg, price

### Requirements
pandas
matplotlib
numpy
Install the requirements using:

pip install pandas matplotlib numpy

### Key Steps
Loading Data: The dataset is imported using pandas.
Renaming Columns: Columns are renamed for easier reference.
Data Cleaning: Missing values are handled, and erroneous data entries are corrected.
Data Transformation: Columns are converted to appropriate data types as needed for analysis.
Exploratory Data Analysis: Basic EDA is performed using histograms, scatter plots, and descriptive statistics.

### Usage
Run the cells in the notebook sequentially to replicate the data wrangling process. The notebook provides comments to guide you through each step.

### Results
By the end of this project, the dataset is structured, cleaned, and ready for analysis, enabling further exploration and modeling.
