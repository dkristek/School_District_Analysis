# School District Analysis
## Overview
In the PyCitySchools Jupyter Notebook an analysis on all of the high schools in a given district was performed to compare testing scores using various metrics. It was determined that one of that the 9th grade students at one of the schools were academically dishonest. In the 'PyCitySchools_Challenge' Jupyter Notebook the falsified scores were replaced with 'NaN' in the dataset and the analysis was ran on the cleaned data. This ReadMe will discuss how removing those datapoints affected the results.
## Results
* District Summary
  - Original:
  ![District Summary Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/district_summary.png)
  - Adjusted:
  ![District Summary Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/district_summary_cleaned.png)
  -The district summary, which averages the grades of all the schools in the district, is not affected by the removal of the Thomas High School Ninth graders (**get pic with rounded percents**). There are less than 500 ninth graders at Thomas High School while the district has nearly 40,000 students. Removal of such a small amount of samples negligibly impacts the average.
* School Summary
  - Original:
  ![School Summary Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/school_summary.png)
  - Adjusted
  ![School Summary Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/school_summary_cleaned.png)
* Thomas High School's relative performance
  - Top Five Schools Original
  ![Top Five Schools Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/top_schools.png)
  - Top Five Schools Adjusted
  ![Top Five Schools Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/top_five_schools_cleaned.png)
  - Thomas High School's position as the second best performing school in the district is unaffected by the removal of their ninth grades
* Math and Reading Scores by Grade
  - Math Scores Original
  
  ![Math Scores Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/math_scores_grade.png)
  - Math Scores Adjusted
  
  ![Math Scores Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/math_scores_grade_cleaned.png)
  - Reading Scores Original
  
  ![Reading Scores Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/reading_scores_grade.png)
  - Reading Scores Adjusted
  
  ![REading Scores Adjsuted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/reading_scores_grade_cleaned.png)
* Scores by Spending
  - Spending Original
  ![Spending Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/spending_summary.png)
  - Spending Adjusted
  ![Spending Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/spending_summary_cleaned.png)
* Scores by Size
  - Scores By Size Original
  ![Scores By Size Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/size_summary.png)
  - Scores By Size cleaned
  ![Scores By Size Cleaned](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/size_summary_cleaned.png)
* Scores By School Type
  - Original
  ![Scores By School Type Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/type_summary.png)
  - Adjusted
  ![Scores By School Type Adjsuted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/type_summary_cleaned.png)
  
