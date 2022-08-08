# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
The vehicle length and ground clearance have p values that are below the 0.05 signifcance level and therefore we can conclude that these factors have the most impact on the mpg. The summary includes that the overall p value is 5.35e-11 and this is also below the 0.05 signoficance level. Therefore there is enough evidence to reject the null hypothesis, which was that the slope of the linear model is zero. The alternative hypothesis is the slope is not zero. Finally, the r squared value is 0.71 which means that the model accounts for 71% of the variablility. The p value is statistically significant with a high r square value therefore this model is effective in predicting the mpg outside the data set. 

<img width="507" alt="Screen Shot 2022-08-07 at 12 00 07 PM" src="https://user-images.githubusercontent.com/102255823/183301215-9498f638-3c0f-4190-814a-69a82b9ffdde.png">

## Summary Statistics on Suspension Coils
From the total summary, we can see that the variance is 62.29 which is below the requirement. However, under the lot summary, we see that the variance is 170.29 for Lot 3. Therefore lot 3 does not meet the requirements of having a variance less than 100 PSI. 

<img width="361" alt="Screen Shot 2022-08-07 at 12 29 21 PM" src="https://user-images.githubusercontent.com/102255823/183301307-0f8ce9a8-6333-4a7a-98d8-fd8b347c0951.png">

<img width="496" alt="Screen Shot 2022-08-07 at 12 29 50 PM" src="https://user-images.githubusercontent.com/102255823/183301315-8e21b446-0cc8-42ca-ab76-85719a9faa5c.png">

## T-Tests on Suspension Coils
The one sample t test determines a statistically significant difference between the mean of the sample versus the mean of a hypothetical population. The null hypothesis being tested is that there is no statistical difference between the observed mean and the presumed population mean. For the first t test the null hpothesis is there is no statistical mean difference between the PSI of all the lots versus the population mean of 1500 PSI. The output gave a p-value less than 2.2e-16 which is less than the 0.05 significance level. Therefore we have sufficent evidence the reject the null hypothesis and state that the sample mean is statistically different to the population mean. 

<img width="418" alt="t-test_PSI_ss" src="https://user-images.githubusercontent.com/102255823/183458252-a0f41a88-9390-4211-b591-07a63e02efd8.png">

Then each lot average PSI was tested against the presumed population mean of 1500. Testing each lot against the population mean showed the same p values of less than 2.2e-16. Which means that each lot's mean is statistically different than the presumed population lot of 1500 PSI. 

![ttest_LOT1_ss](https://user-images.githubusercontent.com/102255823/183459859-b587e4d1-d97e-4350-a46a-f25187b1a868.JPG)
![ttest_LOT2_ss](https://user-images.githubusercontent.com/102255823/183459873-bf086463-c45e-424b-add4-fa7b5ebeae68.JPG)
![ttest_LOT3_ss](https://user-images.githubusercontent.com/102255823/183459888-7d3f5a14-b8ab-4419-bb4a-95d7af9aeea5.JPG)


## Study Design: MechaCar vs Competition
In order to compare MechaCar against a competitor a two samplehypothesis test can be used. The null hypothesis is that there is no difference between the parameters of the two populations. The alternative hypothesis is that there is a difference between the groups. If we test the difference btween means we can use the mpg parameter to see if the two companies are as fuel effecient. Or we can also compare other parameters. Overall this can show if Mechacar is within the range to be competition against other companies. 
