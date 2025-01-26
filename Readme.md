# NYC Motor Vehicle Collisions Data Analysis

This repository contains a data analysis project focused on exploring the New York City Motor Vehicle Collisions dataset. The goal of the project is to clean, preprocess, analyze, and visualize data to uncover insights related to vehicle crashes, contributing factors, trends, and geographical patterns.

## Project Milestones

### Milestone #1 - Data Preparation
The main goal of this milestone is to set up the environment, install required packages, and perform initial exploratory data analysis.

#### Libraries Used:
- **Pandas**: A data manipulation library for Python that provides data structures and functions for working with structured data such as tables and time series.
- **Matplotlib**: A Python library used for 2D plotting and visualizing data through graphs like bar charts, line graphs, and histograms.
- **Seaborn**: A high-level data visualization library based on Matplotlib that provides an easy interface for creating attractive and informative statistical graphics.

#### Steps:
- **Install and set up required libraries**
- **Mount Google Drive to access the dataset**
- **Perform initial exploratory data analysis (EDA)** to understand the structure and missing values in the dataset.

### Milestone #2 - Data Ethics, Pre-Processing, and Exploration
The goal of this milestone is to assess the dataset for missing values and decide what to do with those data points.

#### Key Insights:
- **Data Ethics**: Ethical considerations include the potential biases in data collection, particularly regarding well-resourced versus under-resourced communities, and the absence of data affecting the representativeness of the samples.
- **Missing Values**: Several columns, including `VEHICLE TYPE CODE 5` and `CONTRIBUTING FACTOR VEHICLE 5`, have a high percentage of missing values. This is expected, as not all crashes involve multiple vehicles or factors.
  
#### Exploratory Analysis:
- **Top Contributing Factors**: Driver Inattention/Distraction, Failure to Yield Right-of-Way, and Following Too Closely.
- **Recommendations for Drivers**: Minimize distractions, maintain a safe following distance, and adapt driving based on weather conditions.

### Milestone #3 - Time Series Analysis
In this milestone, we explore time-based trends to understand patterns in crashes over different time intervals.

#### Key Insights:
- **Crash Trends by Time of Day**: The highest frequency of crashes occurs between 16:00 and 17:00, likely due to increased traffic from people finishing work and reduced visibility due to sunset.
- **Impact of COVID-19 on Crashes**: We will analyze how COVID-19 affected crash rates per month.

### Milestone #4 - Geospatial Analysis
The goal of this milestone is to explore the geographical aspects of the dataset, such as borough-wise crash frequency and spatial patterns.

#### Key Insights:
- **Highest Number of Crashes**: Brooklyn has the highest number of crashes, likely due to its high population density and traffic volume.
- **Lowest Number of Crashes**: Staten Island has the lowest number of crashes, likely due to its lower population density and less traffic congestion.

## Conclusion
This project provides valuable insights into the factors contributing to motor vehicle crashes in New York City, as well as time and spatial trends that can inform public safety initiatives. It emphasizes the importance of ethical considerations when working with real-world datasets and highlights key patterns and recommendations for improving road safety.

## Technologies and Tools
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab (for data analysis and visualization)

## Getting Started
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Karthik-MP/NSDC-Transportation-Data-Science-Project.git

2. [Download Dataset](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
