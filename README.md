# School_District_Analysis

## <font color=#6495ED>Overview of Project</font>
The school board has found out that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered, they want to uphold state-testing standards, which means the math and reading scores for Thomas High School should be replaced with NaNs. Once the replacements are finished, we will repeat the school district analysis and find out how these changes affected the overall analysis.
### <font color=#6495D>Purposes</font>

1. Replace ninth-grade reading and math scores for Thomas High School with NaNs
2.	Give a high-level snapshot of the district's key metrics, presented in a table format
3.	Display an overview of the key metrics for each school, presented in a table format
4.	Display tables presenting each of the following metrics:
    *	Top 5 and bottom 5 performing schools, based on the overall passing rate
    *	The average math score received by students in each grade level at each school
    *	The average reading score received by students in each grade level at each school
    *	School performance based on the budget per student
    *	School performance based on the school size 
    *	School performance based on the type of school


---
## <font color=#6495ED>Resources</font>
* Data Source:
    * schools_complete.csv
    * students_complete.csv
* Software: Python3.9, anaconda3, Jupyter Notebook


## <font color=#6495ED>Results</font>

- In disrict summary, key metrics values are going down slightly
    * Before
    
    ![distric_summary_df_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/distric_summary_df_before.png?raw=true)
    * After
    
    ![distric_summary_df_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/distric_summary_df_after.png?raw=true)
- In school summray, key metrics values for Thomas High School drop a little except average reading score.
    * Before
    
    ![school_summary_df_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/school_summary_df_before.png?raw=true)
    
    * After
    
    ![school_summary_df_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/school_summary_df_after.png?raw=true)
- Thomas High School still ranks second in performance after ninth graders' scores were replaced.
    * Before
    
    ![Top_schools_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Top_schools_before.png?raw=true)
    * After
    
    ![Top_schools_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Top_schools_after.png?raw=true)
- Replacing the ninth-grade scores doesn't affect other grades' scores for Thomas High School.
    * Math scores by grade before replacement.
    
    ![math_scores_by_grade_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/math_scores_by_grade_before.png?raw=true)
    * Math Scores by grade after replacement.
    
    ![math_score_by_grade_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/math_score_by_grade_after.png?raw=true)
    * Reading scores by grade before replacement.
    
    ![reading_scores_by_grade_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_before.png?raw=true)
    * Reading scores by grade after replacement.
    
    ![reading_scores_by_grade_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_after.png?raw=true)
- Math score is lower while reading score is higher in the range of school spending between $631 and $645 where Thomas High School falls in.
    * Before
    
    ![Scores_by_school_spending_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_spending_before.png?raw=true)
    * After
    
    ![Scores_by_school_spending_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_spending_after.png?raw=true)

- Math score is lower while reading score is higher in the range of school size between 1000 and 1999 where Thomas High School falls in.
    * Before
    
    ![Scores_by_school_size_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_size_before.png?raw=true)
    * After
    
    ![Scores_by_school_size_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_size_after.png?raw=true)
- Math score is lower while reading score is higher by charter school to which Thomas High School belongs.
    * Before
    
    ![Scores_by_school_type_before](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_type_before.png?raw=true)
    * After
    
    ![Scores_by_school_type_after](https://github.com/NingYang2022/School_District_Analysis/blob/main/Resources/Scores_by_school_type_after.png?raw=true)

  ## <font color=#6495ED>Summary</font>  
  There are four changes in the updtaed analysis after reading and math scores for ninth grade at Thomas High School have been replaced with NaNs.
  * In disrict summary, key metrics values are lower than before
  * In school summray, key metrics values for Thomas High School drop a little While average reading score goes up.
  * Math scores are lower than before by school spending, school size and school type
  * Reading scores are higher than before by school spending, school size and school type
