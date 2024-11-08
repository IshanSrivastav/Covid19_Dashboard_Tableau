# COVID-19 Dashboard

This project provides an interactive COVID-19 Dashboard created using Tableau, visualizing global COVID-19 cases and trends. The dashboard includes key metrics like confirmed cases, death cases, and top-10 affected countries, with case trends displayed over time.

![COVID-19 Dashboard](Dashboard.png)

## Understanding the Data - Project Covid

The data used for this dashboard includes information on COVID-19 confirmed cases, deaths, and trends across different countries. The dataset (`COVID-19.csv`) provides a breakdown of case numbers over time, allowing for detailed analysis and visualization of how the pandemic has affected various regions.

## Designing the Dashboard

The dashboard is composed of the following visual elements:

1. **Symbol Map Showing COVID-19 Cases Worldwide**:
   - A map visualization where bubbles represent the number of cases in each country or region. Larger bubbles indicate higher case counts.

2. **COVID-19 Case Trends with a Stacked Area Chart**:
   - This chart shows the progression of COVID-19 cases over time. The stacked area chart provides a cumulative view of cases, allowing users to see how the case numbers have grown over the months.

3. **Top-10 COVID-19 Affected Countries and Their Trends**:
   - A bar chart displaying the top-10 countries with the highest confirmed cases, helping users identify the most affected regions. Additionally, individual trend lines for these countries are shown to understand their case growth over time.

4. **Confirmed Cases and Death Cases Pie Chart**:
   - A pie chart that provides a quick summary of the distribution between confirmed cases and death cases. This chart offers a straightforward way to understand the proportion of outcomes.

## Preparing the Final Dashboard - Project Covid

After creating the individual sheets, the final step is to integrate all visuals into a cohesive dashboard in Tableau. The design includes interactive filters for case type (confirmed or deaths) and a date selector, allowing users to customize their view of the data. The final dashboard layout is organized to provide a comprehensive yet accessible overview of the COVID-19 situation globally.

## Overview

The COVID-19 Dashboard visualizes:
- **Map of confirmed COVID-19 cases worldwide**: Bubble sizes represent the number of cases in each region.
- **Confirmed Cases and Death Cases**: A snapshot of confirmed and death cases globally as of the last update.
- **Case Trends**: A line chart showing the growth of confirmed cases over time.
- **Top-10 Countries by Cases**: A bar chart listing the countries with the highest case counts.

## Data Source

The dashboard uses data from the provided file `COVID-19.csv` convert it to `COVID-19.xlsx`, which contains COVID-19 statistics for various countries. This data includes information on confirmed cases, deaths, and trends over time.

## File Structure

- `Dashboard.png`: A screenshot of the Tableau COVID-19 Dashboard.
- `COVID-19.csv`: The dataset containing COVID-19 cases, deaths, and other relevant information.
- `README.md`: Documentation for setting up and running the dashboard.

## Requirements

- **Tableau Desktop**: You need Tableau to open, edit, and view the dashboard. Tableau Public (free version) can be used to view and publish dashboards online.
- **Concert CSV Data File To xlsx Format**: Ensure `COVID-19.xlsx` is available in the project directory for data import into Tableau.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/IshanSrivastav/Covid19_Dashboard_Tableau.git
    cd covid19-dashboard
    ```

2. **Open Tableau**:
   - Launch Tableau Desktop or Tableau Public.
   - **Open Dashboard:** Access the project on [Tableau Public](https://public.tableau.com/app/profile/ishan.srivastav4644/viz/Covid-19-Dashboard_17310662793620/Dashboard1?publish=yes) or use the local `.twbx` file.

3. **Import Data**:
   - Connect to the `COVID-19.csv` file within Tableau.

4. **Build the Dashboard**:
   - Use the following sheets to recreate the visuals:
     - **Map Visualization**: Display confirmed cases on a world map with bubble sizes representing the number of cases.
     - **Case Trends**: Create a line chart to show the progression of COVID-19 cases over time.
     - **Top-10 Countries**: Generate a bar chart showing the countries with the highest confirmed cases.
     - **Confirmed and Death Cases**: Use KPI indicators for the total confirmed and death cases.

5. **Customize Filters**:
   - Add a date filter to explore data across different time periods.
   - Include filters for case type (confirmed or deaths).

## Usage

Once setup, you can interact with the dashboard:
- Use filters to view data for specific dates or case types.
- Hover over map bubbles to view case counts by region.
- Analyze trends and compare case growth between countries.

# Contributing

**Contributions are welcome! If you have ideas for enhancements or spot any issues, feel free to submit a pull request.**

