# Project 2 - KGS CO2 COMPENSSATED BY A HOLDING

<p align="left"><img src="https://ep01.epimg.net/estaticos/arc/2021/08/leroy-bosques/images/ilustracion-bosques.svg"></p>

## **Introduction:**

Nowadays, the suistainability in the bussiness market is not only a reality, it's mandatory to implement a Carbon Neutral roadmap and implement different accionts to achieve the Zero Emmission compromise. Cabify is leader of the Spanish market making this compensation for years but now the Companies are really interested in knowing as much information as possible. 

## **Status:**

At the moment, holdings are facing the following issues: 

- A holding is not capable of view all of the companies that belongs to the same group at the same time, it's necessary to login one by one
- The platform is not showing the Kgs of CO2 at any level but Cabify has all the data collected. 

## **Dashboard Solution:**

The dashboard that I've designed is solving both issues at the same time. On one side, it generates the data of a specific holding and, on the other hand, it presents the Kgs of CO2 in different situations requested by clients. 

## **Data Model:**

![_CO2 Compensated](https://github.com/Louruiz89/Project_2/assets/123680936/c602e844-f196-4b4b-b2d1-34e378e31dee)

## **Dashboard Data:**

The Dashboard created for this project contains the following information: 

*Note - All the categories has been anonimized by ids for privacy reasons

- Holding: The data is filtered by specific Holding
- Companies: The compnaies grouped in the holding
- Journey: All the journeys generated by each company inside of this holding
- Address: Start and End points
- Latitude and Longitude of each journey
- User: Worker of each company
- Kms traveled
- Type of vehicle: The category selected by each user as it could be ECO (electric or hybrid) or any of the vehicles (this category may contain ECO or any other type fo vehicle) 
- Date: From March 2022 to May 18th 2023

## **Dashboard:**
The dashboard collect the following information in each chart: 

- **Total Kgs CO2 Compensated 2023:** The total generated in the whole holding in 2023 (untill May 18th 2023)
- **Kms by Category 2023:** PieChart of ECO vs Cabify in Kms traveled
- **CO2 / Journey:** Map with all the journeys marked where they started. By default is all the data but you are able to select per month and scroll to see all the country. 
- **Kgs CO2 Compensated by Company:** You are able to see the information of CO2 Kgs Compensated by each company month by month. 
- **Kgs CO2 2022 vs 2023:** Barchar comparing the same month of different years. 
- **Kgs CO2 - Top 5 users:** The top 5 users that have generated more trips and, for instance, more compensation by each company

[LINK TO TABLEAU](https://tableau.cabify.com/#/site/cabify/views/CB4CO2ParentCliente/Dashboard12_1?:iid=5)

## **Insights:**

- **Total Kgs CO2 Compensated 2023:** First impact of how many KGs are generated by a holding to understand how important is to know and share the information. 
- **Kms by Category 2023:** The main category selected is Cabify. People need to increase the demanding in the ECO category. The holding should push this category as mandatory.
- **CO2 / Journey:** It's easy to know where the journeys are focused and maybe the company can present a green project where the impact is higher. 
- **Kgs CO2 Compensated by Company:** It's easy to find quick which company is generated the biggest amount of trips and compensated more CO2. 
- **Kgs CO2 2022 vs 2023:** The compensation is getting higher (surely due Covid situation as there were lower amount of trips) but it's a good chart for the incoming months. 
- **Kgs CO2 - Top 5 users:** Again, it's a great hint to know how many Kgs of CO2 a person could generate just for business trips. Each company could make a follow up on the top users to find the more suistainability way to travel. 


