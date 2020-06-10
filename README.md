# An Accessible Introduction to Multi-level (or Mixed Effects) Models

This repository currently serves as a place for brainstorming about a book for [Ed Tech Books](https://edtechbooks.org/).

## Applications

- network data, with relations nested in groups
- repeated measures within groups
- longitudinal data within groups
- individuals nested in high-level groups (statistically the same as repeated measures within units, but conceptually different)

## Principles

- Multi-level models are *just regressions*, with one important difference: effects associated with groups are weighted (or "regularized") by how much information there is for the effect for each specific group
- See what difference a multi-level approach makes (compare multi-level models to linear model alternatives)
- Thinking creatively and flexibly about the structure of data (groups are not only those due to the nesting of individuals)
- Recognize that every little bit (of data) counts (multi-level models can handle different amounts of information for each group)
- Use modern, freely-available, and open-source software
- Connect to powerful ideas about Bayesian methods of inference

## Ideas for Datasets

- Toddlers
- Fruits
- Reviews on review websites
- Relations *between* students in a class

## Resources

- [Data Science-ish](https://github.com/jrosen48/data-science-ish)
- [Multiple Uses for Multi-Level Models](https://joshuamrosenberg.com/posts/multiple-uses-for-multi-level-models-examples-from-recent-research/)
- [Comparing estimates and their standard errors from mixed effects and linear models
](https://joshuamrosenberg.com/posts/comparing-mixed-effects-and-linear-models/)
- [Finding the top rail-trails in each state using mixed effects models](https://joshuamrosenberg.com/posts/find-the-top-rail-trails-in-each-state/)
- [Explorations in Markov Chain Monte Carlo - comparing results from MCMCglmm and lme4](https://joshuamrosenberg.com/posts/explorations-in-markov-chain-monte-carlo-mcmc/)

