This project focuses on time-series data analysis and forecasting using an Amazon dataset to evaluate historical sales trajectories, project future revenue, and analyze product category demand patterns. By applying statistical modeling and moving average calculations, the notebook processes transaction data to uncover trends, seasonal variations, and category-specific purchasing behaviors.

The core of the analysis centers on two main components visualized through custom Python plots:

ARIMA Monthly Sales Forecasting:
An Autoregressive Integrated Moving Average (ARIMA) model is implemented to analyze aggregate monthly revenue over time. The model processes historical sales data—capturing key peak shopping spikes and fluctuations—and projects future monthly performance out through mid-2027. It also incorporates shaded confidence intervals that expand over the forecast horizon to reflect long-term uncertainty in the predictions.

3-Month Moving Average Category Demand:
To smooth out short-term noise and highlight structural growth, the project computes rolling 3-month moving averages across distinct product categories such as Electronics & Mobiles, Apparel & Fashion, Home & Kitchen, Beauty & Personal Care, and Pantry & Groceries. This visualization clearly maps out volume differences and demand trends across each department over multiple years.

Tech Stack & Tools:

Python: Core programming language used for data manipulation and modeling.

Pandas & NumPy: Used for cleaning, structuring, and resampling transaction data.

Statsmodels: Utilized for implementing the ARIMA time-series forecasting model.

Matplotlib: Used to generate the detailed historical and forecasted line charts with custom gridlines, legends, and dual-state coloring.

This repository serves as a straightforward, practical example of applying time-series methods to retail and e-commerce datasets for trend analysis and visual reporting.
