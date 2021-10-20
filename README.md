# LastFM-recommender-system

The application of machine learning in recommender systems stands as one of the leading examples of data science used in the real-world. As the amount of content created on the Internet increases exponentially, it becomes more and more difficult for users to find books, movies, TV shows, and music that they might love. 

However, this increase in data paves the way for the development of recommender systems. Comapnies providing multiple products or services via the Internet heavily rely on recommender systems to increase customer engagement and sales. If you ever purchase a product on a website, you will often see suggestions like "Customers who bought this product also bought xxx...". Sites like YouTube also provide a list of videos under the heading "Recommended for you". These are recommender systems implemented by the company, using your previous interactions and preferences to infer other items that you are also likely to enjoy. 

Any small improvements in the effectiveness of this system can lead to a huge amount of additional revenue, making R&D in this area very lucrative. The original example of this is the [Netflix Prize competition](https://netflixtechblog.com/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429), hosted in 2009; participants had the chance to win $1 million if they could beat the company's current recommender system by 10%.

Content-Based Filtering models were initially designed to recommend items to users that were similar to items they purchased before. This performs well for the most part, but it leaves little possibility for suggesting a different product that the user has never tried before but may really enjoy. This is where Collaborative Filtering comes in. Here, we look at other users and how similar they are to our original user. We take the most similar users and suggest items that they have enjoyed to the original user. This method of recommending items to users based on interactions between other users and that item proves to be very effective at making good recommendations.

More recently, hybrid recommender systems have emerged, which make use of both Content-Based and Collaborative Filtering. These models can take metadata about items and incorporate it into their Collaborative Fitering approach. In many cases, this produces a significant improvement in performance, particularly in cases where there is not much data about a new user.

In this notebook, we would like to build and test multiple iterations of recommender systems to examine their strengths and weaknesses. We would also like to see how each model performs on different types of users, and whether a particular set of users are easier to recommend for than others. 

[Link to Google Colab notebook](https://colab.research.google.com/drive/1WTm50hPwwxsWpYjwDlGO5eOI9OKtdTgj#scrollTo=IbzV3y8bPuzt)
