Alex Hayes
alexpghayes@gmail.com
Rice University

On modelling in R

# Towards a grammar of modelling in R

# Intuitive modelling in R via statistical type safety

## Abstract

Recent developments in the R ecosystem, particularly the advent of the tidyverse, have res

Statistical modelling in R is notoriously laborous. Each modelling technique lives in its own package, has its own (sometimes idiosyncratic) interface and see of methods. In this talk, I argue that we need to differentiate between statistical models (KNN with k = 5) and statistical model families (KNN). I will argue that models and model families should be represented by their own objects with distinct classes, and distinct methods acting on those classes. I will discuss ongoing efforts to standardize methods for fitting and interacting with statistical models, and show how these first attempts at a grammar of modelling result in an interface that is intuitive for users and also a target interface for researchers developing new methods. I will discuss the technical debt incurred by the current modelling ecosystem in R and steps towards a pit of success for the modelling ecosystem, including 

- the pit of the success: we ain't there yet
- my background: running kaggle workshops for students just getting into R and Python
- models and model families (motivating example: LASSO)
- distinct objects with distinct classes
- why current interfaces are conceptually confusing and need revision
- ongoing work to standardize model construction and usage (recipes, rsample, tidyposterior, broom)
- interface: researchers need to be able to target it. many connections and intermediate pieces that haven't been standardized (what broom tries to do). broom interesting: standardize in one place or in each home package: only good if everyone follows community standards.
- best practices from modelling


Yes I would like to apply for a scholarship.