# TDI_challenge
TDI challenge project documents
In summary what I have done so far is reading Yahoo stock prices for 100 stocks (2009 to 2016) and created 22 most famous technical indicators
and used them as features for training machine learning models to predict future stock returns. I have anonymized the identity 
of the entities and applied generic labels so that I can approach this problem as a pure machine learning type exercise. 
So far, I used linear regression, Adaboost regression and simple neural network methods. 
I researched the prediction accuracy of the models  for minute analysis and uploaded two plots (for Adaboost regression accuracy result).
While for most it lies in the range of 55%-60%, for a few it is a tremendous 70-80%, which I found very 
surprising. For example, for stock #907834. It has a slight negative autocorrelation (for minute analysis), with a value of -6% for 1 step lag, 
-3% for 2 step lag, and continues to move to 0. 


However, looking at the average daily accuracy of the model, i.e. the percentage of minute returns that it managed to predict 
correctly as being up or down during a day, and it lies in the above mentioned range of 70%-80%. But is a huge prediction 
power, I mean to be able to predict 70% of the time whether a stock will go up or down in the next minute, is too good I think.
After running the code several times I see about 5 stocks with great accuracy level, and 
about half that were in the more reasonable range 50-60%, which could still be useful. The graphs are actually 20day averages 
of the daily accuracy, as otherwise the variability made it too hard to read the graph. 

 
