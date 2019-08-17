---
title: "Practical_Machine_Learning_Human_Activity_Project"
author: "Venkat"
date: "8/11/2019"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Overview

In this project, our goal is to use data from accelerometers on the belt, forearm, arm, 
and dumbell of 6 participants. 
They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. 

More information is available from the website here: http://groupware.les.inf.puc-rio.br/har 
(see the section on the Weight Lifting Exercise Dataset).

## Data Processing

The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har

The data contains NA, nulls, empty spaces and "#DIV/0". This needs to be cleaned. 
There are lot of categorixal data that does not contribute to the analysis and needs to be excluded in the analysis.


## Modeling

Here we are using 3 models and comparinfg the 3 models for efficiency.

## Final result of the test data.
We are using the best model and predicting the output using the best perfoming model - random forest.
