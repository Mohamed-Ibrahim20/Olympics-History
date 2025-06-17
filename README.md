# Olympic Data Dashboard with PowerBI

This repository contains a PowerBI dashboard developed to analyze the "120 Years of Olympic History - Athletes and Results" dataset, spanning from Athens 1896 to Rio 2016. The dashboard provides an interactive visualization of Olympic data, offering insights into medal distributions, athlete demographics, and country performances. Built using PowerBI, this project transforms raw data into actionable visualizations, making it an excellent resource for sports analysts, data enthusiasts, and Olympic history researchers.

## Project Overview

The dashboard leverages a comprehensive dataset from Kaggle (https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results/data), which includes records of athletes, events, games, and results. The goal was to create an intuitive interface to explore key metrics such as total medals, gold medal leaders, and athlete age distributions, all presented through dynamic charts and maps. This project was implemented using PowerBI to craft an interactive and visually appealing dashboard.

## Dashboard Features

- **Total Metrics**: Displays an overview with 39,783 total medals (13,372 Gold, 13,116 Silver, 13,295 Bronze) and 135,571 total athletes.
- **World Map Visualization**: Highlights medal counts by country, with interactive filtering by year, country, medal type, gender, sport, and age group.
- **Medal Distribution by Sport**: Bar chart showing top sports like Athletics, Swimming, and Cycling based on medal counts.
- **Medal Distribution by Country**: Stacked bar chart comparing medal types (Gold, Silver, Bronze) for top countries like the United States, Soviet Union, and Germany.
- **Total Medals by Age Group**: Bar chart breaking down medal counts across age buckets (Under 20, 20-30, 30-50, Above 50).
- **Top 5 Athletes Table**: Lists leading athletes (e.g., Michael Phelps with 18 medals, Larisa Latynina with 18) with their countries and total medals.

## Technical Details

- **Tool**: Microsoft PowerBI
- **Data Source**: Kaggle dataset (CSV files processed and imported into PowerBI).
- **Date Range**: 1896–2016 (based on available data).
- **Interactivity**: Filters allow users to drill down by year, country, gender, sport, and age, enhancing data exploration.

## Screenshots

![Olympic Dashboard Screenshot](https://raw.githubusercontent.com/Mohamed-Ibrahim20/Olympics-History/main/dashboard_screenshot.jpg)*Figure: Screenshot of the PowerBI dashboard showcasing key visualizations.*

## How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Mohamed-Ibrahim20/Olympics-History.git
   cd Olympics-History
   ```
2. **Download the Dataset**: Obtain the dataset from https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results/data and place the CSV files in a `data/` folder.
3. **Open in PowerBI**: Load the included `.pbix` file (if uploaded) or recreate the dashboard by importing the dataset and replicating the visualizations.
4. **Explore**: Use the interactive filters to analyze specific metrics and trends.

## Future Improvements

- Incorporate data from the 2020 and 2022 Olympics (post-2016) for updated insights.
- Add more advanced analytics, such as predictive models for future performances.
- Enhance accessibility with exportable reports and additional visualizations.

## Acknowledgments

- **Data Source**: 120 Years of Olympic History - Athletes and Results by Heesoo37 on Kaggle.
- **Tools**: Thanks to Microsoft for PowerBI and its robust data visualization capabilities.
