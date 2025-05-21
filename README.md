# Bellabeat Analysis
**Google Data Analytics Capstone Project**  
**Michalis Loizos, May 2025**

This is my capstone project for the Google Data Analytics Certificate, analyzing Bellabeat health tech data (Fitbit usage trends from 34 users) to deliver wellness marketing insights. Built with Google Sheets (data cleaning, pivot tables), SQL (data filtering), and R (tidyverse, ggplot2 for visualizations), it showcases my skills in data wrangling, visualization, and business recommendations. Complements my independent [Hotel Booking Analysis](insert_hotel_booking_repo_link) for a diverse portfolio targeting data analyst roles.

## Project Overview
- **Dataset**: Fitbit user data from 34 users, including daily activity (steps, calories), hourly trends (calories, steps, intensities), spanning 30 days (not included due to course restrictions).
- **Tools**: Google Sheets, SQL, R (tidyverse, ggplot2, kableExtra).
- **Analysis**:
  - Cleaned data (e.g., converted UTC times to 24-hour format).
  - Categorized users by activity level (Lightly, Fairly, Very Active) based on average calories burned.
  - Analyzed hourly trends for the top 10 most active users, identifying 50% peak workouts in the late evening to nighttime period.
  - Recommended notifications and nutritional suggestions aligned with workout hours.
- **Key Skills**:
  - Data Cleaning: Handled inconsistencies and created pivot tables in Google Sheets.
  - SQL: Applied filters to extract top users.
  - R: Visualized trends with ggplot2 (pie chart, faceted bar charts) and summarized data with kableExtra.
  - Business Insights: Delivered actionable marketing strategies.

## Files
- `bellabeat_analysis.Rmd`: R Markdown source with code, visualizations, and narrative.
- `bellabeat_analysis.pdf`: Full report with tables (e.g., pivot table) and figures (e.g., activity distribution, hourly trends).

[View the Full Report (PDF)](bellabeat_analysis.pdf)

## Key Visualizations
- **Figure 1**: Pie chart of user activity levels (Lightly, Fairly, Very Active) based on calories burned.
- **Figure 2 & 3**: Hourly calorie burning trends for the top 10 users (daytime and nighttime).
- **Figure 4 & 5**: Hourly step trends for the top 10 users (daytime and nighttime).
- **Figure 6 & 7**: Hourly workout intensity trends for the top 10 users (daytime and nighttime).


## How to Run
1. Clone this repo: `git clone https://github.com/your-username/bellabeat-analysis.git`
2. Install dependencies in R: `install.packages(c("tidyverse", "ggplot2", "kableExtra", "RColorBrewer"))`
3. Open `bellabeat_analysis.Rmd` in RStudio and knit to PDF (requires the dataset, not included).

*Dataset not included due to course restrictions. Contact me for details.*

## Contact
- LinkedIn: [Michalis Loizos](https://www.linkedin.com/in/michalis-loizos/)
- Email: mihalis.loizos@gmail.com
