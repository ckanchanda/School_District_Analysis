# School_District_Analysis

## Overview
The purpose of this analysis was to gather data from multiple high
schools across several districts, analyze the passing rates of students' 
reading and math standardized test scores, and determine the overall
school's performance based on funding/budget per student.  


## Results

- In Deliverable 1, we changed the 9th grade reading and math scores
at Thomas High School to NaNs due to inaccurate data. The results are
displayed below
	**insert image**

- In Deliverable 2:
* The average scores and passing percentage in the district summary 
DataFrame changed slightly with the changes made (Changing 9th grade 
THS scores to NaNs) in deliverable 1.
	**insert new and OG District Summary df images)
* The School Summary DataFrame shows the average scores and passing
percentage in relation to the Per Student Budget.
	**insert school summary df image
* Replacing the 9th graders scores at THS improves the overall performace
of Thomas High Schools, making it second on the High Performing Schools.
* Replacing the 9th grade scores affects
	- The Math and Reading Scores by grade was unaffected and the 
	9th graders at THS scores were replaced with NaNs.
	- THS had a higher passing overall percentage than what was average
	in the spending per student category. 
	-THS scores by school size was average for the expected passing rate 
	for a medium sized school. 
		**insert scores_by_school_size image
	- Thomas High School's scores were in line with the average scores
	for its school type (Charter).



## Summary
The overall math and reading scores, math and reading passing percentage, 
and overall passing percentage decreased when I replaced all the 9th graders
at THS scores with NaNs. In addition, the new district summary's scores and
percentages are slightly lower than the originl district summary in the 
PyCity Schools DataFrame. 