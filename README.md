# MGT4250-Final-Project
## Part 1
This is for the class project of MGT 4250 Fall 2023 at Elon University

[Visual 1 Map](https://public.tableau.com/shared/FCQHF6FCT?:display_count=n&:origin=viz_share_link)
[Visual 2 Bar Graph](https://public.tableau.com/shared/QPP99P9WG?:display_count=n&:origin=viz_share_link)
[Visual 3 Line Graph](https://public.tableau.com/shared/6Y8XB8BPT?:display_count=n&:origin=viz_share_link)
### Question 
How has the attendance at NFL games shifted in the past 19 years?
### Importance
This question is important because Football has undergone substantial changes in this time, including new rules, player dynamics, and strategic approaches. Our goal is to assess fans' perceptions of the current state of football by examining stadium attendance trends in NFL games over the last 19 years based on city. We anticipate that teams with consistent or improved performance during this period will likely show steady or growing attendance, while those experiencing declines in performance may see a decrease in attendance as well as see which if teams moved due to a decline in attendance. Our dataset comprises attendance records for both home and away NFL games spanning the past 19 years for each team including if the team moved cities in this time period.

## Part 2
### How To Download
Our data can be accessed by navigating to Kaggle.com and searching for NFL attendance. Next, click on the entry labeled, “NFL Stadium Attendance Dataset” by Sujay Kapadnis. Download the csv file from this page. 

### Data Types and Descriptions
The columns of the dataset are as follows. Firstly, there is a column named, “team”, under which a team’s city or location is listed as a string. The next column is called, “team_name”. This contains the name of the team as a string. Next there is a column named, “year”, which contains the year of the season as an integer. After this is the column, “total”. This contains the total attendance across 17 weeks of play listed as a double. After this comes the “home” and “away” columns which list the attendance for home and away games respectively represented as a double. Next, there is the, “week” column. This contains the week of the game in question, represented as a string. There is then “weekly_attendance” column which shows the weekly attendance number as a double. Lastly, we have added two columns, one for longitude and another for latitude. These were added for the purpose of creating a map visualization of the data at the specific points where each team plays their home games.

## Part 3 
### Vizualizations
1. Our first visualization is a map of the United States which shows attendance for each team at their respective geographical locations. We have excluded the New York Giants and the New York Jets from this visual because they play in the same stadium and this would skew the data. This is important for our quesrion to help show which areas are profitable for teams to be in and which areas draw less of a crowd. you could look deeper to look at the sports teams recoreds as well and see if that has an effect on the attendance as well.
2. A bar graph illustrating NFL game attendance across a 19-year timeline offers a visual of the attendance fluctuations and trends over this period. By presenting annual attendance figures in a graphical format, it enables an immediate assessment of how attendance has changed year by year. The graph allows for a quick comparison of attendance levels between different seasons, making it easier to identify peaks, lows, or patterns that signify changes in fan turnout. Analyzing the heights of the bars representing each year's attendance provides a straightforward way to grasp overall trends, spot outliers, and recognize any notable shifts in attendance dynamics, offering a clear and concise answer to how NFL game attendance has changed over the specified 19-year span.
3. A line graph representing NFL game attendance across a span of 19 years serves as a strong visual, showing us the shifts and overarching trends in fan turnout over this duration. The continuous line connecting yearly attendance data points offers a clear depiction of the attendance trajectory, enabling immediate recognition of any patterns, gradual changes, or abrupt shifts in fan engagement over time. By presenting a single view of attendance figures across nearly two decades, the line graph facilitates a understanding of the overarching direction—whether attendance has shown consistent growth, fluctuated periodically, had notable peaks or declines, or remained relatively stable. This visualization method becomes an important tool in comprehending the long-term change and dynamics of NFL game attendance, offering insights into the fan interest and engagement throughout the extended 19-year timeframe.

## Part 4 

[Link To Artical Used](https://www.sportsbusinessjournal.com/Journal/Issues/2023/01/16/Upfront/nfl-attendance.aspx)
### Summerization 

In 2022, NFL attendance raised by 3.25%, averaging 69,442 fans per game—the second-highest attendance in almost two decades. This surge marked a reversal from the attendance decline seen in the late 2010s, credit is given partly to the lifting of pandemic restrictions across all markets and reduced COVID-19 concerns. Notably, 24 teams saw increases while only six experienced declines in attendance. Factors like consumer behavior and economic conditions influenced ticket sales, with most tickets sold post-pandemic threat but before serious inflation hit. The NFL received credit for effectively engaging both older and younger fan bases, contributing to this attendance growth.

However, the reported box score attendance figures, including all distributed tickets, have limitations and may not accurately reflect actual turnstile activity. Changes in counting metrics by teams, such as including unused distributed tickets, influenced reported numbers. Despite these considerations, the 2022 season's average attendance almost matched the 2016 high mark, signaling positive growth post-pandemic. The inauguration of new stadiums in Los Angeles and Las Vegas played a pivotal role in boosting attendance compared to the 2010s when teams played in older venues.


### Generative AI

Question 1. was there a overall large increast in attendance between the two years?

Response 1. Yes, there was a notable increase in NFL attendance between the two years. In 2022, there was a 3.25% surge in average attendance compared to the previous year, marking a significant rise in fan turnout across the league. This increase nearly countered the declining attendance trend that had been observed in the late 2010s, showcasing a substantial upturn in overall attendance levels for NFL games.

Question 2. what was the reason for this increase?

Response 2.Post-Pandemic Conditions: With pandemic restrictions fully lifted across all markets and reduced fears surrounding COVID-19, fans felt more comfortable attending games, leading to a widespread surge in attendance.Consumer Behavior and Economic Conditions: Most NFL tickets were sold after the COVID-19 threat had subsided but before inflation became a significant concern. This window of time likely encouraged ticket purchases.Improved Fan Engagement: The NFL was credited for effectively addressing weaknesses in fan engagement, appealing to both older and younger fan bases, which contributed to increased attendance.New Stadium Openings: The inauguration of new stadiums in Los Angeles and Las Vegas was cited as a key factor in boosting attendance compared to previous years when teams played in older venues. These modern venues likely drew more fans to games.These factors, coupled with the widespread lifting of pandemic restrictions and the league's efforts to engage fans, collectively contributed to the notable increase in NFL attendance in 2022.

Question 3. did any rule changes effect this?

Response 3.There weren't specific rule changes in the NFL that directly impacted attendance in the 2022 season. However, the league has implemented various rule changes over the years aimed at enhancing the fan experience and player safety, which indirectly could influence attendance trends by affecting the quality of the game and fan engagement.
The surge in attendance for the 2022 season was mainly attributed to factors such as the lifting of pandemic restrictions, reduced COVID-19 concerns, improved fan engagement strategies by the NFL, and the opening of new stadiums in key markets. While rule changes can impact the game itself and fan perception, they were not highlighted as direct contributors to the notable increase in attendance during that specific season.

Question 4. did having games in other countries have an effect?

Response 4. Games held in other countries can affect average attendance figures, especially if those games are included in the calculations. In the analysis mentioned, five "home games" in foreign neutral sites were considered, impacting the total attendance figures for some teams. For instance, the inclusion of these games might have affected the average attendance of certain teams negatively if those games had lower attendance figures compared to their regular home games. Conversely, teams playing in those international games might have seen a slight increase in their overall average attendance due to the addition of these games. However, the impact of these international games on the overall league attendance might not have been substantial enough to significantly alter the general trend of increased attendance observed in the 2022 season. The larger factors influencing attendance were likely the lifting of pandemic restrictions, improved fan engagement, and new stadium openings rather than the international games themselves.
