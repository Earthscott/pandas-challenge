# Heroes of Pymoli

The objective is to analyze a sample of purchase data for a fictional fantasy game, **Heroes of Pymoli**, and infer meaningful insights. The data file has the following fields:

1. `Purchase ID`: Ascending numeric index for each individual purchase
2. `SN`: Player ID (string)
3. `Age`: Player age (years)
4. `Gender`: Player gender ('Male', 'Female', or 'Other / Non-Disclosed')
5. `Item ID`: Numeric ID for item purchased
6. `Item Name`: Name of item (string)
7. `Price`: Amount paid for item purchased (note that the price may vary)

The analysis was performed in Jupyter Lab with Python using Pandas. The analysis file is named HeroesofPymoli.ipynb.

<hr>

The following are reported:

### Player Count

* Total number of unique players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

*Calculate each by gender:*

* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Gender

### Age Demographics

*Calculate age demographics for players using bins of 5 years (i.e. &lt;10, 10-14, 15-19, etc.):*

* Count of players
* Percentage of players

### Purchasing Analysis (Age)

*Using the same age group bins, calculate the following statistics using purchase data:*

* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person by Age Group

### Top Spenders

*Identify the the top 5 spenders in the game by total purchase value, then tabulate the following:*

* SN
* Purchase Count
* Average Purchase Price
* Sum of Purchases

### Most Popular Items

*Identify the most popular items first by purchase count and second by total purchase value. List at least the first five items, but add more items to the list as needed if there are ties. Tabulate the following for the most popular items:*

* Item ID
* Item Name
* Purchase Count
* Item Average Price
* Total Purchase Value

### Most Profitable Items

*Identify the 5 most profitable items by total purchase value, then tabulate the following:*

* Item ID
* Item Name
* Purchase Count
* Item Average Price
* Total Purchase Value


