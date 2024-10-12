![image](https://github.com/user-attachments/assets/9bb27a15-a8d9-4b85-b715-de75945c4961)
![image](https://github.com/user-attachments/assets/0f0264d5-6db7-4a02-a96a-37ea5d247c66)


How To View Project:
Download Pbix file and open in Power BI desktop.
Cannot Host as power Bi does not allow for free users
Summary of the project components:

1. Data Transformation (using Power Query):
   - Converted the year column to an integer type from a string.
   - Corrected misspelled team names in columns containing team names.
   - Corrected misspelled venue names in the venue column.

2. Data Modeling:
   - Connected the match ID of the IPL matches table and the IPL ball-to-ball table, likely to link ball-by-ball data with match data.
   - Created a new table named "calendar" containing all the dates of IPL matches, probably for time-based functions and date analysis.
   - Connected the dates columns in the "calendar" table and the "IPL matches" table, presumably to link the match data with the dates.

3. Data Visualization:
   The project presents several visualizations and insights based on the transformed and modeled data. These visualizations likely include:
   Page1
   - A slicer or filter for selecting IPL seasons to focus on a specific year.
   - Displaying the winner of each IPL season (Season Winner).
   - Identifying the Orange Cap holder (leading run-scorer) and Purple Cap holder (leading wicket-taker) for each season.
   - Showing the number of 6's and 4's hit in the IPL matches.
   - Showing the player with most 6's, 4's and boundaries.
   - Analyzing matches won by the toss decision (batting or bowling first).
   - Analyzing matches won by different result types (e.g., win by runs, win by wickets, tie).
   - Analyzing matches won at each venue based on the result type.
   - Displaying the total wins by each team and possibly providing a modified and enhanced view of the data for better insights.
     
   Page2
   - Providing batting statistics such as runs scored, number of 6's, 4's, strike rate, centuries and half centuries for each batsman.
   - Providing bowling statistics such as wickets taken, economy rate, average, and bowling strike rate for each bowler.


Overall, this project aims to offer a comprehensive analysis of IPL data through data transformation, data modeling, and data visualization techniques. It enables users to explore and understand various aspects of IPL matches, team performance, and individual player achievements over different seasons and venues.
