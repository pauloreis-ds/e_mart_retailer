[Context](#Context)<br>
[Presentation](#Presentation)<br>
[Segmentation (Clustering Algorithm)](#Segmentation)<br>


## Context

E-Mart is a Chinese retailer that discovered the e-commerce as a way to sell to the entire world, rather than just to the population of their home city. The company has been growing without much worries, and now It wants to start using the data collected during its 4 years of e-commerce to keep growing and make more money.

The data can be accessed from this repository: https://github.com/pauloreisdatascience/datasets/tree/main/e_market


The company has been growing without much worries, and now It wants to start using the data collected during the years to keep growing and make more money.
At first, the board of directors expects:

- A Dashboard with KPIs to track their growth.

- Robust Data Analysis, as well as recommendation of actions. What's the actionable based on your analysis?

- **An Analysis on geolocation, a segmentation by sales, profit and more. They want insights to help increasing revenue.** 

- Sales forecast for the next year, in order to enable strategic planning.
      
### Presentation
      
<p align="center">
    <img src="images/presentation1.PNG"/>
</p>

<br>

<br>

[Google's First Rule of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml?hl=en): _Don’t be afraid to launch a product without machine learning._

Before applying a clustering algorithm, I looked for natural differences to generate these clusters.

For Sales, there are countries who have lower and higher sales values, but We can't really just differentiate one from another. Many of them overlap.

<p align="center">
    <img src="images/presentation2.PNG"/>
</p>

<br>

<br>

Ideally, We would like to see more differences like this:

<p align="center">
    <img src="images/presentation3.PNG"/>
</p>

<br>

<br>

Using Sales as variable of analysis "We can't really differentiate one (country) from another".

With Profit however, We can see that there are countries that bring deficit to the company (many transactions with negative profit).

<p align="center">
    <img src="images/presentation4.PNG"/>
</p>

<br>

<br>

When analyzing why this happens, I found out that most discounts in these countries are over 35%

<p align="center">
    <img src="images/presentation5.PNG"/>
</p>

<p align="center">
    <img src="images/presentation6.PNG"/>
</p>

<br>

<br>


### Segmentation

On Going...