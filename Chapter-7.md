---
layout: default
title: Chapter 7
---

# Chapter 7 - Estimate and Sample Sizes

---

## 7-2 Estimating a Population Proportion
---

* **Point Estimate:** The sample proportion (denoted by p̂) is the best point estimate (or signle value estimate) of the population proportion p.

* **Confidence Interval:** We can use a sample proportion to construct a confidence interval estimate of the true value of a population proportion, and we should know how to construct and interpret such confidence intervals.

* **Sample size:** We should know how to find the sample size necessary to estimate a population proportion.

---

> A **point estimate** is a single value (or point) used to approximate a population parameter.

---

**The sample proportion p̂ is the best point estimate of the population proportion p.**

---

### Why do we need confidence intervals?
---

> A **confidence interval** (or **interval estimate**) is a range (or an interval) of values used to estimate the true value of a population paramter.  A confidence interval is sometime abbreviated as CI.

---

> The **confidence level** is the probability 1 - a (such as 0.95, or 95%) that the confidence interval actually does contain the population parameter, assuming that the esimation process is repeated a large number of times.  (The confidence level is also called the **degree of confidence**, or the **confidence coefficient.**)

---

A confidence interval is associated with a specific confidence level, such as 0.95 (or 95%).  The confidence level gives us the success rate of the procedure used to construct the confidence interval.  See the following and notice the relationship between the confidence level and the corresponding value of a.

---

| Most Common Confidence Levels | Corresponding Values of a |
| ----------------------------  | ------------------------- |
| 90% (or 0.90) confidence level: | a = .10 |
| 95% (or 0.95) confidence level: | a = .05 |
| 99% (or 0.99) confidence level: | a = .01 |

---

### Interpeting a Confidence Interval
---

We must be careful to interpet confidence intervals correctly.  There is a correct interpretation and many different and creative incorrect interpretations of the confidence interval 0.828 < p < 0.872.

** Correct:** "We are 95% confident that the interval from 0.828 to 0.872 actually does contain the true value of the population proportion p."  This means that if we were to select many different samples of size 1007 and construct the corresponding confidence intervals, 95% of them would actually contain the value of the population proportion p.  (In this correct interpretation, the confidence level of 95% refers to the success rate of the process used to estimate the population proportion.)

** Incorrect:** "There is a 95% chance that the true value of p will fall between 0.828 and 0.872"

** Incorrect:** "95% of sample proportions will fall between 0.828 and 0.872"

---

> **Caution** - Know the correct interpretation of a confidence interval, as given above.

---

> **Caution** - Confidence intervals can be used informally to compare different data sets, but the overlapping of confidence intervals should not be used for making formal and final conclusions about equality if proportions.

---

> **Caution** - Know that in this chapter, when we use a confidence interval to address a claim about a population proportion p, we simply make an informal judgement (that may or may not be consistent with formal methods of hypothesis testing introduced in Chapter 8.)

---

### Critical Values
---

1. Under certain conditions, the sampling distribution of sample proportions can be approximated by a normal, as shown in Figure 7-2.

2. A z score associated with a sample proportion has a probability of a/2 of falling in the right tail of Figure 7-2.

3. The z score separating the right-tail region is commonly denoted by za/2 and is referred to as a critical value because it is on the borderline separating z scores from sample proportions that are likely to occur from those that are unlikely.

---

> A **critical value** is the number on the borderline separating sample statistics that are likely to occur from those that are unlikely.  The number Za/2 is a critical value that is a z score with the property that is separates an area of a/2 in the right tail of the standard normal distribution (as in Figure 7-2).

---

### Margin of Error
---

> When data from a simple random sample are used to estimate a population proportion p, the **margin of error**, denote by **E**, is the maximum likely difference (with probability 1 - a, such as 0.95) between the observed sample proportion p̂

---

### Procedure for Constructing a Confidence Interval for p
---

#### Requirements
---

1. The sample is a simple random sample.  (Caution: If the sample data have been obtained in a way that is not suitable, the estimate of the population proportion may be very wrong.)

2. The conditions for the binomial distribution are satisfied.  That is, there is a fixed number of trials, the trials are independent, there are two categories of outcome, and the probabilities remain constant for each trial.

3. There are at least 5 failures.  (With the population proportions p and q unknown, we estimate their values using the sample proportion, so this requirement is a way of verifying that np ≥ 5 and nq ≥ 5 are both satisfied, so the normal distribution is a suitable approximation to the binomial distribution.  There are procedures for dealing with situation in which the normal distribution is not a suitable approximation, as in Exercise 40.)

---

1. Verify that the requirements in the preceding box are satisfied.

2. Using technology or Table A-2 to find the critical value Za/2 that corresponds the desired confidence level.

3. Evaluate the margin of error E = Za/2 sqrt(pq/n)

4. Using the value of the calculated margin error E and the value of the sample proportion p̂, find the values of the confidence interval limits p̂ - E and p̂ + E.  Substiute those values in the general format for the confidence interval p̂ - E < p < p̂ + E or p̂ + or - E or (p̂ - E, p̂ + E)

5. Round the resulting confidence interval limits to three significant digits.

---

> **Caution** Never have the common misconception that poll results are unreliable if the sample size is a small percentage of the population size.  The population size is usually not a factor in determining the reliability of a poll.

---

### Finding the Sample Size Required to Estimate a Population Proportion
---

**Objective**
---

Determining how large the sample n should be in order to estimate the population proportion p.

**Noation**
---

p = population proportion

p̂ = sample proportion

n = number of sample values

E = desired margin of error

Za = z score seperating an area of a/2 in the right tail of the standard normal distribution

---

**Requirements**
---

The sample must be a simple random sample of independent sample units.

When an estimate p̂ is known: Formula 7-2 n = [Za/2]^2•pq/E^2

When no estimate p̂ is known: Formula 7-3 n = [Za/2]^2•0.25/E^25

---

> **Round-Off Rule for Determining Sample Size**
>
> If the computed sample size n is not a whole number, round the value of n up to the next larger whole number.

--


## 7-3 Estimating a Population Mean
---

* **Point Estimate:** The sample mean x̄ is the best point estimate (or single value estimate) of the population mean µ.

* **Confidence Interval:** We can use a sample mean to construct a confidence interval estimate of the true value of a population mean, and we should know how to construct and interpret such confidence intervals.

* **Sample Size:** We should know how to find the sample size neccessary to estimate a population mean.

---

### Point Estimate
---

The sample mean x̄ is an unbiased estimator of the population mean µ, and for many populations, sample means tend to vary less that other measures of center, so the sample mean x̄ is usually the best point estimate of the population mean µ.

---

> **The sample mean x̄ is the best point estimator of the populaton mean µ.

---

### Confidence Interval for Estimating a Population Mean with σ Not Known
---

**Objective**
---

Construct a confidence interval used to estimate a population mean.

---

**Notation**
---

µ = population mean

x̅ = sample mean

n = number of sample values

E = margin of error

---

**Requirements**
---

1. The sample is a simple random sample.

2. Either or both of these conditions is satisfied: The population is normally distributed or n > 30.

---

**Confidence Interval**
---

x̅ - E < µ < x̅ + E where the margin of error E is found from the following:

E = ta•s/√n

---

**Round-Off Rule**
---

1. When constructing a confidence interval from the original set of data values, round the confidence interval limits to one more decimal place than is used for the orginal set of data.

2. When constructing a confidence interval from summary statistics (n and x̅ and s), round the confidence interval limits to the same number of decimal places used for the sample mean.

---

### Finding the Sample Size Required to Estimate a Population Mean
---

**Objective**
---

Determine the sample size n required to estimate the value of a population mean µ.

---

Notation
---

µ = population mean

σ = population standard deviation

x̅ = sample mean

E = desired margin of error

Za/2 = z score separating an area of a/2 in the right tail of the standard normal distribution

---

**Requirement**
---

The sample must be simple random sample.

---

**Sample Size**
---

The required sample size is found by using Formula 7-4.

Formula 7-4 n = [Za/2σ/E]^2

---

**Round-Off Rule**
---

If the computed sample size n is not a whole number, round the value of n up to the next larger whole number.

---

### Confidence Interval for Estimating a Population Mean with σ Known
---

**Requirements**
---

1. The sample is a simple random example

2. Either or both of these conditions is satisfied:  The population is normally distributed or n > 30

---

**Confidence Interval**
---

x - E < µ < x + E

---

## 7-4 Estimating a Population Standard Deviation or Variance
---

* **Point Estimate:** The sample variance s^2 is the best point estimate (or single value estimate) of the population variance σ^2
* **Confidence Interval:**  When constructing a confidence interval estimate of a population standard deviation (or population variance), we construct the confidence interval using the X^2 (chi-square) distrbution.
* **Chi-Square Distribution:**  We should know how to find critical values of X^2

---

### Estimating a Population Standard Deviation or Variance 
---

In a normally distributed population with variance let σ^2, if we randomly select independent samples of size n and, for each sample, compute the sample variance s^2 (which is the square of the sample standard deviation s), the sample statistic X^2 = (n-1)s^2/σ^2 has a sampling distribution called the chi-square distribution.

---

* **Finding Critical Values of X^2** We denote a right-tailed critical value by X^2R and we denote a left-tailed critical value X^2L.  Those critcal values can found by using technology or Table A-4, and they require that we first determine a value for the number of degrees of freedom.
* **Degrees of Freedom** In general, the number of **degrees of freedom** (or **df**) for a collection of sample data is the number of sample values than can vary after certain restrictions have been imposed on all data values.  For the methods of this section, the number of degrees of freedom is the sample size minus 1.

**Degrees of Freedom: df = n -1**

---

> **Caution** In later chapters we will encounter situations in which the degrees of freedom are not n-1, so it is wrong to make the incorrect generalization that the number of degrees of freedom is always n - 1.

---

### Properties of the Chi-Square Distribution
---

1. The chi-square distribution is not symmetric, unlike the normal and Student t distributions.  (As the number of degrees of freedom increases, the distribution becomes more symmetric, as Figure 7-8 illustrates.)

2. The values of chi-square can be zero or positive, but they cannot be negative (as shown in Figure 7-7).

3. The chi-square distribution is different for each number of degrees of freedom (as illustrated in Figure 7-8).  As the number of degrees of freedom increases, the chi-square distribution approaches a normal distribution.

---

### Confidence Interval for Estimating a Population Standard Deviation or Variance
---

**Objective**
---

Construct a confidence interval used to estimate a population standard deviation or variance.

**Notation**
---

σ = population standard deviation

s = sample standard deviation

n = number of sample values

X2L = left-tailed critical value of X2

σ^2 = population variance

s^2 = sample variance

E = margin of error

X2R = right-tailed critical value of X2

---

**Requirements**
---

1. The sample is a simple random sample. 

2. The population must have normally distributed values (even if the sample is large).  The requirement of a normal distribution is much stricter here than in earlier sections, so departures from normal distributions can result in large errors. 

---

Pg 364

---

Pg 364

---

**Round-Off Rule**
---

1. When using the original set of data values to construct a confidence interval, round the confidence interval limits to one more decimal place than is used for the original set of data.

2. When using the summary statistic (n,s) for constructing a confidence interval, round the confidence interval limits to the same number of decimal places used for the sample standard deviation.

---

> **Caution** COnfidence intervals can be used informally to compare the variation in different data sets, but the overlapping of confidence intervals should not be used for making formal and final conclusions about equality of variances or standard deviations. 

---

### Using Confidence Intervals for Hypothesis Tests
---

> **Caution** Kown that in this chapter, when we use a confidence interval to address a claim about σ or σ^2, we are making an informal judgment (that may or may not be consistent with formal methods of hypothesis testing introduced in Chapter 8).

---

### Table 7-2
---

|  σ  |  | 
| --- | --- |
| **To be 95% confident that s is within** | **of the value of σ, the sample size n should be at least** |
| 1% | 19,205 |
| 5% | 768 |
| 10% | 192 |
| 20% | 48 |
| 30% | 21 |
| 40% | 12 |
| 50% | 8 |
| **To be 99% confident that is is within** | **of the value of σ, the sample size n should be at least** |
| 1% | 33.218 |
| 5% | 1,336 |
| 10% | 336 |
| 20% | 85 |
| 30% | 38 |
| 40% | 22 |
| 50% | 14 |

---

| σ^2 | | 
| --- | --- |
| **To be 95% confident that s^2 is within** | **of the value σ^2 the sample size n should be at least**|
| 1% | 77,208 |
| 5% | 3149 |
| 10% | 806 |
| 20% | 211 |
| 30% | 98 |
| 40% | 57 |
| 50% | 38 |
| **To be 99% confident that s^2 is within** | **of the value σ^2 the sample size n should be at least**|
| 1% | 133,449 |
| 5% | 5,484 |
| 10% | 1,402 |
| 20% | 369 |
| 30% | 172 |
| 40% | 101 |
| 50% | 68 |

---
