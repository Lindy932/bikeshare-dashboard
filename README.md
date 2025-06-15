# 🚲 Bike Share Rides Usage Analytics Dashboard

## Goal ✅
I developed a interactive data visualization dashboard to analyze and identify urban bike usage patterns. The project focuses on identifying trends in ride frequency, user behavior, station demand, popular routes, and user behavior with the use of real-world bikeshare datasets. It is established to have better support toward strategic decision-making with a focus on transportation optimization, predictive analytics, and operational efficiency. 

## Insights 📈
- Identified peak ride hours and high-demand stations/routes for optimal bike station distribution.
- Segmented users by bike (Electric vs. Regular) and rider types (Member vs. Casual), revealing usage behavior for targeted services improvements
- Applied K-Means clustering to show distinct user behavior patterns
- Detect loop rides (15%) that demonstrated recreational usage around certain areas
- Built predictive forecasting model (Prophet) of bike rides usage for the next month with 85%+ accuracy.
- Rush hour indicators based on days of the week and amount of rides


## Dataset
Public Citibike NYC dataset with 81,000+ ride records are utilized for this visualization which provided station names, timestamps, user's metadata, and geolocations.

## Data Wrangling 🔧
- Cleaned data with Python using Jupyter Notebook, handled missing values, normalized timestamps, and engineered time-based features like querying for ride duration given start and end times of each ride.
- Aggregated, queried and modeled data in SQL and Power BI for performance, predictability, and flexibility. 

## Tools 🛠
  MySQL, MySQL Workbench, Power BI, Tableau, Python (Pandas, Scikit-learn, Prophet, Matplotlib), SQL, DAX, Power Query, Jupyter Notebook


## Visualization 📊
Produced interactive dashboard using Tableau. More advanced data visualizations such as predictive analysis are created using Power BI dashboard with python visuals.

### Tableau: [Link](https://public.tableau.com/app/profile/lindy.lin1797/viz/BikeshareVisualizationDashboard/Dashboard1)

<img width="898" alt="Screen Shot 2025-06-13 at 12 33 34 AM" src="https://github.com/user-attachments/assets/23ae44c6-2eb6-462c-9250-ef57e3fab861" />

### Power BI: 

<img width="1067" alt="Screen Shot 2025-06-13 at 12 06 11 AM" src="https://github.com/user-attachments/assets/c07ea0fd-0a93-4d94-9f5d-dfd6be4122e3" />

⚠️ Note: When opening the pbix file, Python visuals are visible only when the report is opened in Power BI Desktop with Python installed. They will not render in Power BI Service without a Premium license.


### Analysis Results:







