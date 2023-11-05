# Web_analysis
**Conclusion**

The data presented are for groups of people with common interests who viewed the site X times.

The challenge posed was to properly prepare the data and then analyze it and make a prediction for December 2022.

**Seasonality.**

A noticeable seasonality can be observed. The data in Figures 1 and 2 show how directly proportional displays increase over the year. The trend is presented practically as a straight line.

**Similarities.**

From the data received, it was necessary to separate those from Saturday and Sunday.

You can see the apparent similarities between the segments in Figure 3.

Technology & Computing, Travel, Style & Fashion, Sports, Shopping, Book and Literature are very close to each other in the charts. This can be explained by the fact that these segments relate to our daily lives

A similar situation applies to Science and Religion & Spirituality, as well as Sensitive Topics about Pets - in the latter case the convergence is less.

The similarity between Science and Religion & Spirituality can be explained by the fact that these segments are somewhat similar to each other. Since time immemorial, science and religion have intersected and challenged each other's beliefs.

Real Estate has no data similarity.

**Correlation.**

Correlation in Figure 4 occurs between all segments.

A Pearson coefficient of 0.991 indicates a very strong linear relationship, and a P-value < 0.05 in both (Destop and Mobile) cases says that the data are stastically significant

**Prediction.**

ARIMA, SARIMA and LSTM were used as predictive models. With such a large data set, LSTM performed best in this case. This is due to the fact that it retains long-term memory, can detect patterns among the data, can highlight many features or avoids the problem of disappearing gradient
