# **Students Performance Analysis**

## **Objective :**
The goal of this project was to analyze student's performance in exams based on the given factors that are: 
gender,	race/ethnicity, parental level of education, lunch(type), test preparation course (taken or not), math score, reading score, writing score


## **Analysis:**
To perform the analysis, first I needed to clean the data, perform statistical analysis and finally find meaningful and interesting insights. <br/>

**Some interesting findings :**

1. All three numerical distributions are generally symmetrical or regularly distributed.

2. Statistical analysis using a t-test revealed that men exhibited superior performance in mathematics, whereas women demonstrated superior performance in reading and writing.

3. There is a high positive correlation between the scores. That is, students who flourish in one topic are likely to excel in another. For math/reading, math/writing, and writing/reading, the R-values are 0.80, 0.78, and 0.95, respectively.

![score_correlation](https://github.com/moinul-hossain-dhrubo/Student-Performance-Analysis/assets/122023969/dc3640bb-a9a0-4525-b06b-775cdf7abe43)

4. The similarity of the mean and median in each individual shows that the distributions are symmetric.

5. Comparable levels of variability are shown by similar standard deviations among the three participants.

6. According to T-test results, there is a considerable difference in math, reading, and writing performance between male and female pupils.

![hypothesis_test](https://github.com/moinul-hossain-dhrubo/Student-Performance-Analysis/assets/122023969/f41f578b-98e9-47c5-98ab-9b23798a8ceb)

7. Students seems to perform better when their parents education level is higher.

![average_score_by_parental_education](https://github.com/moinul-hossain-dhrubo/Student-Performance-Analysis/assets/122023969/72cb0896-76d3-46a0-96fd-0d0386e87acc)

**Full analysis can be found in `notebooks/datastudents_performance_in_exams_analysis.ipynb`**


