developing data products
========================================================
author: pavan vasanth
date: 26/10/2019
autosize: true

Introduction
========================================================

This presentation is done as part of the final course project for 'Developing Data Products' course in the Data Science Specialization track by John Hopkins University on Coursera.

The web application is hosted on the link below:
https://pavanvasanth.shinyapps.io/ChooseYourCar/


Application Overview
========================================================

This web application allows you to choose a car that suits your needs.

Enter the distance and price of gas and the application will show the cars having mpg in your suitable range.

Additionally, you can also choose some characteristics of the cars that you desire: Cylinders, Displacement, Horse Power and Transmission. 

Dataset Overview
========================================================

The application uses 'mtcars' dataset from the 'datasets' package in R which lists down 10 aspects of automobile design and performance for 32 cars.


```r
library(datasets)
data(mtcars)
head(mtcars, 4)
```

```
                mpg cyl disp  hp drat    wt  qsec vs am gear carb
Mazda RX4      21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag  21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
Datsun 710     22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
Hornet 4 Drive 21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
```






Variable Correlation
========================================================







```
Error in parse(text = x, srcfile = src) : 
  attempt to use zero-length variable name
```
