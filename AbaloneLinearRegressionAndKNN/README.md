# Introduction
 
I will be working with a data set from the UCI (University of California, Irvine) Machine Learning repository ([see website here](http://archive.ics.uci.edu/ml/datasets/Abalone)). The full data set consists of $4,177$ observations of abalone in Tasmania. (Fun fact: [Tasmania](https://en.wikipedia.org/wiki/Tasmania "Tasmania") supplies about $25\%$ of the yearly world abalone harvest.)

![*Inside of an abalone shell.*](images/17612037-abalone-shell-inside.jpg){width="309"}

The age of an abalone is typically determined by cutting the shell open and counting the number of rings with a microscope. The purpose of this data set is to determine whether abalone age (**number of rings + 1.5**) can be accurately predicted using other, easier-to-obtain information about the abalone.

The full abalone data set is located in the `\data` subdirectory. Read it into *R* using `read_csv()`. Take a moment to read through the codebook (`abalone_codebook.txt`) and familiarize yourself with the variable definitions.

Make sure you load the `tidyverse` and `tidymodels`!
