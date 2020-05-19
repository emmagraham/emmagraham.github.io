Welcome to bootcamp!
--------------------

This bootcamp was originally desgined for my MD/PhD cohort at
UW-Madison. However, anyone can follow along! This curriculum is
designed for individuals new to both R and coding in general. NO PRIOR
CODING EXPERIENCE REQUIRED! **I have not created any materials presented
in this bootcamp.** Rather, I have put together a roadmap of resources
that I think will help students build the coding skills and statistical
knowledge needed to analyze a large, "high-dimensional" dataset.

Phase 1 consists entirely of CodeAcademy PRO's R course, in addition to
practice sets designed by Jenny Bryan for UBC's STAT545 lecture. By the
end of Phase 1 of this boot camp, you should be able to:

-   manipulate a dataset into "tidy" format
-   generate a variety of different graphs from a "tidy" dataset
-   analyze trends over different groupings of data
-   calculate mean/median/mode/IQR and perform basic statistical tests
    (t.tests, generalized linear models)

After getting your feet wet with data cleaning/data viz, we will move on
to more complex concepts featured in the R Software Carpentry workshops
that will make your coding life easier! By the end of phase 2, you
should be able to:

-   understand how to construct and interprete an if/else statement
-   push/pull something from github

Phase 3 of this bootcamp will focus on providing an overview of
statistics concepts needed to understand most computational approaches,
particularly those in the genomics field. We will focus particularly on
two-group comparisons, linear modeling, multiple testing and
supervised/unsupervised learning. Phase 3 will refer to slidedecks
prepared for UBC's STAT540 course. By the end of phase 3, you should be
able to:

-   understand what quality checks should be performed on a dataset
    before conducting any analyses
-   understand the statistical underpinnings of two-group comparisons
    and linear models
-   know why multiple testing is important in "big data" studies
-   perform PCA analysis
-   understand supervised and unsupervised clustering methods

Syllabus
--------

### Phase 1

To complete this phase, you will need to sign up for CodeAcademy's PRO R
course. After completing each lesson, do the practice sets in your
Google collab document. If a lesson does not have any associated
practice sets, continue on to the next lesson. If you have any
questions, just make a comment in the Google Collab document and tag me.

<table>
<thead>
<tr class="header">
<th align="left">Lesson Title</th>
<th align="left">More practice</th>
<th align="left">Practice answers</th>
<th align="left">Due date</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Introduction to R Syntax</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="even">
<td align="left">Learn R: Data Frames</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="odd">
<td align="left">Data Cleaning</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="even">
<td align="left">Data Visualization with ggplot2</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://campus.datacamp.com/courses/effective-data-storytelling-using-the-tidyverse/filtering-grouping-summarizing?ex=2">Logical operators from DataCamp</a></td>
<td align="left"><a href="https://emmagraham.github.io/HW/HW%201.md">HW1</a>, <a href="https://emmagraham.github.io/HW/HW%202.md">HW2</a></td>
<td align="left"><a href="https://github.com/emmagraham/RBootcamp_answers/blob/master/HW1_answers.md">HW1 answers</a>, <a href="https://github.com/emmagraham/RBootcamp_answers/blob/master/HW2_answers.md">HW2 answers</a></td>
<td align="left">June 1st</td>
</tr>
<tr class="even">
<td align="left">Aggregates</td>
<td align="left"><a href="https://emmagraham.github.io/HW/HW%203.md">HW3</a></td>
<td align="left"><a href="https://github.com/emmagraham/RBootcamp_answers/blob/master/HW3_answers.md">HW3 answers</a></td>
<td align="left">June 1st</td>
</tr>
<tr class="odd">
<td align="left">Joining Tables</td>
<td align="left">HW4</td>
<td align="left">Link coming soon!</td>
<td align="left">June 1st</td>
</tr>
<tr class="even">
<td align="left">Mean, Median and Mode</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="odd">
<td align="left">Variance and Standard Deviation</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="even">
<td align="left">Quartiles, Quantiles and IQR</td>
<td align="left"></td>
<td align="left"></td>
<td align="left">June 1st</td>
</tr>
<tr class="odd">
<td align="left">Hypothesis testing</td>
<td align="left">HW5</td>
<td align="left">Link coming soon!</td>
<td align="left">June 1st</td>
</tr>
</tbody>
</table>

### Phase 2

Make sure you have RStudio up and running on your own machine.
Instructions for how to do this should have been provided in Lesson 1 of
CodeAcademy, but if you didn't get a chance to set that up, there are
instructions
[here](https://happygitwithr.com/rstudio-git-github.html#rstudio-git-github).

<table>
<thead>
<tr class="header">
<th align="left">Lesson Title</th>
<th align="left">Source</th>
<th align="left">Due date</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="https://swcarpentry.github.io/r-novice-gapminder/07-control-flow/index.html">If/else statements</a></td>
<td align="left">Software Carpentry</td>
<td align="left">June 15th</td>
</tr>
<tr class="even">
<td align="left">Natural Language Processing</td>
<td align="left">TBD</td>
<td align="left">June 15th</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://swcarpentry.github.io/r-novice-gapminder/16-wrap-up/index.html">Tenents of writing good code in R</a></td>
<td align="left">Software Carpentry</td>
<td align="left">June 15th</td>
</tr>
</tbody>
</table>

### Phase 3

This phase will focus on understanding conceptual topics foundational to
genomics-based/statistical research. The slide decks below are
referenced from UBC's STAT540 course. They are used with permission from
Sara Mostafavi (course director).

<table>
<thead>
<tr class="header">
<th align="left">Lesson Title</th>
<th align="left">Source</th>
<th align="left">Date</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect03_explore.pdf">Exploratory data analysis and quality control</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect04_StatReview.pdf">Stats/math background for big data</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect05_TwoGroupComp.pdf">Two group comparisons</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect06_ANOVA.pdf">ANOVA</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect07_LinearModels.pdf">Linear models</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect08_Continuous.pdf">Linear modeling with continuous variables</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect09_MultipleTesting.pdf">Multiple testing</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect13_PCA.pdf">Principal component analysis</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect16_ClusterAnalysis.pdf">Cluster analysis</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect20_classification.pdf">Supervised learning</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
<tr class="odd">
<td align="left"><a href="https://stat540-ubc.github.io/lectures/lectures_2020/lect21_SL2.pdf">Supervised learning part 2</a></td>
<td align="left"><a href="https://stat540-ubc.github.io/">STAT540</a></td>
<td align="left">TBD</td>
</tr>
</tbody>
</table>
