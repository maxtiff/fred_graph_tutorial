<link rel="stylesheet" type="text/css" href="css/bootstrap.css">

Graphing Examples

<img src="FRED Logos/FRED.png" alt="FRED"> 
<h1><small>https://research.stlouisfed.org/fred2/graph/</small><h1>

Compute and graph Quarterly Real GDP for the US economy: Y = C + I + G + NX
1.	Let’s start with C: real personal consumption expenditures, seasonally adjusted (PCECC96).
![Add Data Series](C:\Users\tmay\Pictures\graph_examples\graph1.png)
2.	Select the series, then click the 'Add Series' button as prompted.
3.	Change the observation date range year from 1947 to 1973.
4.	Click the Add Data Series bar then select the 'Modify existing series' radio button to add the next series to the same line. 
5.	Do the same for I: Real Gross Private Domestic Investment, seasonally adjusted (GPDIC96).
6.	And G: Real Government Consumption Expenditures & Gross Investment, seasonally adjusted (GCEC96).
7.	Now, to derive NX: first, add Real Exports of Goods & Services (EXPGSC96) to Line 1. Likewise for Real Imports of Goods & Services (IMPGSC96).
8.	Below the data series, there is a section titled ‘Create Your Own Data Transformation’. In the ‘Formula’ field enter  a + b + c + (d – e) where C = a, I = b, G = c and NX = (d – e). Now redraw the graph.
 
9.	The result: (image)
 
 
Compare the calculation with the official Real GDP series (GDPC1) using the same graph, but a new line.
1.	Go to the Add Data Series bar.
2.	Instead of adding this new series to Line 1, we’ll add it to a new line.
3.	Search for Real Gross Domestic Product, 1 Decimal (GDPC1) and hit enter.
4.	Adjust the observation date range year from 1947 to 1973 and click ‘Redraw Graph’.
(image)
 

Save the graph.
1.	Above the graph click the ‘Save Graph’ link.
2.	To save anything in FRED you must be logged in. If you are not logged in, you will be prompted to do so when you try to save. If you don’t have an account, you can click the ‘Register Now!’ link to the right of the login prompt.
3.	Enter a name for the graph, and, if you chose, edit the date ranges and assign a custom category to your graph for easy reference.

Compute the percent change from a year ago
1.	We’ll need only one line for this exercise, so select ‘Line 2: Real Gross Domestic Product, 1 Decimal (GDPC1)’, and then click the ‘Remove Line’ button.
2.	Only our previously calculated GDP should be on the graph now.
3.	Within the data transformation section, there is a drop-down menu with options to apply a transformation to the formula result.
4.	Select ‘Percent Change from Year Ago’ and then redraw the graph and save it.
(image)
 

Visualize the annual output gap
1.	You can revert the graph back by selecting the blank option in the transformation drop-down menu and then clicking ‘Redraw Graph’.
2.	Change the frequency to annual.
3.	Add Real Potential Gross Domestic Product (GDPPOT) to a new line.
4.	Change the date range observation beginning year from 1947 to 1973 and the ending observation year from 2023 to 2013. Redraw the graph and save it.
(image)
 
Calculate the annual output gap
1.	Remove Line 2 from the graph.
2.	Add Real Potential Gross Domestic Product (GDPPOT) to Line 1.
3.	In the formula field enter f – (a + b + c + (d – e)). Redraw the graph and save it.
(image)
