# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    All wheel drive, vehicle weight, and spoiler angler all had a non random amount of variance in relation to the mpg values.  
Is the slope of the linear model considered to be zero? Why or Why not?
    No because the co-efficients for each variable are not zero, so the slope of the linear regression is not zero.  
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
    With an Rsquared value of 71, this means that we can predict the mpg of a car using these variables 71% of the time.  While that still leaves a wide margin of error, that is still a reasonable tool to use.  The addition of other variables would lilely make the tool have a higher Rsquared value.
    
## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not
    Lot 1 and Lot 2 are both within design specifications and have the same mean and median. Lot 3 shows more variance and exceeds the given manufacturer design specifications.
    
## T-test on suspension coils
Lot 1 pvalue =1, so we cannot reject null hypothesis
Lot 2 pvalue =.6072, so we cannot reject null hypo
lot 3 pvalue = .04, so we can reject the null. 

## study design
While people who shop for cars likely weigh mpg highly when purchasing a new vehicle, there are several other factors a customer may take into account.  These considerations begin with who your target customer base is, which is also likely correlated to the model of the car being purchased. Holding all things equal (no significance in price or mpg compared to competitors), a big distinguisher between the MechaCar brand and others would be safety features.

Similarly to how we determined which features are correlated to a car's mpg, we would need to determine which features of a car would have a non-random amount of cariance in relation to safety ratings.  This would be done by acquiring a large pool of data for several different mechacar features and competitors features.  Linear regression and subsequent summary statistics would provide coefficients that would tell us which variables are related to safety.  We would then perform a t.test on those categorical features (say, break traction in inclimate weather) to determine if there is any statistical significace between means of Mechacar's safety and competitors safety.
