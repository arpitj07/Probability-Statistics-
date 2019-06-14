# Probability-Statistics


### T-test vs F-Test [[Here](https://www.researchgate.net/post/What_is_the_difference_between_T-test_F-Test_and_anova_tests_in_statistics)]

   A t-test is used to examine the differences between the means of two groups. For example, in an experiment you may want to compare the overall mean for the group on which the manipulation took place vs a control group.
   
   However, if you have more than two groups, you **shouldn't** just use multiple t-tests as the error adds up (see familywise error) and thus you increase your chances of finding an effect when there really isn't one (i.e. a type 1 error).Therefore when you have more than two groups to compare e.g. in a drugs trial when you have a high dose, low does and a placebo group (so 3 groups), you use **ANOVA** to examine whether there any differences between the groups.
   
   To examine whether there are differences between the groups you would use the F-ratio, which essentially measures the improvement due to fitting the model i.e. the group means versus the grand mean of scores for all participant and compares this against the error remaining in the model, which is the difference between the actual scores and the respective means of the groups. Therefore, the F-test is the ratio of systematic variance : unsystematic variance, so higher scores are better.
   
   Going a little beyond your question, an ANOVA only tells you that there are differences between your groups, not where they lie. Therefore you would use a priori contrasts to test hypothesised differences between the groups or post-hoc tests to examine where the differences lie.

[watch this video](https://www.youtube.com/watch?v=SULO2-gjZoY)


### P-value in Regression [[Here]()]

   - [watch Video](https://www.youtube.com/watch?v=6psBul7K2gw)



- **Useful Links**
   - [ANOVA (One Way Vs. Two Way)](https://medium.com/@StepUpAnalytics/anova-one-way-vs-two-way-6b3ff87d3a94)
   - [Regression Analysis: How Do I Interpret R-squared and Assess the Goodness-of-Fit?](https://blog.minitab.com/blog/adventures-in-statistics-2/regression-analysis-how-do-i-interpret-r-squared-and-assess-the-goodness-of-fit)
   - [Statistical tests](https://towardsdatascience.com/statistical-tests-when-to-use-which-704557554740)
   - []()
