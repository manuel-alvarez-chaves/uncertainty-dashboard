### Uncertainty Dashboard
This is a very simple streamlit dashboard used to analyze how deterministic point predictions compare to probabilistic distribution-based predictions. The dashboard shows the output of a hydrological model and two metrics are shown: `NSE` and `Log-likelihood`.

#### Metrics
* `NSE`: measures accuracy of point-predictions. Similar to a coefficient of determination $R^2$.
* `Log-likehood`: measures the density of the predicted distribution over the observed data.