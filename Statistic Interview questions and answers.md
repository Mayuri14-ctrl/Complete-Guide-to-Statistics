Q1 What are different types of Statistics?
Descriptive Statistics
We describe the data using its mean, variance and distribution
Inferential Statistics
We estimate population by making assumptions using samples or hypothesis testing to assess our assumptions

Q2 What are the different Data Types and Level of Measurement?
Conitnuos data
Discrete data
Nominal data : Nominal Scale: This scale contains the least information since the data have names/labels only.
ordinal data : Ordinal Scale: In comparison to the nominal scale, the ordinal scale has more information because along with the labels, it has order/direction.
Example: Income level – High income, medium income, low income.

Q3 what are the Measures of Central tendency?

Q4 what are the Measures of Dispersion?
Varinance, Range, SD
Q5 Whare the measures of SKewness
Positive skew when most of the data is on left side and there is tail on right side. mean>median
Negative skew when most of the data is on right side and there is tail on left side. mean<median
Q6 Kurtosis
Q7 What is Central Limit Theorem and why is it important?
1. It helps in inferential statistics by enabling as to make approximation about popoulation based on sample data
The distribution of sample means (from any population) will be approximately normal if the sample size is large enough (
𝑛≥30
2. It justifies parametrics test (like z test t test ). It can make use of sample mean , so it assumes sample mean is normal
3. Helps in Constructing Confidence Intervals: 
4. Useful for hypothesis testing
   
5. It helps in calculating probability for population
   Example:
A university claims the average exam score is 70 with a standard deviation of 10. If we take a sample of 50 students, what’s the probability that their average score is below 67?
Compute standard error 10/sqrt(50)
z score= 67-70/ se
p value


Q8 what are Probability distributions: it is the all probability of all possible outcomes of a variable
Q9 What is Bernolli distribution: There are only two possible outcome: A Fair coin
Q10 What is Binomial distribution: When a experimented is repeated over number of times and all are independent, A coin is tossed 10 times
Q11 What is Poisson's distribution: Probabiliy of number of event over a fixed period of time. No of customers call per minute
Continuous Distribution
Q12 What is Normal Distribution
Q13 what is exponential distribution: model the time between two events. If a store receives customers at a rate of 10 per hour , the probability that the next customer arrives after 10 minutes is:
A14 What is uniform distribution: All values in a given range are equally likely
Q12 What is A/B testing
A/B testing is an experiment where two versions (A & B) of a webpage, feature, or product are compared to determine which performs better based on statistical evidence.

Q13 What is Hypothesis
Q14 What is the difference between Type I and Type II errors?
Type I -FP-Precision
Type II FN -Recall

Q15 What is Pvalue 
probility of getting values as extreme as obeserved when null hypothesis is true

Q16  What is Bayesian Statistics? How is it different from Frequentist Statistics?

Q17 What is t test and z test
t test is when population variance is unknown and sample size <30
var=sum((x-m)**2 for x in data)/len(data)
SD=sqrt(var)
t_stat=(x_mean-pop_mean)/(SD/n**0.5)

How do you manually perform a two-sample t-test to compare means of two independent samples?
((s1**2)/n)+((s2**2)/n)**0.5

Manual Calculation of Z-Test and T-Test for Proportions
(p1-p2)/SE
pooled proportion=(x1+x2)/(n1+n2)
SE=(pool(1-pool)*(1/n1+1/n2))**0.5
1. t-test, based on t distibution, check degree of freedom, at Alpha=0.05 significance level, critical value of z score is +-2.045,we fail to reject 𝐻0
   df=min(n2-1,n1-1)
3. for z test , at Alpha=0.05 significance level, critical value of z score is +-1.96,we fail to reject 𝐻0
   
Q18 paired vs. unpaired t-test?
Q19 What is ANOVA, and how does it differ from a t-test?

Q20 What is the difference between one-way and two-way ANOVA?
Q21 What is a Chi-square test, and when is it used?
Q22 What is a Mann-Whitney U test? How does it differ from a t-test?
Q23  What is the Wilcoxon Signed-Rank Test?
Test Type                     	         Parametric Test	                             Non-Parametric Alternative
Compare Means (2 groups)               	t-test	                                     Mann-Whitney U test
Compare Means (3+ groups)	              ANOVA	                                       Kruskal-Wallis test
Check Relationship (Correlation)	      Pearson Correlation	                       Spearman Correlation
Check Relationship (Categorical Data) 	Chi-Square Test	                       Fisher’s Exact Test

7. How do you decide which statistical test to use?
   
 
