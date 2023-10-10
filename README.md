# 🙋‍♂️ Support
If you like this project, give it a ⭐ and share it with friends!

# Here is the explanation of the project.......
## Value at risk (VaR):

* Value at risk (VaR) is a way to quantify the risk of potential losses for a firm or an investment.

* This metric is most commonly used by investment and commercial banks to determine the extent and probabilities of potential losses in their institutional portfolios. Risk managers use VaR to measure and control the level of risk exposure.

* There are 3 components to a VaR measurement. 
 1) A time Frame
 2) A confidence Level
 3) A Loss Amount

* Here I am showing at 99 % confidence level, what is the most amount or percentage that can be expected to be lost on the investment over the next month.

* This metric can be computed in three ways: the historical, variance-covariance, and Monte Carlo methods. In this project, I use Monte Carlo method to calculate VaR.

* The Monte-Carlo method envolves developing a model and using that to predict to future investment prices and using that data do an testical analysis to determine the worst case loss in the investment. 

* Here the resulting Z-score tells us how many standard deviations a data point is away from the mean. A positive Z-score indicates that the data point is above the mean, while a negative Z-score indicates that it's below the mean. A Z-score of 0 indicates that the data point is exactly at the mean.

* In the context of the code, log returns are calculated from historical stock prices to represent the daily performance of each stock. These log returns are then used to estimate potential portfolio gains or losses through Monte Carlo simulations, which are an effective way to model various market scenarios. By using log returns in these simulations, the code aims to provide a more accurate understanding of the potential risks and rewards associated with the portfolio.

![VaR-Pict01](https://github.com/i-am-surovi/mat120-project-bracu/assets/117065226/dc711a36-1b7e-47a2-a60c-0d354f8296dc)
