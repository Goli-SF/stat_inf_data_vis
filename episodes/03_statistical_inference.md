---
title: 'Statistical Inference'
teaching: 10
exercises: 0
---


:::::::::::::::::::::::::::::::::::::: questions 

- What does statistical inference mean?
- What other mathematical concepts are needed to understand statistical inference better?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand the mathematical concept of statistical inference.
- Understand the difference between descriptive and inferential statistics, correlation and causation. 
- Understand the meaning of regression. 

::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor
There is a lot of text in this episode, which is meant for self study. Make sure to have read the text yourself
before the workshop and explain the main concepts to the learners. Put emphasis on the keywords: descriptive and 
inferential statistics, correlation, regression and causation. Let the learners know that they should keep the 
information from this episode in mind before moving on to the next one. In the next episode, they are going to 
learn how to put this knowledge to use for analyzing data and predicting values with data visualization. 
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


This episode demonstrates that data visualization is about more than just storytelling. A common misconception is 
that humanities researchers and scholars find it difficult to grasp statistical concepts and, therefore, the 
mathematics behind machine learning and AI. In this episode, you'll explore the concept of statistical inference, 
with data visualization serving as a helpful learning tool as you will see in the next episode. This episode will 
show you how, besides describing your research data, you can also use visualization for predicting missing values 
and coming up with hypotheses for further research. 

::::::::::::::::::::::::::::::::::::: challenge 

## Question

Have you ever heard of statistical inference? What does this concept mean in statistics?

:::::::::::::::::::::::: solution 

## Answer
 
<u>Inferential statistics</u>, along with <u>descriptive ststistics</u>, are two major methods of statistical analysis. 

- Descriptive statistics summarizes and explains the data we already have, without making generalizations about a 
larger population.
- In contrast, inferential statistics allows us to draw conclusions about an entire population or predict future 
trends through hypotheses. These hypotheses are formed based on observations and analysis of a sample from the 
population. The next step is to test whether the hypothesis is true and applicable to the broader population, or 
whether our observations were simply due to chance, making the hypothesis false.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: discussion

### Statistical inference according to The online Encyclopedia of Mathematics

"At the heart of statistics lie the ideas of statistical inference. Methods of statistical inference enable the 
investigator to argue from the particular observations in a sample to the general case. In contrast to logical 
deductions made from the general case to the specific case, a statistical inference can sometimes be incorrect. 
Nevertheless, one of the great intellectual advances of the twentieth century is the realization that strong 
scientific evidence can be developed on the basis of many, highly variable, observations.

The subject of statistical inference extends well beyond statistics' historical purposes of describing and 
displaying data. It deals with collecting informative data, interpreting these data, and drawing conclusions. 
Statistical inference includes all processes of acquiring knowledge that involve fact finding through the 
collection and examination of data. These processes are as diverse as opinion polls, agricultural field trials, 
clinical trials of new medicines, and the studying of properties of exotic new materials. As a consequence, 
statistical inference has permeated all fields of human endeavor in which the evaluation of information must 
be grounded in data-based evidence.

A few characteristics are common to all studies involving fact finding through the collection and interpretation 
of data. First, in order to acquire new knowledge, relevant data must be collected. Second, some variability 
is unavoidable even when observations are made under the same or very similar conditions. The third, which sets 
the stage for statistical inference, is that access to a complete set of data is either not feasible from a 
practical standpoint or is physically impossible to obtain." 
([Encyclopedia of Mathematics](https://encyclopediaofmath.org/wiki/Statistical_inference))

:::::::::::::::::::::::::::::::::::::::::::::::::::

When using methods of statistical inference, we work with samples of data because we don’t have access to the 
entire population. We observe and measure patterns and categories within these samples to form a hypothesis. 
Proving or rejecting the hypothesis requires mathematical methods that go beyond the scope of this lesson. 
If you're interested in learning more about hypothesis testing, you can watch the 
[YouTube video](https://www.youtube.com/watch?v=2fgQ_8AKhJY) on this topic by DATAtab. 

## 3.1. Correlation and Regression in Inferential Statistics

To perform inferential statistical analysis, it’s important to identify **correlations** between features in the data. 
If two numerical features are correlated, an increase or decrease in one tends to coincide with an increase or 
decrease in the other. For example, if we have data on the lifestyle habits of a group of people and their age at 
death, we can look for lifestyle factors (such as the frequency of physical exercise or eating habits) that may 
correlate with longevity and a higher age at death.

If such a correlation is observed and measured, we can use it to predict the lifespan of individuals whose data 
is not part of the sample. To make this prediction, we first need to establish a mathematical or numerical 
relationship between lifespan and the other features in the dataset that may correlate with it. In this case, 
lifespan is considered the *dependent* variable, as its value depends on the other features. The other features, 
in turn, are considered *independent* variables, as their values do not depend on lifespan. This process of 
numerically relating a dependent variable to independent variables is called **regression**.

::::::::::::::::::::::::::::::::::::::: callout

### Note

Correlation is not causation! In the example above, even if a correlation is found between lifestyle 
and lifespan, scientists must seek clinical evidence to determine whether there is also a causal relationship 
between these two factors. Tyler Vigen, author of the book *Spurious Correlations*, created a 
[website](https://www.tylervigen.com/spurious-correlations) where he shares humorous correlations between 
unrelated trends to emphasize this important point: correlation does not imply causation.

However, correlations can still be useful for predicting future trends through regression methods, 
even if they don’t explain the underlying reasons for these trends.

:::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints 

- The concept of statistical inference. 
- The difference between descriptive and inferential statistics.
- The concepts of correlation, regression and causation.
::::::::::::::::::::::::::::::::::::::::::::::::

