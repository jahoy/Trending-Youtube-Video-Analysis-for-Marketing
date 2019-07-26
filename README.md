# Youtube Channel Recommendation for Influencer Marketing

YouTube nowadays is the largest video hosting website, and it has profound influences on the U.S. This project can help marketing team to select youtube channel and influencer for marketing their business. *This project will provide business recommendations for them, including which channels have more business value and what people are concerning about now.*

## Objectives

Firstly, I will help marketing team to find the category that have relatively higher business potential. I drafted four judgment criterias, which are the number of videos in each category, average view count, variance of view count, average time interval(trending_date-publishedAt).

Secondly, I will help them find out most favoured and hottest channels by four drafted judgment criterias including the appearance frequency, like to dislike Ratio, growth rate, sentiment polarity. The goal is that marketing team can choose to sign contract with these channels to make profit. In addition, they can choose these channels/YouTubers to see if they match the characteristics of their products and find potential customers.

## Data Description

In order to get the data from youtube, I used a script, which is reference from GitHub: https://github.com/DataSnaek/Trending-YouTube-Scraper, to collect data. This youtube scraper can scrape the most trending video from different countries, however, I will mainly focus on the US trending videos based on the data through *March and April 2019.*


`Video_id`: the unique identity of a video     
`Trending_date`: the date that video is ranked     
`Title`: the title of video of the video     
`Channel_title`: the title of the channel which the video belongs to     
`Category_id`: the category of video, which can be looked up using the included JSON files     
`Publish_time`: the time video was published     
`Tags`: the tags a video contains     
`Views`: the number of views each video have     
`Likes`: the number of like each video have     
`Dislikes`: the number of dislikes each video have     
`Comment_count`: the number of comment each video have     
`Thumbnail_link`: the link connected to the cover page     
`Comments_disabled`: if people can leave comments or not     
`Ratings_disabled`: if people can rate the video or not     
`Description`: description of the video     


### Data Analysis Task 1: Most Valuable Category Selection
For this analysis, I aimed to find out the top valuable categories and select one of them to do further study. So, I decided to look at following four attributes by category to assess categories and developed a matrix:

- `Number of trending videos`
- `Average view count`
- `Variance of view count`
- `Average time interval(trending_date-publishedAt)`


### Data Analysis Task 2: Top Hottest Channel Selection
According to previous section, I would like to focus on `Entertainment`.
I will evaluate the channels from these criteria:  
+ `Appearance Frequency`
+ `Like to Dislike Ratio`
+ `Growth Rate`
+ `Sentiment Polarity`


### Conclusion

In my report, I develped two major evaluation matrixs to analyze the value of categories and channels on YouTube so as to help marketing team select channels that is worth to advertise or cooperate. Based on the YouTube data I scrapyed from March to May, I found that `entertainment` category is the most valuable category with the best overall performance. So, I digged into entertainment category, and my finding was that **Binging with Babish Channel** is the most favourable and hot channel in entertainment category. As a result, I would like to recommend *Binging with Babish channel* to marketing team, while I also recommend a controversial Channel, **MrBeast**, since it appears to has high attraction on people.




