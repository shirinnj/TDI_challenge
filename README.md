# TDI_challenge project documents

In summary what I have done so far is reading Yahoo stock prices for 100 stocks (the sampling period is 2009 to 2016) and created 22 most famous technical indicators
and used them as features for training machine learning models to predict future stock returns. I have anonymized the identity 
of the entities and applied generic labels so that I can approach this problem as a pure machine learning type exercise. 
So far, I used linear regression, Adaboost regression and Decision tree methods. 
I researched the prediction accuracy of the models for daily analysis and uploaded two plots (for Adaboost regression accuracy result).

While for most it lies in the range of 55%-60%, for a few it is a tremendous 70-80%, which I found very 
surprising. For example, for stock #907834. It has a slight negative autocorrelation, with a value of -6% for 1 step lag, 
-3% for 2 step lag, and continues to move to 0. After running the code several times, I see about 5 stocks with great accuracy level (more than 70%), and about half that were in the more reasonable range 50-60%, which could still be useful. The graphs are actually 20day averages of the daily accuracy, as otherwise the variability made it too hard to read the graph. 

Next step would be using 

 
