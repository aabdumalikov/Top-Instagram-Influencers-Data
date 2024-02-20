## About dataset
In this file, basically there are 10 attributes. It has been ordered on basis of the rank which has been decided on basis of "followers".

rank: Rank of the Influencer on basis of number of followers they have
channel_info: Username of the Instagrammer
influence score: Influence score of the users. It is calculated on basis of mentions, importance and popularity
posts: Number of posts they have made so far
followers: Number of followers of the user
avg_likes: Average likes on instagrammer posts (total likes/ total posts)
60_day_eng_rate: Last 60 days engagement rate of instagrammer as faction of engagements they have done so far
new_post_avg_like: Average likes they have on new posts
total Likes: Total likes the user has got on their posts. (in Billion)
country: Country or region of origin of the user.


## Tasks
* Top Rank draw 15 users through bar chart
* Draw 15 users by Top posts via bar chart
* Draw 15 users by bar chart according to Top Total Likes
* Draw 15 users by bar chart according to Top Average Likes
* Average number of layers top 10 users draw through pie chart
* Draw all users between countries through Sunburst - > path=[Country,
channel_info] by followers
* Draw all users between countries through Sunburst - > path=[Country,
channel_info] by avg_likes
* Draw all users between countries through Sunburst - > path=[Country,
channel_info] by posts
* Draw all users between countries through Sunburst - > path=[Country,
channel_info] by total_likes


## Installation
There are some libraries the I used during the project. You can download required files from requirements.txt file 
runnig these terminal codes below
```    
    # write it in your terminal
    pip install -r requirements.txt   
```


## Usage
You can use this project by running [influencers_analytics.ipynb](influencers_analytics.ipynb) file. For runnig this file Do these instead:
```angular2html
jupyter notebook my_mobapp_studio.ipynb
```
You can see analysis of this project on my [medium blog](https://medium.com/@abdumalikov7475/google-play-store-apps-dca65861d7f8) post.