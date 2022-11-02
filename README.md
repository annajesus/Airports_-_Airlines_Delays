# First Project - Airport and Airline Delays

![pexels-oleksandr-pidvalnyi-1004584](https://user-images.githubusercontent.com/108558769/199157699-e61fdfb5-9313-44c7-a1d8-2a51bbf2eb41.jpeg)

* During this first group project, my group members and I did exploratory data analysis and git collaboration on a data set. First, groups were formed and we outlined project ideas. After researching datasets and submitting a project proposal for approval, we began developing our project as a team. We chose to analyze data on airport and airline flight delays. We found a dataset on Airline On-Time Statistics and Delay Causes from the Bureau of Transportation Statistics website.

* First, we used Pandas to clean and format our dataset. Next, we created Jupyter notebooks to describe the data exploration and cleanup process. Then, we created Jupyter notebooks to illustrate the final data analysis. We used Matplotlib to create visualizations of our data. Next, we created write-ups summarizing our major findings. 

* Then, we prepared a formal 10-minute presentation that covers the following topics: questions that we found interesting and what motivated us to answer them, where and how we found the data that we used to answer these questions, the data exploration and cleanup process, the analysis process, our conclusions (including numerical summaries and visualizations of the summary and the implications of our findings. We have included our Jupyter notebook scripts that we used to run our analysis in this folder.

## Research Questions and Analysis

* 1. What types of delays were seen in airports for all of the years?
   - Air Carrier: Any cancellation or delay due to circumstances within the airline's control (e.g. maintenance or crew problems, aircraft cleaning,    
     baggage loading, fueling, etc.).
   - Extreme Weather: Significant meteorological conditions (actual or forecasted) such as tornado, blizzard or hurricane.
   - Security: Delays or cancellations caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative     
     screening equipment and/or long lines in excess of 29 minutes at screening areas.
   - National Aviation System (NAS): Delays and cancellations attributable to the national aviation system that refer to a broad set of conditions, such as      non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control.
   - Late-arriving aircraft: A previous flight with same aircraft arrived late, causing the present flight to depart late.
    
    https://user-images.githubusercontent.com/108558769/199366165-a2a55ea7-eda0-4f92-81f6-dd90ee326bac.mp4
    https://user-images.githubusercontent.com/108558769/199366250-18d00622-d71b-4328-8440-ec7dbe45a9ff.mp4
    https://user-images.githubusercontent.com/108558769/199366383-a331d9b0-21b3-4f62-8465-7982d2cd5e58.mp4
    https://user-images.githubusercontent.com/108558769/199365758-67bb398b-a7fa-447d-b748-df2620eaca8c.mp4
    
    
    *1.1 Which month had the highest delays for all of the years?
      - The group plot shows percentage delay for each month over the years. The months of June and July showed had the highest percentages of delays.
        


* 2. Which of those types of delays have the greatest impact?
  - To measure the impact of the delays we used the minutes registered to calculate and indicator of average minutes per type of delay
  - For all four years evaluated, a weather delay took on average 25 to 39 minutes longer than any other type of delay. Being 2019 the year with the  
    highest difference (114 min per weather delay)
  - The most impactful type of  delays are the ones caused by weather.
  
  - For airlines with more than 10k delayed arrivals registered, the impact of weather delays is represented below.


* 3. What is the relationship between the types of delays from 2019 to 2022? Hypothesis: As the years increase, the percentage of each type of delay 
    decreases. 
    Firstly, after viewing the data and visualizations that we have generated, we can conclude that there was no relationship between the types of delays 
    from 2019 to 2022.
  - Air Carrier Delays: Increased, then decreased
  - Aircrafts Arriving Late:  Decreased, then increased
  - National Aviation System Delays: Increased, then decreased
  - Security Delays: Increased, then decreased
  - Weather Delays: Increased, then decreased
  - Implications of these findings: as years increase, percent of each type of delay did not decrease; airlines were not able to figure out a way to lower 
    the percent of delays occurring.
    
    
* 4. Which airline & airport had the greatest delay?
    *4.1  Top 3 Worst Airports analysis by Delay Percent
          -Aguadilla, Puerto Rico
          -Punta Gorda, Florida
          -Phoenix, Arizona
  - The pie charts to the right show top 3 worst Airports by Delay Percent breaking down by different categories of delays
  - Carrier, Late Aircraft and National Aviation System (NAS) are the main contributors for the delays 
  - Delay occurrences due to Weather and Security is minimal. However, if the delay due to Weather occurs, delay time by category type  analysis shows that 
    weather delays on average can have more impact.

    *4.2  Top 3 Worst Airlines Analysis by Delay Percent
          -JetBlue Airways
          -Allegiant Air
          -Expressjet Airlines
  - The pie charts to the right show top 3 worst Airlines by Delay Percent breaking down by different categories of delays.
  - Carrier, Late Aircraft and National Aviation System (NAS) are the main contributors for the delays.
  - Delay occurrences due to Weather and Security is minimal. However, if the delay due to Weather occurs, delay time by category type  analysis shows that     weather delays on average can have more impact.
  - In our Analysis we see the same trend in the delay types for both Worst Airport & Airlines.

    *4.3  Worst & Best Airlines Analysis in Top 10 Busy Airports
  - Top 10 Busy Airports are identified based on the total Arrival Flights
  - The group plot to the left shows the worst and best Airlines by Delay Percentage for each airport.
  - For example, for the the busiest airport Atlanta (ATL), the worst Airline is Frontier Airlines with 25% delays and the best airline is Endeavor Air Inc     with 10% delays.
  - Frontier Airlines has max delay percentage in 4 out of 10 busy airports while SkyWest Airlines has the least delay percentage in 4 out of 10 busy     
    airports. 


* 5. Correlation between the average  number of flights arrived and percentage delay.
  - line plot below shows  the correlation between the number of flights arrived and   percentage delay.
  - From the line plot we can see that as the number of flights arrived in airport increased the delay percentage increases.
  - The correlation factor between  average number of flights arrived in airport per month and percentage delay is 0.96.
  - The correlation factor 0.96 indicates there is strong and positive association between number of flight arrived and percentage delay.

    
    
    

## input_Data
### This folder contains Airline_Delay_Cause.csv, the CSV file that we used during our analysis.
