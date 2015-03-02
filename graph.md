<link href="http://bootswatch.com/cerulean/bootstrap.css" rel="stylesheet"></link>

<img src="FRED Logos/FRED.png" alt="FRED">
## Graphing Basics


#### Compute and graph Quarterly Real GDP for the US economy: Y = C + I + G + NX
1.	Start with Consumption: real personal consumption expenditures, seasonally adjusted (PCECC96).
![Add Data Series](C:\Users\tmay\Pictures\graph_examples\graph1.png)
2.	Select the series, then click the 'Add Series' button as prompted.
3.	Change the observation date range year from 1947 to 1973.
5.	Add Investment: Real Gross Private Domestic Investment, seasonally adjusted (GPDIC96).
4.	Click the Add Data Series bar then select the 'Modify existing series' radio button to add the series to the same line. 
6.	Add G: Real Government Consumption Expenditures & Gross Investment, seasonally adjusted (GCEC96).
7.	Construct NX: first, add Real Exports of Goods & Services (EXPGSC96) to Data Series 1. Likewise for Real Imports of Goods & Services (IMPGSC96).
8.	Below the data series, there is a section titled ‘Create Your Own Data Transformation’. In the ‘Formula’ field enter  
<pre><code>a + b + c + (d – e)</code></pre> where C = a, I = b, G = c and NX = (d – e). Click 'Apply'.

#### Transform the data
*	Below the formula box, select 'Percent Change from a Year Ago' from the Transformation dropdown menu. The graph will update automatically.

#### Save the graph.
1.	To save anything in FRED you must be logged in. If you are not logged in, you will be prompted to do so when you try to save a graph. If you don’t have an account, you can click the ‘Register Now!’ link to the right of the login prompt.
2.	To the left of the graph, in the tan box, click the ‘Save Graph’ link.
3.	Enter a name for the graph, and, if you chose, edit the date ranges and assign a custom category to your graph for easy reference.


