# MIST-4610-Group-Project-2
Team Name: 21479 Group 8

**Group Members**
1. Yared Awoke

2. Shruti Ganesh

3. Yunus Lallo

4. Ayad Momin

**Dataset Description:**
The Motor Vehicle Collisions dataset for New York City, accessible through this link, https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes, records each vehicular crash reported to the NYPD. Information is collected via MV-104AN forms which are filled out for crashes involving significant injury, death, or damages exceeding $1,000. This dataset includes a variety of data dimensions such as the crash date and time, borough location, zip code, and specific street coordinates. It also details the type and number of injuries or deaths involved, contributing factors to the crash, collision ID, and vehicle types involved. It uses several data formats to provide a detailed view of traffic accidents throughout New York City.

**Question One:** From the years 2020-2024, which boroughs in New York had the most and least number of people killed in car crashes?
   
**Importance & Relevance:**

**Health and Safety:** This map identifies the specific borough in New York where accidents frequently occur, helping us prevent injuries and save lives by making those areas safer.

**Road Improvements:** The data helps us know where to add things like speed bumps or new streetlights to improve road safety.

**Cost Savings:** Accidents are expensive due to medical and emergency costs. Knowing where they happen helps reduce these financial burdens.

**Community Action:** By seeing accident hotspots, communities can work together to push for safer streets in their areas.

**Policy Making:** With this information, the government can create better traffic laws to make driving safer, like adjusting speed limits or upgrading traffic signals.


**Tie to the Dataset:**
The dataset from the link, https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes,  is useful for recognizing car crash patterns in New York. It has a full list of crashes, complete with exact spots where they occurred. When we put this information on a map, we can notice the areas with the most problems at a glance. This kind of map helps us see trends, like if one borough has more accidents than another. With this knowledge, city planners and safety officials can work on making those high-crash areas safer for everyone.

**Mapping locations:** They turned street addresses into coordinates on a map, showing where each crash occurred.

**Adding up deaths:** They counted how many people died in crashes in each part of the city to show which areas are most affected.

**Organizing by area:** They arranged the crash data so you can see details for each specific area separately.

**Highlighting danger zones:** They used different colors on the map to mark places with more accidents, making it easier to see where the most dangerous spots are.


**Question Two:** Out of the two boroughs found with the most and least number of people killed in car crashes, which specific car model had the most people killed during the same time period? 

**Importance & Relevance:**

Safety Analysis: Allows the understanding of which car models are involved in the most fatalities and can provide information about the safety of different vehicles. This information can be used by regulatory agencies, car manufacturers, and consumers to assess and improve vehicle safety standards.

Policy Implications: Identifies common factors associated with fatalities, such as specific car models, and can inform policy decisions aimed at reducing the number of deaths on the road. This may include implementing stricter safety regulations and incentivizing the adoption of safer vehicles.

Consumer Awareness: Consumers can use this information to make more informed decisions when purchasing vehicles. Knowing which car models are associated with higher fatality rates may influence individuals to choose safer options, therefore potentially reducing their risk of being involved in a fatal crash.

Interventions: Local authorities and transportation agencies can use insights from this analysis to implement things in areas with higher fatality rates or with specific vehicle models that are at higher risk of being involved in fatal crashes. This could include improved road infrastructure, enhanced law enforcement, or public awareness campaigns targeting drivers of these vehicles.

**Tie to the Dataset:**
The dataset from the link, https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes,  is useful for recognizing car crash patterns in New York. It has a full list of crashes, complete with exact spots where they occurred. When we put this information on a map, we can notice the areas with the most problems at a glance. This kind of map helps us see trends, like if one borough has more accidents than another. With this knowledge, city planners and safety officials can work on making those high-crash areas safer for everyone.

It identifies the boroughs with the most and least number of people killed in car crashes by analyzing the dataset, we can determine which boroughs had the highest and lowest number of fatalities in car crashes during the specified period.

It filters the dataset to include only the car crashes in these boroughs which allows us to subset the dataset to include only the records where the crashes occurred in the two identified boroughs.

The data analyzes the dataset to determine the specific car models involved and contains information about the vehicles involved in each crash, including their make and model. By analyzing this information within the filtered dataset, we can identify the specific car models that were involved in fatal car crashes in the selected boroughs.

We aggregated the data to find the car model with the highest number of people killed. Once we have identified the car models involved in fatal crashes, we can aggregate the data to determine which specific car model had the highest number of fatalities in each of the two boroughs.

**Manipulations Applied to the Dataset:**

**Analysis and Results:**
1. From the years 2020-2024, which boroughs in New York had the most and least number of people killed in car crashes?
   <img width="741" alt="Screenshot 2024-04-26 at 6 25 12 PM" src="https://github.com/shrutiganesh2005/MIST-4610-Group-Project-2/assets/114629015/cb4c95c7-f8eb-493c-80d6-3daeea5e1841">

The time period displayed is contrained to the years 2020 through 2024. The borough of Brooklyn is visually the darkest portion on the map due to having the highest rates of people killed in car crashes. Brooklyn is known for its popular attractions including Coney Island and the Brooklyn Bridge, leading to a high number of people consistently within this area. The number of cars on the road is drastically higher than other regions in New York, and the data reveals that the highest number of accidents occuring here aligns with the apparent popularity of the area. Statistics show that 130 people were killed and 29,058 people were injured in car crashes within the Brooklyn borough between 2020 and 2024. 

On the other hand, the borough with the lowest rate of people killed in crashes was Staten Island. Out of all the boroughs in New York, Staten Island has the lowest population altogether. Statistics show that 18 people were killed and 2,839 people were injured in car crashes within the Staten Island borough between 2020 and 2024. This data also aligns with the fact that the borough is sparsely populated in comparison to the rest of New York.

Relative to each other, Brooklyn is known for its large city presence while Staten Island is known for its prominent green spaces and historical buildings. The living areas of these two boroughs match up with the car crash statistics, allowing researchers to make sense of the meaning behind certain data and which parts of New York are more populated compared to others. 

2. Out of the two boroughs found with the most and least number of people killed in car crashes, which specific car model had the most people killed during the same time period?
<img width="628" alt="Screenshot 2024-04-26 at 6 25 43 PM" src="https://github.com/shrutiganesh2005/MIST-4610-Group-Project-2/assets/114629015/41d2e2d4-0c36-478f-ab39-a2452ca852dc">
<img width="776" alt="Screenshot 2024-04-26 at 6 27 30 PM" src="https://github.com/shrutiganesh2005/MIST-4610-Group-Project-2/assets/114629015/2d98c18f-2a78-469d-bcaf-3e0cd29af339">

After finding which boroughs had the most deaths from car crashes, we found which specific vehicles in each region were responsible for the most crashes. After determining the number deaths for each type of vehicle, we condensed the data to the top five vehicles with the most crashes: bus, e-bike, motorcycle, sedan, and station wagon/sport utility vehicle. 

Relative to each other, Brooklyn having the highest number of deaths and Staten Island having the lowest number of deaths, both shared the similarity of the type of vehicle causing the most deaths. The Sedan caused 13,663 people to be injured and 42 people to be killed between the years 2020-2024 in Brooklyn, NY. In Staten Island, Sedan vehicles caused 1,728 people to be injured and 9 people to be killed. 

On the other hand, the vehicle with the lowest number of deaths was also similar to both boroughs. 437 people were injured by e-bike and 3 were killed in Brooklyn between 2020 and 2024. 2 people were injured and 1 person was killed by e-bike in Staten Island between 2020 and 2024. While each borough has vastly different populations, they both show similarities in aiding researchers to figure out which vehicles seem to be more dangerous on the road. 

**Tableau Packaged Workbooks Attached to ELC**
