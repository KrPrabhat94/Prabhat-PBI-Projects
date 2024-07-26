#Amazon Prime Video-Dashboard

## Dashboard Link: https://app.powerbi.com/groups/me/reports/d4208445-50f9-4f4f-813e-28f2d0f64a8d/ReportSection

#Problem Statement

This dashboard helps understand their users better. It helps to know if their users are satisfied with their services. Through the different ratings, they get to know their improvement area. It also lets them to know most viewed content by users, thus since by using this dashboard they have identified that which type of contents need to highlight.


Since, number of Senior Citizen users (almost 41%) are more than Teen and Young users (around 24%), thus in all, they must work on improving their services.

Also, Favorite Genres highlighted on the basis of users age group.

Highlighted, Number of users by usages frequency, engagement metrics and location. 

##Steps Followed

-Step 1 : Load data into Power BI Desktop, dataset is a CSV file.

-Step 2 : Open Power Query editor & In view tab under Data preview section, Check "Column Distribution", "Column Quality", & "Column Profile" options.

-Step 3 : Also since by default, profile will be opened only for 1000 rows So you need to select "Column Profiling" based on entire dataset.

-Step 4 : It was observed that none of the columns error & empty values were present.

-Step 5 : For calculating number of total users, taken distinct user Id.

-Step 6 : In the report view, under the view tab, theme was selected.

-Step 7 : Visual (Cards) were added for six field named "Location", "Subscription", "Age Group", "Gender", "Devices Used", & "Favorite Genres".

-Step 8 : Added Stack column chart, Treemap, Waterfall chart, Pie chart, & Clustered column chart to represent Number of users by location and age group, Number of users by usages frequency and engagement metrics, Count of devices id, Number of users by age group, Count of users by favorite genres respectively.

Although, representing various visuals on another tab (User-Platform-Info).

-Step 9 : representing four card visuals to Count of customer support, Count of device used, Count of subscription, & Count of user id.

-Step 10 : Added, a bar chart column, Pie chart, Funnel chart, & Line chart to represent below;

 (a) Count of user id by device used and engagement metrics.
 
 (b) Sum of customer support interactions by engagement metrics and devices used.

 (c) Sum of Feedback/Ratings by devices used.

 (d) Sum of Feedback/Ratings by engagement metrics and devices used.
