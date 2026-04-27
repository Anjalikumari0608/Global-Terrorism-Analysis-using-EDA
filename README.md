# Global-Terrorism-Analysis-using-EDA

<img width="800" height="400" alt="WhatsApp Image 2026-04-26 at 23 09 16" src="https://github.com/user-attachments/assets/8dabf73b-80be-4ab0-9822-d47c8945ec31" />

# 📌Project Overview
This project focuses on analyzing global terrorism data from 1970 to 2017 using Exploratory Data Analysis (EDA) techniques. The main objective is to identify patterns, trends, and key insights related to terrorist activities across different countries and regions.

The dataset includes important information such as year, country, region, attack type, and casualties (killed and wounded). Initial steps involved data cleaning, handling missing values, and selecting relevant features for analysis.

The analysis reveals that terrorist activities have increased significantly over time, especially after 2000. Countries like Iraq, Afghanistan, and Pakistan are among the most affected. Bombings and explosions are the most common types of attacks, followed by armed assaults. Region-wise, the Middle East and South Asia show a higher frequency of incidents.

Additionally, casualty analysis indicates that the number of wounded people is generally higher than fatalities, highlighting the severe impact of such incidents.

Overall, this project provides meaningful insights into global terrorism trends, helping in better understanding patterns and supporting effective decision-making for prevention and strategic planning.

# 🎯 Problem Statement
The objective of this project is to perform Exploratory Data Analysis (EDA) on the Global Terrorism Dataset to understand patterns, trends, and key factors related to terrorist activities across the world. The analysis focuses on identifying the most affected countries, regions, attack types, and yearly trends in terrorist incidents. By analyzing this data, we aim to gain meaningful insights that can help in understanding the severity and distribution of global terrorism.

# 💼 Business Objective
The objective of this project is to analyze the UNGTA terrorism dataset to uncover meaningful patterns and trends that can help governments, researchers, and security agencies understand the global landscape of terrorism. By identifying high-risk regions, common attack methods, major terrorist groups, and casualty patterns, the analysis aims to support better decision-making and more effective counter-terrorism strategies.

# EDA Workflow based on Objective

<img width="1024" height="1536" alt="WhatsApp Image 2026-04-26 at 22 52 28" src="https://github.com/user-attachments/assets/ead71e67-8226-40ae-884e-3ccc02aa096a" />

# 📂 Dataset Information
The Global Terrorism Dataset includes the following key variables:

* iyear – Year of incident
* country_txt – Country where attack occurred
* region_txt – Region of the world
* attacktype1_txt – Type of attack
* gname – Terrorist group name
* nkill – Number of people killed
* nwound – Number of people wounded

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

# 🛠️ Technologies Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

# 📈 Key Insights
* Terrorist attacks increased significantly after 2000
* Middle East & North Africa region has highest attacks
* Terrorism is concentrated in specific countries
* Bombing and armed assault are most common attack types
* Few terrorist groups dominate attack frequency
* Casualties fluctuate with peaks in certain years
* Some countries experience significantly higher casualties
* High severity incidents are limited but impactful

# 📌 Solution to Business Objective
Based on the analysis, I suggest focusing on high-risk regions and frequently occurring attack types by strengthening security measures and surveillance systems. Governments and organizations should allocate more resources to vulnerable areas and implement preventive strategies such as intelligence monitoring and emergency response planning.

Using data-driven decision making can help reduce the number of incidents, improve public safety, and enhance overall economic stability.

# 📌 Conclusion
In this project, I performed exploratory data analysis on global terrorism data to identify patterns, trends, and key factors influencing attacks. The visualizations helped in understanding high-risk regions, common attack types, and casualty distributions.

The insights obtained from this analysis can support better decision-making, strengthen security policies, and minimize risks. Overall, this project highlights the importance of data analysis in improving public safety and strategic planning.

  
