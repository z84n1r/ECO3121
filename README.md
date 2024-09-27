java c
Problem Set 1
ECO3121 - Fall 2024
Due 3 PM, October, 11, 2024
Please remember to submit your Stata code for Question 2 (including “.do” file that records commands and “.log” file that records corresponding outputs) as it will be graded.
Question 1
Suppose we are given a sequence of data {yi, xi}ni =1. We are trying to estimate two models.
1. Consider the following model: yi = β0 + µi. Derive the OLS estimator of β0. (2 points)
2. Consider the following model: yi = β1xi + µi. Derive the OLS estimator of β1. (2 points)
Question 2
Download from the blackboard site and load into Stata the Indonesia education and earning data inpresdata.dta. The main data we use is the 1995 intercensal survey of Indonesia (SUPAS), which is a nationally representative large cross section of men born between 1950 and 1972 from the 1995 intercensal survey of Indonesia. It is the main dataset used in the influential paper “Schooling and Labor Market Consequences of School Construction in Indonesia: Evidence from an Unusual Policy Experiment” by Esther Duflo.
Since this will be a univariate model, we’ll be estimating regressions of the form.
wagei = α + β1educationi + µi
First, let’s analyze the effect of years of education on monthly wages.
1. What sign do you predict β1 will have? Why? (1 point)
2. Run the regression and report the estimated coefficients, their standard errors, and R2. Does the estimated value of β1 agree with your prediction? (2 points)
3. Interpret the value of the estimated parameters βˆ0 and βˆ1 from the model. (2 points)
4. Compute the fitted value wagei and the residual ˆµi for each observation, and verify that the residuals (approximately) sum to 0. (1 point)
5. According to the estimated relation, what is the predicted wageifor an individual with an education level of 10 years? (1 point)
6. How much of the variation in wage for these individuals is explained by their educa-tion years? Can you provide some reasons for why education might be lower among rural residents? (2 points)
7. A professor asks you whether they should estimate a linear relationship between wage and education. She asks you to explore alternative functional forms for this relationship. Using 代 写ECO3121 - Fall 2024 Problem Set 1Python
代做程序编程语言the provided data, you estimate the following equations:
* A log-linear relationship: log(wage)i = β0 + β1 educationi + µi
* A linear-log relationship: wagei = β0 + β1 log(education)i + µi
* A log-log relationship: log(wage)i = β0 + β1 log(education)i + µi
We take natural log here. In Stata, the coding is "log(variable)"
Run the regressions recommended by the professor. Interpret the parameters on education years (or log(education years)) in each of these equations. (3 points)
8. Describe the SLR.4 assumption under this case. Do you think that assumption holds? (1 point)
Question 3
A large-landholding farmer outsmarts others by running an experiment to measure the effect of fertilizer application on agricultural yields. She randomly assigns her 400 land plots into two groups. In the first group, she inputs 20 kg/mu of fertilizers, while the other group receives 40 kg/mu of fertilizers. She also keeps other agricultural inputs (water, pesticides, labors) equally between these two groups. Let Yi denote the yields for ith plot, let Xi denote the amount of fertilizer application per unit of land, (Xi = 20 or 40), and consider the regression model Yi = β0 + β1Xi + µi
1. Explain what the error term µi represents. Propose a potential reason that why different plots might have different values of µi? (2 points)
2. Is E[µi|Xi] = 0 in this case? Explain why or why not? (1 point)
3. The estimated regression is Yi = 300 + 0.7Xi + µi.
(a) Is ˆβ1 = 0.7 an unbiased estimator? (1 point)
(b) After you got this estimation, the farmer’s assistant tells you that he is con-cerned that the program may not actually have randomly allocated fertilizer quantity across the 400 plots, and that some cheating may have gone on (he heard that the richest land (land with highest soil quality) were more likely to be put into the more fertilizer group). What concern would this give rise to in your estimation? (1 point)
(c) What additional variable (data) would you like to collect to verify whether the assistant’s concern is true, and what regression specification would you use these data for to investigate whether his concern is true? (3 points)







         
加QQ：99515681  WX：codinghelp
