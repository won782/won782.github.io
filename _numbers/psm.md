---
title: "Causality and Propensity Score Matching"
date: 2018-02-09  18:57:00 -0500
tags:
   - propensity score matching
   - statistics
   - causality
   - observational data
headline: "Work in Progress!"
---

I have my own branching model of data in different buckets, in 3 dimensions.

* **Data Format**
    * Numeric
        * Continuous
        * Binary
        * Count
    * Categorical
    * Text
    * Image
    * Time
* **Data Type**
    * Attribute :
    If primary key is the subject of interest OR sampling unit for the analysis
    * Record :
    If primary key is an event that can be associated with sampling unit
* **Data Source**
    * Experimental :
    If data is generated in controlled setting (e.g. Randomized Controlled Trial)
    * Observational :
    If data is a collection of observations

---

Data format has more to do with statistical techniques. There are different probability distributions that fits data well - count with Poisson, binary with Binomial, Bernoulli, Hypergeometric, and continuous with Gaussian, Log-normal, Beta... list goes on.

Data type is more about how to query and transform data. Lots of joins, group bys, or some neat `dplyr` skills.

Data source is often neglected and what I want to write about here. Most of data in the world are observational data. And often times, we make wrong causal claims using observational data and this should be done in a cautious manner.

---

Suppose you have only two records; number of firefighters dispatched and amount of financial damage a building had. Of course those two will have very high correlation. However, we will not make such a claim that *firefighters will bring financial damage to the building*.

Above is typical case of **spurious correlation**. Underlying variable in above is **fire**. If fire happens, firefighters are dispatched, and desipte the efforts, there will be some financial damage to the building. Similar to this case, we often see ridiculous claims from people (viral media, maybe?) using these correlation and signficance to claim causal relationship.

Often times in observational data, we lack these underlying varibles. Unfortunately, it is often those underlying factors that are more difficult to measure.

Consider the case of student achievement in Mathematics and absences. There will pretty strong negative correlation between two variables, but we cannot attribute 100% of low achievement to absences. Underlying psychological factors such as 'giving up', 'not motivated' or even socio-economical factors are often not measured.

---

There are two different schools of thought to solve this issue (although they are closely related).

One is Rubin Causal Model

Other is Counterfactual Model by Judea Pearl

( TO BE CONTINUED WITH CONCRETE EXAMPLES! )
( USE NBA DATA? )
