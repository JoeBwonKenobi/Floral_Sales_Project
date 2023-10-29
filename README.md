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
These visualizations helped to identify the trends and patterns for sales throughout the different months of the year for five and a half years. The first of which helps us to see the trends in sales by Quarterly segments for each year organized by the order date. This can help the shop owners to identify what months out of the year they may need temporay help with arrangements and deliveries, or for slower months cut back on ordering extra stock.


![New_Yearly_Totals](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/452cded1-41ef-4832-863f-51852d7e049f)



- As expected, the months that have major holidays (Christmas, Valentine's day, and mother's day) are the busiest year over year.
- March, April, June and July seem to consistantly be the slower months year over year.

## **Monthly Order Method Grand Total**

This second visulization shows the order method distribution for each month. This can help the owner's identify what months are more popular for walk-ins and deliveries.

![Monthly Aggregation of Order Method Grand Total Phone vs  Walk in](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/e1bcf781-99c0-41f0-8230-9d010405c325)

- There are noticable spikes in the walk-in traffic for November and December yearly, obvisously due to the holidays.
- There are overall way more phone orders than walk-in traffic regaurdless of the time of year.
- Florist-to-florist category was a recent addition as an order option which is why we see almost no representation on the visualization.

## **Yearly Total for Payment Methods and Order Types**
 This shows a comparison of the different payment methods customers used to pay for the different order types.


![Yearly Total for Payment Methods and Order Types](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/66fde718-8c8a-463e-86cd-7c7df9ebf4fe)



- As exspected, most customers use a creditcard or the website for a delivery and pickup.
- Credit cards are the most popular across every category, and cash seems most popular for taken and pick-up orders.

## **Monthy Order Type Average Total Per Order**

This shows an average grand total per order monthly so that the show owner can see trends in the average amount a customer spends depending on The Order Type

![Monthly Order Type Average Total Per order](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/6245a9ee-a313-4f53-84e4-7c71444acecc)

- The average for wire-out is so high due to the fact that it represents the shop owner buying flowers in-bulk for another floral shop. They are normal large orders because there are frequently discounted rates on a higher quantity of flowers.
- The lowest average total per order overall is taken which represents a customer walking in and taking the purchased prodcuts out of the store themselves.
- This compairson provides helpful insight that the owner can use to construct pricing strategies, optomize inventory, gain operational efficiency, and serve as a guide for scheduling promotional efforts.

# **Summary of trends and patterns:**

- The 4th quarter consistantly has the most sales year over year, due to a consistant spike in sales for the holiday season.
- December is consistantly the highest selling month (due mostly to christmas and other winter holidays) followed by May (Mother's Day).
- Months that have major holidays (Valentine's day, Mother's Day, and Christmas) have the biggest spike in sales year over year.
- The most popular order method is by phone, followed by Walk-in. This is because most customers want to talk to a designer about customizing their arangement.
- The most popular payment method overall is credit cards for all orders including orders made through the website.
- The most popular Order type is delivery, followed by taken (Products taken out of the store by walk-in customers), and then pick-up (customer picks up in-store, usually at a later date).
- Slower months are consistantly January, April, June, and July year over year.

# Description of final model

## **A Random Forest reggression model made to make sales predictions.**

I built, ran, and tuned hyperparameters for a number of different models, but the best preforming model was the Random Forest Regressor. The Random Forest Regressor model performed strongly, explaining 91.2% of the variation in the test data. On average, it's predictions were off by approximately $12.7, and the largest prediction error was around $51.8. This suggests the model's overall accuracy, with room for minor enhancements to minimize prediction discrepancies. There are many variables to consider when predicting sales, but this model is using only the sales data I was provided from the shop owner.

Below is a look at the model's performance and how the coefficient of determination plays a critical role in telling us how well the model actually performed at predicting sales.

![Random_Forest_R2_Score](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/c57b22e7-1bad-4947-ae44-ff92eb1d0d5d)


# Recommendations
One recomendation I have for the shop owner would be to make an modification to the website that requires certain information like ocassion, product description, and recipient to be entered to place an order. This way, there would be alot more specific data about product popularity to analyze that gives insight on the most popular ocassion, and who the most common senders and recipients are. This would have to be a conversation between the shop owner and the company that the website is run through. If accomplished, this could make a major impact on the amount of usable data available and provide much more insight about specific trends and patterns for what products are most popular for each time of the year and what is not selling. In addition, because alot of the volume is associated with floral arrangements, finding a method to keep track of which flowers were used for which arrangements would provide insight as to which flowers were used more often at certain times of the year.

# Limitaions & next steps
This project was limited to the data I was provided, which was limited to only sales statistics because of the inconsistent website data. There are many customers that purchase things from the store in-person just by browsing throughout the store, there are also many customers who have never been to the store but repeatedly order from the website. It is located in a rather rich part of town where alot of elderly people live. It is also next to a popular local coffee shop which brings in a decent amount of foot traffic consistently during the week on fair weather days. The shop is generally closed on sundays (There are rare exceptions) and usually open from 9:00 am - 4:30 pm; but these hours are subject to change via the owner's descresion. The patterns and trends I've help to bring to light, may help the owner to make descisions about opening and closing times  and wether or not to open on sunday depending on the time of year or schedule of holidays in a given year. The next steps are to show the shop owner my findings of the trends and patterns in sales so that he may optomize things like payroll during slow seasons, product inventory before and after busy months, what the most popular order methods and types are, scheduling hours of operations for specific times of the year and the most profitable months for specific quarters of the year.
