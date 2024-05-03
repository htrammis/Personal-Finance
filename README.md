# Personal Finance PowerBI Dashboard
A project that utilizes Microsoft PowerBI to analyze personal financial data and visualize expenses through an interactive dashboard.
## Problem Description
As one should, I have been downloading data from https://github.com/aj112358 then customize data and analyze 
## Project Goals
Here are the questions I would like the PowerBI dashboards to answer:
- Quarterly/Monthly/weekly spending/income/balance (in a given year).
- How much money spent per item category/group category.
- How much money spent per location.
- The number of purchases in various price ranges.
- Various average costs (per week, month, day).
- Comparison of food costs to restaurant costs.
- Comparison of weekday and weekend spending.
In order to answer these questions, I invested time in planning the PowerBI measures I would need to create and also planned a rough outline of the dashboard visuals I wanted.

## Hardware and Software Used
- Windows 11 Machine
- Microsoft PowerBI Desktop (v2.93)
- Microsoft Excel

## Data Collection Methodology

I collected this data by using data from https://github.com/aj112358. The dataset have 1 table with 5 columns: Date, Item Category, Price, Location, Comment.
To delve deeper into personal finance analysis, I have created an additional income table with 2 columns: data and income.

## Data Cleaning
 I had to do some basic editing of the 'Item' category column, in order to have consistent categories. For example, I had 'food', 'Food' as separate categores, and so had to standardize this into simply a 'Food' category.
 Similarly, I have done the same with values such as 'Restaurant' and 'Hair Cut'.
Beside, I changed data type of date's column and remove null ( This would not drastically affect the variance of the overall data).
## Measure Creation & Visualizations
In order to help answer the questions listed above, I started by making three other tables: (i) Calendar Lookup, (i) Item Lookup, (iii) Location Lookup.

The calendar lookup contains each range of dates from the data. From this I created various other useful calculated columns including month name/number, month-and-year, quarter,  and end of week/month.
  
I categorize items into groups. For example, 'Chiro,' 'Gym membership,' etc., will be placed into the 'Healthcare' group.
 
The location table contains a single column of each distinct location of purchase.

Once these lookup tables were ready, I followed my planned layout above and created each visual one at a time. As I created these, I also created the associated measure I would need to portray the data. Some of the measures I made were:
- total cost/ total income/balance
- price ranges
- average cost per day, week, year
The main visuals I used were 'slicers'. I created calendar slicers for overall date, year, quarter, month, and day of week. With these one has a lot of options as to what granularity they wish to visualize their data with respect to dates.  There is also a slicer that acts as a dropdown to select various purchase price ranges.

## Conclusion

Using PowerBI I was able to visualize my purchases data in an interactive way. This allowed me to drill deeper into my spending behaviour and with this information I can now be more conscientious of what I choose to spend my money on.

## Reference 
https://github.com/aj112358

