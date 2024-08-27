
# Power BI IPL Dashboard Project
## Overview
This project uses the Cricbuzz Cricket API to access and display live IPL (Indian Premier League) match data through a dynamic dashboard (Power BI). Although the IPL season has concluded, the project now focuses on analyzing and presenting detailed reports from past matches. It has interactive scorecards, and the ability to navigate through various data points like team performance and points table.



## IPL-Dashboard (Link from PowerBi Service)

### Dashboard Link :https://app.powerbi.com/reportEmbed?reportId=7aafefe1-3d02-42db-9be9-fb4c78d6f343&autoAuth=true&ctid=850aa78d-94e1-4bc6-9cf3-8c11b530701c (Access to this link requires my permission.)
   


## Navigation Guide
### Tab 1: Dashboard Overview

-> Welcome Screen: The first tab greets users with a visually engaging image and a button labeled "Dashboard." This button serves as the entry point to the main analytics section, guiding users seamlessly into the live data visuals.



![Screenshot 2024-08-27 162301](https://github.com/user-attachments/assets/b71d3cbb-18fd-4d41-ae46-9a86f1587131)

_

### Tab 2: Live Data
-> Interactive Visuals: This tab is the heart of the project, displaying real-time data through dynamic visuals. The live scorecard is enriched with interactive tooltips for each player's image and his contribution, allowing users to dive deeper into individual performances.

-> Captain Showcase: At the top of the dashboard, images of both team captains with their teams stats are prominently displayed, adding a personal touch to the data.

-> Sidebar Navigation: The sidebar includes three clickable options—"Home," "Live Dashboard," and "Points Table." These options enable users to easily navigate between different sections, enhancing the user experience.

_

![Screenshot 2024-08-27 172336](https://github.com/user-attachments/assets/069ff395-0c9c-41c7-a0ea-6b57d92c9c96)
In the sidebar- 'Home' and 'Points Table' will take you to the 1st and 3rd tab. 'Live Score' option is not enabled here.

_ 

![Screenshot 2024-08-27 173101](https://github.com/user-attachments/assets/63432431-f48d-449a-9105-b842a18d34e1)
There are 2 tooltips- 1st for batsmen (displaying the batsman's contribution) and 2nd for bowlers (displaying the bowler's contribution) connected to the both tables and Pie Charts.

![Screenshot 2024-08-27 185547](https://github.com/user-attachments/assets/a0f2f075-0f83-41ba-b8ae-402487a1031d)
Tooltips feature allows users to see the bowler’s contribution by simply hovering over a row in Bowlers Table and same for Batmen Table and The Pie Charts below shown.

_

### Tab 3: Points Table
-> Interactive Points Table: This tab features an interactive table showcasing the standings of IPL teams. Users can explore detailed stats by clicking on specific teams, with the top of the page highlighting selected teams from the points table.

-> Team Showcase: The selected teams are prominently displayed at the top, providing a focused view of their performance and ranking.

_

![Screenshot 2024-08-27 174424](https://github.com/user-attachments/assets/0ced663d-fa50-4533-8c8b-ea7db1ab3566)
Sidebar offers to go 'Live Score' tab and to 'Home' tab.

_

![Screenshot 2024-08-27 175002](https://github.com/user-attachments/assets/c01cf882-ca0d-4382-b8be-520fc4e79a13)
In this tab we can see the stats of a particular team by clicking on that Team row from the Points Table.

## Technical Details
-> Data Source: The Cricbuzz Cricket API is used to retrieve live and historical IPL data, ensuring up-to-date and accurate information for analysis.

-> Data Transformation: The data was cleaned and structured using Power BI's "Transform Data" feature. By converting the data into tables, it was optimized for visualization, enabling the creation of clear and accurate analytics.

-> Visual Design: The dashboard utilizes Power BI’s robust visualization tools, including interactive scorecards, dynamic images, and detailed points tables. Each visual element is designed to provide deep insights while maintaining an intuitive user interface.

_

![Screenshot 2024-08-27 182552](https://github.com/user-attachments/assets/978aa4ea-701c-4577-ac71-c7a27d3588fe)
API data Accessing.

After accessing data from API, from "Transform Data" feature I cleaned all the data.

_

![Screenshot 2024-08-27 181443](https://github.com/user-attachments/assets/4014403c-d3c9-45e5-ba4f-00a154a597be)
_

-> From here we can change match numbers, since The IPL is over so we can access the same dashboard I showed earlier for all the Matches.

![Screenshot 2024-08-27 182629](https://github.com/user-attachments/assets/e5c1fd2a-d36d-42bf-a016-39a846045dca)
After selecting 8th match, we get can same dashboard for this match.
we can mannualy change the Match_Numbers.

## Conclusion
This Power BI project effectively demonstrates the power of data visualization in sports analytics. By transforming and cleaning raw IPL data into an interactive and insightful dashboard, this project showcases advanced analytical skills, attention to detail, and a strong understanding of user-centric design.
