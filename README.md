# CompExam

For question 12, I first started off by converting all of the variables to numbers. I did this by employing sk learns label encoder. Once converted, I created a heatmap of the correlations to see which variables would be best to use to predict BMI. The highest correlated variables were, region, charges and age. 

I then split the dataset and trained it on a linear regression model. I then had it predict 5 variables from the test section just to see if it worked. Once I knew it worked, I then rated it's accuracy using sklearns mse and r^2 scores.

The value I got for the R^2 was only 0.05 which means that it is slightly more accurate than just using the mean BMI. 
The MSE being 32 also indicated that the model was just as good as using the mean and not much else. 

If I had more time to work with this, I would try to fit a logistical regression model, but in order to do that I would need to categorize the bmi and the charges because they are both continuous. 
