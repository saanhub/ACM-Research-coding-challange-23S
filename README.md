ACM Research coding challenge (Spring 23) : Analysing star types and it's relationship with temperature.

PROBLEM STATEMENT AND INTENT:

Analysing and visually representing the various star types and creating bar graphs with its temperature and spectral class to obtain some relationship between the two.


APPROACH:

1. I imported and used multiple python modules such as numpy, pandas and matplotlib to help with the visual representation of data.
2. I decided to make a pie chart, bar grpahs and a scatterplot to describe some of the relationships between the properties of stars.

3. Firstly, I created a function to chart the number of each star type present in the data. I felt that this was best represented with a pie chart so that it can be seen percentage wise and analysed. After obtaining the pie chart I realised that the number of each star type is the same in the 240 lines of data given. The pie chart below shows the same. 

![image](https://user-images.githubusercontent.com/112913549/215925685-02b77287-47e0-4038-96f7-84161915c5a2.png)

4. Next, I made a function to display tables containing the relationship between the different spectral classes and star temperatures measured in Kelvin. I made two tables-one representing the maximum temperature of each spectral class, and the second representing the minimum temperature. I used the groupby function under python pandas to do the same.

![image](https://user-images.githubusercontent.com/112913549/215926355-52e19ba8-3b50-488e-8f0a-d774721fd69e.png)
![image](https://user-images.githubusercontent.com/112913549/215926389-819711a3-2077-4e2e-b223-dd337110f51a.png)

5. With information from the above tables, I made a list of the median temperature of each spectral class and created a bar graph to represent the same.
From the bar graph, we can see that Spectral Classes O and B have the highest temperatures 





OBSERVATION AND FUTURE STEPS:

After a preliminary analysis, we can say that the amount of data provided may be used to draw logical conclusions from the years 2010-2020, provided that more data can be recorded from the years that are missing it. Additionally, predictive analysis is a possiblity from the data provided in the CarForSale file. With further clean data, a machine learning model can be made in order to predict future pricing and customer satisfaction based on purchases and customer reviews.
