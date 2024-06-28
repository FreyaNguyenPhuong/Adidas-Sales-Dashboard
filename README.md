# Adidas-Sales-Dashboard
Basic sales dashboard for sales manager

We hear about dashboards all the time. For a newbie, it is easy to mix up dashboard and report. There is a significant difference between these two. A report focuses on analyzing problems and gives insights; thus, it involves lots of information (numbers, texts, graphs, etc.). A dashboard is designed for the user to quickly grasp the importance, usually in graphical form, typically one page with measures against KPI.

Dashboard is the easiest way to keep people focused. Imagine a sales manager whose KPI is achieving sales targets. Her daily concern is to make sure sales are progressing. She probably needs to monitor the results to quickly spot any unusual event and fix it ASAP. A dashboard helps her, and her team watch out for the performance anytime while doing the sales.

In this project, I used PBI to build a sample dashboard for a store/account manager whose KPI is sales target. The original data source is an Adidas sales dataset taken from [Kaggle](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset). I have edited the date column, moving it to the next 3 years to start at 1/1/2023 and dropping some so that it now ends 30/6/2024 (which is “the present”). I have also added the monthly target information under the assumption that 2024 sales grow by 5% from the actual result of 2023 and monthly targets are allocated based on the actual 2023 month and location/product contribution.

The dashboard contains two pages. The first page is an overview of the sales performance. It will be helpful for the manager to get the latest contribution of her store/account in company results as well as the split by different categories namely retailer, sales method, location, and product. The second page monitors the progress of the sale versus the target. The manager needs to track daily sales to ensure the current month's achievement and the progress toward the year-end goal. 

Page 1:
![image](https://github.com/FreyaNguyenPhuong/Adidas-Sales-Dashboard/assets/99577057/34feece8-e2e1-42c8-acb2-78150062f847)
Page 2:
![image](https://github.com/FreyaNguyenPhuong/Adidas-Sales-Dashboard/assets/99577057/9965f6fb-8830-4db0-90e1-0a4c329dad95)

The technical highlights in building the dashboards are listed below:
-	Views in different unit measures
-	Model actual and target data tables
-	Combine Year-to-date actual performance and target Year-to-go

When sales data of a longer timeframe is available, the dashboard can be improved with row-level security, time series analysis, as well as product and channel mix. In addition, as a sales manager, dashboards about stock level, customer profile, and promotion tracking are desirable to the goal of meeting sales targets.

[Dashboard demo](https://github.com/FreyaNguyenPhuong/Adidas-Sales-Dashboard/assets/99577057/48930e31-a39b-430e-8f54-c005a55f6381)

