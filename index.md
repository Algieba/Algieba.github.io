---
title: "Survival of passengers on the Titanic"
author: "Antonio Lloris Amor"
highlighter: highlight.js
output:
  html_document:
    keep_md: yes
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: Developing Data Products - Project
framework: io2012
widgets: []
---

## Introduction

- This presentation show information about 'Survival' app. 'Survival' app let us
filter the information in 'Titanic' dataset and show the results by a chart and 
a data table.

- 'Titanic' data set provides information on the fate of passengers on the fatal
maiden voyage of the ocean liner 'Titanic', summarized according to economic
status (class), sex, age and survival.

- Our app let us filter that information by 'Class', 'Sex' and 'Age' and give the
numbers of survival and no survival passengers. The results can be show by a pie
or by a bar graph and a table.

- When the user change some thing in a category, or charge the graph type, the
table and the graph are automatically updated. 

---

## 'Titanic' Dataset

This dataset is included in package 'datasets' version 3.1.3. Originally is a 
matrix with 4 dimensions, but we transform it to a data frame because is easier
to handle.















