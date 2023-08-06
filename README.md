# Power BI Student Survey Report

This repository contains a Power BI project that analyzes and visualizes data from a student survey, focusing on students' spending habits across various categories and store settings. The goal of this project is to provide meaningful insights into students' purchasing behaviors, segmented by different factors, and create informative visualizations for decision-making.

## Project Tasks and Visualizations

### Tabular Visualization - Total Amount of Purchase (TAP) by Store Location and Setting

- A tabular visualization is created to display the total amount of purchase (TAP) based on the store location and store setting.
- Conditional formatting is applied to TAP values using color codes:
  - Red: TAP < 35000
  - Yellow: 35000 <= TAP < 60000
  - Blue: TAP >= 60000

### Matrix Visualization - Amount Spent on Outdoor Sports by Age and Store Setting

- A matrix visualization displays the amount spent on outdoor sports across different age groups and store settings.
- Color formatting is used to highlight the amount spent on outdoor sports.

### Funnel Chart - Total Amount of Purchase by Store Setting

- A funnel chart illustrates the total amount of purchase by store setting.
- Data labels are displayed as a percentage of the first value.

### Pie Chart - Total Amount of Purchase by Store Location (Suburban Setting Only)

- A pie chart visualizes the total amount of purchase by store location for the suburban store setting.
- Data is filtered to show only the suburban setting.

### Scatter Plot - Video Games Purchase vs. Outdoor Sports Spent by Age

- A scatter plot displays the relationship between video games purchases and outdoor sports spending across different age groups.
- Color saturation represents outdoor sports spending.

### Sand Dance Plot - Indoor Sports vs. Video Games Spent by Age

- A Sand Dance plot showcases the comparison between indoor sports spending and video games purchases across age groups.

### Data Restriction for Users

- Data access is restricted for specific users based on the "User mapping" table.
- Users are granted access to view data only for their respective store settings.

### Publishing and Automation

- The Power BI report is published to the Power BI Cloud Service for easy access and sharing.
- A master dashboard is created, featuring the funnel chart and scatter plots.
- The dashboard is scheduled to refresh six times every 4 hours to provide up-to-date information.

### Q&A Feature

- The Power BI Q&A feature is utilized to answer specific queries:
  - Average age of students
  - Donut chart displaying the total amount of purchases by store location

## How to Use

1. Download or clone this repository.
2. Open the Power BI project file (.pbix) using Power BI Desktop.
3. Connect the project to your data source or replace the existing data with your own.
4. Customize visuals, filters, and data models as needed.
5. Publish the report to the Power BI Cloud Service for online access.
6. Explore the master dashboard for key insights and trends.

## Contributors

- [Rahul KB] - [Your GitHub Profile]([https://github.com/yourusername](https://github.com/RahulKB31))

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to tailor the above text to fit your specific project and repository details. This README file will provide a clear overview of the project's objectives, tasks, visualizations, and instructions on how to use the Power BI report.
