# Covid_2k19_analysis_R
* For convenience, I will rename the data frame variable to “data.” I will also clear all existing variables, import a library called Hmisc, and use its describe function to better understand our data
* you will see a lot of information in the console. For instance, we have 1085 rows. If we look at the death section, we see that there are 14 distinct values. This may seem a little bit weird, but the death column either has a 0 (no death), 1 (no death), or simply the date of the patient’s death. This is difficult to work with because we want all 0s and 1s
* Let us fix this by adding a death_dummy column to our dataset, which only contains the values 0 and 1
* The media claims that older people are more likely to die than younger people from COVID-19. Is this true? Let us check with our dataset. First, we will subset our dataset into patients who are alive and patients who have died and compare the mean ages
* This will be very similar. We want to see if the death rate is similar for men and women. Let us again split our data and perform the t-test
* Conclusion
As you can see, R helps us perform statistical analysis on important datasets quite easily. Thank you for reading!
