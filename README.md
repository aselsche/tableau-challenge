***Citi Bike Analysis***

This is a data visualization report that uses Tableau Public, a free platform to publicly share and explore data visualizations online. The task of this project is to share information about the New York Citi Bike program from January 2019 until September 2021. 

**Overview**

Citi Bike is the nation's largest bike share program, with 25,000 bikes and over 1,500 stations across Manhattan, Brooklyn, Queens, the Bronx, Jersey City and Hoboken. As a new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, my task is to oversee the largest bike sharing program in the United States. Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. 

**Data Source**

Monthly CSV files (September 2019- September 2021) were collected from Citi Bike Data webpage [Citi Bike Data](https://www.citibikenyc.com/system-data).  

**Tableau Story Board**

The link to Tableau story board is here:https://public.tableau.com/app/profile/asel6958/viz/CityBike_16333958185400/Story1#1. 

The story board analyzes data for the period of September 2019 and September 2021.  The story board not only visualizes the Citi Bike's data for 2 years but also presents the impact of the global pandemic to the program operations. The analyzed csv files are stored in the Resources folder of this repository.

**Cleaning the data**
The steps to clean the data are captured and documented in the citi_bike.ipynb jupyter notebook file in this repository.

**Conclusion**
- People seem to ride more bikes during summer than winter. 
- September 2021 was the busiest month in terms of the number of bike rides.
- This past summer was record-breaking summer for the Citi Bike program. 
- Grove Street in [Greenwich village ](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.forbes.com%2Fsites%2Fforbes-global-properties%2F2021%2F07%2F24%2Fexploring-greenwich-village-where-cultural-preservation-meets-renovation%2F&psig=AOvVaw0vvZafInN4HAjWH9VD2rSa&ust=1634007588299000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCJja8uSuwfMCFQAAAAAdAAAAABAm)in Manhattan is the busiest station to start and end the journey.
- Peak hours in Summers are 6 PM. In winters, the peak hours are 8 AM in the morning and 5-6 PM in the evening.
- Since 2021 summer was one of the busiest summers of our program, I looked how it varied by gender. The prpgram stopped tracking gender end of 2020 so the Chart analyzes data only through December 2020. The majority of the bike riders are males. In 2020, due to the global pandemic, the number of rides significantly has decreased.
- The number of subscribers has grown in the past 2 years. The most signicant growth occured in number of casual riders in the past 2 years -- it increased by 598% in 2020 and 110% in 2021 and the number of sunscribers/long term membership went down. The data in Python was cleaned considering some changes: in February 2021, CitiBike changed it's category name for User Type from  Subscriber/Customer to Member/Casual Ride. 




