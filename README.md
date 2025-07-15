
# Amazon-Dashboard

## Problem Statement

The Amazon Global Sales Dashboard (2012–2015) provides a clear summary of Amazon’s performance across sales, product units, returns, KPIs, and regional data. It shows a sales projection of 18 million and a total of 8,998 product units sold. KPIs reach 31K, with 368 recorded returns. Customer returns are highest in the Consumer segment (51.9%), followed by Corporate (30.6%) and Home Office (17.5%). Region-wise, the highest return rate comes from Asia Pacific (31.95%), then Europe (23.93%), US & Canada (21.81%), LATAM (17.04%), and Africa (5.24%).

Top-performing employees like Sargit Chand, Elpidia Ritter, and Carol Adams contribute significantly to profits, while high-return product codes such as OSF-BI-4821 and TEC-PHI-3807 indicate areas for quality review. A global sales map highlights strong presence in North America, Europe, and Asia. Overall, the dashboard helps Amazon identify improvement areas, track performance, reduce returns, and support data-driven decisions to enhance service and efficiency.

# Snapshot of Dashboard (Power BI Service)


 
![Dashboard_upload](https://github.com/VedantNarkhede5/Power-BI-Porject/blob/main/Flipkart%20Screenshort.PNG)



### Steps followed 


Step 1: Load the dataset (CSV file) into Power BI Desktop.

Step 2: Open Power Query Editor. Under the View tab → Data Preview, enable:

Column Distribution

Column Quality

Column Profile

Step 3: Change the profiling option to “Based on entire dataset” to get complete insights (default only checks 1000 rows).

Step 4: On data inspection, no missing or error values were found in most columns except in the "Delivery Delay" column, which had a small percentage of nulls.

Step 5: While calculating average delivery delay, null values were excluded, as they were less than 1% of the total.

Step 6: In the Report View, a custom theme was selected from the View tab to enhance dashboard aesthetics.

Step 7: A new custom visual was imported using the three ellipses (… icon) in the Visualizations pane, used for showing product or category-wise ratings.

Step 8: Slicers (visual filters) were added for better interactivity:

Customer Segment

Product Category

Region

Sales Channel

Step 9: Two Card visuals were added:

One to show Total Sales (in ₹)

One for Average Delivery Delay (in days/minutes)

In the Visual Filters pane, null values were unchecked to exclude them from calculations (although Power BI by default ignores blanks in averages).

Step 10: A Bar Chart was used to show the number of Positive vs Negative Reviews.
The "Customer Gender" field was added to the Legend bucket to break down feedback by gender.

Step 11: A Ratings Visual was used to display average ratings for various sales-related parameters:

Product Quality

Delivery Speed

Customer Support

Order Accuracy

Packaging

Website Usability

Return Process

Payment Experience

Inventory Availability

Price Satisfaction

Mobile App Experience

Courier Service

Any value 0 (representing Not Applicable or not rated) was excluded from rating averages.

Step 12: In Insert tab under Report View, two Text Boxes were added:

One displaying the dashboard name: "Amazon Sales Dashboard"

Another showing the company’s tagline

Step 13: A Rectangle shape was inserted as a design element and the company logo was added using the Insert > Image option.


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.
