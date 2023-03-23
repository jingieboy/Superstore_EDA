# Superstore Case Study (Exploratory Data Analysis)

## <ins>Background</ins>
With growing demands and cut-throat competitions in the market, a Superstore Giant in the US is seeking our knowledge in understanding what works best for them in terms of profitability and sales. 

**About the data:**
- Spans around 4 years
- Sales totalling at \$2.3M and a profit of $286K
- 1862 unique articles in their inventory which are divided into 3 categories (Office supplies, Technology, Furniture), all of which are being sold across 49 states in the US.

## <ins>Approach</ins>
![Approach](/aproach.png)
I want to look at this from 3 key main areas:

- Product Analysis
- Segment Analysis
- Geographical Analysis


### 1. Product Analysis
Looking at the data, I want to identify and look into the revenues and profits from each product category: 

![Piechart](/product.png)
a) From the figure above, we can see that the sales are divided almost equally among the categories. And, the total profit margin is at 12.5%.

However, looking at each product category's share of profit, margins on Furniture is quite low in comparison to Office Supplies & Technology. (This could be due to furniture being a long time purchase, you dont buy furniture often). 

Next, I want take a look at the sub-categories and their respective margins:

![Sub_categories](/sub.png)

So here we have the Top sub-categories with the highest profit margins. And we can see that the drop off in margins is quite big within Tables and Bookcases. Even the 15th highest margin item within Tables is actually being sold at a loss (out of 56 of it's items).

However, we see that Supplies here surprisingly, have a very high margin on many of it's items. Yet, the sub-category as a whole is sold at a loss. And I believe the explanation for this is that the highest selling items (most revenue and impactful on category profit) are being sold at a loss, therefore bringing the margin down for the entire sub-category.

b) So, there are a number of products within Supplies, who have really high sales but are being sold at a negative profit, and thats not really ideal. And to prove this…

![Supplies](/supplies.png) 

I took a look at some of the items in Supplies that contribute to the highest number of sales, and we find that they are being sold at a lost. So, definitely overall it brings the entire profit margin of the whole sub category down, which is not ideal.

### 2. Segment Analysis
So here we have segments of the customers, its being divided between 3 main groups which are Consumer, Corporate and Home Office.

Looking at the segments for the Superstore it is apparent that the Consumer segment is contributing the most to sales.

However, the consumer segment has a bit lower profit margin than Corporate and Home Office. This is most likely due to the high volume of sales it's doing in Furniture, which we saw before has the lowest profit margin out of all the categories of products.

![Segment](/segment.png)

Next, we can see here a distribution of the main categories across different segments. From here, we know that most of the sales for each segment is within Technology, which on average has a high profit margin.

### 3. Geographical Analysis
a) Here we have an overview of the revenue generated from top 10 states in the US.
![Geo](/rev_per_state.png)
We can clearly see that , California is sort of the dominant state. It has around 50% of the total revenue.

However we also see that the drop of in sales between states is quite large as California has 50% more sales than New York (2nd highest by sales) and New York has 80% more sales than Texas (3rd highest by sales). Next, I want to see which states are profiting and which are not.

b) So here we have a chart showing which states are operating at a loss , and which states are doing fine

![profit_states](/share_state.png)

It's important we take a look at states that are on aggregate are making a loss. An important finding here is that some of the states where this company is making most of their sales is actually bringing down the profit that this company is making.

Texas for instance, which is their third highest segment in terms of sales, is actually contributing to more than 1/4 of the loss that the company is making on it's sales.

## <ins> Key Takeaways </ins>
- Technology & Home Office have on average a high profit margin, while Furniture are being sold at low margin or even at a loss for some of its subcategories
- Consumer segment driving most of the Superstore's sales, Technology contributing most revenue across all segments
- Over 50% of their profit is being made in California and New York. This makes this store quite geographically dependent on keeping up their sales here.
- Their sales in Texas (which is their 3rd highest state in sales) is on aggregate making a loss.
  
#### Recommendation: 
**1. Stop selling to certain states where they on aggregate are making a loss.**
        - loss can be attributed to the types of items that are being sold to the customers in this state or that shipment costs to certain areas are driving their profits down

**2. Stop selling non-profitable products**
        - Customer basket analysis
        - Check if low or non-profit items are part of customer baskets that on aggregate are making a profit
  
**3. Cost analysis**
        - Some costs to manufacture items could be reduced to increase profit margins
        - Optimising supply chain process (shipment errors & processes etc.)




























    


