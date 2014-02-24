---
layout: page
title: Chapter 4
---

## 4-1 Review and Preview
---

> **Rare Event Rule for Inferential Statistcs**
>
> If, under a given assumption, the probability of a particular observed event is extremely small, we conclude that the assumption is probably not correct.

---

## 4-2 Basic Concepts of Probability
---

> An **event** is any collection of results or outcomes of a procedure.

---

> A **simple event** is an outcome or an event that cannot be further broken down into simpler components.

---

> The **sample space** for a procedure consists of all possible simple events.  That is, the sample space consits of all outcomes that cannot be broken down any further.

---

> In the following display, we use "b" to denote a baby boy and "g" to denote a baby girl.

---

| **Procedure** | **Example of Event** | **Sample Space (List of Simple Events)** |
| ------------- | -------------------- | ---------------------------------------- |
| Single Birth  | 1 girl (simple event)| (b,g)                                    |
| 3 births      | 2 boys and 1 girl (bbg, bgb, gbb are all simple events resulting in 2 boys and 1 girl) | (bbb,bbg,bgb,bgg,gbb,gbg,ggb,ggg) |

---

> With one birth, the result of 1 female is a simple event because is cannot be broken down any further.  With three births, the event of "2 girls and 1 boy" is not a simple event because it can be broken into simpler events, such as ggb, gbg, or bgg.  With three births, the ***sample space*** consists of the eight simple events listed above.  With three births, the outcome of ggb is considered a simple event, becasue it is an outcome that cannot be broken down any further.  We might incorrectly think that ggb can be further broken down into the individual results of g, g, and b, but g, g, and b are not individual outcomes that are simple events: bbb, bbg, bgb, bgg, gbb, gbg, ggb, and ggg.

---

> **Notation for Probabilities**
>
> P denotes a probability.
>
> A, B, and C denote specific events.
>
> P(A) denotes the probability of event A occuring.

---

Relative Frequency Approximation of Probability

  * Conduct (or observe) a procedure, and count the number of times that event A actually occurs.  Based on these actual results, P(A) is approximated as follows:


```
              number of times A occured
P(A) = -------------------------------------------
        number of times the procedure was repeated
```

---

Classical Approach to Probability (Requires Equally Likely Outcomes)

  * Assume that a given procedure has ***n*** different simple events and that each of those simple events has an equal chance of occurring.  If event A can occur in s of these n ways then

```
            number of ways A occur                s
P(A) = --------------------------------------  =  -
        number of different simple events         n
```

---

> When using the classical approach, always verify that the outcomes are **equally likely.**

---

Subjective Probabilities

  * P(A), the probability of event A, is estimated by using knowledge of the relevant circumstances.

---

> **Law of Large Numbers**
>
> As a procedure is repeated again and again, the relative frequency probability of an event tends to approach the actual probability.

---

### Complementary Events
---

> The **complement** of event A, denoted by A, consits of all outcomes in which event A does not occur.

---

> **Rounding Off Probabilities**
>
> When expressing the value of a probability, either give the exact fraction or decimal or round off final decimal results to three significant digits. (Suggestion: When a probability is not a simple fraction such as 2/3 or 5/9, express it as a decimal so that the number can be better understood.)  All digits in a number are significant except for the zeros that are included for proper placement of the decimal point.

---

### Interpreting Probabilities: Unlikely Events and Unusual Events
---

> An event is **unlikely** if its probability is very small, such as .05 or less.  An event has an **unusually low number** of outcomes of particular type or an **unusually high number** of those outcomes of that number is far from what we typically expect.

---

### Important Principles and Notation for Probability
---

  * The probability of an event is a fraction or decimal number between 0 and 1 inclusive.
  * The probability of an impossible event is 0.
  * THe probability of an event that is certain to occur is 1.
  * Notation: The probability of event A is denoted by P(A).
  * Notation: The probability that event A does not occur is denoted by P(A).

---

> That **actual odds against** event A occuring are the ratio P(A)/P(A) usually expressed in the form of a:b where a and b are integers having no common factors.

---

> The **actual odds in favor** of event A occurring are the ratio P(A)/P(A), which is the reciprocal of the actual odds against that event.  If the odds against A are a:b, then the odds in favor of A are b:a.

---

> The **payoff odds** against event A - (net profit)(amount bet)

---

## 4-3 Addition Rule
---

> A **compound event** is any event combining two or more simple events.

---

> When finding the probability that event A occurs or event B occurs, find the total of the number of ways A can occur and the number of ways B can occur, but find that total in such a way that no outcome is counted more than once.

---

> **Formal Addition Rule**
>
> P(A or B) = P(A) + P(B) - P(A and B)
>
> where P(A and B) denotes the probability that A and B both occur at the same time as an outcome in a trial of procedure

---

> **Intuitive Addition Rule**
>
> To find P(A or B), find the sum of the number of ways event A can occur and the number of ways B can occur, adding in such a way that every outcome is counted only once. P(A or B) is equal to that sum, divided by the total number of outcomes in the sample space.

---

> Events A and B are disjoint (or mutually exclusive) if they cannot occur at the same time. (That is, disjoint events do not overlap.)

---

> **Example of disjoint events:**
>
> Randomly selecting someone who is a registered Democrat.
> Randomly selecting someone who is a registered Republican.
> **(The selected person cannot be both.)**

---

> **Example of events that are not disjoint:**
>
> Randomly selecting someone taking a statistics course.
> Randomly selecting someone who is a female.
> **(The selected person can be both.)

---

> **Rule of Complementary Events**
>
> P(A) + P(Ā) = 1,  P(Ā) = 1 - P(A),  P(A)= 1 - P(Ā)

---

### 4-4 Multiplication Rule: Basics
---

> **Notation**
> P(A and B) = P(event A occurs in a first trial and event B occurs in a second trial)
>
> P(B|A) represents the probability of event B occuring after it is assumed that event A has already occurred. (Interpret B|A as "event B occurring after event A has already occurred.")

---

> **Formal Multiplication Rule**
> P(A and B) = P(A) • P(B|A)

---

> **Intuitive Multiplication Rule**
>
> To find the probability that event A occurs in one trial and event B occurs in another trial, multiply the probability of event A by the probability of event B, but be sure that the probability of event B takes into account the previous occurrence of event A.

---

> Two events A and B are **independent** if the occurrence of one does not affect the probability of the occurrence of the other. (Several events are similarly independent if the occurrence if any does not affect the probabilities of the occurrence of the others.) If A and B are not independent, they are said to be **dependent**.

---

* Sampling with replacemnt: Selections are independent events.

* Sample without replacemnt: Selections are dependent events.

---

> **Exception: Treating Dependent Events as Independent**
>
> Some cumbersome calculations can be greatly simplified by using the common practice of treating events as independent when small samples are drawn from large populations.  In such cases, it is rare to select the same item twice.

---

> **Treating Dependent Events as Independent: 5% Guideline for Cumbersome Calculations**
>
> When calculations with sampling are very cumbersome and the sample size is no more than 5% of the size of the population, treat the selections as being independent (even if they are actually dependent.)

---

### 4-5 Multiplication Rule: Complements and Conditional Probability
---

Complements and Conditional Probability Two Special Applications

* **Probability of "at least one:"** Find the probability that among several trials, we get at least one of some specified event.

* **Conditional probability:** Find the probability of an event occurring when we have additional information that some other event has already occurred.

---

> A **conditional probability** of an event is a probability obtained with the additional information that some other events has already occurred. P(B|A) denotes that conditional probability of event B occurring, given that event A has already occurred. P(B|A) can be found by dividing the probability of events A and B occuring by the probability of event A:

---

```
           P(A and B)
P(B|A) =  ------------
              P(A)
```

---

### 4-6 Counting
---

> **Permutations** of items are arrangements in which different sequences of the same items are counted separately.  For example, with the letters {a,b,c}, the arrangements of abc, acb, bac, cab, and cba are all considered separately as six different permutations.

---

> **Combinations** of items are arrangements in which different sequences of the same items are not counted separately.  For example. with the letters {a,b,c}, the arrangements of abc, acb, bac, cab, and cba are all considered to be same combination.

---
