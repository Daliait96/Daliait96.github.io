---
layout: post
title: Work Stages
---

* Data acquisition.
* Data cleansing.
* Data processing.
* Data visualization.
-----

![Image test]({{ site.url }}/images/dayofweek_outflow.png)


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


Thanks!
