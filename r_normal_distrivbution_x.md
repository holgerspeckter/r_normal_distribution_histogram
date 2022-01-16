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

