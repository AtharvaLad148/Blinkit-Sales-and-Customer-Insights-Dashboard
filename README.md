# Blinkit-Sales-and-Customer-Insights-Dashboard

## Problem Statement

Blinkit requires a comprehensive dashboard to analyze its sales performance, outlet distribution, and customer satisfaction. The primary objective is to uncover key areas for improvement, such as optimizing outlet performance, enhancing customer satisfaction, and refining inventory management to prevent stockouts and overstocking. By addressing these areas, Blinkit aims to boost operational efficiency and revenue. This dashboard will empower Blinkit to make informed, data-driven decisions that enhance overall business performance

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4: Promoted column headers to ensure that the first row of data is treated as column names, establishing a clear and organized dataset for further analysis.
- Step 5: Standardized the "Item Fat Content" column by correcting cells labeled as "LF" and "reg" to "Low Fat" and "Regular," respectively, ensuring consistency across the dataset.
- Step 6 : Added four card visuals to the canvas to display key performance indicators: Total Sales, Average Sales, Number of Items, and Average Rating.
- Step 7 : Added a line chart to visualize trends over time, depicting the growth of outlet establishments from 2012 to 2022.
- Step 8 : Used a treemap to represent the breakdown of total sales by outlet size and fat content, providing a hierarchical view of the data.
- Step 9 : Added a bar chart to compare the distribution of outlet sizes and locations, highlighting areas of high sales concentration.
- Step 10 : Incorporated a pie chart to show the percentage breakdown of outlet types, indicating the contribution of each type to total sales.
- Step 11 : Added a custom visual to represent average ratings for different categories like Baggage Handling, Check-in Services, and Cleanliness, allowing for detailed customer satisfaction analysis.
- Step 12 : Added slicers to the dashboard for filtering data interactively by Outlet Location Type, Item Type, and Outlet Size.
  
### DAX Measures

- Total Sales
        
        Total Sales = SUM('BlinkIT Grocery Data'[Sales])
        
 - Average Sales
 
        Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
 

 - Number of Items
 
         No of Items = COUNTROWS('BlinkIT Grocery Data') 
    

 - Average Rating

        Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
   
## Snapshot of Dashboard 
https://github.com/AtharvaLad148/Blinkit-Sales-and-Customer-Insights-Dashboard/blob/main/blinkit.jpg

        
## Insights 

### Overall Performance
- Strong Sales: Blinkit has achieved a total sales volume of $1.20M, indicating robust performance across its outlets.
- High Average Sales: The average sales per item stand at $141, suggesting effective pricing and strong customer demand.
- Customer Satisfaction: An average rating of 3.9 out of 5 indicates general customer satisfaction, though there's potential for improvement.
### Outlet Performance
- Outlet Growth: The line chart highlights a steady increase in the number of outlets from 2012 to 2018, followed by a slight decline, suggesting a need to reassess expansion strategies.
- Outlet Size Contribution: Medium-sized outlets contribute the most to total sales ($507.9K), striking a balance between scale and efficiency.
- Outlet Location: Tier 3 outlets, while smaller in size, contribute significantly to total sales ($472.13K), indicating higher demand or lower competition in these areas.
- Outlet Type: The pie chart reveals that supermarket-type outlets dominate sales, with Supermarket Type 1 leading at $787.55K, followed by Grocery Stores at $151.94K.
### Item Performance
- Fat Content: Low-fat items make up a large portion of sales, with $425.3K, reflecting a strong consumer preference for healthier options.
- Item Type: Fruits and snacks are the top-performing categories, each generating around $0.18M in sales, indicating a focus on convenience and health-conscious products.
### Customer Satisfaction
- Average Rating Distribution: The custom visual shows that most outlets maintain a rating close to the overall average of 3.9. However, areas like cleanliness and baggage handling might need improvement to boost ratings further.
- Item Visibility: Some items, despite their popularity, have lower visibility, suggesting the need for better placement or marketing strategies to maximize their potential.
