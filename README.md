# ML_Trading-Algo
Trading Algo using sklearn, Log Regression, SVC, and scaler to train my datasets.

As I work through the models hoping to increase speed and accuracy I noticed the training end period impacted the accuracy of the models.

When I set my Simple Moving Average(SMA) dates to 5/13 in 3 months, .72 is the F1-Score with 2327 examples belonging to this class. 
SMA 5/13 in 6months, .72 is the F1-Score with 2277 examples belonging to this class.
SMA 4/100 in 6months, .72 is the F1-Score with 1838 examples belonging to this class.
SMA 4/100 in 12months, .72 is the F1-Score with 1931 examples belonging to this class.
SMA 20/100 in 3 months, .72 is the F1-Score with 2288 examples belonging to this class. 

SMA 4/100 in 12 months had the highest correlation
![image](https://user-images.githubusercontent.com/119983738/230537345-9c5b575d-ec9f-4d60-9c11-0c43b8ed66c8.png)







SMA 5/13 in 3 months
![image](https://user-images.githubusercontent.com/119983738/230538321-a881a86f-a451-4275-97af-daa83fb05cc7.png)
