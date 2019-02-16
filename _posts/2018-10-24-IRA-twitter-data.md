---
layout: post
title: "Some Insight on IRA Twitter Data"
date: 2018-10-24
---
I've been spending some time going through the [Twitter's data dump](https://about.twitter.com/en_us/values/elections-integrity.html#data) of the Russian Internet Research Agency. I read a few articles about this - lots of bar charts and time series. But I'm a very visual guy. Other than just looking at the frequency of tweets over time, I though I'd build some wordclouds from the user profile descriptions and hashtags. For the purposes of this, I only considered accounts listing English as their language. 

Code can be found [Here](https://github.com/harakasj/ira-twitter-data)

Below are hashtags included in each tweet - 442754 hashtags. 

<img src="../../../../images/IRA-hashtag-tweets-wordcloud.png" alt="alt text" width="500">

Below is a wordcloud of hashtags pulled from twitter profile descriptions - around 1000 hashtags from unique profiles.

<img src="../../../../images/IRA-hashtag-profile-wordcloud.png" alt="alt text" width="500">

But I did look at the frequency of tweets from Russian and English (US) accounts. I'm going to take the word of other journalists that the spikes in tweets in Russian are related to Crimea. 

<img src="../../../../images/IRA-TweetsPerDay.png" alt="alt text" width="900">

More work to come!
-John
