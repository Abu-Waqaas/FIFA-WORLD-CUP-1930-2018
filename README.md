# Project Objective
At side hustle Boot Camp, my team was expected to make research on FIFA World Cup from its inception till 2018, and the following questions were to be answered.

1. Number of World cup winning title : Meaning how many world cup has been played since 1930- 2018
2. Attendance, Number of teams, Goals and Matches per cup
3.  Goals per team per World Cup
4. Matches with the highest number of attendance
5. Stadium with Highest Average Attendance
6. Which countries had won the world cup?
7. Number of goals per country
8. Matches outcome by home and away
9. All time highest Goal scorer
10. Total number of Goals scored in the world cup from 1930 - 2018
11. Number of qualified teams per year
12. Number of competition hosted by continents

# Data Source
The data were gathered from kaggle and online. The format was CSV

## Data  Preparation / Transformation

The data were cleaned using Power Query in Microsoft Excel and also a new column was created in the process of cleaning and transformation.
In the Matches sheet, some columns were removed, because we don't really need them and a column was also added, which is the column for home and away wins, and it was created using one of the functions in Microsoft Excel, which is = IFS (Home team goal> Away, "H", Home team goal < Away team goal, "A", Home team goal = Away team goal, "D")

### Analysis
The data was analysed using Microsoft Power BI, different visuals were used in the analysis processes e.g Bar chart, Pie Chart, Images,  Table, Card etc. 

This virtual below was created using Card, and it shows the number of title that has been played since the begining of the tournament in 1930 -2018

![Screenshot (108)](https://user-images.githubusercontent.com/106377378/175816132-1659eebb-58f0-42e6-bbe6-a2193ad5f75d.png)

The Country with the highest number of title won is Brazil, and they've won it 5 times (1958, 1962, 1970, 1994 and 2002)

![Brazil](https://user-images.githubusercontent.com/106377378/175819071-af6f19d7-b110-4215-a276-0956be573935.png)

And the average attendace of stadium was gotten using line chart, and it shows that Maracana stadium in Brazil has the highest average attendance in the competition history

![Screenshot (109)](https://user-images.githubusercontent.com/106377378/175816318-78b44395-a474-4afc-b9e8-2f2630f3c6e4.png)

And also the top 5 matches with the highest number of attendance since the beginning of the competition, was also gotten with Bar chart, and the matches were represented wuth their Match I.D, with the match played between Brazil aand uruguay on the 16th of June 1950 with I.D 1170 being the match with the highest attendace,

![Screenshot (110)](https://user-images.githubusercontent.com/106377378/175816758-710e9ea0-99da-4185-ae5e-8eebfea810e8.png)

We also visualized the host countries also by continent and it shows from the visuaals that Europe is the highest host of the tournament, having hosted the tournament 11 times.

![Screenshot (112)](https://user-images.githubusercontent.com/106377378/175816980-832eeef4-448f-4394-ad9d-10082b47a757.png)

The country with the highest overall goals since the begining of the tournament were also gotten using table and it shows that, Germany has the highest overall goals (229), since the begining of the tournament.

![Screenshot (114)](https://user-images.githubusercontent.com/106377378/175817331-564f55dc-33ea-4351-a314-05af27a373b6.png)

The overall highest goal scorer is Miroslav Klose(Germany) with 16 goals.

![image](https://user-images.githubusercontent.com/106377378/175818201-76d87824-68f6-4fe3-baf5-60c66e642bca.png)

The match outcome by home/away/draw was also visualised using Pie chart

![Screenshot (121)](https://user-images.githubusercontent.com/106377378/175827181-6eba7009-82dd-419d-8061-68e5934a48a4.png)



**Some others visuals were also made and they can seen in the report, in the Visualization section**



### Visualization

![Screenshot (122)](https://user-images.githubusercontent.com/106377378/175827206-fc966dff-35b1-47d2-8dba-323c3a1e8ea2.png)

![Screenshot (123)](https://user-images.githubusercontent.com/106377378/175827237-4d8874f1-0661-4985-968d-a6645977b906.png)



### Observations
The first thing that was observed was that, the competition is a quadrennial competition, that it is, it takes place in every four years.

It was also noticed that the competition didn't take place two tmies cosecuttively, in the hear 1942 and 1946 and research shwoed that this happened due to the world Wear II that was on then.

From the research it also shows that the competition has been played 21 times.

It also shows that Brazil has won the tournament 5 times and making it the country that has won the competition most.

it was also shown notice that Europe continent has won the tournament most 12 times, than any other tournament with 5 countries having won it from the competition and  American continent has won it 9 times with (Southern and Northern part of the continent being added together) with # countries from the tournament.

Miroslav Klose of Germany has the highest number of goals in the competition 16 goals and participated in the competition four times in 2002-2014.

The competition is often hosted in a country except for 2002 when two countries hosted it Korea and Japan.

The highest number of venues that has been used for the tournament is 20 venues in the year 2002.

Brazil has participated in the tournament 21 times, making it the country with highest number of attendant oin the tournament and the only counntry that has never missed any tournament since the beginning of the tournament.

The highest goal scored in a tournament is 171, in the year 1998 and 2014 and the lowest goal scored in the competition is 70 in the year 1930 and 1934.

The competition statrted with 13 countries in the year 1930, then gradually it started increasing and now it's being played by 32 countries since 1998.

And the competition recorded its highhest number of attendance in the year 1994 with 3,568,567 in the United states of America, and recorded its lowest number of attendance in the year 1934, with total number of 395,000 in Italy.

The match with the highest number of attendance was the final between Uruguay and Brazil in the 16th of June in the year 1950, with the total number of 173,850 














