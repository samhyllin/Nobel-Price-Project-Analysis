# Nobel-Price-Project-Analysis

## Background
This project analyzes historical Nobel Prize data to uncover patterns across laureates, prize categories, gender distribution, countries of birth, organizations, and prize shares. The dataset contains rich information about winners, including their demographics, affiliations, award categories, and how prizes were shared.

The goal of the project is to explore long-term trends in global recognition, representation, and institutional impact using data-driven analysis and visualization.

## Project Structure
```
│
├── • data
│ └── • nobel_prize_data.csv
│
├── • notebooks
│ └── • nobel_prize_analysis.ipynb
│
├── • images
│ ├── • gender_distribution_pie.png
│ ├── • prizes_per_category_bar.png
│ ├── • prizes_over_time_trend.png
│ ├── • top_birth_countries_bar.png
│ └── • top_organizations_bar.png
│
└── • README.md
```

## Data Cleaning
Key preparation steps included:
```
• Checking for duplicates and confirming none existed
• Identifying missing values across columns
• Interpreting missing birth dates correctly for organizations
• Converting birth_date from text to datetime format
• Engineering a new column share_pct from fractional prize shares
• Validating data types for consistent analysis
```

These steps ensured the dataset was reliable and structured for deeper exploration.

## Analysis and Visualization
The analysis covered several major areas:
```
• Gender Distribution
• Visualized male vs female representation across laureates
• Created donut charts to highlight imbalance across categories

• Multiple-Time Winners
• Identified individuals and organizations that won more than once
• Revealed repeat winners such as Marie Curie and the Red Cross

• Top Birth Countries
• Analyzed which countries produced the most Nobel laureates
• Bar chart revealed the United States as the highest contributor

• Prize Categories
• Counted total prizes awarded per category
• Visualized distribution using vertical bar charts

• Category by Gender
• Compared male vs female winners across categories
• Highlighted strong gender gaps in Physics, Chemistry, and Medicine

• Prizes Over Time
• Analyzed number of prizes awarded per year
• Applied rolling average to reveal long-term trends

• Top Organizations
• Identified institutions with the highest number of Nobel-affiliated winners
• Horizontal bar chart showed dominant research institutions globally
```

## Project Overview
The project focuses on:
```
• Exploring gender distribution among Nobel laureates
• Identifying countries with the highest number of winners
• Analyzing prize distribution across categories
• Detecting repeat winners and organizations with multiple awards
• Examining how prizes are shared among winners
• Tracking how the number of prizes awarded changes over time
```

This project demonstrates strong skills in data cleaning, feature engineering, aggregation, visualization, and analytical storytelling.

## Tool Used
```
• Python
• pandas for data manipulation and aggregation
• numpy for numerical operations
• matplotlib for static visualizations
• seaborn for statistical visualizations
• plotly for interactive charts
```

## Key Insights
```
• Male winners heavily dominate most Nobel categories
• The United States leads significantly in total laureates by birth country
• Physics, Chemistry, and Medicine have the highest prize volumes
• Only a small number of individuals and organizations have won multiple times
• Prize activity has grown over time with clear historical trends
• Certain institutions consistently produce high-impact laureates
```
## Project Summary
This project analyzes Nobel Prize data to uncover patterns across years, categories, gender, countries, and institutions. The dataset includes laureate details, prize categories, birth information, organizations, and prize shares. The analysis focuses on data cleaning, feature engineering, and exploratory analysis to reveal long-term trends and meaningful insights.

Key findings include:
```
• The United States ranks highest in total Nobel laureates by birth country
• Strong gender imbalance exists across most categories, especially Physics and Medicine
• Six individuals and organizations received the prize more than once, including Marie Curie and the Red Cross
• Prize awards per year show long-term growth when viewed through a moving average
• Top research institutions dominate total awards, showing concentration of academic excellence
• Prize share was successfully converted from fractions into usable numeric values for deeper analysis
```

The project demonstrates skills in data cleaning, transformation, aggregation, visualization, and analytical storytelling using Python, Pandas, Matplotlib, and Plotly
