# Global-Terrorism-Analysis-using-EDA

<img width="800" height="400" alt="WhatsApp Image 2026-04-26 at 23 09 16" src="https://github.com/user-attachments/assets/8dabf73b-80be-4ab0-9822-d47c8945ec31" />

# 📌Project Overview
This project focuses on analyzing global terrorism data from 1970 to 2017 using Exploratory Data Analysis (EDA) techniques. The primary objective is to understand patterns, trends, and insights related to terrorist activities across different countries and regions. Terrorism has been a major global issue, and analyzing such data helps in identifying high-risk areas and common attack patterns.

The dataset used in this project contains detailed information about terrorist incidents, including year, country, region, type of attack, number of people killed, and number of people wounded. Initially, the dataset was loaded and basic data cleaning was performed. Missing values were handled, and only relevant columns such as Year, Country, Region, Attack Type, Killed, and Wounded were selected for analysis.

Various visualizations were created to better understand the data. A year-wise analysis showed that terrorist activities have increased significantly over time, especially after the year 2000. This indicates a rising global concern regarding terrorism. Country-wise analysis revealed that countries like Iraq, Afghanistan, and Pakistan are among the most affected by terrorist attacks.

Further analysis of attack types showed that bombing and explosion are the most common forms of terrorist attacks, followed by armed assaults. This indicates that explosive-based attacks are widely used due to their high impact. Region-wise analysis highlighted that the Middle East and South Asia are the most affected regions, showing a higher frequency of attacks compared to other regions.

Additionally, casualty analysis was performed to understand the impact of these attacks. It was observed that the number of wounded people is generally higher than the number of fatalities, indicating the severe impact of such incidents on human lives.

Overall, this project provides meaningful insights into global terrorism trends. These insights can be useful for governments, security agencies, and policymakers to improve preventive measures and strategic planning. The use of data visualization makes it easier to interpret complex data and identify important patterns effectively.

# 🎯 Problem Statement
The objective of this project is to perform Exploratory Data Analysis (EDA) on the Global Terrorism Dataset to understand patterns, trends, and key factors related to terrorist activities across the world. The analysis focuses on identifying the most affected countries, regions, attack types, and yearly trends in terrorist incidents. By analyzing this data, we aim to gain meaningful insights that can help in understanding the severity and distribution of global terrorism.

# 💼 Business Objective
The objective of this project is to analyze the UNGTA terrorism dataset to uncover meaningful patterns and trends that can help governments, researchers, and security agencies understand the global landscape of terrorism. By identifying high-risk regions, common attack methods, major terrorist groups, and casualty patterns, the analysis aims to support better decision-making and more effective counter-terrorism strategies.

# EDA Workflow based on Objective

<img width="1024" height="1536" alt="WhatsApp Image 2026-04-26 at 22 52 28" src="https://github.com/user-attachments/assets/ead71e67-8226-40ae-884e-3ccc02aa096a" />

# 📂 Dataset Information
The Global Terrorism Dataset includes the following key variables:

iyear – Year of incident
country_txt – Country where attack occurred
region_txt – Region of the world
attacktype1_txt – Type of attack
gname – Terrorist group name
nkill – Number of people killed
nwound – Number of people wounded

# 🧹 Data Preprocessing
In the data wrangling process, missing values were handled by removing columns with more than 50% null values. Remaining missing values in numerical columns were filled using median, and categorical columns were filled using mode.

Duplicate records were checked and no significant duplicates were found, ensuring data quality. After cleaning, the dataset was reduced to 58 columns from the original dataset, making it more efficient for analysis.

Insights: The dataset is large with over 181,000 records and contains significant missing values initially. After cleaning, the data became more structured and reliable, making it suitable for further analysis and visualization.

# 🔍 Exploratory Data Analysis
EDA was performed to understand terrorism patterns and global trends.

Analysis Performed

* Terrorist attacks per year
* Country wise attack analysis
* Region wise distribution
* Attack type analysis
* Terrorist group analysis
* Casualty distribution
* Total casualties over time
* Region wise casualties
* Country wise casualties

# 📊 Visualizations Included
* Number of Attacks per Year
* Top 10 Countries with Highest Terrorist Attacks
* Number of Terrorist Attacks by Region
* Top 10 Most Common Attack Types
* Top 10 Weapon Types Used in Terrorist Attacks
* Success vs Failure of Terrorist Attacks
* Number of Attacks by Month
* Top 10 Target Types
* Top 10 Attack Types
* Total Deaths per Year due to Terrorist Attacks
* Corelation Heatmap(Year, kill, casualities and wounded)
* Pair Plot(Year, kill, casualities and wounded)

# 📈 Key Insights

  
