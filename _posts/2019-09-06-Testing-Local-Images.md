---
layout: post
title: Project one
---

Analysis of MTA subway data for NYC.

WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer.

The company responsible for organizing the gala want to place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to the gala. They want to increase the participation of women in technology.


```
---
Project Name: Analysis of MTA subway data for NYC
Team: Data alliance for science.
---
```

As we are a Data scientist team, we conducted an EDA on MTA data set to get insights on the data for client’s purpose.

We will help them to optimize the placement of their street teams by determining the busiest stations and times.


-----

### Work Stages

* Data acquisition.
* Data cleansing.
* Data processing.
* Data visualization.

-----

### Data acquisition

We used the last week of May 2019 from MTA dataset in the analysis process.

* [MTA Dataset](http://web.mta.info/developers/turnstile.html)


### Data cleansing

* Strip White Spaces.
* Make sure there are no NaN values.
* Extract the actual from Entries and Exits values by replace the negative values by zero.
* Set a limit for the entries and exits values.
* Look for the most turnstile.
* Look for the stations near the LAGUARDIA and JFK airports.

After extracting the most crowded stations the airport stations weren’t part of them.

### Data processing

Extract Top crowded ten stations and do the following:

* Top five crowded station by number of exits.
* Look for the most crowded day.
* Look for the most crowded time.
* Set a limit for the entries and exits values.
* Parse Date & Time columns to timestamp.

### Data visualization

![Image test]({{ site.url }}/images/Top 10 stations.png)

![Image test]({{ site.url }}/images/turnstiles.png)

![Image test]({{ site.url }}/images/dayofweek_outflow.png)

![Image test]({{ site.url }}/images/station_outflow.png)

### The Result:

Stations:
34-ST_PENN STA, GRD CNTRL, 34- ST HERALED, 14 ST_UNION, TIMES SW-42 ST.

Day:
Wednesday.

Time:
From 8:00 AM to 11:00 Am.






