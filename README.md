# Floral_Sales_Project

![flowers](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/21abb11b-0243-48ce-8ca3-7b09ff3a1261)

Predicting Future Floral sales data
# Description

The goal of this project is to help the owner of the floral shop to understand the trends and patterns in sales, and use a predictive machine learning model to make predictions for the future sales of the shop. This uses real data from a shop-owner , for the sake of privacy I will not use the actual name of the shop, but the data is from a fine floral shop in middle Tennennsee. 

# Data 

The data was provided to me be the shop owner, who uses floranext and Bloom Nation as their sales operating systems. I was provided sales reports downloaded from these sites in csv format as the data i will be using. The Bloom Nation data set was limited in what it could provide as far as useful data relevant to our project goal because it does not require the customer to fill out every option availble to them when making a purchase order.

# Methods
I downloaded the data sets and combined them together using SQL Lite. I then cleaned the data, addressed the null values, and prepared the data for visualization and then pipeline construction to prepare it for modeling. I used a Random Forest reggression model to make predcitions based on the sales data I was provided with.

# Visualizations

## **Quarterly Product Total by Year**
The visualizations helped to identify the trends and patterns for sales throughout the different months of the year for five and a half years. The first of whcich helps us to see the trends in sales by Quarterly for each year organized by the order date. This can help the shop owners to identify what months out of the year they may need temporay help with arrangements and deliveries, or for slower months cut back on ordering extra stock.

![Quarterly Product Total through the years](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/10691d1c-885e-480f-b60b-f69ecaec0005)

- As expected, the months that have major holidays (Christmas, Valentine's day, and mother's day) are the busiest year over year.
- March and April seem to consistantly be the slower months year over year.

## **Monthly Order Type Grand Total**

This second visulization shows the order type distribution for each month. This can help the owner's identify what months are more popular for walk-ins and deliveries.

![Monthly aggregation of Order Type Grand Total](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/2d56f9e4-221d-402e-97ff-9557773dc61e)

## **Yearly Total for Payment Methods and Order Types**
 This shows a comparison of the different payment methods customers used to pay for the different order types.

![Yearly Total for Payment Methods and Order Types](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/31086fff-c9b2-428a-b820-2c4fb394c7ca)

- As exspected, most customers use a creditcard or the website for a delivery and pickup.
- Credit cards are the most popular across every category, and cash seems most popular for taken and pick-up orders.

# Description of final model
A Random Forest reggression model made to make sales predictions.
I tried several other models, but this one preformed the best of all of them

[Link Text]([URL](https://public.tableau.com/views/Floral_Data_Visualizations-paymentmethodbyyear/Sheet42?:language=en-US&:display_count=n&:origin=viz_share_link))


# Recommendations
One recomendation I have for the shop owner would be to make an modification to the website that requires certain information like ocassion and recipient to be entered to place an order. This way there would be alot more data to analyze that gives insight on the most popular ocassion, and who the most common recipients are. This would have to be a conversation between the shop owner and the company that the website is run through. If accomplished, this could make a major impact on the amount of usable data available and provide much more insight about specific trends and patterns.

# Limitaions & next steps
This project was limited to the data I was provided, and my personal experience from working at the store for a short time to understand the inner workings of the store. There are many customers that purchase things from the store in-person. It is located in a rather rich part of town where alot of elderly people live. It is also next to a popular local coffee shop which brings in a decent amount of foot traffic. There is limited data for these sales for the () columns. The next steps are to show the shop owner my findings of the trends and patterns in sales so that he may optomize things like payroll during slow seasons, product inventory before and after busy months, which things sale the most fequenty in-store, and the most popular occassions for specific months of the year.

# For further information
