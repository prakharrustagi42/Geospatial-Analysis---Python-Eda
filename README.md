# Geospatial-Analysis---Python-Eda



• Performed data preprocessing and transformation with pandas to evaluate delivery and rating metrics over time.<br />

• Visualized Seaborn scatterplot to perform bivariate analysis between cost and rating to derive a relationship
  between the two.<br />

• Utilized the Nominatim geocoder against restaurant instances, to generate folium heatmaps to study cuisine and
  budget distribution across various locations.<br />



Insights and Recommendations :<br />

1) Used Counters form collection library to find that the most famous cuisines are North Indian, Chinese and South Indian in Bnaglore.<br />

2) The median cost for two people eating is Rs. 450 whereas the mean cost is Rs.594 .<br />
   The difference is there due tosome restaurants having subtantially large cost for 2.<br />

3) Using Dist plots from seaborn to study the cost distribution found out that most of the restaurant pricings are under 1000 , therefore they are more budget 
   friendly and affordable.<br />

4) Restaurants with online orders have lower prices than resturants not having online orders( Used Boxplots)<br />

5) The top 5 locations for having the highest numbers of budget restuarants (rating > 4 and cost <=500) are :<br />
    1 BTM<br />
    2.Banashankari<br />
    3	Banaswadi	<br />
    4	Bannerghatta Road	<br />
    5	Basavanagudi<br />

6) **Heatmaps insights and recommendations** :<br />
      MOST of the restaurants are in the central region of Banglore<br />
      The density decreases as we move away from the centre<br />
      Therefore potential entrepreneurs should look for a central location.<br />
   
8) HeatMap according to the cusisine density indicated :<br />
      **The highest number of North Indian restaurants are located in Koramangala**<br />
      Therefore customers should travle to this region to taste premium north indian cuisine.<br />
   
