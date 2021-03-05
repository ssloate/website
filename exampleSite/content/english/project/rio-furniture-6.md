---
title: Mandatory Minimums and Mass Incarceration
description: " Research Assistantship"
image: images/portfolio/work6.jpg
bg_image: "/images/jail_fence.jpg"
category: Data Science
information:
- label: Working With
  info: <a href="https://www.nickeubank.com">Dr. Nick Eubank</a> <br> <a href="https://www.david-hausman.com/">David
    Hausman, JD</a>
- label: What We're Doing
  info: Academic Research
- label: Tools Used
  info: Python, GitHub
- label: Started
  info: December 2020
- label: Skills
  info: Causal Inference <br> Python  <br> Project Management <br> Statistical Analysis

---
## Understanding Trends and Causes

In the past 30 years, many states have enacted mandatory minimum legislation that purports to decrease judicial and prosecutorial discretion in sentencing, as well as increase the minimum time served by convicted defendants. But our understanding of these policies -- which emerged largely during the tough-on-crime period of the 1990s --  is surprisingly limited. While one may assume that high mandatory minimum sentences would lead to longer prison sentences, recent work has shown little evidence to confirm that actual sentence length increased proportionally to lengths in sentencing laws. Prosecutorial discretion may be behind this phenomenon, as prosecutors use harsh sentencing laws to coerce defendants into pleading guilty to lesser crimes. <p>

Given increasing evidence from the mid-1990s forward that mass incarceration is driven by a rise of the share of cases charged by prosecutors, it is critically important to understand understand the role of mandatory minimum and "third strike" sentencing laws that similarly impose higher penalties. This project aims to fill data gaps by estimating the causal effect of mandatory minimum and third strike legislation on plea bargaining outcomes.<p>

The project uses a confidential DOJ dataset: <i> State Court Processing Statistics: Felony Defendants in Large Urban Counties. </i> To answer the research question, I use Python to track individuals throughout the stages of arrest, criminal charge, adjudication outcome, and conviction. I employ a difference-in-difference framework and regression packages to statistically analyze the effect of third strike laws on any changes in outcomes, such as the distribution of arrest charge types, plea bargain frequency, case dismissal frequency, etc. around the time that states begin implementing third strike laws.