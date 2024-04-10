# Literature_on_Chinese_aid_and_emperical_research
Understanding determinants of Chinese aid and other forms of state financing
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/89fa8973-2105-4266-82fa-d2a593dd4b30)


Topic: Is Chinese aid primarily channeled towards nations that have poor governance, significant poverty levels, or those that maintain strong diplomatic relations with China? 

In this project, I go over the literature on Chinese aid and utilize data provided by Aid Data, World Bank, OECD, and more data sources to understand the determinants of Chinese aid and other forms of state financing.			


Empirical Methodology:
•	Two different levels: One for all projects and another on only projects in Africa

1.	Pooled regression
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/b0ca27ec-9a43-403a-a851-5077c28d1006)
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/a89b2c41-5545-4410-9907-52cb7f229a15)

   
3.	Fixed effects (country, region (if we do all of the data and not just Africa)
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/8f514623-2fc7-4d3a-a0ec-eec495333886)
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/47c0442b-c922-4b78-a3ca-f3688b5d474d)
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/1f0179f0-33c4-42e5-93b5-9d847f142c65)
![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/4e44eaba-9ea7-49c4-99a4-6e9e0a8ef138)


Interesting variables to consider:
•	Commitment Year
•	Recipient Country
•	Recipient Region
•	Flow Type
•	Intent
•	Concessional
•	Flow Class
•	Sector Name
•	Amount (constant 2017)

Other controls to consider:
•	Institutional Quality (Electoral democracy 2017) – should I pool results or do phase (2000,2005,2010,2015)
•	OECD ODA Givings (should I pool results or do phases?)
•	Relations with Taiwan
o	Recognition of Taiwan (binary)
o	Duration of Relations with Taiwan
•	Natural Resources
o	Share of oil, ores and metal exports
•	Country Characteristics
o	Population
o	GNI per capita
o	Net ODA received per capita
o	Total debt service (% of GNI)
o	Foreign direct Investment, net inflows


•	Dependent variable
o	Y = Total commitment of finance in a given year to country i
o	Y = Total commitment of finance given to country i

o	No umberella records should be included in the analysis
•	I’m considering providing lagged data for some characteristic values(population, GNI per capita, Net ODA received per capita, Total debt service, FDI net inflows) or bucket this into a 5 year trend if that’s possible

![image](https://github.com/KalideEndale/Literature_on_Chinese_aid_and_emperical_research/assets/58799484/8899cf76-bdb8-4622-bd42-ca5a7a410e8f)

