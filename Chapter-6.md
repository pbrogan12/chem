---
layout: default
title: Chapter 6
---

# Chapter 6 - Normal Probability Distributions

---

## 6-2 The Standard Normal Distribution
---

1. The graph of the standard normal distribution is bell-shaped.

2. The standard normal distribution has a mean equal to 0 (that is, µ = 0).

3. The standard normal distribution has a standard deviation equal to 1 (that is, σ = 1)
---

### Uniform Distributions
---

1. The area under the graph of a probability distribution is equal to 1.

2. There is a correspondence between area and probability (or relative frequency), so some probabilities can be found by Identifying the corresponding areas in the graph.

> A continuous random variable has a **uniform distribution if its values are spread evenly over the range of possibilities.  The graph of a uniform distribution results in a rectangular shape.

---

> The graph of continuous probability distribution, is called a **density curve**.

---

#### Requirements for a Density Curve.
---

1. The total area under the curve must equal 1.

2. Every point on the curve must have a vertical height that is 0 or greater.  (That is, the curve cannot fall below the x-axis.)

---

#### Standard Normal Distribution
---

> The **standard normal distribution** is a normal distribution with the parameters of µ = 0 and σ = 1.  The total area under its density curve is equal to 1.
---

#### Critical Values
---

> For the standard normal distribution, a **critical value** is a z score separating unlikely values from those that are likely to occur.

---

> **Notation**
>
> The expression Zα denotes the z score with an area of α to its right.  (α is the Greek letter alpha.)

---

## 6-3 Applications of Normal Distribution
---

```
**Formula 6-2**
     x - µ
z = ------- (round z scores to 2 decimal places)
      σ
```

---

### Procedure for Finding Areas with a Nonstandard Normal Distribution
---

1. Sketch a normal curve, label the mean and any specific x values, then shade the region representing the desired probability.

2. For each relevant value x that is a boundary for the shaded region, use Formula 6-2 to convert that value to the equivalent z score.

3. Use computer software or a calculator or Table A-2 to find the area of the shaded region.  This area is the desired probability.

### Finding Values from Known Areas
---

1. **Don't confuse z scores and areas.**  Remember, z scores are distances along the horizontal scale, but areas are regions under the normal curve.  Table A-2 lists z scores in the left columns and across the top row, but areas are found in the body of the table.

2. **Choose the correct (right/left) side of the graph.  A value separating the top 10% from the others will be located on the right side of the graph, but a value separating the bottom 10% will be located on the left side of the graph.

3. A z score must be negative whenever it is located in the left half of the normal distribution.

4. Areas (or probabilities) are positive or zero values, but they are never negative.

#### Procedure for Finding Values from Known Areas or Probabilities
---

1. Sketch a normal distribution curve, enter the given normal distribution curve, enter the given probability or percentage in the appropriate region of the graph, and identify the x values being sought.

2. If using technology, refer to the instructions at the end of this section.  If using Table A-2, refer to the body of Table A-2 to find the area to the left of x, then identify the z score corresponding to that area.

3. If you know z and must convert to the equivalent x value, use Formula 6-2 by entering the values for µ, σ and the z score found in Step 2, then solve for x.  Based on Formula 6-2, we can solve for x as follows:
x = µ + (z • σ)

4. Refer to the sketch of the curve to verify that the solution makes sense in the context of the graph and in the context of the problem.

---

### Important Information
---

* We should always draw a graph to visualize the information.
* We should determine whether we want to find area or a value of x.
* Regardless of the situation, we must usually work with a cumulative area from the left.
* We should know that a z score and x value are distances along horizontal scales, but percentages or probabilities correspond to areas under a curve.

---

## 6-4 Sampling Distributions and Estimators
---

> The **sampling distribution of a statistic** (such as a sample mean or sample proportion) is the distribution of all values of the statistic when all possible samples of the same size n are taken from the same population.  (The sampling distribution of a statistic is typically represented as a probability distribution in the format of a table, probability histogram, or formula.)

---

### Sampling Distribution of the Sample Mean
---

> The **sampling distribution of the sample mean** is the distribution of all possible sample means (or the distribution of  the variable x) with all samples having the same sample size n taken from the same population.  (The sampling distribution of the sample mean is typically represented as a probability distribution in the format of a table, probability histogram, or formula.)

---

### Behavior of Sample Means
---

1. The sample means target the value of the population mean. (That is, the mean of the sample means is the population mean.  The expected value of the sample mean is equal to the population mean.)

2. The distribution of sample means tends to be a normal distribution.  (This will be discussed further in the following section, but the distribution tends to become closer to a normal distribution as the sample size increases.)

### Sampling Distributions of the Sample Variance
---

> The **sampling distribution of the sample variance** is the distribution of sample variances, with all samples having the same sample size n taken from the same population.  (The sampling distribution of the sample variance is typically represented as a probability distribution in the format of a table, probability histogram, or formula.)

---

> **Caution** When working with population standard deviations or variances, be sure to evaluate them correctly.  In Section 3-3 we saw that the computations for population standard deviations or variances involve division by the population size N(not the value of n - 1), as shown here.

---

### Behavior of Sample Variances
---

1. The sample variances target the value of the population variance.  (That is, the mean of the sample variances is the population variance.  The expected value of the sample variance is equal to the population variance.)

2. The distribution of sample variances tends to be a distribution skewed to the right.

---

### Sampling Distributions of Sample Proportion
---

> The **sampling distribution of the same proportion** is the distribution of sample proportions, with all samples having the same sample size n taken from the same population.

---

> **Notation for Proportions**
>
> p = population proportion
> p with a carrot on top = sample proportion

---

### Behavior of Sample Proportions
---

1. Sample proportions target the value of the population proportion.  (That is, the mean of the sample proportion is the population proportion.  The expected value of the sample proportion is equal to the population proportion.)

2. The distribution of sample proportions tends to approximate a normal distribution

---

### Estimators: Unbiased and Biased
---

> An **estimator** is a statistic used to infer (estimate) the value of a population parameter.

---

> An **unbiased estimator** is a statistic that targets the value of the population parameter in the sense that the sampling distribution of the statistic has a mean that is equal to the mean of the corresponding parameter.

---

### Unbiased Estimators
---

These statistics are unbiased estimators.  That is, they each target the value of the corresponding population parameter:

* Mean - x underneath a bar
* Variance - s^2
* Proportion - p with carrot

---

### Biased Estimators
---

The statistics are biased estimators.  That is, they do not target the value of the corresponding population parameter:

* Median
* Range
* Standard Deviation s^*

---

### Why sample with replacement?
---

1. When selecting a relatively small sample from a large population, it makes no significant difference whether we sample with replacement or without replacement.

2. Sampling with replacement results in independent events that are unaffected by previous outcomes, and independent events are easier to analyze and result in simpler calculations and formulas.

---

> **Caution** Many methods of statistics require a simple random sample.  Some samples, such as voluntary response samples or convenience samples, could easily result in a very wrong results.

---

## 6-2 The Central Limit Theorem
---

> **Central Limit Theorem**
>
> For all samples of the same size n with n > 30 the sampling distribution x can be approximated by a normal distribution with mean µ and standard deviation σ / sqrt(n)

---

* As the sample size increases, the sampling distribution of sample means tends to approach a normal distribution.

* The mean of all sample means is equal to the mean of the original population.

* As the sample size increases, the spans of the dotplots become narrower, showing that the standard deviations of sample means become smaller as the sample size increases.

---

> **Notation for the Sampling Distribution of x&#772; **
>
> If all possible simple random samples of size n are selected from a population with mean µ and standard deviation σ, the mean of the sample means is denoted by µ x&#772; and the standard deviation of all sample means is denoted by σ x&#772; . (σ x&#772; is called the standard error of mean.)
>
> Mean of all values x&#772;: µx&#772; = µ
>
> Standard deviation of all values of  x&#772;: σ&#772 = σ/√n

---

## 6-6 Assessing Normality
---

> A **normal quantile plot** (or **normal probability plot**) is a graph of points (x,y) where each x value is from the original set of sample data, and each y value is the corresponding z score that is a quantile value expected from the standard normal distribution.

---

**Procedure for Determining Whether It Is Reasonable to Assume That Sample Data Are From a Population Having a Normal Distribution**

---

1. Histogram: Construct a histogram.  If the histogram departs dramatically from a bell shape, conclude that the data do not have a normal distribution

2. Outliers: Identify outliers.  If there is more than one outlier present, conclude that the data do not have a normal distribution.  (Just one outlier could be an error or the result of chance variation, but be careful, because even a single outlier can have dramatic effect on results.)

3. Normal quantile plot: If the histogram is basically symmetric and the number of outliers is 0 or 1, use technology to generate a normal quantile plot.  Apply the following criteria to determine whether or not the distribution is normal.  (These criteria can be used loosely for small samples, but they should be used more strictly for large samples.)

---

**Normal Distribution:** The population distribution is normal if the pattern of the points is reasonably close to a straight line and the points do not show some systematic pattern that is not a straight-line pattern.

**Not a Normal Distribution:** The population distribution is not normal if either or both of the two conditions applies:

* The points do not lie reasonably close to a straight line.

* The points show some systematic pattern that is not a straight-line pattern.

---

## Normal as Approximation to Binomial
---

> **Notation**
>
> n = the fixed number of trials
> x = the specific number of successes in n trials
> p = probability of success in one of the n trials
> q = probability of failure in one of the n trials (so q = 1 - p)

---

### Continuity Correction
---

> When we use the normal distribution (which is a continuous probability distribution) as an approximation to the binomial distribution (which is discrete), a **continuity correction** is made to a discrete whole number x in the binomial distribution by representing the discrete whole number x by the interval from x - 0.5 to x + 0.5 (that is, adding and subtracting 0.5)

---

**Using Probabilities to Determine When Results Are Unusual**
---

* **Unusually high number of successes:** x successes among n trials is an unusually high number of success if the probability of x or more successes is unlikely with a probability of 0.05 or less.  This criterion can be
