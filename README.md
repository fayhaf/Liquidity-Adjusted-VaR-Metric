# Liquidity Adjusted VaR Metric
Created a unique statistical measurement that measures risk efficiently and gives clear, unbiased insight into the potential downside of a security.

# About LaVaR Metric
The Liquidity-Adjusted Value at Risk (LAVaR) is calculated as:

LAVaR=VaR+LC

VaR (Value at Risk) measures the maximum potential loss over a given time frame with a certain confidence level.
LC (Liquidity Cost) estimates the cost associated with liquidating the asset position over the desired time frame, taking into account the market impact, bid-ask spread, and depth of the market for the asset.

Calculation of LC (Liquidity Cost):
LC =(Bid-Ask Spread Cost+Market Impact Cost)×Position Size

Bid-Ask Spread Cost can be determined from current market data.
Market Impact Cost can be estimated based on historical data regarding how previous large transactions have affected the asset's price.

The LAVaR metric provides a more holistic view of risk by incorporating the liquidity aspect. This allows the fund to understand not just the risk of a position, but how easily and at what cost the position can be unwound. With insights from LAVaR, the fund can make more informed decisions about asset allocation, especially in terms of diversifying into less liquid assets or sectors. By adjusting for liquidity, LAVaR allows for a more accurate assessment of the fund's performance, particularly in stress scenarios where liquidity can significantly affect returns. LAVaR can help in meeting regulatory requirements related to liquidity risk management, ensuring the fund maintains a healthy liquidity profile. Demonstrating a sophisticated approach to measuring and managing risk, including liquidity risk, can increase investor confidence in the fund's management capabilities.

The Liquidity-Adjusted Value at Risk (LAVaR) offers a comprehensive risk metric that integrates the cost of liquidity into the traditional VaR model. For student-managed investment funds, this metric is particularly valuable for balancing risk and liquidity considerations, thereby supporting more informed and strategic investment decisions.
