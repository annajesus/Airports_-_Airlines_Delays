<img width="1032" alt="Screen Shot 2022-11-01 at 8 33 16 PM" src="https://user-images.githubusercontent.com/108558769/199367247-ec96cd77-c402-45e3-99a6-4a9e4499bb68.png">

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
    
    <img width="623" alt="Screen Shot 2022-11-01 at 8 30 33 PM" src="https://user-images.githubusercontent.com/108558769/199367286-2daddf3d-74c3-47aa-b007-5103d63933ce.png">


* 2. Which of those types of delays have the greatest impact?
  - To measure the impact of the delays we used the minutes registered to calculate and indicator of average minutes per type of delay
  - For all four years evaluated, a weather delay took on average 25 to 39 minutes longer than any other type of delay. Being 2019 the year with the  
    highest difference (114 min per weather delay)
  
    <img width="915" alt="Screen Shot 2022-11-01 at 8 35 49 PM" src="https://user-images.githubusercontent.com/108558769/199367544-a08d7bc9-86f5-48e2-8080-0be106f132af.png">

  - Despite weather delays being the most impactful, the total volume of minutes of delays is dominated by “Carrier” and “Late Aircraft” delays, which are     under the airlines control. 
  - Using the measure of average minutes per delay we found that the longest delays on average come from Mesa Airlines and the shortest on average come  
    from Southwest, followed by Alaska Airlines

    <img width="896" alt="Screen Shot 2022-11-01 at 8 36 59 PM" src="https://user-images.githubusercontent.com/108558769/199367601-150cda67-2827-4706-908c-1fc11adfda0f.png">



* 3. What is the relationship between the types of delays from 2019 to 2022? Hypothesis: As the years increase, the percentage of each type of delay 
    decreases. 
    - Firstly, after viewing the data and visualizations that we have generated, we can conclude that there was no relationship between the types of 
      delays from 2019 to 2022.
               Air Carrier Delays: Increased, then decreased
               Aircrafts Arriving Late:  Decreased, then increased
               National Aviation System Delays: Increased, then decreased
               Security Delays: Increased, then decreased
               Weather Delays: Increased, then decreased
       - Implications of these findings: as years increase, percent of each type of delay did not decrease; airlines were not able to figure out a way to          lower the percent of delays occurring.
    
    <img width="709" alt="Screen Shot 2022-11-01 at 8 38 12 PM" src="https://user-images.githubusercontent.com/108558769/199367700-dadac655-dc4a-4c97-9edf-30617829a297.png">

     - Secondly, after viewing the data and this visualization, we can conclude that as the years passed, the percent of Air Carrier Delays, Aircrafts   
       Arriving Late, and National Aviation System Delays remained higher than the percent of Security Delays and Weather Delays.
     - Implications of these findings: as the years passed, more passengers were affected by Air Carrier Delays, Aircrafts Arriving Late and National    
       Aviation System Delays than Security Delays and Weather Delays. The airlines were not able to devise a way to lower the percent of flights delayed        due to these three factors.
    
     <img width="661" alt="Screen Shot 2022-11-01 at 8 39 54 PM" src="https://user-images.githubusercontent.com/108558769/199367843-88e3a69c-bbf2-464a-aca2-04e3f9734d6d.png">

     <img width="478" alt="Screen Shot 2022-11-01 at 8 41 01 PM" src="https://user-images.githubusercontent.com/108558769/199367949-ddc14752-d3bf-44cd-aa7a-0ee088b61de3.png">

      - Thirdly, we can conclude that as the years passed:
         - Total percent of flights delayed due to Security Delays and Weather Delays: did not change a lot
         - Flights delayed due to Aircrafts Arriving Late: lower in 2020 than in other years
         - Flights delayed due to Air Carrier Delays: lower in 2019 than in later years
         - Flights delayed due to National Aviation System Delays: higher in 2019 and 2020 than in 2021 and 2022
      - Implications of these findings: after 2020, passengers were less delayed due to National Aviation System Delays in flights. Airlines were able to         devise a way to lower delays due to this cause. The implications of these findings also indicate that as the years passed, passengers were however          more delayed due to Air Carrier Delays. Airlines were not able to come up with a way to lower delays due to this cause.

     <img width="688" alt="Screen Shot 2022-11-01 at 8 41 52 PM" src="https://user-images.githubusercontent.com/108558769/199368033-ef191e93-d100-4855-8d16-2128ecfd3824.png">
    
    
* 4. Which airline & airport had the greatest delay?
    *4.1  Top 3 Worst Airports analysis by Delay Percent
          - Aguadilla, Puerto Rico
          - Punta Gorda, Florida
          - Phoenix, Arizona
          - The pie charts show top 3 worst Airports by Delay Percent breaking down by different categories of delays
          - Carrier, Late Aircraft and National Aviation System (NAS) are the main contributors for the delays 
          - Delay occurrences due to Weather and Security is minimal. However, if the delay due to Weather occurs, delay time by category type  analysis               shows that weather delays on average can have more impact.

    <img width="261" alt="Screen Shot 2022-11-01 at 8 42 54 PM" src="https://user-images.githubusercontent.com/108558769/199368126-8b7cc299-f2d9-4a06-9851-81e47d1e25c6.png">


    *4.2  Top 3 Worst Airlines Analysis by Delay Percent
          -JetBlue Airways
          -Allegiant Air
          -Expressjet Airlines
         - The pie charts show top 3 worst Airlines by Delay Percent breaking down by different categories of delays.
         - Carrier, Late Aircraft and National Aviation System (NAS) are the main contributors for the delays.
         - Delay occurrences due to Weather and Security is minimal. However, if the delay due to Weather occurs, delay time by category type  analysis  
           shows that weather delays on average can have more impact.
         - In our Analysis we see the same trend in the delay types for both Worst Airport & Airlines.

    <img width="261" alt="Screen Shot 2022-11-01 at 8 42 54 PM" src="https://user-images.githubusercontent.com/108558769/199368126-8b7cc299-f2d9-4a06-9851-81e47d1e25c6.png">


    *4.3  Worst & Best Airlines Analysis in Top 10 Busy Airports
         - Top 10 Busy Airports are identified based on the total Arrival Flights
         - The group plot to the left shows the worst and best Airlines by Delay Percentage for each airport.
         - For example, for the the busiest airport Atlanta (ATL), the worst Airline is Frontier Airlines with 25% delays and the best airline is Endeavor            Air Inc with 10% delays.
         - Frontier Airlines has max delay percentage in 4 out of 10 busy airports while SkyWest Airlines has the least delay percentage in 4 out of 10  
           busy airports. 

    <img width="659" alt="Screen Shot 2022-11-01 at 8 44 59 PM" src="https://user-images.githubusercontent.com/108558769/199368380-af294dc4-b55c-4677-a717-efb513f9b87f.png">



* 5. Correlation between the average  number of flights arrived and percentage delay.
  - line plot below shows  the correlation between the number of flights arrived and   percentage delay.
  - From the line plot we can see that as the number of flights arrived in airport increased the delay percentage increases.
  - The correlation factor between  average number of flights arrived in airport per month and percentage delay is 0.96.
  - The correlation factor 0.96 indicates there is strong and positive association between number of flight arrived and percentage delay.

      <img width="606" alt="Screen Shot 2022-11-01 at 8 45 54 PM" src="https://user-images.githubusercontent.com/108558769/199368556-d2d33fb4-858e-437f-a872-d68a7d6e6870.png">  
    
    

## input_Data
### This folder contains Airline_Delay_Cause.csv, the CSV file that we used during our analysis.
