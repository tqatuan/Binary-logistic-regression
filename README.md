# Binary-logistic-regression
##Stock market data

We will begin by examining some numerical and graphical summaries of the `Smarket` data, which is part of the `ISLR2` library. This data setconsists of percentage returns for the S&P 500 stock index over 1,250
days, from the beginning of 2001 until the end of 2005. For each date, we have recorded the percentage returns for each of the five previous trading days, `Lag1` through `Lag5`. We have also recorded `Volume` (the number of shares traded on the previous day, in billions), `Today` (the percentage return on the date in question) and `Direction` (whether the market was Up or Down on this date). Our goal is to predict `Direction` (a qualitative response) using the other features.

## Default data

We used logistic regression to predict the probability of `default` using `income` and `balance` on the `Default` data set, which is part of the `ISLR2` package. You will now estimate the test error of this logistic regression model using the validation set approach. Do not forget to set a random seed before beginning your analysis.
