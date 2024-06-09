# New York Trip Duration
#### A simple linear regression project to predict the total ride duration of taxi trips in New York City.

#### This was a part of a Kaggle competition. The dataset was released by he NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

[Visit the New York Trip Duration Competition on Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration)

## Evaluation Metrics

#### The evaluation metric for this competition is Root Mean Squared Logarithmic Error.


We define the error term $\epsilon$ as follows:

$$
\epsilon = \sqrt{\frac{1}{n} \sum_{i=1}^{n} \left( \log(p_i + 1) - \log(a_i + 1) \right)^2}
$$

