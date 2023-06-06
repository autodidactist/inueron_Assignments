---
title: Probability Notes
author: Mohammed Shahid
date: 2023-05-07
geometry: a4paper
description: This is a brief description of my document.
header-includes:
  - \usepackage{ebgaramond}
  - \usepackage{framed}
  - \usepackage{xcolor}
  - \usepackage{tikz}
  - \usepackage{tcolorbox}

---

\definecolor{pastelRed}{RGB}{255,166,158}
\definecolor{pastelOrange}{RGB}{255,202,153}
\definecolor{pastelYellow}{RGB}{255,241,153}
\definecolor{pastelGreen}{RGB}{187,255,153}
\definecolor{pastelTurquoise}{RGB}{153,255,247}
\definecolor{pastelBlue}{RGB}{153,198,255}
\definecolor{pastelPurple}{RGB}{214,153,255}
\definecolor{pastelPink}{RGB}{255,153,228}
\definecolor{pastelGray}{RGB}{204,204,204}
\definecolor{pastelLime}{RGB}{191,255,0}
\definecolor{pastelTeal}{RGB}{0,128,128}
\definecolor{pastelLavender}{RGB}{230,230,250}
\definecolor{pastelMint}{RGB}{152,255,152}
\definecolor{pastelSalmon}{RGB}{255,160,122}
\definecolor{pastelGold}{RGB}{255,215,0}
\definecolor{pastelKhaki}{RGB}{195,176,145}

\newcommand{\redt}[1]{\textcolor{red}{#1}}
\newcommand{\bluet}[1]{\textcolor{blue}{#1}}
\newcommand{\greent}[1]{\textcolor[HTML]{5E7914}{#1}}

# Introduction

### DEFINITION 0:
Probability is the study of Randomness.

### DEFINITION 1:
Probability is the measure of the likelihood of an event occuring.

### DEFINITION 2:
Probability is the measure of the likelihood/chance/odd of an event occuring.

### DEFINITION 3:
Probability is a measure of the likelihood or chance that a particular event will occur. It's expressed as a number between 0 and 1.

### A Short Naive Explanation:
Probability can be used to express the likelihood or chance of an event occurring, and it is typically expressed as a number between 0 and 1. A probability of 0 means that the event is impossible, while a probability of 1 means that the event is certain to occur. Converting probabilities into percentages can make them more understandable to laypeople, since percentages are commonly used in everyday language. For example, a probability of 0.5 can also be expressed as 50%.

### Example 1:
Am I gonna eat dinner. It's an event that may or may not occur in the future. So the measure of me eating the dinner can be measured using probability. Like What are the odds/chance/liklihood of me eating the dinner. And it can be expressed within 0-1. But u can also convert that into percentage bythat we can sound more layman.

### Example 2:

What are the odds thar CSK will win the IPL?. It can be answered using probability.

### Note:
Both examples can be answered by getting the historical data of those events. And we can use probability to predict it.
So clealrly we use some stats and probability both to predict real world events.

### What is not Probability?
Anything that cannot be measured in terms of likelihood or chance cannot be considered as probability. For example, subjective opinions, emotions, beliefs, and values are not probabilities because they cannot be measured in terms of likelihood or chance.


### Probability Theory
Probability Theory is a mathematical framework that allows us to describe and analyze random phenomena in the world around us. By random phenomena, we mean events or experiments whose outcomes we can't predict with certainty.

\centerline{\strong{OR}}

Probability theory is a branch of mathematics that deals with the analysis and interpretation of random phenomena.

\centerline{\strong{OR}}

Probability theory is a branch of mathematics that deals with the study of random phenomena and uncertainty. It provides a framework for analyzing and predicting the likelihood of various outcomes or events, based on known or assumed probabilities.

\centerline{\strong{OR}}

Probability theory provides a solid framework to study random phenomena. It starts by assuming axioms of probability, and then building the entire theory using mathematical arguments.

\centerline{\strong{OR}}

The foundation of probability theory is the concept of probability, which is a measure of the likelihood of an event occurring. Probability can range from 0 (indicating impossibility) to 1 (indicating certainty), and it is usually expressed as a decimal or percentage.

### Why we need Probability Theory?


1. Uncertainty: Probability theory provides a framework for dealing with uncertain events or situations where outcomes are unpredictable. By assigning probabilities to different outcomes, we can estimate the likelihood of future events and make informed decisions.

2. Data analysis: Probability theory is critical for data analysis and statistical inference. It helps us model and understand complex data sets, test hypotheses, and make predictions based on observed data.

3. Risk management: Probability theory is essential in assessing and managing risk. It helps us quantify and evaluate risks associated with various activities and take appropriate measures to minimize them.

4. Machine learning: Many machine learning algorithms rely on probability theory to build models and make predictions. For example, Bayesian networks use probability distributions to represent relationships between variables.

### What is not Probability Theory

Not everything can be described or predicted by probability theory. Here are some examples of things that are not probability:

1. Deterministic events: Probability theory deals with events that have an element of chance or uncertainty. Deterministic events, on the other hand, always have a fixed outcome and can be predicted with certainty.

2. Logical truths: Probability theory is concerned with uncertain events, but it cannot predict logical truths or tautologies. For example, the statement "All humans are mortal" is a logical truth and does not involve any element of probability.

3. Causality: Probability theory can describe correlations and associations between events, but it does not provide information about causality. It cannot tell us whether one event causes another or whether their relationship is just a coincidence.

4. Personal beliefs: Probability theory uses objective methods to calculate probabilities based on data and evidence, but personal beliefs or opinions are subjective and cannot be quantified using probability theory.

In summary, probability theory is a useful tool for dealing with uncertainty and predicting outcomes in certain situations, but it has its limitations and cannot be applied to all types of events and phenomena.

## Possibility vs Probability vs Plausibility

**Possibility** refers to whether something can happen or exist. In other words, it describes whether something is capable of happening or being true.

**Probability** refers to the chance or likelihood that something will happen. It is usually expressed as a percentage or a fraction, ranging from 0 (impossible) to 1 (certain).

**Plausibility** refers to how believable or convincing something is. It is often based on evidence or reasoning and takes into account what is known about the situation or circumstances.

### Note:

The difference between possibility and probability is the measurement. Thats it.

Consider the below example:

Just because Im a human I have the ability to
throw a pen. We can say it's possible because I can.
And I can throw the pen because. Lets say I do all the
time at night and it can be answered using probabilty. I throw the
pen because the flowing of ink is not good in the
pen. And it can be asnwered using plasuible.

The thing is we may see many scenarios are intersecting and quite similar. So to use the better word in the situation is based on the context of understanding the situation. Most of the time people don't give a damn about it and we will understand the situation.

### What is Probability trying to solve?
Probability is trying to solve predicting the outcomes of random events. By using probability theory.

Probability theory is a mathematical framework for analyzing the random events.

### But random(unpredictable) events are  unpredictable by definition. So How it solve it?


It's true random(unpredictable) events are  unpredictable by definition,  probability theory can still help us make sense of them by providing a way to quantify the likelihood of different outcomes.

It just helps us to make sense out of the situation bruh.

Probability Theory has proven to be a powerful way to understand Randomness and manage its effects.


