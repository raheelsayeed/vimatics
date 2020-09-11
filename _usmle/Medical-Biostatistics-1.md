---
layout: post
tags: [biostatistics, formulae]
---



### Central Tendency

- Center of Normal distribution
- Mean: avg
- Mode: most frequent
- Median 
    - Odd = Middle number is Median
    - Even = Avg of Middle two numbers
- Chart: Mode is the heights point in the chart
- Chart: Positive Skew / Negative Skew (Mode [top] > Median > Mean)
- Chart: Mode least likely to be affected by outliers, only affected if common number is changed
- ![](https://i.pinimg.com/originals/63/3d/f8/633df8ee468b9860bfb9d8fc01d5fc5d.jpg)
- 

### Dispersion Measures

1. Standard Deviation
2. Variance
3. Standard Error of the Mean
4. Z-score
5. Confidence interval

### Sd

How dispersed is the data set? Two datasets can have the same mean, median, mode but can be different in how much they are spread out (far away from the mean).

1. first get difference between each data point and mean
3. Squared of the sum (remove neg signs)
2. Sum of those difference

- +-1Sd == 68% of population
- +-2Sd == 95% of population
- +-3Sd == 98.7% of populationb

### Variance

It is Sd squared. 

### Standard Error of the mean

How precisely you know the true population mean. How close we are to the true mean. The higher sample number, the less SEM (closer to true mean)

- `StdErr = Sd/ n`

### Z-score

Equal to the number of Sdeviations you are away fromt he mean

1. 0 == mean
2. +1 == 1sd > mean
3. -1 == 1sd < mean


### Confidence intervals

CIs are for estimating population mean from a sample dataset (which is a subset of the population and not the entire population)

- Formula: `CI = Mean +/- (1.96 x StdErrMean)`

