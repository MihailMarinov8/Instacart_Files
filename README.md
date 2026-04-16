#               **Instacart Product Performance Analysis**

- Conducted an in-depth analysis to re-evaluate the available data from Kaggle and pursue a short and long-term plan of action for the marketing,operations and finance teams. Used Microsoft Excel and Power BI to restructure,measure and analyse limited key performance metrics like- ATC order,Word Performance,and Product Performance,with their respective quantative results in correlation and request to all teams that utilise the outcome.
- Showed a clear path to the designated goal,by creating a heatmap of a product's popularity in a chosen cart with the top 12 products that drive the most sales percentage-wise,achieving tangible results along with the needed steps for each individual team and lead in order to achieve a streamlined process.
- Designed and submitted an interactive and intuitive dashboard in Power BI,where the actions are few and the insights and outcomes are many.Included custom metrics and performance indicators to contextualize information and adapt to the user's level of understanding.
---

 ## **Client Background** 
 **Instacart** is a rapidly growing retail media and delivery company in the US and Canada utilizing both a website and a mobile app.Established in 2012 by Maplebear Inc.It offers service from over 2000 retailers with nearly 100 000 stores and has a reported revenue of 3.38 billion US dollars for 2024,making it a valuable business to major investors.

---

## **Note:**

The download link for the Power BI dashboard can be found [here](https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/f02cca8e615ad6f500f9f62fedf4bd3e4e1ba939/Instacart_Dashboard.pbix)  
The Excel Tables can be downloaded [here](https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/f02cca8e615ad6f500f9f62fedf4bd3e4e1ba939/Products_Cleaned.xlsx), [here](https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/f02cca8e615ad6f500f9f62fedf4bd3e4e1ba939/Product_Orders_Cleaned.xlsx) and [here](https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/f02cca8e615ad6f500f9f62fedf4bd3e4e1ba939/Product_Analysis_Cleaned.xlsx)

Total data entries in excel - over **1 million**,with their respected order and product id/name.  
**ATC order = Add to cart order**

---

## **Executive Summary:**

### 1) Product Popularity

The **Top 20%** of products account for more than **80%** of total orders,with the **Bananas, Organic Avocados and Organic Hass Avocados** being the top 3 most purchased and repurchased products (making up ~22% of all products) and seem to be a frequent buy,across all customers.  
The rest of the products contribute a small fraction of the orders so it is best to avoid focusing on them, in order not to decrease ROI.

---

### 2) Product Behaviour/Volutility

Overall,the word **"Organic"** appears to have a negative overall result,doing more harm than good.  
This can potentially lead to an long-term category item being transfered to a short-term infrequent decision,with only a small spike in sales to offer.

---

### 3) Heatmap Findings

There is a strong initial evidence based on the heatmap that the same items are being repurchased alone (and together in the same cart) with other top 10 items.  
After that we can see a slow branch out to other main items in their name/type adjecent products - all the way to the 25th item,meaning the middle pack is most dependent on external factors.  
The last items picked are often not a part of main grocery lists and are mostly "guilty pleasures".

---

### 4) Team Recommendations

#### Marketing Team:
The heatmap analysis highlights two key actions for the marketing team. First,they can test repositioning negatively impacting keywords by placing them later in the product page to improve initial click-through and conversion rates. Second,they can explore targeted rebranding strategies,such as customer/season-based bundles,to guide users toward related products and increase overall engagement.

#### Operations Team:
Based on the Product Performance and Heatmap analyses, the operations team should first conduct an on-site organizational sanity check to identify gaps and ensure store employees and managers are aligned on product accessibility. Additionally,they can initiate a query feature project within the customer app to capture structured feedback on key product characteristics. This would help uncover customer preferences and pain points more effectively. Together,these actions can improve both in-store efficiency and data-driven decision-making in the future.

#### Finance Team:
A monthly revenue forecast across selected locations:top-performing,underperforming,and average-can provide a broader basis for identifying trends and opportunities for improvement. Additionally,reassessing the logistics budget between warehouses with a focus on long-term resource allocation can help create a clearer operational distinction between online and in-person retail channels.

---

## Power BI Dataset Structure

<p align="center">
  <img src="https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/main/Instacart_DataTable_Relations.png" width="900"/>
</p>

---

## Deep-Dive into Insights and Findings:

### Customer Cart Behavior and Bundle Optimization Opportunities

- In the bar graph below we can see that customer purchasing patterns show a clear trend where the first few items added to the cart are relatively consistent with the overall most-purchased items, most commonly **Banana,Avocado,and Blueberry products**.  
As the shopping process continues,the order of added items becomes less predictable,suggesting that customers begin their visit with a clear intention but gradually become more influenced by situational factors before returning to familiar products later in the order.  
Such tendencies are easily altered,so it is imperative that we manage them,using marketing strategies that encompass a large time-frame and customer profile.

- More specifically- **the middle 60%** of items seem to follow a preditermined order that is mainly influenced by the previous items in a given cart.  
This unique quality gives the oppurtunity to implement bundle deals for specific groups of products,and track them for more information.  
In this way we can artificially create item funnels that have the potential of a more significant revenue and sales boost.  
Such a marketing tactic can more easily guide customers and bump up revenue **simultaneously**.

---


<p align="center">
  <img src="https://raw.githubusercontent.com/MihailMarinov8/Instacart_Files/main/Photo2.png" width="300"/>
</p>

---

## Core Product Clustering and Strategic Sales Funnel Optimization

- By analysing the heatmap we notice that the same 12 items are consistently being bought in 5 items or less(regardless of previous items added to cart)- so we can logically assume that they are structually thought out as **"the main items"** before even entering the store.  
- It could be of interest to do an on-site organisation sanity check in that segment of the store,if needed.  
That would help to improve certain product popularity by not diluting the popular items area with rarely bought products.  
Such a process can gradually guide a small but consistent group of customers further along the sales funnel, where they can be "rewarded" with a discounted item. By rotating these discounted items, the business can maintain revenue diversity while avoiding logistical bottlenecks caused by repeatedly focusing on the same product.  
Not only that,but since there is more than a 3 item position margin from the 25th item onwards (on average)-it strongly suggests that those exact products stop influencing one another and are a one-off choice.  
- A monthly revenue forecast can also be a helpful tool in hand-picked locations-the best,the worst and most average one to cast a wide net for further improvements.By allowing us to get a bigger picture of the situation,we can then start making more specific store-by-store plans of action-both short and long term.

---

(photo 3)

---

Bottom 10% of all items are ~20k in number (by ATC order)  
Each row number in both heatmaps represent its "add to cart" order rank in relation to the other 11 products in the cart  
The heatmap in Power BI is only of the top 12 products in order to dive in more into the top performers and how their pick order changes in between one another.  
There is a bigger and more spread out version in Excel- its also where the data was imported from.

---

## Negative Keyword Impact and Price Perception Effects on Product Performance

- In the tables below is the calculation for the word performance of the word **"Organic"** and its effect on item popularity.  
Here we can observe a major marketing and/or branding anomally. Usually words like **"Organic" "Vegan"** and so on boost an item's performance,but in this case it does more harm then good. The marketing team can further investigate this issue by requesting for a query in the customer app and build on that.  
One additional observation is that the negative impact may not come from the word itself,but from price anchoring—customers could be associating **"Organic"** with higher prices and subconsciously filtering those items out before even evaluating them. A useful experiment would be to temporarily remove or delay the **"Organic"** label in the initial browsing view,and only reveal it deeper in the product page,to see whether click-through and conversion rates improve.

---

(photo 4)

---

## Final Recommendations:

### Marketing Team:
- 1) A possible push-back of the **negatively-impacting keywords** in the product labels,putting them later in the product page,to see whether click-through and conversion rates improve.  
- 2) A selected product **rebrand/marketing** campaign that includes:customer or season based bundle that guides the person onto other products of the same variety.

### Operations Team:
- 1) Perform an on-site organisation sanity check,in order to fill missing links,and get store employees/managers on the same page,regarding item accessability.  
- 2) Request the start of a query feature project for the customer app,that tracks valuable feedback regarding the most important product characteristics.

### Finance Team:
- 1) A monthly revenue forecast can also be a useful tool in hand-picked locations-the best,the worst and most average one to cast a wide net for further analyses and improvements.  
- 2) Another way to increase our understanding could be to re-evaluate our budget for logistics between warehouses,focusing on the long-term expenditure for resources,so that there is a clear margin of separation between online stores and in-person locations.

---

## Caveats and Assumptions:

Since there is no time dimension in the picked dataset it can be tricky to pinpoint an exact cause for certain product behaviour/volatility,so there have been adequate adjustments made.This is excluding the Customer Frequency metric since it is not comprehensive enough.
