# Analysis of some predictions about the 2018 EA Survey

Note: Conclusions unsure, because I don't know whether the target interval is 80 or 60%

## Introduction.
Some effective altruists made predictions about the 2018 EA Survey: a survey which aims to reach most people within the effective altruism movement. Here, I present the set up for the prediction making, the questions, and explain some judgement calls I made when judging the answers. Everything is written such that you can play along.

## Set up
For every question, try to come up with an interval such that you're 80% confident the answer lies in it. If you use a search engine, the surveys from previous years are fair game.

## Judgement call
In some cases, people didn't answer the question. For example, under the is.veg variable, you can have TRUE, FALSE, or NA: Not Available. If their number is respectively x, y and z, it might be a good first order approximation to estimate the actual proportion of vegetarians/vegans as x/(x+y).

However, I've decided to be extremely anal about it, and choose to define the actual proportion of people who define as vegan as x/(x+y+z). This doesn't make much of a difference in the case of plant eating, but it does in the identity politics questions.

## Questions

1. How many people do you think will take the EA survey?

1. What percent of people will say they got involved in EA in 2017?

1. What percent of people will say they first heard about EA from a personal contact?

1. What percent of people will say they first heard about EA from LessWrong?

1. What percent of people will say they are involved in a local EA group?

1. What percent of people will say they have taken the Giving What We Can pledge?

1. What percent of people will say they find the EA community either welcoming or very welcoming?

1. What percent of people will say they find the EA community either unwelcoming or very unwelcoming?

1. What percent of people will say that global poverty should be the top or near top priority?

1. What percent of people will say that cause prioritisation should be the top or near top priority?

1. What percent of people will say that reducing risks from AI should be the top or near top priority?

1. What percent of people will say that animal welfare/rights should be the top or near top priority?

1. What percent of people will say that meta charities should be the top or near top priority?

1. What percent of people who took the survey will be between 20 and 35 years of age?

1. What percent of people will identify as male?

1. What percent of people will identify as white?

1. What percent of people will say they live in the US or UK?

1. What percent of people will say they live in continental Europe?

1. What percent of people will say they are atheist, agnostic or non-religious?

1. What percent of people will say they are vegan or vegetarian?

1. What percent of people will say they are politically on the left or centre left?

1. What percent of people will say they are politically on the centre?

1. What percent of people will say they are politically on the right or centre right?

1. What percent of people will say that they are single?

1. What percent of people will say that they are employed?

1. What percent of people will say that they are a student?

## Answers
1. 22.20943613
1. 33.17990027
1. 11.73762946
1. 15.53509781
1. 25.77675489
1. 59.37859609
1. 4.75642501
1. 61.33486766
1. 41.46528577
1. 44.1503644
1. 35.28960491
1. 34.06214039
1. NA
1. 59.76217875
1. 78.17414653
1. 52.35903337
1. NA
1. 72.0751822
1. 38.43498274
1. 60.98964327
1. 8.630609896
1. 2.685078634
1. 35.82662064
1. 52.5508247
1. 26.50556195

## Calibration results
For the 35 people who took part in the original prediction making, their results can be seen in the following graphics:

![](https://nunosempere.github.io/rat/EA-predictions/Scatterplot.jpeg)
![](https://nunosempere.github.io/rat/EA-predictions/Scatterplot2.jpeg)
![](https://nunosempere.github.io/rat/EA-predictions/histogram.jpeg)
![](https://nunosempere.github.io/rat/EA-predictions/Brier-scores.jpeg)

The average accuracy is 55.12%, that is, the average participant got 13.22 out of 24 questions right. If it had been reached, a target credence of 80% would imply an average of 19.2 correct answers. In other words, in this limited domain, when these people say 80%, the thing happens 55% of the time. If they bet, they'd replace ~1:1 bets with 1:4 bets.


