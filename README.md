# Designing-effective-heatmap-visual-using-excel( Analysis of Nigerian Banks twitter activities)
Understand the dataset
-  54K rows of data from 17 commercial banks’ Twitter activity
-  Data for 3 years 
-  Not all activities were captured in the scraping
Extracting additional fields
- By extracting Year, Month, Hour of Day, Day of Week from the datatime columns using functions like Year,Text, Hour, Day
Design pivot tables
Apply conditional formatting 
- Add a nice and easy to comprehend colour scale by using conditional formatting 
- in this case 
 -- RED - shows the most active period
 -- GREEN - shows the least active period
 Apply a custom number format
 - Make the numbers within the colour codes invisible by changing the number format to ;;;
 Add custom image to chart
 -  Create another summarized pivot table
 - Create horizontal bar pivot chart 
 -  Replace bars with image 
 - Style axes by reversing the order to match the heatmap 
 Created the heatmap legend by:
 Calculating the Max, Average, Min then apply conditional formatting 
