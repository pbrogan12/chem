---
layout: page
title: Chapter 3
---

# Chapter 3 - Statistics for Describing, Exploring and Comparing Data

## 3-2 Measures of Center
---

1. Basic Concepts of Measures of Center
---

> A **measure of center** - is a value at the center or middle of a data set.

---

There are several different ways to determine the center, so we have different measures of center, including the mean, median, mode, and midrange.

### Mean
---

> The **mean**, of a set of data is the measure of center found by adding the data values and dividing the total by the number of data values.

---

### Median
---

> The **median** of a data set is the measure of center that is the middle value when the orginal data values are arranged in order of increasing (or decreasing) magnitude.

---

### Calculation and Notation of the Median
---

1. If the number of data values is odd, the median is the number located in the exact middle of the sorted list.
2. If the number of data values is even, the median is found by computing the mean of the two middle numbers in the sorted list.

### Important Properties of the Median
---

* The median does not change by large amounts when we include just a few extreme values (so the median is a resistant measure of center).
* The median does not use every data value.

### Mode
---

> The **mode** of a data set is the value that occurs with the greatest frequency.

---

### Finding the Mode
---

* When two data values occur with the same greatest frequency, each one is a mode and the data set is **bimodal**.
* When more than two data values occur with the same greatest frequency, each is a mode and the data set is said to be **multimodal**.
* When no data value is repeated, we say that there is **no mode**.

### Midrange
---

> The **midrange** of a data set is the measure of center that is the value midway between the maximum and minimum values in the original data set.  It is found by adding the maximum data value to the minimum data value and then dividing the sum by 2, as in the following formula

---

```
            maximum data value + minimum data value
midrange = -----------------------------------------
                            2
```

---

### Important Properties of the Midrange
---

* Because the midrange uses only the maximum and minimum values, it is very sensitive to those extremes.
* In practice, the midrange is rarely used, but it has three redeeming features:

  1. The midrange is very easy to compute.
  2. The midrange helps reinforce the very important point that there are several different ways to define the center of a data set.
  3. The value of the midrange is sometimes used incorrectly for the median, so confusion can be reduced by clearly defining the midrange along with the median.

> Round-Off Rules:
>
> For the mean, median, and midrange, carry one more decimal place than is present in the orginal set of values/
>
> For the mode, leave the value as is without rounding.

---

### Calculating the Mean From a Frequency Distribution
---

### IQ Scores of Low Lead Group
---

| IQ Score | Frequency ***f*** | Class Midpoint ***x*** | ***f*** * ***x*** |
| -------- | ----------------- | ---------------------- | ----------------- |
| 50-59    | 2                 | 59.5                   | 119.0             |
| 70-89    | 33                | 79.5                   | 2623.5            |
| 90-109   | 35                | 99.5                   | 3482.5            |
| 110-129  | 7                 | 119.5                  | 836.5             |
| 130-149  | 1                 | 139.5                  | 139.5             |
| **Totals:** | **sum(F)**     |                        | **sum( f * x) = 7201.0 |


---

> Mean from frequency Distribution = First multiply each frequency and class midpoint; then add the products.  Then divide by the sum of frequencies.

---

### Example
> mean = 7201.0 / 78 = 92.3
> 92.3 is an approximation of the mean.

---

## 3-3 Measures of Variation
---

The topic of variation is the single most important topic in statistcs.
This section includes these measures of variations range, standard deviation, and variance.

### Range
---

> The **range** of a set of data values is the difference between the maximum data value and the minimum data value.

> **Range = (maximum data value) - (minimum data value)**

---

Because the range uses only the maximum and the minimum data values, it is very senstive to extreme values and isn't as useful as other measures of variation that uses very data value, such as standard deviation.

> Round-Off Rule for Measures of Variation
>
> When rounding the value of a measure of variation, carry one more decimal place than is present in the original set of data.

---

### Standard Deviation of a Sample
---

> The **standard deviation** of a set of sample values, denoted by s, is a measure of how much data values deviate away from the mean.  It is calculated by using the Formula 3-4 or 3-5.  Formula 3-5 is just a different version of Formula 3-4, so both formulas are algebraically the same.

---

<img width="100%" src="{{ site.baseurl }}/images/chapter3/SD_Formula.gif">

---

### Important Properties of Standard Deviation
---

* The standard deviation is a measure of how much data values deviate away from the mean.
* The value of the standard deviation ***s*** is usually positive.  It is zero only when all of the data values are the same number.  (It is never negative.)  Also, larger values of ***s*** indicate greater amount of variation.
* The value of the standard deviation ***s*** can increase dramatically with the inclusion of one or more outliers (data values that are very far away from all of the others).
* The units of the standard deviation ***s*** (such as minutes, feet, pounds, and so on) are the same as the units of the original data values.
* The sample standard deviation ***s*** is a **biased estimator** of the population standard deviation ***o***, as described in Part 2 of this section.

### Range Rule of Thumb for Understanding Standard Deviation
---

> The **range rule of thumb** is a crude but simple tool for understanding and interpreting standard deviation.  It is based on the principle that for many data sets, the vast majority (such as 95%) of sample values lie within 2 standard deviations of the mean.

---

### Range Rule of Thumb
---

**Interpreting a Known Value of the Standard Deviation** - If the standard deviation of a collection of data is a known value, use it to find rough estimates of the minimum and maximum ***usual*** sample values.

minimum "usual" value = (mean) - 2 x (standard deviation)

maximum "usual" value = (mean) + 2 x (standard deviation)

### Estimating a Value of the Standard Deviation ***s***
---

To roughly estimate the standard deviation from a collection of known sample data, use

```
     range
 s = -----
       4
```

---

### Standard Deviation of a Population
---

A slightly different formula is used to calculate the standard deviation of a population.

### Variance of a Sample and a Population
---

> The **variance** of a set of values is a measure of variation equal to the square of the standard deviation.
>
> **Sample variance:** s^2 = square of the standard deviation ***s***.
>
> **Population variance:** o^2 = square of the population standard deviation ***o***.

---

### Summary of Notaion for Standard Deviation and Variance
---

> ***s*** = sample standard deviation
> ***s^2*** = sample variance
> ***o*** = population standard deviation
> ***o^2*** = population variance

---

### Important Properties of Variance
---

* The units of variance are the ***squares*** of the units of the original data values. (If the original data values are in feet, the variance will have units of ft^2; if the orginal data values are in seconds, the variance will have sec^2.)
* The value of the varaince can increase dramatically with the inclusion of one or more outliers.
* The value of the variance is usually positive. It is zero only when all of the data values are the same number. (It is never negative.)
* The sample variance ***s^2*** is an **unbiased estimator** of the population variance ***o^2***, as describesd in part 2 of this section.

---

### Empirical (or 68-95-99.7) Rule for Data with a Bell-Shaped Distribution
---

A concept helpful in interpreting the value of a standard deviation is the **empirical rule.**  This rule states that for data sets having a distribution that is approximately bell-shaped, the following properties apply.

* About 68% of all values fall within 1 standard deviation of the mean.
* About 95% of all values fall within 2 standard deviation of the mean.
* About 99.7% of all values fall within 3 standard deviation of the mean.

### Chebyshev's Theorem
---

> **Chebyshev's Theorem**
>
> The proportion (or fraction) of any set data lying within ***K*** standard deviations of the mean is always at least 1 - 1 / K^2, where K is any positive number greater than 1.
> For K = 2 and K = 3, we the following statements:
> * At least 3/4 (or 75%) of all values lie within 2 standard deviations of the mean.
> * At least 8/9 (or 89%) of all values lie within 3 standard deviations of the mean.

---

The empirical rule applies only to data sets with bell-shaped distributions, but Chebyshev's Theorem applies to any data set.  Unfortunately, results from Chebyshev's Theorem are only approximate.

### Comparing Variation in Different Populations
---

> The **coefficient of variation** (or **CV**) for a set of nonnegative sample or population data, expressed as a percent, describes the standard deviation relative to the mean, and is given by the following:

```
     Sample           Population
        s                   o
   CV = - * 100%     CV =   - * 100%
        x                   u
```

---

> **Round-Off Rule for the Coefficient of Variation**
>
> **Round the coefficient of variation to one decimal place (such as 18.3%).**

---

## 3-4 Measures of Relative Standing and Boxplots
---

### Z Scores

> A **z score** (or **standardized value**) is the number of standard deviations that a given value x is above or below the mean.  The z score is calculated by using one of the following:

```
        Sample              Population
      X - mean(X)             X - u
z = -------------- or z = -------------
          s                     o
```

---

> **Round-Off Rule for z Scores**
>
> **Round z scores for two decimal places (such as 2.31).**

---

Z scores that are less than -2 or greater than 2 is it an unusual value.

### Properties of z Scores
---

1. A z score is the number of standard deviations that a given value x is above or below the mean.
2. z scores are expressed as numbers with no units of measurement.
3. A data value is unusual if its z score is less than -2 or greater than +2
4. If an individual data value is less than the mean, its z score is a negative number.

### Percentiles
---

> **Percentiles** are measures of locations, denoted P1,P2,...,P99, which divide a set of data into 100 groups with about 1% of the values in each group
