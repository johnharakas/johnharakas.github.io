---
layout: post
title: "Some Insight on IRA Twitter Data 2"
date: 2018-10-25
---
As in my previous, I was working on some wordclouds with Twitter's IRA data dump. To follow up, I'm just adding some network visualization that I was really interested in doing. The below images show a network of Twitter accounts related by retweets - IRA account nodes are listed in green while non-IRA accounts are red. It's interesting to see that there are a ton of inactive accounts represented as isolated nodes, whereas others are strongly connected. Unfortunately, the images don't really do justice to the size of the network - its much more interesting to me as an interactive visual tool. The node size is related to the degree of connectedness - more edges -> bigger node size. 

Here is an overview of the entire network after some clustering. 

<img src="../../../../images/network_overview.png" alt="alt text" width="500">

Twitter bots with very little activity on the outer ring

<img src="../../../../images/deadbots.png" alt="alt text" width="500">

One cluster that I found particularly interesting.  

<img src="../../../../images/Bot-Cluster.png" alt="alt text" width="500">

One strongly connected node.  

<img src="../../../../images/many_edges.png" alt="alt text" width="500">

It goes without saying that there is a whole lot more that could go into this. For one, I didn't take into account multiple instances of edges between accounts - or in other words, an account retweeting multiple times. But I also think that there is a wealth of information to be explored if given the time.
