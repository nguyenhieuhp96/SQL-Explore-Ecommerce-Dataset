# SQL-Explore-Ecommerce-Dataset
Utilized SQL in Google BigQuery to write and execute queries to find the desired data
### I. INTRODUCTION 
#### Database
* ##### This project contains an eCommerce dataset that I will explore using SQL on Google BigQuery. The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.


### II. Exploring the Dataset!

#### Write 08 query in Bigquery base on Google Analytics dataset
### Query 01: Calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
![Cau 1](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/6404a62f-e168-48da-af9d-ca350d65369c)
![Cau 1-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/b4ade2c9-9a28-4dfc-bf38-b15580e65f51)

### Query 02: Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)
![Cau 2](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/043a31c4-d9c6-4231-bd50-094aca03a201)
![Cau 2-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/5f4df1aa-0826-48cb-80cc-bdeabbf94c14)

### Query 03: Revenue by traffic source by week, by month in June 2017
![Cau 3](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/aace35b8-ba17-4ad5-904b-d0f8dbc58cf4)
![Cau 3-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/2240aefc-dbe2-437b-ae2b-bef64456a4e6)

### Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017
![Cau 4](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/07b8eae6-01de-462c-aec1-aae231da68ca)
![Cau 4-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/5843a225-50ae-42d9-82b2-f7bf87d1523f)

### Query 05: Average number of transactions per user that made a purchase in July 2017
![Cau 5](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/5cdcb5af-4844-44ce-9d44-65094f463fe8)
![Cau 5-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/5596c1f5-d92a-4e93-8d88-3983728cda2e)

### Query 06: Average amount of money spent per session. Only include purchaser data in July 2017
![Cau 6](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/0a339c4b-c9fc-4480-b078-d31c0bee4ab4)
![Cau 6-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/868c1761-e803-477a-a4f3-c10426a4f75a)

### Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered
![Cau 7](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/e2c7ccf6-cd94-471d-9922-1f2bf50635bd)
![Cau 7-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/39396473-ad89-43d0-a302-9a48cac0f839)

### Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017
![Cau 8](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/4e5d7ad1-7724-447e-81b2-e98138e09ba8)
![Cau 8-](https://github.com/nguyenhieuhp96/SQL-Explore-Ecommerce-Dataset/assets/135586659/54ef178e-939c-417d-902b-95e871621c09)


### III. Conclusion
* ##### The eCommerce dataset using SQL on Google BigQuery based on the Google Analytics dataset has revealed several interesting insights
* ##### We gained valuable information about total visits, pageview, transactions, bounce rate, and revenue per traffic source,.... which could inform future business decisions
* ##### We can visualize the data with Power BI 
