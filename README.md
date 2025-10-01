🌍 Exploratory Analysis of Global Crime Data

This project is very exciting for me because as a true crime "fan", I wanted to check a crime dataset to explore. This project explores global crime statistics, with a focus on intentional homicide rates across countries and regions. The dataset was sourced from the United Nations and includes homicide rates per 100,000 inhabitants, as well as related indicators.

🛠 Steps Performed

1. Data Understanding

Loaded the dataset and inspected its structure.

Identified columns such as Country, Year, Series, Value, Footnotes, Source.

2. Data Cleaning

Fixed column names (original dataset had generic names like Unnamed: 2).

Dropped irrelevant metadata rows and columns.

Converted Year to integers and Value to numeric.

Removed rows where Country contained numeric IDs instead of names.

3. Exploratory Data Analysis (EDA)

Identified the available crime indicators in the dataset.

Calculated summary statistics for homicide rates.

Visualized global homicide trends over time.

Created a bar chart of the Top 10 countries by homicide rate (latest year).

4. Feature Engineering

Added Year-over-Year (YoY) change for homicide rates.

Calculated regional averages (e.g., Total Africa, Total Europe).

Pivoted the dataset into a wide format with crime indicators as features.

⚠️ Challenges Faced

Incomplete information: Several country names were missing or replaced with numeric codes.

High proportion of missing values across some indicators.

Some records only contained global/regional totals but not country-specific values.

Data inconsistencies required extra cleaning before analysis.

(Despite that it was very fun to practice with this dataset)

📊 Results & Visualizations

Global homicide rates have generally shown variation across years.

Some countries have significantly higher homicide rates than the global average. Eventhough, I cannot know which countries those are because the data is incomplete. 

Year-over-year change helps highlight countries with improving or worsening situations.

Conclusion

Crime is something that changes by country and also by time period. In the future I will select another dataset that has more accurate information. 

Thanks!
