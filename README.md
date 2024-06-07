# Creating Business Intelligence Dashboards with Amazon QuickSight
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/dfaba3dd-1068-4882-a437-d33059d0ebe6)
# Creating Dataset
On Datasets, we choose a New Dataset to create a new one. 
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/fc4ea9d0-959a-4cc3-b54b-48890e307651)
On the Data Sources dashboard, choose Upload a file. In the dialog box that appears, browse to and select the Sales Orders.xlsx file, and then choose Open.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/c44e7dfa-30a5-4b26-b72f-dfca34c82723)
In the Choose your sheet dialog box, select orders and then choose Edit/Preview data.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/b9fe9b69-5974-4c8b-8323-dc7c044b3277)
# Preparing Data
On the Edit/Preview data screen, clear the check box for Row ID. This removes the Row ID field from the data set. Then, choose Add calculated field.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/9e624af6-5caa-4a98-a9fc-c570f860fc39)
In the Edit calculated field dialog, in the Functions list, choose dateDiff. Then, in the Field list, choose Order Date, type a comma, and choose Ship Date. Name the Calculated field Processing Time. The formula for your new calculated field should appear as dateDiff({OrderDate},{ShipDate}). Choose Create.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/ea58ec82-9857-4eb2-824d-34de01ecda6f)
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/1f5c75ac-ae71-494b-a1a2-a552f2fb1ae3)
# Creating Analysis
On the Your Data Sets dashboard, choose Sales Orders.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/5f11ca8a-155e-4386-9e36-3f87a3d2cece)
# Creating Visuals
In the Fields list, choose Customer ID. The AutoGraph generates showing a Count of Records by Customer ID.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/bc5cd97d-6db1-493f-9e67-0f2b43564dbc)
# Modifying Visuals
Now that you created your first visual, you can make changes to the visual, such as adding a filter or changing the visual type.
In the Fields list, choose Order Priority. Now, you have a count of records by priority placed by each customer.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/aeac4413-3073-4728-9f75-f3eb01b93560)
In the left menu bar, choose Filter, then choose Create one and select Country.Select the Country filter to edit it. In the Edit filter dialog, select the check box for United States and choose Apply. Then, choose Close. Now, the count of records by priority and customer ID are displayed only for the United States.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/95fcd966-e8a2-4f8c-8c1f-daae69472ca9)
# Adding more visuals
For Visual types, choose Pie chart, and in the Fields list, choose Region. Resize the workspace by selecting and dragging the bottom right corner.
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/787680bc-fe27-49bd-ad68-87de2c66cb24)
# Publish to the dashboard and create a story
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/e958fa02-5953-4b4d-bcb8-8c57700db9f4)
![image](https://github.com/lgoljana/AWS-QuickSight---BI-Dashboards/assets/160978196/ffde1fd6-190b-411d-863b-5f7a1cfcbda4)
