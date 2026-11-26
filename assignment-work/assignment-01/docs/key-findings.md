# Key findings

## Housing price analysis

- The dataset contains 21,613 house records and 22 columns.
- Longitude alone explains almost none of the variation in price (`R² = 0.000468`).
- `sqft_living` explains about 49.3% of the variation in the full dataset (`R² = 0.492853`).
- The required multiple-feature model reaches `R² = 0.657695` in-sample.
- A scaled second-order polynomial pipeline reaches `R² = 0.751341` in-sample.
- On the held-out test set, Ridge regression reaches `R² = 0.647876`.
- Polynomial Ridge reaches `R² = 0.700274` on the held-out test set.
- `sqft_above` has a positive correlation with price (`r = 0.6056`).
- Waterfront properties show a greater number and magnitude of high-price outliers.

## Interpretation cautions

- In-sample and held-out R-squared values answer different questions and should be reported separately.
- The models are predictive and descriptive; they do not justify causal claims about individual features.
- The dataset is a course-provided educational extract, so results should not be generalised beyond the observed market context.