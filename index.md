## Welcome to Representation Page
Click [here](https://idatavisualizationlab.github.io/B/congnostics/layout.html) to go to the prototype

## Monday, January 20th, 2020

### Content
1. Quantities for diagnosing features/partterns of time series.
2. Use cases of the proposed quantities.
3. Drawback of the proposed quantites.
4. Future works

### 1. Quantities for diagnosing features/partterns of time series.
1.1. Trend

I use non-parametric Mann-Kendall test:
![trend](Jan_19/trend.png)

1.2. Periodicity

The periodogram element is squared of the Fourier coefficient of the series. We score the periodicity measure of a time series as the sum of all peaks in the periodogram, and divide it by sum of all elements to get standardized value.
![periodicity](Jan_19/periodicity.png)

1.3. Auto-correlation

![auto-correlation](Jan_19/auto_correlation.png)

1.4. Mean and Standard deviation

![auto-correlation](Jan_19/mean_sd.png)

1.6. Mean and Standard deviation of the first difference

The first difference:
![first_diff](Jan_19/firstDiff.png)
Mean and Standard deviaiton of the first difference
![first_diff](Jan_19/Net_mean_sd.png)

1.7. Net outlying

We use box-plot rule for detecting outliers of values of time series and the first difference.
![outlying](Jan_19/outliers.png)


