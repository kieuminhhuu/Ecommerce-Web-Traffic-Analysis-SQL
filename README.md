# Ecommerce-Web-Traffic [SQL in Bigquery]
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
<img src="https://github.com/user-attachments/assets/83a1cea9-6557-4b98-a4e3-0412d06daee5" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/8e07f411-84a3-4ae3-8f60-cb40e317e050" alt="..." width="600" /><br />

**Query 02: Bounce rate per traffic source in July 2017 (order by total_visit DESC)**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/37509bdd-67da-49c8-98ef-20c220881a01" alt="..." width="600" /><br />
- Query result <br/>
<img src="https://github.com/user-attachments/assets/148d762d-e06c-4230-bbad-c8888bf2ad44" alt="..." width="600" /><br />

**Query 03: Revenue by traffic source by week, by month in June 2017**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/362c8f7d-e4f3-4cae-a821-fab531602fe0" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/4225038a-f468-421e-8d66-2e8e72db4a8a" alt="..." width="600" /><br />
- Query result <br/>
<img src="https://github.com/user-attachments/assets/17cf923b-c4f2-4036-a50e-2384cd6ca458" alt="..." width="600" /><br />

**Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017**
- SQL code <br/>
<img src="https://github.com/user-attachments/assets/c83bd633-dec3-4a10-9e3b-43e2ecd02ebd" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/2324f9dd-a165-4091-8667-e8919295c588" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/6574f3d5-959d-4ef4-94e9-4abad81fd396" alt="..." width="600" /><br />

**Query 05: Average number of transactions per user that made a purchase in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/8ab88d1d-db2e-4cc8-ab99-2a9fb9a3f93f" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/6c248627-4571-4ceb-b763-818e37b41531" alt="..." width="600" /><br />

**Query 06: Average amount of money spent per session. Only include purchaser data in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/fe717f77-585a-4835-bda7-b37cad97231b" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/501cad13-426b-4921-9a9d-5b79fa3181ce" alt="..." width="600" /><br />

**Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/91144084-880f-44dd-bdd7-32cc6ed7e31c" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/16d32e60-636e-44c9-ac34-4bdcb7423057" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/9643637a-662d-4ce9-a810-9865c171d443" alt="..." width="600" /><br />

**Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017**
- SQL code <br />
<img src="https://github.com/user-attachments/assets/6ae32655-b2ed-49d0-a61f-caa6463fd727" alt="..." width="600" /><br />
<img src="https://github.com/user-attachments/assets/ce522711-22a5-4c17-af9f-d390d3774e97" alt="..." width="600" /><br />
- Query result <br />
<img src="https://github.com/user-attachments/assets/02b5cb7c-d3cd-467e-9950-d0a3ea97153b" alt="..." width="600" /><br />

## IV. Conclusion
- In conclusion, my exploration of the eCommerce dataset using SQL on Google BigQuery based on the Google Analytics dataset has revealed several interesting insights.
- By exploring eCommerce dataset, I have gained valuable information about total visits, pageview, transactions, bounce rate, and revenue per traffic source,.... which could inform future business decisions.
- To deep dive into the insights and key trends, the next step will visualize the data with some software like Power BI,Tableau,...
- Overall, this project has demonstrated the power of using SQL and big data tools like Google BigQuery to gain insights into large datasets.
