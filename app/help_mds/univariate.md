
Univariate analysis is the simplest form of data analysis where the data being analyzed contains only one variable. Since it's a single variable it doesn't deal with causes or relationships.   

##### T-test

T-test is a parametric statistical hypothesis test in which the test statistic follows a Student's t-distribution under the null hypothesis. This analysis is used when you are comparing two groups. This test assumes the normal distribution of features. T-test results can be visualized in the volcano plot provided at EDA panel.      

  - Equal Variance (or pooled) T-test: The equal variance T-test is used when the variance of the two tested groups is similar.   
  - Unequal Variance T-test: The unequal variance T-test is used when the variance of the two tested groups is different (default). This test is also called Welch's T-test.   

  - Paired T Test: The paired T-test is performed when samples consist of matched pairs of similar units or when there are cases of repeated measures. This method can also applies on cases where the samples are related in some manner or have matching characteristics (default is that groups are not paired).   

##### ANOVA

The analysis of variance (ANOVA) tests the hypothesis that the averages of two or more groups are the same. The ANOVA evaluates the importance of one or more factors when comparing the means of the response variable in the different levels of the factors. The null hypothesis states that all the means of the groups are the same while the alternative hypothesis states that at least one is different. ANOVA is a parametric method that assumes the normal distribution of features.   

If one or more covariates have been included in the target file, an analysis of covariance (ANCOVA) is performed automatically and the results are available at the "ANCOVA Results" tab. The ANCOVA is a general linear model which mix ANOVA and regression. ANCOVA evaluates whether the means of the groups are equal while statistically controlling the effects of other continuous variables that are not of primary interest (as group or treatment), known as covariates.   

##### Mann-Whitney U Test

Mann-Whitney U test is the non-parametric alternative test to the independent sample T-test. It's a non-parametric test that is used to compare two group means that come from the same population, and used to test whether two sample means are equal or not. Usually, the Mann-Whitney U test is used when the assumptions of the T-test are not met. When the study groups are paired, this test becomes a Wilcoxon signed-rank test.         

##### Kruskal Wallis Test

Kruskal-Wallis test is a non-parametric alternative to ANOVA. It is an extension of the Mann-Whitney U test for 3 or more groups. Kruskal-Wallis test does not assume normality in the data, as opposed to the traditional ANOVA.        

