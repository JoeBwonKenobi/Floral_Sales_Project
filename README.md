# Floral Sales Project


![Screenshot 2023-08-30 203845](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/39c7e26f-8f99-4ea3-8e80-e9305851afa2)

*I do not own this photo*

# **Project Objective**

Identify trends and predict future floral sales data.

# Description of Project

The goal of this project is to help the owner of the floral shop to understand the trends and patterns in sales, and use a predictive machine learning model to make predictions for the future sales of the shop. This uses real data from a fine floral shop owner. For the sake of privacy I will not use the actual name of the shop. 

# Data 

The data was provided to me be the shop owner, who uses floranext and Bloom Nation as their sales operating systems. I was provided sales reports downloaded from these sites in csv format as the data i will be using. The Bloom Nation data set was limited in what it could provide as far as useful data relevant to our project goal because it does not require the customer to fill out every option availble to them when making a purchase order.

# Methods
I downloaded the data sets and combined them together using SQL Lite. I then cleaned the data, addressed the null values, and prepared the data for visualization and then pipeline construction to prepare it for modeling. I used Tableau for visualizing the data after cleaning it because Tableau hasso many chocies for making vivd, powerful visualizations. Then, I preprocessed the data and formated it to make sure it was ready for modeling. I tried several machine learning models, the best of which was a Random Forest reggression model to make predcitions based on the sales data I was provided with.

# Visualizations

## **Quarterly Product Total by Year**
The visualizations helped to identify the trends and patterns for sales throughout the different months of the year for five and a half years. The first of whcich helps us to see the trends in sales by Quarterly for each year organized by the order date. This can help the shop owners to identify what months out of the year they may need temporay help with arrangements and deliveries, or for slower months cut back on ordering extra stock.


![Quarterly Product Total through the years](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/fa029b94-0751-41ac-8aba-508b47b824c3)


- As expected, the months that have major holidays (Christmas, Valentine's day, and mother's day) are the busiest year over year.
- March, April, June and July seem to consistantly be the slower months year over year.

## **Monthly Order Type Grand Total**

This second visulization shows the order type distribution for each month. This can help the owner's identify what months are more popular for walk-ins and deliveries.

![Monthly aggregation of Order Type Grand Total](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/6e54c648-4034-4c71-91a0-21e769d3d3ca)


## **Yearly Total for Payment Methods and Order Types**
 This shows a comparison of the different payment methods customers used to pay for the different order types.

![Yearly Total for Payment Methods and Order Types](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/735fe6e7-88e5-46c0-90d0-18febaa6aec4)


- As exspected, most customers use a creditcard or the website for a delivery and pickup.
- Credit cards are the most popular across every category, and cash seems most popular for taken and pick-up orders.

# **Summary of trends and patterns:**

- The 4th quarter consistantly has the most sales year over year, due to a consistant spike in sales for the holiday season.
- December is consistantly the highest selling month (due mostly to christmas and other winter holidays) followed by May (Mother's Day).
- Months that have major holidays (Valentine's day, Mother's Day, and Christmas) have the biggest spike in sales year over year.
- The most popular payment method overall is credit cards for all orders including orders made through the website.
- Slower months are consistantly January, April, June, and July year over year.

# Description of final model

## **A Random Forest reggression model made to make sales predictions.**

I built, ran, and tuned hyperparameters for a number of different models, but the best preforming model was the Random Forest Regressor. The Random Forest Regressor model performed strongly, explaining 91.2% of the variation in the test data. On average, its predictions were off by approximately $12.7, and the largest prediction error was around $51.8. This suggests the model's overall accuracy, with room for minor enhancements to minimize prediction discrepancies. There are many variables to consider when predicting sales, but this model is using only the sales data I was provided from the shop owner.


# Recommendations
One recomendation I have for the shop owner would be to make an modification to the website that requires certain information like ocassion, product description, and recipient to be entered to place an order. This way, there would be alot more specific data about product popularity to analyze that gives insight on the most popular ocassion, and who the most common recipients are. This would have to be a conversation between the shop owner and the company that the website is run through. If accomplished, this could make a major impact on the amount of usable data available and provide much more insight about specific trends and patterns for waht products are most popular.

# Limitaions & next steps
This project was limited to the data I was provided, which was limited to only sales statistics because of the inconsistent website data. There are many customers that purchase things from the store in-person just by browsing throughout the store. It is located in a rather rich part of town where alot of elderly people live. It is also next to a popular local coffee shop which brings in a decent amount of foot traffic consistently during the week on fair weather days. The next steps are to show the shop owner my findings of the trends and patterns in sales so that he may optomize things like payroll during slow seasons, product inventory before and after busy months, what the most popular order methods and types are, and the most profitable months for specific quarters of the year.
