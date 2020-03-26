# LMA_Econometrics
Labour Market Analysis (Econometric)

Gender Pay Gap Increased By Among Multilingual Workers:
Indicative of Discrimination Against Immigrants and Woman

### Data
pulled from the American Community Survey (ACS) from the year 2017 for the state of Texas

Descriptive statistics

![image](https://user-images.githubusercontent.com/55430338/77609638-bc0cba80-6edd-11ea-8a3b-ff201a4e200e.png)

From a dataset with 265,842 observations and 286 variables, we limited our sample size to 107,181 observations and 30 variables.

### Prerequisite
R

## Intro

With the increasing diversification in the United States and many corporations going multinational, we see that the economic and business landscapes are changing. Although it’s might be common knowledge that being bilingual gives the individual more advantages in the job market, we can see an earning gap between many non-white and immigrant workers and their white counterparts. There have been many research papers suggested there is a slight premium in the labor market for English speakers who can speak another language, however, it is not very clear how the labor market outcomes for people whose native language is not English and only have acquired English as their second language (Gandara, 2015). Through this study, we would like to see whether it is true that being multilingual really brings advantage to annual earning and how the gender gap persists in this intersection of segments. 

## Modeling 
Regressing our independent variables against the logarithm of earnings allowed reduced our variance and removes the majority of our heteroskedastic distribution, though not all. 


Table1:
![image](https://user-images.githubusercontent.com/55430338/77609780-27568c80-6ede-11ea-8426-cd813f52b6d1.png)


Table2:
Initial Robust Model and Coefficients Corrected for Heteroskedasticity ~ Not Separated for Gendered Interaction Effects
![image](https://user-images.githubusercontent.com/55430338/77609813-389f9900-6ede-11ea-87f9-e585a01763b5.png)


Table 3: 
Comparison of Female and Male Robust Models Corrected for Heteroskedasticity
![image](https://user-images.githubusercontent.com/55430338/77609853-5a008500-6ede-11ea-911e-63fe31842aa0.png)


Table 4: 
Interpretation of Robust Models' Coefficients ~ the percentage change in earnings
![image](https://user-images.githubusercontent.com/55430338/77609875-697fce00-6ede-11ea-8cdf-41f489cbdccd.png)

## Conclusion
Through our results, it is clear that being multilingual is not a beneficial skill and that workers are penalized for it. What’s more concerning is that the gender pay gap seems to widen for multilingual workers. The probability of these individuals being immigrant workers is high enough that this is most likely an indicator of discrimination against immigrants as well. While policy already protects individuals from being discriminated against, it is clear that Texas does not uphold these constitutional rights as it should.




