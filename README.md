# Customer Behavior


By:
- Andrew Samy
- Renad Hamdy
- Mohamed Walid
- Mohamed Osama


## 🎯 Contributors

<a href="https://github.com/IIAndrewII/Customer_Behavior/graphs/contributors">
<img src="https://contrib.rocks/image?repo=IIAndrewII/Customer_Behavior" />


## 🍀 Sponsors

This project exists thanks to:  **information technology institute(iti)**

</p>

<p align="center">
		<img width="10%" src="https://user-images.githubusercontent.com/81884621/188256478-03c82499-b8dc-425c-a160-5ebab2cd2350.png">
	</a>


</p>


## About the data



This is a behavior data set that contains about 9 million rows for two months (October and November 2019) from a medium cosmetics online store hosted by REES46 niche-specific personalization engine Platform. 


## About the Data 
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

 `We will go through a series of:`
 
 - Data cleansing,  
 - Data Transformation,  
 - RFM analysis,  
 - Power BI dashboards
 - Design a recommendation engine using association analysis
 
 
 `To fulfill the following Business Requirements:`


- To what extent we are meeting our KPI’s?

- products to feature in the next campaigns and promotions

- Brand that the customer loyal to 

- Who is the most valuable customers ?

- Is there any price trends !?

- How to increase the profit

- Activate the sleepy customers 

- Percent of lost customers 

- Design a system that helps the customer by suggesting products related to his cart Customized discounts 


### Tech Stacks:
- Python
- Pandas (Library)
- Numpy (Library)
- Matplotlib.pyplot (Library)
- Seaborn (Library)
- datetime (Library)
- apyori (Library)
- Power BI (Dashboard and Analysis)


### Contributors:
- Andrew Samy ([Email](andrew.samy.hanna1998@gmail.com), [GitHub](https://github.com/IIAndrewII))
- Renad Hamdy ([Email](renadhamdy3@gmail.com), [GitHub](https://github.com/renadhamdy))
- Mohamed Osama ([Email](Mohamed7osama7@gmail.com), [GitHub]())
- Mohamed Walid ([Email](), [GitHub]())

