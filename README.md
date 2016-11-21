Title: Introduction to R and RStudio
Author: Marcin Adamski
Affiliation: CBBU, RSB ANU
Date: 18-11-2016

---
# *** Introduction to R and RStudio ***


### Time: Two 4-hour sessions

## Learning objectives:
1. Becoming comfortable using RStudio Integrated Development Environment
2. Learning basic operations in R
   - Variables and their types
   - Vectorization - the concept and applications 
3. Working with data
    - Reading and writing data files
    - Subsetting and joining data
4. Performing basic statistical analyses
5. Creating simple plots
6. Controlling the flow
    - Making choices with if-the-else
    - Repeating operations with for loop
7. Extending R features
    - The packages and their installation
8. Creating plots with ggplot2 package
9. Understanding good coding practice

---
*** First 4-hours session: ***
---
> We start with a bit of "dry theory" when we are still fresh:

## Introduction to R and RStudio
 - What is R and RStudio?
 - How to get it installed?
 - Where to look for help?
 - Presentation of RStudio IDE (Integrated Development Environment).
 - Help in R and RStudio.
 - Concept of an RStudio project.
 
## First steps:
 - "Hello World!" in R.
 - Using R as a calculator; math. operators and functions.
 - Text and logical operators.
 - Variables - operations with variables, creation and removal.

## Vectors and vectorization:
 - Creating vectors.
 - Math. operations on vectors.
 - Type coercion.
 - Factors.

## Other data structures, referring with dollar notation and indexes:
 - Vectors with named elements,
 - Matrices,
 - Arrays,
 - Lists,
 - Data frames.


> Now, it finally is the time to start using the skills we just learned (and getting some new ones as we go). Some parts of the exercises below we will do ourselves (not just following the instructor) as 'challenges'.

```
Exercise 1: A simple single-vector dataset to analyze. We will calculate basic 
statistics (mean, median, variance, std.dev.), summarize the data, and create 
a box-plot and a histogram. Then we will customize the look of the histogram.
```

```
Exercise 2: Another simple one-vector dataset. We will redo the same exploratory 
analyses as previously. Then, using one-sample t-test we will test if the 
dataset's mean varies significantly from the expected value. Next we will check 
our data for normality of distribution with Q-Q plot and Shapiro-Wilk normality test.
```
```
Exercise 3: Finally we start working with 'real' data: We read the data from a 
tab-delimited text file and create a data.frame structure. We talk a bit about 
different formats of text files. We do basic exploratory analyses including plots, 
followed by a two-sample paired t-test, and a corelation test.
```
---
*** Second 4-hours session: ***
---

## Working with files and data frames (using the dataset from exercise 3):
 - Subsetting (splitting data frame into two).
 - Joining data frames together.
 - Shuffling and ordering rows.
 - Deleting rows and columns.
 - Writing to disk.

```
Exercise 4: We will work with a bit larger multi-column dataset. We will have 
the opportunity to use the skills we learned today.
```

## Control flow:
  - The _if-then-else_ statement
  - The _for_ loop

## Extending R features:
  - Installing packages.
  - Examples of popular and useful packages.
  - Calling functions from specific packages.

## The _ggplot2_ package:
 - The Grammar of Graphics: Data, aesthetic mapping, geometric object, statistical transformations, scales, coordinate system, position adjustments, faceting.
 - Aesthetics,
 - Geometic Objects,
 - Layers,
 - Scales
 - Facets (multi panels)
 - _qplot()_ vs. _ggplot()_ functions

```
Exercise 5: We revisit the dataset from previous exercise. We will 
present the data using several features of the ggplot2 package.
```
---
*** End of the workshop***
---
