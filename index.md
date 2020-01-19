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

I use non-parametric Mann-Kendall test [12]:
![trend_formula](Jan_19/trend_formula.png)
where
![sign_formula](Jan_19/Sign_formula.png)
The picture below shows how to calculate the trend measure.
![trend_explain](Jan_19/trend_explain.png)

1.2. Periodicity

Two common approaches for detecting periodicity time series are periodogram and auto-correlation. The latter is difficult to automatically determine periods [20], so we use the former for this score. The periodogram element is squared of the Fourier coefficient of the series [3, 20]:
![periodogram](Jan_19/DFT_formula.png)
