# Leveraging Online Customer Reviews to Analyze Product Features

**Objective**

Online product reviews have been shown to be a viable source of information for helping customers make informed
purchasing decisions. In several cases, customers can rate products on a numerical scale, and also provide textual feedback pertaining a purchased product.Product attributes expressed online prove useful during the product development stage, as they serve as strong indicators of future outcomes when utilized in an efficient manner.Thus online customer reviews if mined and analyzed correctly can increase the chances of a products being successful in the market through a deeper understanding of market needs.Along with business insights such analysis can also help to improve customer service. 
The objective of my project is to identify the key features of a product that are popular among customers.

**Data set**:

I originally planned to use the publicly available dataset of amazon reviews on AWS. I am currently analyzing that dataset on AWS, but for this analysis I used the dataset on amazon reviews from kaggle.com.For this analysis I focussed on 2 products' 'Amazon Paperwhite Kindle' and 'Amazon HD 8 Firetablet."

**Analysis**

I used NLP to extract text from online reviews.To extract product freatures from text comments, I used LDA topic modeling on cleaned text comments.With topic modeling I selected the top 5 features topics for both the products. To extract the sentiment associated with different product features, I used sentiment analysis on the text comments.The sentiment analysis was performed on each comment.To better understand the effect of each topic on the overall sentiment of the comments, a random forest regrssor was used.The model was selected because it provides values to important features which can provide information about relation between each topic and the overall sentiment.Once I found the important features for each product, I built a chat bot to assist customers in knowing about diffrent features of the 2 products.

**Findings**
This analysis was conducted on 'Amazon Paperwhite Kindle' and 'Amazon HD 8 Fire Tablet".

**Amazon HD 8 Fire Tablet**

Overall customers viewed all the features for this product with a positive sentiment.They were more satisfied with the price and the battery life of the product compared to other features like screen size, games and app.

**Amazon Kindle Paperwhite**

Overall customers were satisfied with all features for this product.Ther were slightly more happy witht the battery life of this product compared to its other features.

**Currently in Progress**

As per my findings , ther customers were happy with all the features of the 2 products. Once reason for this could be the fact that comments for both the products had more positive reviews.So I was intersted in finding a dataset that might have more polarized reviews for both the products. So currently I am analyzing the AWS publicly avaiable datset on customer reviews on an AWS machine. It has csutomer reviews from 1995 to 2017. Hopefully that would give a good insight into importance of different product features.

**Future Work**

I would like to compare the product features of amazon HD 8 fire tablet with its competitors like the ipad 2. That way I can find out wich features of the fire tablet have the potential to give the product on edge over its competition.





