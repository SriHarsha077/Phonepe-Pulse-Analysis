# PhonePe Insurance, Transaction and User Engagement Analysis

## Project Overview
This project analyzes insurance transactions and user engagement trends on PhonePe, a leading digital payments platform in India. The goal is to provide data-driven insights into geographical, brand-specific, and user engagement performance metrics, helping to optimize insurance transaction efficiency and customer engagement on the platform.

## Business Problem Statement
With PhonePe expanding its financial services, particularly in insurance, it's essential to:
- Brand-wise Transaction Analysis Dashboard ("This dashboard helps in analyzing brand-wise transaction trends for PhonePe services."
                                               "The objective is to identify top-performing brands, examine market penetration, and extract actionable insights for brand promotion and strategic decision-making.)
- District-wise Transaction Analysis Dashboard("This dashboard focuses on analyzing transaction trends across different districts"
         "The goal is to uncover which districts contribute the most to transaction volumes and amounts, and how this evolves over time."
- PhonePe Insurance Transaction Interactive Dashboard
- User Engagement and App Opens Analysis Dashboard("The key challenge is identifying districts with high user registrations but low app engagement, allowing targeted strategies to boost app usage. Understanding the correlation between registered users and app opens is crucial for improving marketing campaigns and user experience.")

These insights are valuable in developing targeted strategies for market penetration, revenue growth, and user re-engagement.

## Data Processing
The raw data was initially available in JSON format. Using Python libraries—`os`, `json`, and `pandas`—the data was converted to CSV files to facilitate easier manipulation and analysis.

Steps:
1. **Data Loading and Transformation**: Read JSON data, clean, and structure it into CSV format.
2. **Data Storage**: Store processed data in a format compatible with analytical tools like Power BI.

## Exploratory Data Analysis (EDA)
EDA was performed to understand the dataset and discover patterns and correlations in:
- State-wise and district-wise insurance transaction trends.
- Brand-wise transaction volumes.
- User engagement metrics, correlating registered users with app opens.

## Data Visualization
The project includes interactive visualizations for decision-making, developed in two tools:
- **Power BI Dashboard**: Displays transaction metrics across quarters, years, states, districts, and brands, with engagement insights.
- **Streamlit Application**: Provides a user-friendly, web-based interface for real-time data insights.

### Power BI Dashboard Visuals
1. **Quarterly and Yearly Transaction Trends**: Transaction counts and amounts over time.
2. **Geographic Insights**: State-wise and district-wise transaction performance.
3. **User Engagement Metrics**: Comparison of registered users and app opens to identify engagement opportunities.

## Technologies Used
- **Data Processing**: Python (pandas, json, os)
- **Visualization**: Power BI, Streamlit

