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


