# Instagram-reach-casestudy

# **Problem Statement**

**Instagram is a popular social media app used by millions of people. It can be used for promoting businesses, creating content, blogging, and building portfolios. As Instagram keeps changing to improve itself for users and content creators, Data Science can help them adapt to these changes in the long run.**

# ****Stakeholder****

****Social Midea Marketing Head/Content Creator****

# Steps

- **Importing Libraries**
- **Checking for Null Values in the Dataset**
- **Analyzing Instagram Reach**
- **Evaluating the Percentage of Impressions from Various Sources on Instagram**
- **Create a word cloud for captions to find most used words.**
- **Create a word cloud for hashtags to find most used hashtags.**
- **Analyzing Content**
- **Analyzing Relationships**
- **Analyzing Conversion Rate**
- **Splitting the Data into Training and Test Sets Prior to Model Training**
- **Training the Model to Predict Instagram Post Reach Using PassiveAggressiveRegressor()**
- **Predicting Instagram Post Reach by Providing Inputs to the Machine Learning Model**

# Important Insights -

- **It's hard to reach all my followers daily based on my home impressions.**
- **Hashtags help new users discover our content, but not all posts can be reached through them.**
- **While some posts have good reach from the explore section, it's still much lower compared to reach from hashtags. Instagram does not recommend our posts as much as we would like.**
- **According to the donut plot, almost 44.1% of our reach is from followers, 33.6% is from hashtags, 19.2% is from the explore section, and 3.05% is from other sources.**
- **The number of comments on a post doesn't impact its reach. Shares do have some impact on reach, but not as much as likes.**
- **There appears to be a linear relationship between the number of times a post is saved and its reach. Finally, let's examine the correlation of all columns with the Impressions column.**
- **Correlation -**

| Impressions  | 1.000000 |
| --- | --- |
| From Explore | 0.893607 |
| Follows | 0.889363 |
| Likes  | 0.849835 |
| From Home | 0.844698 |
| Saves  | 0.779231 |
| Profile Visits | 0.760981 |
| Shares | 0.634675 |
| From Other | 0.592960 |
| From Hashtags | 0.560760 |
| Profile Visits | 0.760981 |
- **More likes and saves will increase reach on Instagram. Shares can also help, but having few shares won't impact reach significantly.**
- **Instagram account's conversation rate is 41%.**

# **Conclusion**

****If a content creator wants to do well on Instagram in a long run, they have to look at the data of their Instagram reach. That is where the use of Data Science in social media comes in.****
