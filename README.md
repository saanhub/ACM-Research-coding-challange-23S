ACM Research coding challenge (Spring 23) : Analysing star types and it's relationship with temperature.

PROBLEM STATEMENT AND INTENT:

Analysing and visually representing the various star types and creating bar graphs with its temperature and spectral class to obtain some relationship between the two.


APPROACH:

1. I imported and used multiple python modules such as numpy, pandas and matplotlib to help with the visual representation of data.
2. I decided to make a pie chart, bar graphs and a scatterplot to describe some of the relationships between the properties of stars.

3. Firstly, I created a function to chart the number of each star type present in the data. I felt that this was best represented with a pie chart so that it can be seen percentage wise and analysed. After obtaining the pie chart I realised that the number of each star type is the same in the 240 lines of data given. The pie chart below shows the same. 

![image](https://user-images.githubusercontent.com/112913549/215925685-02b77287-47e0-4038-96f7-84161915c5a2.png)

4. Next, I made a function to display tables containing the relationship between the different spectral classes and star temperatures measured in Kelvin. I made two tables-one representing the maximum temperature of each spectral class, and the second representing the minimum temperature. I used the groupby function under pandas module to do the same.

![image](https://user-images.githubusercontent.com/112913549/215926355-52e19ba8-3b50-488e-8f0a-d774721fd69e.png)
![image](https://user-images.githubusercontent.com/112913549/215926389-819711a3-2077-4e2e-b223-dd337110f51a.png)

5. With information from the above tables, I made a list of the median temperatures of each spectral class and created a bar graph to represent the same.
From the bar graph, we can see that Spectral Classes O and B have the highest temperatures and M has the lowest temperatures.

From the given data, we can also see that all stars with Spectral class O are Blue in color. Thus, combining information from the bar graph and the given data, we can conclude that stars with very high temperatures are blue in color. Similarly, we can also see that stars with relatively lower temperatures are of the M spectral class and are red in color.

![image](https://user-images.githubusercontent.com/112913549/215928110-e7c8b808-88d9-4ab6-81ed-bf2c8abbe259.png)

6. I have always wonder if the brightness or luminosty of a star is directly related to its temperature. So I decided to create a scatterplot to understand the Luminosities of different star types. From the scatterplot below, we can see that Supergiants and Hypergiants have the highest luminosity. However, the given data shows that the temperatures of supergiants and hypergiants are highly variable and lie accross a huge spectrum. Thus, I believe that more analysis must be done on this aspect to abtain its relationship with temperature.

![image](https://user-images.githubusercontent.com/112913549/215930644-8a8e1431-8296-4717-9f9f-6bae32719eec.png)


OBSERVATION AND FUTURE STEPS:

After some preliminary analysis, we can see that there definitely is a relationship between temperature, spectral classes and star types. With further cleaning of data, some more conclusions can be made with respect to star color too. 
With this information various machine learning models can be created to understand star patterns and the way temperature affects their star type and class. 

