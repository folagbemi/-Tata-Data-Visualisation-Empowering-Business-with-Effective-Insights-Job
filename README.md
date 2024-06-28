# Tata Data-Visualisation-Empowering-Business-with-Effective-Insights-Job

## Client's Background
Tata is a multinational conglomerate headquartered in India. Established in 1868, it is currently among India's biggest and most varied businesses.The industries covered by Tata's corporate portfolio include automotive, consumer goods, energy, engineering, materials, services, and technology.

## Busines Problem
TATA's executive team, which includes the CEO and CMO, aims to use their extensive data collection to inform strategic choices. Understanding seasonal income trends and locating areas with strong product demand are the CEO's main areas of interest when considering possible business expansion. The CMO seeks to identify high-value clients and top-performing nations in order to improve marketing tactics and increase client retention.


## The Project-Objectives
- To clean and prepare the data for analysis. <br>
- To create specific visualizations in Power BI that answer the key questions posed by the CEO and CMO.
- To provide insights that will assist the CEO and CMO in strategic decision-making.

#### Chief Executive Officer Objectives:
- Analyze monthly income trends for 2011.
- Determine which areas have the greatest demand for the product to guide your expansion plans.

#### CMO Objectives:
- Determine the top 10 countries generating the highest revenue, excluding the UK.
- Identify the top 10 customers by revenue for targeted marketing and customer satisfaction efforts.



 #### The dataset includes the following fields:

- InvoiceNo: Unique identifier for each transaction.
- StockCode: Product code.
- Description: Product description.
- Quantity: Number of items sold (includes returns marked by negative values).
- InvoiceDate: Date of transaction.
- UnitPrice: Price per unit of product.
- CustomerID: Unique identifier for customers.
- Country: Country of the customer.

## Data Cleaning
To ensure data integrity and reliability for analysis:
I have noticed that the data contains some returns to the store which are provided in negative quantities and there are unit prices which were input in error. I therefore performed the following steps to clean this data.

- Created a check that the quantity should not be below 1 unit

- Records with unit prices below zero were removed to eliminate erroneous entries.

- This cleaned data was prepared for subsequent analysis in Power BI.

### Tools Used
- Power BI Desktop: For data visualization and analysis.
- Power Query Editor: For initial data review and cleaning.

## Analysis and Visualizations

1. CEO’s Interest in Revenue Trends for 2011
   
Objective: Visualize monthly revenue for 2011 to identify seasonal trends.

<img width="778" alt="Revenue 2011" src="https://github.com/folagbemi/-Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights-Job/assets/134072177/c11d5ac5-97bb-4629-998d-80979337fc58">

November was the month with the highest revenue in 2011 ($1,161,817), while February had the lowest revenue of $447,137. September saw the first significant increase in revenue, which increased by 40% over August. This upward trend persisted, peaking in November at $1.1 million. December's data is not complete enough to draw any conclusions, but it does show a promising month. This analysis reveals a seasonal impact on sales and demonstrates significant growth in specific months.

2. CMO’s Interest in Top 10 Revenue2-Generating Countries (Excluding UK) <br>
Objective: Identify the top 10 countries by revenue and their quantities sold.
<img width="675" alt="top 10 countries" src="https://github.com/folagbemi/-Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights-Job/assets/134072177/2b4550f3-387e-4938-a071-e917bce8d81a">


The Netherlands led the top ten countries in both income and quantity, excluding the United Kingdom, with statistics of $285,446.34 and 200,937 units, respectively. Japan, on the other hand, has the lowest revenue and quantity, totaling $37,416.37 and 26016 units, respectively. This insight gives light on the performance of growth-oriented countries. Notably, countries such as the Netherlands, Germany, Ireland, and France have significant levels of unit sales and income.

3. CMO’s Interest in Top 10 Customers by Revenue
Objective: Identify the top 10 customers by revenue and understand their purchasing behavior.

<img width="695" alt="Top 10 customer" src="https://github.com/folagbemi/-Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights-Job/assets/134072177/f3d62f3e-52ce-4deb-9a91-954a69e3bac7">


According to the analysis of the data, Customer ID 14646 produced the most revenue (280,206.02) out of all the customers, while Customer ID 12346 generated the least (77,183.60).

4. CEO’s Interest in Product Demand by Region (Excluding UK)
Objective: Map the demand for products across different countries.

<img width="590" alt="Map quatity" src="https://github.com/folagbemi/-Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights-Job/assets/134072177/e82f4ef2-5fc4-48e0-a87c-38da31504e85">

Geographic demand for products was mapped, identifying regions such as the Netherlands, Ireland, Germany, France, and Australia with high sales potential.The map also shows that sales are concentrated in the European region, with very few occurring in the American zone. Russia, along with Asia and Africa, have no market for the goods. Potential improvements to sales revenues and overall profitability could come from a new strategic approach aimed at different regions. Furthermore, the Netherlands, with 200,937 units sold, is the nation with the biggest quantity.

## The Dashboard.

<img width="827" alt="Tata Visualization" src="https://github.com/folagbemi/-Tata-Data-Visualisation-Empowering-Business-with-Effective-Insights-Job/assets/134072177/1519de8a-e47b-4a6b-93a3-57d12894919a">



## Recommendations

CEO: Consider strategic expansions in high-demand regions identified in the analysis. Use revenue trends to optimize inventory and marketing efforts during peak seasons.

CMO: Focus marketing efforts on the top revenue-generating countries and customers. Implement targeted retention strategies for high-value customers.

## Conclusions

The analysis provided TATA Online Retail Store with crucial insights derived from their sales data. Revenue patterns, top-performing nations, high-value clients, and areas with substantial product demand were all highlighted by Power BI visualizations.These insights empower the CEO and CMO to make data-driven decisions, enhancing strategic planning, marketing effectiveness, and overall business growth. The project’s outcome ensures TATA can leverage their data to improve customer satisfaction and drive future expansions successfully.

Click [here](https://www.canva.com/design/DAGJW87yMNs/szQyt0-VFqsEkQTvUXQ4Nw/view?utm_content=DAGJW87yMNs&utm_campaign=designshare&utm_medium=link&utm_source=recording_view) to view the prsentation video slides on the analysis of this project 


