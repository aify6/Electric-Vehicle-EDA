# Electric Vehicles (EV) Data Analysis and Visualization Project

## Overview

This project explores an electric vehicle (EV) dataset, performing comprehensive exploratory data analysis (EDA) using Python. The EDA includes univariate, bivariate, and multivariate analysis, as well as interactive visualizations such as choropleth maps and bar chart race animations. The main goal is to understand the trends and distributions of various attributes in the EV dataset, such as vehicle make, model year, and electric range.

## Key Features

- **Univariate Analysis**: Analyzing the distribution of individual variables such as electric range and MSRP.
- **Bivariate Analysis**: Investigating the relationships between two variables, e.g., Electric Range vs. Base MSRP.
- **Multivariate Analysis**: Exploring the relationships between multiple variables at once.
- **Interactive Visualizations**:
  - Choropleth map of EV vehicle distribution across locations.
  - Animated bar chart race showing the top EV manufacturers over time.

## Dataset

The dataset consists of electric vehicle data with the following key columns:

- **Model Year**: The year the vehicle was manufactured.
- **Make**: The manufacturer or brand of the vehicle.
- **Electric Vehicle Type**: Type of electric vehicle (e.g., battery electric, plug-in hybrid).
- **Electric Range**: The electric range of the vehicle in miles.
- **Base MSRP**: Manufacturer's Suggested Retail Price (MSRP) of the vehicle.

## Tools & Libraries

The project is built with Python and utilizes the following libraries:

- **pandas**: For data manipulation and analysis.
- **plotly**: For creating interactive visualizations.
- **bar_chart_race**: For creating bar chart race animations.
- **plotly.express**: For creating the interactive choropleth map.
- **matplotlib** and **seaborn**: For static plots used during EDA.

## Installation

Before running the analysis, ensure you have Python installed, along with the required libraries.

### Step 1: Clone the Repository

  ```
  git clone https://github.com/aify6/Electric-Vehicle-EDA.git
  cd Electric-Vehicle-EDA
```

## Step 2: Install Required Libraries
You can manually install the required libraries using:

```
pip install pandas matplotlib seaborn plotly bar_chart_race
```

### Project Structure
```
EV-Data-Analysis/
│
├── Ev_Analysis.ipynb                 # Jupyter Notebook containing the full EDA
└── README.md                    # Project documentation (this file)
```

### Usage
To run the analysis, simply open the EV_Analysis.ipynb Jupyter Notebook and execute the cells in order.

## Analysis Summary
- **Univariate Analysis**
  - Electric Range: Most EVs have a range between 50-100 miles, with a few outliers extending beyond 300 miles.
  - Base MSRP: The majority of EVs are priced between $30,000 and $60,000, though some luxury models go above $100,000.
- **Bivariate and Multivariate Analysis**
  - Electric Range vs. Base MSRP: There is a positive correlation between electric range and MSRP, indicating that higher-range vehicles tend to be more expensive.
  - Distribution of EVs by Make and Model Year: Certain brands like Tesla dominate the market in specific years.
- **Choropleth Map**
  -A choropleth map was created using plotly.express to visualize the distribution of electric vehicles across different geographic locations based on available data.

- **Bar Chart Race Animation**
  - An animated bar chart race was created using the bar_chart_race library, showing the count of EVs for each manufacturer across different years.

## Visualizations
- Choropleth Map

- Bar Chart Race

## Conclusion
This project provides insights into the electric vehicle market, including the evolution of various manufacturers over the years and the distribution of EVs across different regions. It also highlights trends in electric range and pricing, which are key factors in understanding the growth and adoption of electric vehicles.

## Acknowledgments
This project was completed as part of an internship with Innomatics Research Labs. Special thanks to the team for their guidance and support.

## Connect
Feel free to connect with me on LinkedIn to discuss more about the project or explore collaborations!
https://www.linkedin.com/in/ifeanyi-njoku/
