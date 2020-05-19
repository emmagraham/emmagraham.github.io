---
layout: page
title: HW2
subtitle:  
---

**1. Load the gapminder and tidyverse packages. Is the gapminder dataset
a data frame? Use the str() function to find out. What class of data is
each column (Factor, vector etc)?**

**2. What is the range of life expectancies observed in the Asian
continent? Use filter, select and summary(). The summary function
displays summary statistics (mean, median, IQR) for a given variable.**

**3. What countries are part of the Asian continent? Use filter, select
and unique(). Unique() identifies all unique entries, including those
that are included twice or more.**

**4. Explore how life expectancy in Asia has been changing been 1952 and
2007.**

-   Explore the range of life expectancy values in each year using
    summary().
-   Say we want to represent this data in units of 10^3 people. Use
    mutate() to create a new column, pop\_k, in which the population is
    represented in units of 1000 people. For the year 1952, plot this
    against lifeExp for all countries within Asia. Label both axes.
-   Use ggplot2() to plot life expectancy for each country in Asia
    within this time period. Label both axes.

**5. Using a scatterplot, examine the relationshp between GDP per capita
and life expectancy in each country in Asia across all recorded years.**

**6. You want to isolate only rows with data describing Rwanda or
Afghanistan. What is wrong with the following piece of code? How would
you fix it?** **gapminder %&gt;% filter(country == c("Rwanda",
"Afghanistan"))**
