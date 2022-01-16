# r_normal_distribution_histogram
---
title: "Histogram of X"
output: html_notebook
---

Plotting a normal distributions of X as Histogram

```{r}
# Scope: Creating a Histogram

x <- rnorm(2000)
hx <- hist(x, breaks=200, plot=FALSE)
plot(hx, col=ifelse(abs(hx$breaks) < 1.5, 2, 3))
```

![rnormaldistribution](https://user-images.githubusercontent.com/96922284/149667256-5d60589e-ea5f-41e7-a90c-159525219787.PNG)
