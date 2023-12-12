# Walmart-Stocking-Optimization
This repository contains code for a product stocking presciption algorithm developed for class 15.095, MIT Fall 2022. 

We implement some baseline prescription models, namely sample average approximation (SAA), regress-and-compare, and optimizing over previous store values.
We also implement some more sophisticated models, namely a classification and regression tree (CART) for prescription, and an optimal regression tree (ORT).

Our best prescription model, the ORT, improves week profit by nearly $400K from the SAA baseline, demonstrating the power of optimization in prescriptive contexts.

Contents:
* `Data` - contains product stocking information and some external variables from a selection of Walmart shops
* `Models` - contains implementations of baseline and more sophisticated prescription models
* `Results` - contains plots and tables comparing model results
* `Project_Report.pdf` - contains the written report for this project, submitted as a final deliverable for class 15.095
* `Project_Slidedeck.pdf` - contains the presentation slidedeck for this project, presented as a final deliverable for class 15.095

Contributors:
> Zach Wayne `zwayne24` <br /> Daniel Chung `djaechung`
