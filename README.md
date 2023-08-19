# Floral_Sales_Project

![flowers](https://github.com/JoeBwonKenobi/Floral_Sales_Project/assets/117705408/21abb11b-0243-48ce-8ca3-7b09ff3a1261)

Predicting Future Floral sales data
# Description

The goal of this project is to help the owner of the floral shop to understand the trends and patterns in sales, and use a predictive machine learning model to make predictions for the future sales of the shop. This uses real data from a shop-owner , for the sake of privacy I will not use the actual name of the shop, but the data is from a fine floral shop in middle Tennennsee. 

# Data 

The data was provided to me be the shop owner, who uses floranext and Bloom Nation as their sales operating systems. I was provided sales reports downloaded from these sites in csv format as the data i will be using. The Bloom Nation data set was limited in what it could provide as far as useful data relevant to our project goal.

# Methods
I downloaded the data sets and combined them together using SQL Lite. I then cleaned the data, addressed the null values, and prepared the data for visualization and pipeline construction to prepare it for modeling. I used a reggression model to make predcitions based on the sales data I was provided with.

# Visualizations
The visualizations helped to identify the trends and patterns for sales throughout the different months of the year for five and a half years. Only Bloom Nation had certain information specific to the orders purchased through the shops wedsite, these are unfortunately innaccurate as they don't require the customer to fill out all of the available categories to place an order so a lot of the the data is just not there. The visualizations about () are only using data from Bloom Nation's sales, not the total sales of the store overall. There are many customers who purchase items in-store as walk-ins and do not have recorded date for occassion(other collumns).

%%html
<div class='tableauPlaceholder' id='viz1692320040992' style='position: relative'><noscript><a href='#'><img alt='Grand Total By Month ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fl&#47;Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fl&#47;Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1692320040992');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


[Link Text]([URL](https://public.tableau.com/app/profile/joseph.lardie/viz/Floral_Data_Visualizations-paymentmethodbyyear/Sheet42))



%%html
<div class='tableauPlaceholder' id='viz1692327975842' style='position: relative'><noscript><a href='#'><img alt='Monthly Aggregation of Order Type Grand Total ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fl&#47;Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet13&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet13' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fl&#47;Floral_Data_Visualizations-paymentmethodbyyear&#47;Sheet13&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1692327975842');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
# Description of final model

A reggression model made to make predictions

[Link Payment Method by Year]([URL](https://public.tableau.com/views/Floral_Data_Visualizations-paymentmethodbyyear/Sheet42?:language=en-US&:display_count=n&:origin=viz_share_link))


# Recommendations
One recomendation I have for the shop owner would be to make an modification to the website that requires certain information like ocassion and recipient to be entered to place an order. This way there would be alot more data to analyze that gives insight on the most popular ocassion, and who the most common recipients are. This would have to be a conversation between the shop owner and the company that the website is run through. If accomplished, this could make a major impact on the amount of usable data available and provide much more insight about specific trends and patterns.

# Limitaions & next steps
This project was limited to the data I was provided, and my personal experience from working at the store for a short time to understand the inner workings of the store. There are many customers that purchase things from the store in-person. It is located in a rather rich part of town where alot of elderly people live. It is also next to a popular local coffee shop which brings in a decent amount of foot traffic. There is limited data for these sales for the () columns. The next steps are to show the shop owner my findings of the trends and patterns in sales so that he may optomize things like payroll during slow seasons, product inventory before and after busy months, which things sale the most fequenty in-store, and the most popular occassions for specific months of the year.

# For further information
