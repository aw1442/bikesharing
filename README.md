# bikesharing

## Overview of the analysis

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results

![image](https://user-images.githubusercontent.com/76754655/119265613-2aa9de80-bb9c-11eb-9674-536dc0cee385.png)

1. A line graph shows the number of bikes checked out by duration for all users and can be filtered by the hour.

![image](https://user-images.githubusercontent.com/76754655/119265709-84120d80-bb9c-11eb-9bfe-20618c3e3abf.png)

2. A line graph shows the number of bikes checked out by duration for all users and can be filtered by the hour and gender.

![image](https://user-images.githubusercontent.com/76754655/119265747-9b50fb00-bb9c-11eb-8baf-e0ee53ab40b9.png)

3. A heatmap shows the number of bike trips for each hour of each day of the week.

![image](https://user-images.githubusercontent.com/76754655/119265774-c1769b00-bb9c-11eb-89fc-9b3e061eb229.png)

4. A heatmap shows the number of bike trips for each hour of each day of the week and can be filtered by gender.

![image](https://user-images.githubusercontent.com/76754655/119265803-d5ba9800-bb9c-11eb-862f-a3c9b96a8f68.png)

5. A heatmap shows the number of bike trips for each type of user and gender for each day of the week and can be filtered by user type and gender.

![image](https://user-images.githubusercontent.com/76754655/119265832-07336380-bb9d-11eb-9041-087f15ce9056.png)

6. A bar chart shows the number of bikes checked out for the start time at each hour of the day.

![image](https://user-images.githubusercontent.com/76754655/119265860-33e77b00-bb9d-11eb-89aa-dd3dcd972ba6.png)

7. A pie chart shows the breakdown of gender for Citibike users.

## Summary

The results show that there is a concentration of Citibike users who use Citibike on weekday mornings around 8am and weekday evenings around 5-6pm with usage during the day on Saturday and Sunday. In addition, there are around 2.5 times as many male users compared to female users.

Two additional visualizations that can be suggested for future analysis include:
1. Station capacity for determining which stations are usually at max/min capacity to inform where to add/remove additional stations.
2. Additional analysis based on type of bike such as electronic bikes or different types of builds of bikes with different gears to determine which type of bikes are popular and can be added based on cost/maintenance.
