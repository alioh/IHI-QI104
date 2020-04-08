---
title: L2- How to Learn from Run Charts and Control Charts
author: Ali Alohali
date: 2020-04-08
layout: post
---


## Common Cause vs. Special Cause Variation

to get better results and understand better from our charts, we need to separate from common and special causes of variance.

|Common Cause                   |Special Cause                |
|:--:|:--:|
|Inherent to the system or process|not inherent to the process|
|from regular causes            |from irregular causes        |
|affects on all the outcomes of a process|affects on some but not all|
|Results in a stable process that is predictable|Results in a un-stable process that is not predictable|
|random variation|non-random variation|

This is how common and special causes looks like in a chart:


![](/IHI-QI104/img/L2-1.jpg)  
###### excel file, with the data and chart, can be found [here](/IHI-QI104/xlsx/L2-1.xlsx).  

## Counting Runs on a Run Chart
A run is one or more consecutive points that all lie on the same side of the median. To count runs, we draw circle around each run and count the circles. This example should explain how to count runs:
In this example, we have 13 runs. Each green circle is one run. If point is ont he baseline, it does not count as part of the run.  

![](/IHI-QI104/img/L2-2.jpg)  
###### excel file, with the data and chart, can be found [here](/IHI-QI104/xlsx/L2-2.xlsx).  

## Four Rules for Interpreting Run Charts
Drawing circles around runs help us finding evidences of non-random changes, signals of improving or deterioration. After drawing the circles, we look for the following:

 - **Shift**: Six or more consecutive points above or below the median.
 - **Trend**: Five or more consecutive increasing or decreasing points.
 - **Clusters** (Too Few or Too Many Runs): We can say it is the number of runs, from that number we can tell if we have too many or too few runs.
 - **Astronomical Point**: Abnormal change in data.  

here are example of each one:
![](/IHI-QI104/img/L2-3.jpg)  
###### excel file, with the data and chart, can be found [here](/IHI-QI104/xlsx/L2-3.xlsx).
>  **Note:** For clusters, to know how many is few and how many is too many, we do the following:
 > - Count total data points and subtract points that fall on the median, the results is the **total number of data points**.
 > - Check the following table for the lower number of runs and the upper number of runs that the chart should have based on the **total number of data points**:

|data points|Lower number of runs|Upper number of runs|
|:--:|:--:|:--:|
|10|3|9|
|11|3|10|
|12|3|11|
|13|4|11|
|14|4|12|
|15|5|12|

##### This table are for 10 to 15 data points, [click here](/IHI-QI104/img/L2-3.jpg)  if you have more than 20 data points to see how many lower and upper runs you should have.

If any of the previous explained rules occur, then we can say that there is a non-random patterns in the data. That means what we are measuring is changing. Adding annotations and explaining what it is happening will help non experienced people understand what is happening in the chart.  

