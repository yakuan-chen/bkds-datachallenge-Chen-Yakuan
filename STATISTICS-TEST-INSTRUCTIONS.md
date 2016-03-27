##Overview
This test assesses fundamental knowledge of statistics and probability. 

##Instructions
Please use either R or Python to complete this test. Your answers must be presented in a markdown (.md) file that is formatted for 
HTML output.

Answer every question to the best of your ability, and if you don't know the answer, please describe and articulate why. As with most tests, your problem solving method and approach is 
just as important than the end result.

If you need more clarity for any question, please email hello@brooklyndatascience.com. 

Again, please commit your work as you progress through the exercises. 

##Questions

1. The height (cm) of six random people in Williamsburg is sampled as the following: 178, 163, 168, 167, 170, 150
	
	a. Calculate the Five Number Summary: Min, First Quartile (Q1), Sample Median, Third Quartile (Q2), Maximum
	
	b. Calculate the Sample Mean
	
	c. Calculate the Interquartile Range (IQR)
	
	d. Which, if any, of the observations are possible outliers?
	
	e. Create a boxplot of the observations
	
	f. Calculate the sample variance and sample standard deviation

2. Group the following data types as either Metric, Non-Metric, or Inbetween (Metric implies we can calculate a "distance" between any two random observations),
and categorize each one as either Continuous, Nominal/Categorical, Ordinal, or Interval/Discrete.
	
	i. All real numbers 
	
	ii. {First Place, Second Place, Third Place} 
	
	iii. {Green, Blue, Yellow, Brown} 
	
	iv. Five point scale: 1, 2, 3, 4, 5
	
	v. Ranking of attitudes on a 5 point scale: strongly disagree to strongly agree
	
3. What is the "68, 95, 99.7" rule for the Normal distribution?

4. IQ tests are standardized to follow an approximately normal distribution with a mean of 100 and a standard deviation of 16. (i.e., data is N(100 , 16) ). 
	
	a. What percentile is an IQ of 116?
	
	b. Approximately what percent of people will have an IQ score of 90 or less? What is the z-score?

5. There are three cabinets, A, B, and C, each of which has two drawers. Each drawer contains one coin; 
A has two gold coins, B has two silver coins, and C has one gold and one silver coin. A cabinet is chosen at random, 
one drawer is opened, and a silver coin is found. What is the probability that the other drawer in that cabinet contains a silver coin? 

6. A line segment of length 1 is cut once at random. What is the probability that the longer piece is more than twice 
the length of the shorter piece?

7. 10% of the adult population in Brooklyn has the flu virus. Tests are being given at Duane Reade, and the test has 
a false positive rate of 1% and a false negative rate of .03%. Given that a person has a positive test result, 
what is the conditional probability that this person indeed has the flu virus. 

8. On average, a water treatment facility has a critical component failure 2 times per year, Assuming the failures 
follow a Poisson distribution with mean mu = 2 years, What is the probability of having 100 or more critical failures in the next 50 years? 

9. A particular area in Bushwick contains 8000 new apartment units. In a survey of the occupants, 
a simple random sample of size 100 yields the information that the average number of umbrellas per apartment is 1.6 
with a sample standard deviation of .8. 
	
	a. What is the estimated standard error of the sample mean?
	
	b. What is a 95% Confidence Interval for the population average?
	
	c. What is an estimate for the total number of umbrellas, U? 
	
	d. What is the estimated standard error of U?
	
	e. What is a 95% Confidence Interval for the total number of umbrellas? 
	
10. Use the Monte Carlo method to approximate the standard normal density on the interval [0,1]. 
Use at least 1000 randomly generated points.

11. A particular area in Greenpoint contains 7600 residents. Robertas wants to test wheter a new promotion in this area 
will bring an increase in business. Typically, about 310 residents in the targeted area eats at Robertas each month. 
After running the promotion for one month, 350 residents from this area went to eat at Robertas. Was the promotion effective? Explain.

12. Blue Bottle Coffee tested two new brewing methods, A and B, on a batch of single-orign beans to see which one, if any, produces the most caffeine.
Method A was tested 13 times and Method B was tested 8 times. The following table gives the measured amount of caffeine (mg) 
in an 8oz cup of coffee produced under each method. Assuming all observations are independent and the amount of caffeine produced by each method follows a normal distribution, how confident are you that the results between the two methods differ?

	Method A | Method B
------------ | -------------
79.98 | 80.02
80.04 | 79.94
80.02 | 79.98 
80.04 | 79.97
80.03 | 79.97 
80.03 | 80.03
80.04 | 79.95 
79.97 | 79.97 
80.05 | 
80.03 | 
80.02 | 
80.00 | 
80.02 |


13. The following table gives the number of Airbnb guests staying in a Park Slope neighborhood for each month during 2014. 
Is there a seasonal pattern to when guests stay here? That is, are guest bookings uniformly distributed?

  Month | Bookings
------------ | -------------
Jan | 1668
Feb | 1407 
Mar | 1370 
Apr | 1309
May | 1341 
June | 1338
July | 1406 
Aug | 1446 
Sept | 1332
Oct | 1363
Nov | 1410 
Dec | 1526

14. 12 observations on 2 variables X1 and X2 were made

  X1 | X2
------------ | -------------
16 | 8
12 | 10
13 | 6
11 | 2
10 | 8
9 | -1
8 | 4
7 | 6
5 | -3
3 | -1
2 | -3
0 | 0
	
  a. What is the correlation of X1 and X2? Does this seem high enough to warrant Principal Components Analysis (PCA)?
  
  b. If you believe we should implement PCA, calculate the eigenvectors of the covariance matrix associated with X1 and X2?
  	
  c. What is the variance of the principle components?
  	
  d. How much of the overall variability is explained by a single principal component?
