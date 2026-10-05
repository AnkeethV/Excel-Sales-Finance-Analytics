
# Project Background

Atliq Hardware is a FMCG company which sells computers, laptops and peripherals through e-commerece paltforms like Amazon, Flipkart and through stores like croma, best buy and also their own Atliq Exclusive stores. 

The company has significant amount of data on its sales and operational efficiency that has been previously underutilized. This project analyses this data to uncover critical insights that will improve Atliq's commercial success.

Insights and recommendations are provided on the following key areas:

- **Customer Performance**: Evaluation of historical sales patterns, by region, division and market, focusing on Net Sales Revenue for each customer.
- **Market Performance**: Evaluation of historical sales patterns, by region and division, focusing on Net Sales Revenue for each market and comparison with the target.
- **Profit & Loss Statement**: P & L statement with key metrics Net Sales, COGS, Gross Margin and Gross Margin% by region, division and market.

Customer performance report can be found [here](https://github.com/AnkeethV/Excel-Sales-Finance-Analytics/blob/main/Customer%20Performance.pdf)

Market performance report can be found [here](https://github.com/AnkeethV/Excel-Sales-Finance-Analytics/blob/main/Market%20Performance%20vs%20Target.pdf)

P&L Statement by month can be found [here](https://github.com/AnkeethV/Excel-Sales-Finance-Analytics/blob/main/P%26L%20Statement%20by%20Month.pdf)

P&L Statement by Fiscal years can be found [here](https://github.com/AnkeethV/Excel-Sales-Finance-Analytics/blob/main/P%26L%20Statement%20by%20Fiscal%20Years.pdf)

P&L Statement by Market can be found [here](https://github.com/AnkeethV/Excel-Sales-Finance-Analytics/blob/main/P%26L%20Statement%20by%20Market.pdf)

# Data Structure and Initial checks

Atliq's Data structure consists for four main tables as seen below: dim_customer, dim_product, dim_market, fact_sales_monthly with a total row count of 7,99,962 rows.

#### Description of each table is as follows:
- dim_customer: contains customer-related data.
- dim_product: contains product-related data.
- dim_market: contains market-related data.
- fact_sales_monthly: contains monthly sales data for each product.

![Data Model](images/Screenshot%202026-09-27%20234531.png)

# Executive Summary

#### Sales Overview:

**Net Sales for Atliq's customer has increased significantally year over year** with **Amazon, Atliq Exclusive, Atliq e Store, Sage and Flipkart** being the **top 5 customers with above 200% growth in net sales performance.** In addition to this **5 new customers in the year 2021** have also added to the **overall increase in net sales of 589.9 Million.**

![Customer Performance](images/Screenshot%202026-10-03%20000102.png)

With market performance the net sales for Atliq have performed well but have **failed to reach target set for the fiscal year 2021**, with **Poland, Canada, Spain, Indonesia and Germany are below 12%**. 

![Market Performance](images/Screenshot%202026-10-03%20165531.png)

#### Finance Overview:

We see that **GM% declines to 2% after 2019 this is accounted for as year 2020 was Covid**, although the **overall revenue has increased to about 200% in the year 2021.** 

While these were the key findings the following sections will explore additional contirbuting factors and highlight key oppertunity areas of improvement.

![P&L Statement](images/Screenshot%202026-10-03%20172820.png)

# Insights Deep Dive

#### Customer Performance:

- Atliq's **top 5 customers contributed 39.4%** of **total net sales in the year 2021**, these customers have consistently performed from FY 2019.

- Atliq has **expanded** its **customer base by adding 5 new stores** which have **contributed a total net sales of 6.3 Million of about 1.05% of total net sales in the year 2021**.

![Customer](images/Screenshot%202026-10-04%20171440.png)

#### Market Performance:

- **61.3% of total net sales are contributed by top 5 countries in the FY 2021.** Although these countries have **still failed** to **reach the target set** for FY 2021 and are **behind 6-15%.**

- **Norway, Spain and Newzealand** being the **new markets** the company has entered in the 2020 have an **average 5% increase** in net sales revenue year-over-year.

![Market](images/Screenshot%202026-10-04%20195018.png)

#### Division Performance:

**Peripherals & Accessories(P & A)** account for **major net sales of more than 53%-56%** with **Personal Computer(PC)** contributed an **average net sales of 24%.**

![Division](images/Screenshot%202026-10-04%20211753.png)

#### P & L Statement:

- **GM% declines to about 5%** in 2021 post covid compared to 2019. Although the **overall revenue has increased to about 200% in 2021.**

- **In 2019** there is **no significant variations in GM% which falls between 41-42% range** and **October, February and June peaking at 42%.** **In 2020 and 2021** also there are **no significant variations in GM% which ranges between 37.3-36.4%.**

- Company has **gained highest GM%** in **Newzealand, Japan, Netherlands, France and United Kingdom** contributing an **average of 43.9% to overall GM%.**

- **EU region** markets have **performed well with a GM% of 38.5%**, while **APAC region** has **fallen behind with a GM% of 36.4%.**

![P&L FY](images/Screenshot%202026-10-05%20004539.png)

![P&L Market](images/Screenshot%202026-10-05%20004728.png)

# Recommendations

- **Company's overall net sales revenue of 39.4% is being contributed by its top 5 customers two of which are company owned stores**, **diversifying overall net sales revenue** to more customers will **reduce the dependency** on these customers.

- **Almost 61% of overall net sales revenue are contributed by top 5 markets India being the highest**, Company has already entered **three new markets Norway, Spain and Newzealand** and should continue to **explore more of EU and APAC region.**

- Company has a **major concentration of net sales** in **Peripherals & Accessories(P & A)** which accounts to **55%**. **Personal Computer(PC)** division is **overlooked and has shown great potential of 413% growth in 2021**. **Network & Storage(N & S)** also requires attention in terms of **product optimization**.

- Company should **concentrate on optimising COGS cost which includes manufacturing, freight and other costs or increase net sales** to increase the **GM% as of which is about 37%**

- Company is **well established in India** more diversification is required in APAC region, Countries like **South Korea, Australia and Indonesia to be concentrated**.