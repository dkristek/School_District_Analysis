# School District Analysis
## Overview
In the PyCitySchools Jupyter Notebook an analysis on all of the high schools in a given district was performed to compare testing scores using various metrics. It was determined that one of that the 9th grade students at one of the schools were academically dishonest. In the 'PyCitySchools_Challenge' Jupyter Notebook the falsified scores were replaced with 'NaN' in the dataset and the analysis was ran on the cleaned data. This ReadMe will discuss how removing those datapoints affected the results.
## Results
* District Summary
  - Original:
  ![District Summary Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/district_summary.png)
  - Adjusted:
  ![District Summary Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/district_summary_cleaned.png)
  - The district summary, which averages the grades of all the schools in the district, is not affected by the removal of the Thomas High School Ninth graders. There are less than 500 ninth graders at Thomas High School while the district has nearly 40,000 students. Removal of such a small amount of samples negligibly impacts the average.
* School Summary
  - Original:
  ![School Summary Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/school_summary.png)
  - Adjusted
  ![School Summary Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/school_summary_cleaned.png)
  - For the school summary there are slight changes in the grades for Thomas High School. The average reading score increased by 0.1 grade points, the percent of students passing math decreased by 0.1, the percentage of students passing reading decreased by 0.3, and the overall passing percentage decreased by 0.3.
* Thomas High School's relative performance
  - Top Five Schools Original
  ![Top Five Schools Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/top_schools.png)
  - Top Five Schools Adjusted
  ![Top Five Schools Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/top_five_schools_cleaned.png)
  - Thomas High School's position as the second best performing school in the district is unaffected by the removal of their ninth graders.
* Math and Reading Scores by Grade
  - Math Scores Original
  
  ![Math Scores Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/math_scores_grade.png)
  - Math Scores Adjusted
  
  ![Math Scores Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/math_scores_grade_cleaned.png)
  - Reading Scores Original
  
  ![Reading Scores Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/reading_scores_grade.png)
  - Reading Scores Adjusted
  
  ![REading Scores Adjsuted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/reading_scores_grade_cleaned.png)
  - By removing the ninth graders' scores from the data the reading and math scores by grade are now gone from the adjusted data.
* Scores by Spending
  - Spending Original
  ![Spending Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/spending_summary.png)
  - Spending Adjusted
  ![Spending Adjusted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/spending_summary_cleaned.png)
  - Thomas High School is in the $630-644 range. The Average grades remained the same, however, the percent passing reading and percent passing overall both decreased by 0.1 with the removal of the ninth graders's scores.
* Scores by Size
  - Scores By Size Original
  ![Scores By Size Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/size_summary.png)
  - Scores By Size cleaned
  ![Scores By Size Cleaned](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/size_summary_cleaned.png)
  - Thomas High School is in the 1000 - 2000 population range. The only metric that changed was that the percentage passing reading decreased by 0.1
* Scores By School Type
  - Original
  
    ![Scores By School Type Original](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/type_summary.png)
  - Adjusted
  
    ![Scores By School Type Adjsuted](https://github.com/dkristek/School_District_Analysis/blob/main/Resources/type_summary_cleaned.png)
    
  - Thomas High School is a charter school. As this is a larger grouping of schools than the spending group and the size group, the metrics were not changed at all with the removal of the Thomas High School ninth graders.

## Summary
By replacing Thomas High School's ninth graders' scores with 'NaN' several changes in the metrics occurred. In the school summary the average reading score increased by 0.1 grade points, the percent of students passing math decreased by 0.1, the percent of students passing reading decreased by 0.3 and the overall passing percentage decreased by 0.3. In the scores by school size table the percentage passing reading in the 1000-2000 population bin, the percentage passing reading decreased by 0.1. In the scores by spending table, the percentage passing reading and the overall passing percentage in the $630-$644 range both decreased by 0.1. Finally, in the socres by grade tables the 9th grade math and reading grades in the Thomas High School row were replaced with NaN as all the data for the school was removed.
