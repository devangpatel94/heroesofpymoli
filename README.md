# Heroes of Pymoli
## Summary
* A homework assignment for UC Berkeley's Data Analytics Bootcamp
* Analysis studies a hypothetical fantasy game called "Heroes of Pymoli". The game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience
* The following conclusions can be reached from the analysis:
  * Of the 1163 active players, the vast majority are male (84%). There also exists, a smaller, but notable proportion of female players (14%).
  * Our peak age demographic falls between 20-24 (44.8%) with secondary groups falling between 15-19 (18.60%) and 25-29 (13.4%).
  * Users tend to spend around $4.00.
  * Oathbreaker, Last Hope of the Breaking Storm is the most profitable item with a total purchase value of around $50.
  * The 20-24 age group is the largest age demographic and that age group tends to spend among the most per person (third most of all the age demographics). Under 10 years olds and 35-39 year olds tend to spend a little more per person, but they are also substantially smaller groups.
### Files
* The "heroes_of_pymoli.ipynb" Jupyter Notebook uses Pandas to conduct an exploratory analysis of the game data
* The "purchase_data.csv" file in the "Resources" folder contains the raw data for the Heroes of Pymoli game
## Specific Metrics Studied 
Pandas is used to uncover the following information:
* Player Count
  * Total Number of Players
* Purchasing Analysis (Total)
  * Number of Unique Items
  * Average Purchase Price
  * Total Number of Purchases
  * Total Revenue
* Gender Demographics
  * Percentage and Count of Male Players
  * Percentage and Count of Female Players
  * Percentage and Count of Other / Non-Disclosed
* Purchasing Analysis (Gender)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender
* Age Demographics
  * The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person by Age Group
* Top Spenders
  * Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
    * SN
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
* Most Popular Items
  * Identify the 5 most popular items by purchase count, then list (in a table):
    * Item ID
    * Item Name
    * Purchase Count
    * Item Price
    * Total Purchase Value
* Most Profitable Items
  * Identify the 5 most profitable items by total purchase value, then list (in a table):
    * Item ID
    * Item Name
    * Purchase Count
    * Item Price
    * Total Purchase Value
