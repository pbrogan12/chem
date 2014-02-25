---
layout: default
title: Chapter 5
---

# Chapter 5 - Discrete Probability Distributions

---

## 5-2 Probability Distributions
---

> A **random variable** is a variable (typically represented by x) that has a single numerical value, determined by chance, for each outcome of a procedure.

---

> A **probability distribution** is a description that gives the probability for each value of the random variable.  It is often expressed in the format of a table, formula, or graph.

---

### Probability Distribution: Requirements
---

1. There is a numerical random variable x and its values are associated with corresponding probabilities.

2. ∑P(x) = 1 where x assumes all possible values. (The sum of all probabilities must be 1, but sums such as 0.999 or 1.001 are acceptable because they result from rounding errors.)

3. 0 ≤ P(x) ≤ 1 for every individual value of the random variable x. (That is, each probability value must be between 0 and 1 inclusive.)

---

### Parameters of a Probability Distribution: Mean, Variance, and Standard Deviation
---

> **Formula 5-1** µ = ∑[x•P(x)]
>
> Mean for a probability distribution

---

> **Formula 5-2** σ^2 = ∑[(x - µ)^2 • P(x)]
>
> Variance for a probability distribution (This format is easier to understand.)

---

> **Formula 5-3** σ^2 = ∑[(x^2 • P(x)] - µ^2
>
> Variance for a probability distribution (This format is easier for manual computations.)

---

> **Formula 5-4** σ = √∑[x^2 • P(x)] - µ^2
>
> Standard deviation for a probability distribution

---

When applying Formulas 5-1 through 5-4, use the following rule for rounding results.

> **Round-off Rule for µ, σ, and σ^2 from a Probability Distribution
>
> Round results by carrying one more decimal place than the number of decimal places used for the random variable x.  If the values of x are integers, round µ, σ, and σ^2 to one decimal place.

---

### Expected Value
---

> The **expected value** of a discrete random variable x is denoted by ***E***, and it is the mean value of the outcomes, so ***E*** = µ and ***E*** can also be found by evaluating ∑[x•P(x)], as in Formula 5-1.

---

### Making Sense of Results: Identifying Unusual Values
---

### Identifying Unusual Resutls with Range Rule of Thumb
---

> **Range Rule of Thumb**
>
> maximum usual value = µ + 2σ
> minimum usual value = µ - 2σ

### Identifying Unusual Results with Probabilities: The Rare Event Rule for Inferential Statistics
---

**Using Probabilities to Determine When Results are Unusual**

* **Unusually high number of successes:** x successes among ***n*** trials is an unusally high number of successes if the probability of x or more successes is unlikely with a probability of 0.05 or less.  This criterion can be expressed as follows: P(x or more) ≤ 0.05.*

* **Unusually low number of successes:** x successes among ***n*** trials is an unusally low number of successes if the probability of x or fewer successes is unlikely with a probability of 0.05 or less.  This criterion can be expressed as follows: P(x or fewer) ≤ 0.05.*

* The value 0.05 is not absolutely rigid.  Other values, such as 0.01, could be used to distinquish between results that can easily occur by chance and events that are very unlikely to occur by chance.

---

## 5-3 Binomial Probability Distributions
---

A **binomial probability distribution** results from a procedure that meets all the following requirements:

1. The procedure has a fixed number of trials. (A trial is a single observation.)

2. The trials must be independent. (The outcome of any individual trial doesn't affect the probabilities in the other trials.)

3. Each trial must have all outcomes classified into two categories (commonly referred to as success and failure).

4. The probability of a success remains the same in all trials.

---

> **Notation for Binomial Probability Distributions**
>
> S and F (success and failure) denote the two possible categories of all outcomes.
>
> P(S) = p (p = probability of success)
>
> P(F) = 1 - p = q (q = probability of failure)
>
> n denotes the fixed number of trials.
>
> x denotes a specific number of success in n trials, so x can be any whole number between 0 and n, inclusive.
>
> p denotes the probability of success in one of the n trials.
>
> q denotes the probability of failure in one of the n trials.
>
> P(x) denotes the probability of getting exactly x success among the n trials.

---

<img width="100%" src="http://www.mathnstuff.com/math/spoken/here/2class/90/binom1.gif">

---

## 5-4 Parameters for Binomial Distribution
---

> **For Binomial Distributions**
>
> **Formula 5-6** Mean:     µ = np
>
> **Formula 5-7** Variance: σ^2 = npq
>
> **Formula 5-8** Standard Deviation: σ = √npq
>

---

> **Range Rule of Thumb**
>
> maximum usual value: µ + 2σ
>
> minimum usual value: µ - 2σ

---

## 5-5 Poisson Probability Distributions
---

> A **Poisson distribution** is a discrete probability distribution that applies to occurrences of some event over a specified interval.  The interval can be time, distance, area, volume, or some similar unit.  The probability of the event occurring x times over an interval is given below.

---

> **Requirements for the Poisson Distribution**
>
> **1.** The random variable x is the number of occurrences of an event over some interval.
> **2.** The occurrences must be random.
> **3.** The occurrences must be independent of each other.
> **4.** The occurrences must be uniformaly distributed over the interval being used.

---

> **Parameters of the Poisson Distribution**
>
> * The mean is µ
> * The standard deviation σ = √µ

---

A Poisson distribution differs from a binomial distribution in the fundamental ways.

1. A particular binomial distribution is determined by the sample size n and the probability p, but a Poisson distribution is determined only by the mean µ.

2. In a binomial distribution, the possible values of the random variable x are 0, 1, ....., n, but a Poisson distribution has possible x values of 0,1,2,...., with no upper limit.

---

### Poisson Distribution as an Approximation to the Binomial Distribution
---

The Poisson distribution is sometimes used to approximate the binomial distribution when n is large and p is small.  One rule of the thumb is to use such an approximation when the following two requirements are both satified.


**Requirements for Using the Poisson Distribution as an Approximation to the Binomial**

1. n ≥ 100

2. np ≤ 100

---

> **Formula 5-6 Mean for Poisson Distribution as an Approximation to the Binomial.
>
> µ = np

---
