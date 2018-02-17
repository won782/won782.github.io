---
title: "Big Data in Education Workshop Recap"
date: 2018-02-17  12:50:00 -0500
tags:
   - big data
   - education
   - analytics
   - workshop
headline: "Recap in Big Data in Education Workshop, Feb 17, 2018"
---

## How I heard about this

So last year 1 week before the submissions were due, I stumbled upon
[this](https://sites.google.com/view/bigdataforeducation/competitions)
 data science competiton.

I literally had 1 week left, so without giving a much thought, fitted a neural network with aggregated time series / ordered variables, and after few hours of tuning the parameters, got 'middle of the pack' results (now I am in the mailist, I should be getting a good heads-up next year and see if I can be James Harden at this).

Then as a follow up, I got an email about [this workshop](https://sites.google.com/view/bigdataforeducation/researcher-training-opportunities/boston-big-data-for-education-conference-february-16) that I can attend on Friday at MIT, which is 10 mins away from where I live.

## MOOC
The day started with on-going analytics approach and challenges in MOOC (Massive Online Open Courses). MOOC is uniquely situated that unlike traditional classrooms, the interaction happens online, so that we can collect mouse movement, ask survey, or do lot of other stuffs that is much more difficult in offline classroom settings. The session was led by [Justin Reich](https://openlearning.mit.edu/about/our-team/justin-reich), whom I thought was a great keynote speaker addressing the challenges to people who are not familiar to MOOCs.

There were two main challenges that seems critical to me, and I think it applies to field of education and product research in general.

## Lag Factor
To prove efficacy of product, we need an outcome variable, and in case of education, outcome is vaguely defined, as well as having an *enourmous* time lag.

Recalling my education experience, I think I've had few key teachers / professors or courses growing up; my 4th grade elementary school teacher who gave me an unconditional trust to realize how great of a person I can be, [Dr. Hadley Wickham](http://hadley.nz/) who showed me how awesome statistics can be, and [Dr. David Scott](http://www.stat.rice.edu/~scottdw/) who taught me the foundations for a lot of things that I use daily.

But if I recall *when* such pedagogy has help me in an observable change, it is often in magnitude of years. My 4th grade teacher's help didn't really show up until my 7~9th grade outcomes, and if so, it is hard to associate that with my 4th grade teacher over 6th grade teacher, whom I have no memories of (I can't even say whether it was him or her).

This lag factor does not only apply to education. Thinking about *magical moments* in product, I was wowed by homes that I can rent in airbnb soon as I found out, but my 1st booking happened year or two after.

So I think the problem becomes much easier if we remove the constraint on what *observable change* is. If we can ask users in case of airbnb that "How likely are you to use airbnb after your first look at our offering?", then we have non-time lagged proxy for engagement and conversion. It is easier said than done, as there are selection biases and other factors, but that seems like much easier problem to solve compared to tracking things over time with amplified noise on data.

## Low Tolerence Factor
During the afternoon design session led by [George Mu](https://startmit.mit.edu/mu_george/), I was fortunate to be in a group with my colleage Megan Kenslea and [Tony Emerson](https://rides.gse.harvard.edu/people/tony-emerson). While thinking about what data and analytics can help solve challenges in education, I realized that engagement elasticity to cost / disturbances is one of the key forces driving students away from lot of things.

$$ e_{engagement} = \frac{\Delta \text{Engagement} / \text{Engagement}}{ \Delta \text{Cost} / \text{Cost}} $$

Suppose you are on online banking website and need to pay your phone bill. Regardless of how slow the website is, outdated the UI is, and whether you have better things to do in the evening, you are going to do it, because your engagement (or commitment) to performing a task is almost inelastic with respect to those factors.

In case of education, this could be an interesting way to classfiy programs and create  releveant performance indicators. MOOC is a case where elasticity is high - nothing is mandatory and you are doing for your own good. If there is some UI problem or a bug, your tolenence level of sticking with it is very low. In case of SAT, your elasticity is almost inelastic, as you need to take the exam regardless of how you like it or how you think whether exam is a fair measure of your ability to study in college.

Given different elasticity associated with the product, you can focus your attention; in case of MOOC, it is sensible to focus on reducing barriers, as engagement will be much higher with decreased cost.


## Conclusion
It was a very interesting session overall, to see people across different field and seeing different challenges. After all, it comes down to **good design thinking** and **analytical skills** that can again give **probably approximately correct** solution to these. I will be attending [Education Data Mining Conference 2018](http://educationaldatamining.org/EDM2018) as a follow up to this, to see what things are being done and what are the opportunities for moonshot in the field.
