# Customer Behavior


## 🎯 Contributors

- [Andrew Samy](https://github.com/IIAndrewII)
- [Renad Hamdy](https://github.com/renadhamdy)
- [Mohamed Walid](https://github.com/MohamedWaleed56)
- [Mohamed Osama](Mohamed7osama7@gmail.com)

## 🍀 Sponsor

This project exists thanks to:  **information technology institute(ITI)**

</p>

<p align="center">
		<img width="10%" src="https://user-images.githubusercontent.com/81884621/188256478-03c82499-b8dc-425c-a160-5ebab2cd2350.png">
	</a>


</p>


## About the data



This is a behavior data set that contains about 9 million rows for two months (October and November 2019) from a medium cosmetics online store hosted by REES46 niche-specific personalization engine Platform. 


Each row in the file represents an event. All events are related to products and users. Each event is like many_to-many relation between products and users. A session can have multiple purchase events if it's a single order.

## File structure:
| Property | Description |
 | :---: | :---: |
 | event_time | Time when the event happened (in UTC). |
| event_type |  view - cart - remove_from_cart - purchase |
| product_id | ID of a product |
| category_id | Product's category ID |
| category_code | Description |
| Property | Product's category taxonomy (code name) if it was possible to make it. Usually present for meaningful categories and skipped for different kinds of accessories. |
| brand | Downcased string of brand name. |
| price | Float price of a product. Present.  |
| user_id | Permanent user ID. |
| user_session | Temporary user's session ID. Same for each user's session. Is changed every time user comes back to the online store after a long pause.|




## Business Requirements:

- To what extent we are meeting our KPI’s?

- products to feature in the next campaigns and promotions

- Brand that the customer loyal to 

- Who is the most valuable customers ?

- Is there any price trends !?

- How to increase the profit

- Activate the sleepy customers 

- Percent of lost customers 

- Design a system that helps the customer by suggesting products related to his cart Customized discounts 


## To fulfill the following Business Requirements, we will go through a series of:
 
 - Data cleansing
 - Data Transformation 
 - RFM analysis 
 - Power BI dashboards
 - Design a recommendation engine using association analysis
 
 



## Gallery:


![image](https://user-images.githubusercontent.com/92961262/228973361-3d8f72ce-6d48-4192-9375-46b57ca93d80.png)

Dashboard overview:
Number of rows almost 9 million 
Number of unique customers 713K 
Number of unique products 45K
Number of unique categories 455
Total sales 2.74 M
The first graph illustrate the number pf customers through the two months we can see that there is a peak in customers count from 20th to 25th of November and it makes sense as it the black Fridays season.

The second graph illustrates the traffic of users through day hours.

The third one represents the count of each event type through the two months.

The fourth graph illustrates the percentage of total purchased products compared to the total views products.

Suggestions based on the information mentioned above:
The business should be ready before black Friday time, system is ready, enough products in inventories specially products with high demand.

The total percentage of purchased products compared to viewed ones is very low so we should contact the marketing team to perform more campaigns and offers and request more from highly demanding products.



october infographics 
![image](https://user-images.githubusercontent.com/92961262/228973516-cbcc01f3-f15a-471f-a5fb-32b706fada22.png)



November infographics
![image](https://user-images.githubusercontent.com/92961262/228973612-d494ed14-bbb5-423d-bff7-f29676917d69.png)


Valuable customers and most demanding products
![image](https://user-images.githubusercontent.com/92961262/228973705-fdd32887-85bc-442d-80cd-768fd36b2de7.png)

Dashboard overview:
After we got knowing our business and an overview about our data set, it is the time to know more about our customers and products:

The first graph illustrates the top 10 valuable customers we have.

The second graph illustrates the most demanding brands.

The third one illustrates the most demanding products, products frequently purchased from our customers.


Suggestions based on the information mentioned above:

Provide those top 10 customers with more promotions to keep their interest in our services.

Regarding the most demanding brands, we must keep providing their products over time and identify their key characteristics to find more similar brands.

Then regarding the most demanding products we have to make sure we have enough quantities in our inventories.

