# Explore_Ecommerce_Dataset_2
## I. Introduction
- This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.
- Table Schema: https://support.google.com/analytics/answer/3437719?hl=en
## II. Dataset Access
The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:
- Log in to your Google Cloud Platform account and create a new project.
- Navigate to the BigQuery console and select your newly created project.
- In the navigation panel, select "Add Data" and then "Search a project".
- Enter the project ID "bigquery-public-data.google_analytics_sample.ga_sessions" and click "Enter".
- Click on the "ga_sessions_" table to open it.
## III. Exploring the Dataset
In this project, I will write 08 query in Bigquery base on Google Analytics dataset </br>
**Query 01: Calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/6ea92dcd-88f4-45f4-a72f-5a882c8b8902" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/c119df65-79de-4fc2-b275-0ae9ffb962bc" alt="..." width="600" /><br />

**Query 02: Bounce rate per traffic source in July 2017 (order by total_visit DESC)**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/7b8fcbb6-430f-492d-baf8-b637b2a2c0be" alt="..." width="600" /><br />
- Query result <br/>
<img src="https://github.com/user-attachments/assets/de842b8a-8216-40b4-a2db-c0b7d3789d35" alt="..." width="600" /><br />

**Query 03: Revenue by traffic source by week, by month in June 2017**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/ad304645-606f-41e6-a192-e6a627270e2d" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/fb449d25-8de5-4980-8ffe-b8c643df0372" alt="..." width="600" /><br />
- Query result <br/>
<img src="https://github.com/user-attachments/assets/cfa3efca-207d-45bf-8a60-b7fab0000652" alt="..." width="600" /><br />

**Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/cf0ed985-da8c-493f-a199-808e937907f4" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/8f46acbb-3f7a-4953-ab5d-69e6b87e0690" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/8c215688-91cf-4b9d-b784-5f7c40ade5bd" alt="..." width="600" /><br />

**Query 05: Average number of transactions per user that made a purchase in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/fcda8dce-3fc4-4671-9e49-4fd221604cb6" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/c4140c50-cd6a-4a1e-80ab-85f0f4d44614" alt="..." width="600" /><br />

**Query 06: Average amount of money spent per session. Only include purchaser data in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/9bb339e9-3cec-4fa4-ae6b-9ce207a9c784" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/22f2858c-2846-4ac5-a5a2-b07d806960dd" alt="..." width="600" /><br />

**Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/7f75984b-ff71-46fc-9834-3845c2ab047b" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/61a90ea1-7692-4552-8255-269c909c3f8d" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/adb94f11-0a49-4c60-970c-2bd7be2ec9de" alt="..." width="600" /><br />

**Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/b1bc384c-6848-4f9d-b6fe-b987908675b3" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/d7240d83-230d-4ff5-986d-df45f61f87b4" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/4dc825b7-5d54-4741-9cbb-d2a7edf43b3f" alt="..." width="600" /><br />

## IV. Conclusion
- In conclusion, my exploration of the eCommerce dataset using SQL on Google BigQuery based on the Google Analytics dataset has revealed several interesting insights.
- By exploring eCommerce dataset, I have gained valuable information about total visits, pageview, transactions, bounce rate, and revenue per traffic source,.... which could inform future business decisions.
- To deep dive into the insights and key trends, the next step will visualize the data with some software like Power BI,Tableau,...
- Overall, this project has demonstrated the power of using SQL and big data tools like Google BigQuery to gain insights into large datasets.
