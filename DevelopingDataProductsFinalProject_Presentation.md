Developing Data Products Final Project Presentation ShinyApp with Iris Dataset
========================================================
author: Sydney Yount
date: 5/25/22
autosize: true

App Description
========================================================

The purpose of this app is to explore the spread of different sepal and petal dimensions between species of Iris's

The user can use radio buttons to select 1 of 4 variables to designate what Iris dimension is desired to be visualized and explored. The variables are Petal Length, Petal Width, Sepal Length and Sepal Width.  

A histogram will be displayed to show the spread of the dimension per iris species for comparison. Different species of Iris's are plotted in different colors. 


Iris Dataset
========================================================
The data used for this ShinyApp is the iris data set available within R Studio. A summary of the data set can be seen below:

```r
summary(iris)
```

```
  Sepal.Length    Sepal.Width     Petal.Length    Petal.Width   
 Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100  
 1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300  
 Median :5.800   Median :3.000   Median :4.350   Median :1.300  
 Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199  
 3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800  
 Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500  
       Species  
 setosa    :50  
 versicolor:50  
 virginica :50  
                
                
                
```

ShinyApp Link: 
========================================================
Visit the web app here: [Iris Shiny Web App](https://sydneyyount.shinyapps.io/developingdataproductsfinalproject/)

Here is a sample output of the web app:

![plot of chunk unnamed-chunk-2](DevelopingDataProductsFinalProject_Presentation-figure/unnamed-chunk-2-1.png)
Conclusions: 
========================================================
Here, a Shiny Web App was developed to investigate the spread of various dimensions across 3 species of Iris. This app is based on the Iris data set available through R studio. This app takes a user input to determine the dimension of interest and will use that to plot the relevant data. 
