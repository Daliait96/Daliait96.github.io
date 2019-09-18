---
layout: post
title: Project Two
---
Movies’ Rating Prediction

### Introduction

Predicting the ratings by using IMDb movies’ data , maybe can be useful for the first Saudi cinema company to know the approximate value of the rating for new movies. This will help them better attract more viewers.

---

### Methodoology

Web scraping by using beautifulsoup4.

### Data set

Using IMDb movies’ data:

* Take Data for 1500 Movie.
* 4 features: <br>
Runtime (Numerical) , Gross (Numerical) , Genre (Categorical) , Votes (Numerical).

### Distribution Of Rate Values

![Image test]({{ site.url }}/images/target.png)


### Correlation Matrix

![Image test]({{ site.url }}/images/Heat map.png)


### Model Selection Process

* Stage 1:<br>

Baseline Model:𝑹^𝟐 = .3

* Stage 2:<br>

Features:
Vote , Action,
Thriller and log(Gross)
𝑹^𝟐  = .42

* Stage 3:<br>

Features:
Runtime,  Vote , Action, Comedy,
Thriller and log(Gross)

𝑹^𝟐  = .44

### Gross Transformation

![Image test]({{ site.url }}/images/Gross1.png)

<br>

![Image test]({{ site.url }}/images/Gross2.png)


### Residual and q-q Plots

![Image test]({{ site.url }}/images/R and qq plots.png)


### Actual and predicted values


![Image test]({{ site.url }}/images/actual and predicted values.png)


### Conclusion

Top Features:
* Vote: is the most influential feature.
* Comedy: has the most influence with a negative correlation.

### Future Work

* Add more observations to create a model that better generalize.
* Extract Additional Features: <br>
 Release Date
 The producer of the movie
 

###  Appendix 'A' Number of the frequency of the movie genre

![Image test]({{ site.url }}/images/movies genre.png)

### Appendix 'B' OLS Regression Results

![Image test]({{ site.url }}/images/OLS.png)
























