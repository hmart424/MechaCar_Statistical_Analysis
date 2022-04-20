# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![Screen Shot 2022-04-18 at 5 07 47 PM](https://user-images.githubusercontent.com/95835840/163885467-8f9031bf-3940-419e-80e7-71819b8c6b42.png)

* The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance.
* The Slope of the linear model connot be considered as there is significant variation in the P-Level (5.35e-11) in my opinion the null hypothesis should be rejected.
* The r-squared value of 0.7149 indicates that the model is 71% accurate. Meaning the model does provide some effectiveness although more data could provide a higher r-squared value.

## Summary Statistics on Suspension Coils
![Screen Shot 2022-04-18 at 6 18 42 PM](https://user-images.githubusercontent.com/95835840/163891984-9dad4d6e-2f1d-4e70-8ef8-6057cce0ea56.png)
![Screen Shot 2022-04-18 at 6 18 28 PM](https://user-images.githubusercontent.com/95835840/163892052-edd11080-81a2-4fd2-bcea-9dea08eb4c65.png)

*Lot 1 and 2 meet manufacturing specifications as the variance and Sd are both under 100 pounds while lot 3 is not

## T-Tests on Suspension Coils

![Screen Shot 2022-04-18 at 11 46 39 PM](https://user-images.githubusercontent.com/95835840/163922158-aae14893-1f46-4c7c-9e45-8c1027c1a5f3.png)

* As we can see the overall p-value for lot 1 is (1) which is outside the significance level of 1 as is lot 2 (.6072) The only lot with a p-level under .5 is lot 3. Resulting in a confidence interval of 95 percent. Meaning there is not enough data to reject the null hypothesis. Also the dataset mean and the population mean are statistically similar.

## Study design: MechaCar vs Competition

Our purpose is to design the best possible MechaCar to perform above the general marketplace for vehicles.  
A few metrics to compare include cost, car color, city fuel efficiency, highway fuel efficiency, horsepower, maintenance cost, or safety rating. 

### The data will meet the following metrics:

* All data is to be numerical
* Data samples will be as large as possible
* Data samples need to be randomly selected
* Variance of data needs to be similar

* Null hypothesis -  MechCar is safer than the competition 
* Alternative hypothesis - MechaCar is not safer than the competition 

I would recommend using the t-test to compare dataset with competitors. Using a multiple linear regression statistical summary would show how the variables impact the safety ratings for MechaCar and their competitors. Our t-test will be comparing the population of all types of competitor vehicles.

