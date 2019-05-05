# Twitter-Application-Development
A project from my CSE 487: Data Intensive Computing Course.

**The learning goals of this project were:**
* Familiarize with R language through [Jupyter](https://jupyter.org/) environment 
* Data Collection 
  * Gathered data from a [CDC site of flu data and analysis](https://www.cdc.gov/flu/weekly/fluactivitysurv.htm) and Twitter's [Tweet Search REST API ](https://developer.twitter.com/en/docs/tweets/search/overview)
* Process the data collected for simple data analysis and charting 
* Visualize geo spatial information extracted from the tweets
* Compare CDC's flu HeatMaps with my flu HeatMaps of the USA derived from the twitter data that I obtain 

## So what's in this repo?
### Part 1
In this directory, it consists of statistical and graphical examples that I have done while learning R for first time.

* Barplots
* Boxplots
* Histograms
* HeatMaps (Required libraries [ggmap](https://github.com/dkahle/ggmap), [maptools](http://r-forge.r-project.org/projects/maptools/), [maps](https://eriqande.github.io/rep-res-web/lectures/making-maps-with-R.html), and used
Google [geolocations](https://developers.google.com/maps/documentation/geolocation/intro) API service)
* Scatterplots
* Lines and plots graphs

### Part 2
We make graphs like in part 1, but this time using the data gathered from the CDC site

Here's a few that I made:
* [Graph 1](https://raw.githubusercontent.com/JackFrostiez/Twitter-Application-Dev/master/Lab1/part2/Graph_1.png)
* [Graph 2](https://raw.githubusercontent.com/JackFrostiez/Twitter-Application-Dev/master/Lab1/part2/Graph_2.png)
* [a CDC HeatMap](https://raw.githubusercontent.com/JackFrostiez/Twitter-Application-Dev/master/Lab1/part2/Graph_3.png)

A twitter application implemented in R to gather over 2,000+ tweets with hashtags 
involving the user’s keyword input using the [rtweet](https://rtweet.info/) library.

### Part 3
__For this part, we will start developing a twitter application.__

We need to use Twitter API and do a keyword query search for tweets.  
(_For me, I searched for 10,000 tweets for each keywords "Flu", "Flu Season", and "Sick"._)  

After gathering the tweets, we would need to extract tweets only from users with geolocations found in the data collected.  
(_Note: Not all users provided their geolocations in the twitter data_)

As a result, I successfully made heatmaps representing each keyword.  
Below is the original CDC Heatmap:
![alt text](https://github.com/JackFrostiez/Twitter-Application-Dev/blob/master/Lab1/CDC_HeatMap.png)

__"Flu" Heatmap__
![alt text](https://github.com/JackFrostiez/Twitter-Application-Dev/blob/master/Lab1/Flu_HeatMap.png)  
__"Flu Season" Heatmap__
![alt text](https://github.com/JackFrostiez/Twitter-Application-Dev/blob/master/Lab1/Flu_Season_HeatMap.png)
__"Sick" Heatmap__
![alt text](https://github.com/JackFrostiez/Twitter-Application-Dev/blob/master/Lab1/Sick_HeatMap.png)

I concluded that my "Sick" Heatmap resembleed closest to CDC Heatmap.

__Thanks for reading! I hope you enjoyed seeing my heatmaps!__
