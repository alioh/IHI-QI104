---
title: L1- How to Display Data on a Run Chart
author: Ali Alohali
date: 2020-04-07
layout: post
---


## Why You Need a Run Chart?

Run chart is an effective way to show change over specific period of time.

#### Example:

If a hospital gets complains about wait times in ER. As an improvement team, we will need to come up with specific aim and plan for measuring to check the results as we do changes to fix the issues we have. 
The **key measure** ( the data upon which you will gauge your progress ) is the percentage of patients that leaves ER without been seen every month. It can be calculated as follows:

![](/IHI-QI104/img/L1-eq1.jpg)

where:
 - N = Number of patients who leave ER without begin seen.
 - D = Total number of patients.

The **aim** ( the overall goal of your improvement project ) is to get the percentage of leave without been seen by ER to bellow 1%.

## The Basic Elements of a Run Chart
In our previous example, lets say we have data of one year, the basic elements of our run chart will be:

 1. **Time** along the X axis.
 2. Our key measure **Number of patient left without been seen** along the Y axis.
 3. **Labels** on the X and Y axis.
 4. **Title** for the chart.
 5. The **median** of our key measure.
 6. Any other information such is:
	 - UCL (Upper control limit) is calculated by adding the average (median) to 3 times the standard deviation.
	 - LCL (Lower control limit) is calculated by subtracting the average (median) to 3 times the standard deviation.
	 - Labels to specific event that effected the result on a specific week.

> **Note:** 
  In excel, the **average** can be found using the function: =AVERAGE(column), the **median** can be found using the function: =median(column), and the **standard deviation** can be found with the function =STDEV(column). To get **UCL** the function will be:  
> =AVERAGE(column) + (STDEV(column) * 3 ) , and to get **LCL** the function will be =AVERAGE(column) - (STDEV(column) * 3 )

an example of the result chart is:  

![](/IHI-QI104/img/L1-1.jpg)  

excel file, with the data and chart, can be found [here](/IHI-QI104/xlsx/L1-1.xlsx).


## Baselines, Goal Lines, and Other Annotations
**Annotations** are comments we add to the chart. Add comments to show changes effected the run chart.
**Base Line**  is a line that shows the performance before the start of our test of improvements. Baseline is the median of your measurements from the time prior to any specific tests of change or improvement. We need at least five data points to create baseline median.  
**Goal Line** is a line to show our goal.

This is how the previous chart looks like with annotations, baseline and goal line.  

![](/IHI-QI104/img/L1-2.jpg)  

excel file, with the data and chart, can be found [here](/IHI-QI104/xlsx/L1-2.xlsx).

## Computer Programs for Run Charts
[Click here](http://www.youtube.com/watch?v=lUp_TwMdj8k) to see a quick video on how to create run chart in excel.  