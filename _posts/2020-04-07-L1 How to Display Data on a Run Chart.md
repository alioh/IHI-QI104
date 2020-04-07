---
title: How to Display Data on a Run Chart
author: Ali Alohali
date: 2020-04-07
layout: post
---


# L1: How to Display Data on a Run Chart

## Why You Need a Run Chart?

Run chart is an effective way to show change over specific period of time.

#### Example:

If a hospital gets complains about wait times in ER. As an imporevment team, we will need to come up with specific aim and plan for measuring to check the results as we do changes to fix the issues we have. 
The **key measure** ( the data upon which you will gauge your progress ) is the percentage of patients that leaves ER without been seen every month. It can be calculated as follows:

$$
 \frac {N}{D} * 100
$$
where:
 - N = Number of patients who leave ER without beign seen.
 - D = Total number of patients.
The **aim** ( the overall goal of your improvement project ) is to get the percentage of leave without been seen by ER to bellow 1%.

## The Basic Elements of a Run Chart
In our previous example, lets say we have data of one year, the basic elements of our run chart will be:

 1. **Time** along the X axis.
 2. Our key measure **Number of patient left without been seen** along the Y axis.
 3. **Labels** on the X and Y axis.
 4. **Title** for the graph.
 5. The **median** of our key measure.
 6. Any other information such is:
	 - UCL (Upper control limit) is calculated by adding the average to 3 times the standard deviation.
	 - LCL (Lower control limit) is calculated by subtracting the average to 3 times the standard deviation.
	 - Labels to specific event that effected the result on a specific week.
> **Note:** In excel, the **average** can be found using the function: =AVERAGE(coulmn), and the standard deviation can be found with the function =STDEV(coulmn). To get UCL the function will be:
> =AVERAGE(column)+(STDEV(column) * 3 ) , and to get LCL the function will be =AVERAGE(column)-(STDEV(column) * 3 )

an example of the result graph is:
![](/img/L1-1.jpg)
excel file, with the data and graph, can be found [here](/xlsx/L1-1.xlsx).