# Machine-Learning-Predictive-Models-for-Telecom-Metrics
Telecom Predictive Models
Business Problem
In the highly competitive telecom industry, customer retention and revenue optimization are crucial. This project leverages machine learning models to predict key metrics such as customer activity, average revenue per user (ARPU), customer lifetime value (CLV), and service usage type. Accurately forecasting these metrics enables proactive identification of potential churn, optimization of marketing strategies, and enhancement of customer experiences. The business objective here is to provide actionable insights that help retain high-value customers and improve overall profitability.

Approach
Our dataset contains data across four months: June, July, August, and September. However, for the purpose of this predictive analysis, we focused on the first three months (June, July, August) to build the models.

Data for Months 6 and 7: We used data from the 6th (June) and 7th (July) months to train the models. The feature set includes metrics such as on-net, off-net, total minutes of usage, data volumes (2G, 3G), ARPU, and Age on Network (AON).

Predicting Month 8 (August): Using the data from June and July, we trained four predictive models:

Active Indicator Model: Determines if a customer will be active.

ARPU Prediction Model: Forecasts Average Revenue Per User.

CLV Prediction Model: Calculates Customer Lifetime Value.

Service Usage Prediction Model: Classifies the service type (2G, 3G, Mixed, or No Service).

Comparison with Actual Data: We then compared the predictions for the 8th month (August) with the actual August data to validate the models' accuracy. The results highlight the model's ability to capture trends and make accurate predictions, helping in proactive decision-making and strategic planning.
