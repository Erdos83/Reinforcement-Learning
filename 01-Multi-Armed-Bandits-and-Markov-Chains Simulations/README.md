# Reinforcement Learning: Multi-Armed Bandits and Markov Chains

An R-based computational study of epsilon-greedy action selection and finite-state Markov chains, originally developed as coursework in February 2024.

## Explore the project

- [View the R Markdown source](reinforcement-learning.Rmd)
- [View the rendered report](reinforcement-learning.md)


## Experiments

**10-armed bandits:** Compare epsilon-greedy strategies for epsilon = 0, 0.01 and 0.1 across 2,000 runs of 1,000 steps, plotting average reward and percentage of optimal actions.

**Three-state Markov chain:** Simulate 500 state transitions, approximate the stationary distribution and compare it with observed state frequencies.

### Reproduce the report

1. Open `reinforcement-learning.Rmd` in RStudio.
2. Install the required packages if needed: `install.packages(c("rmarkdown", "knitr"))`.
3. Click **Knit** to generate the Markdown report and accompanying figures.
4. Review the generated files and commit the report and figures to GitHub.

## Reference

Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.
