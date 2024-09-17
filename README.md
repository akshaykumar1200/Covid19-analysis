Data Analysis Project: COVID-19 Impact & Happiness Metrics Correlation

Objective: Analyzed the correlation between COVID-19 infection rates and happiness metrics across various countries to understand the socio-economic factors influencing the pandemic's impact.

Data Sources:

COVID-19 Confirmed Cases Dataset: Aggregated global confirmed cases of COVID-19 by country.
Worldwide Happiness Report Dataset: Included GDP per capita, social support, healthy life expectancy, and other happiness-related metrics.
Key Steps:

Data Cleaning & Preparation:

Dropped unnecessary columns (e.g., latitude, longitude, overall rank) and handled missing values.
Aggregated COVID-19 case data by country and calculated maximum infection rates using the difference between consecutive days.
Feature Engineering:

Merged COVID-19 data with happiness report data on country names.
Created new features such as logarithmic transformation of infection rates and scaling GDP per capita.
Visualization & Analysis:

Used Seaborn and Plotly for visualizations, including scatter plots and regression analysis.
Explored correlations between maximum infection rates and happiness metrics such as GDP per capita, healthy life expectancy, social support, and freedom to make life choices.
Tools Used: Python (Pandas, NumPy), Seaborn, Plotly, Matplotlib

Insights:

Observed strong correlations between GDP per capita and infection rates, as well as life expectancy and infection rates, indicating that wealthier nations with better health infrastructure tend to handle pandemics more effectively.
