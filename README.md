# School-District-Anaysis

## Overview of Project

The purpose of the analysis is to generate insights from a large dataset of schools within a district using Pandas and Jupyter Notebook.

### Purpose

The purpose of the project is-
* To draw actionable insights from csv files with data about schools and students, using Pandas library with Python and Jupyter Notebook.
* The insights would be further inform district officals about budgeting and other decisions that will bring positive changes in the schools.

## Results

### District Summary

* There are a total of 15 different schools with 39,170 students.
* The total budget of all schools is - $24,649,428.
* The average reading score and percentage across the district is higher than the average math score and percentages.
* The overall passing percentage of students is 64.9%.

![district-summary](https://github.com/divitaN-dev/School-District-Anaysis/blob/main/resources/district_summary.png)


### School Summary

* There are almost as many District schools as Charter schools.
* The budget per student is in the range of $580 - $655, and appears propotinal to student population in schools.
* The overall passing percentages range from 53% - 91%, with Cabrera High School having the highest overall passing percentage.

![school-summary](https://github.com/divitaN-dev/School-District-Anaysis/blob/main/resources/school_summary_overall.png)


### Resulting student performance after replacing the ninth graders’ math and reading scores at Thomas High School

* The overall passing percentage and reading score percentage dropped by 0.3% for grades 10th-12th.
* The math score percentage dropped by 0.1% for grades 10th-12th.
* The ranking of Thomas High School remained same at 2nd after replacing 9th graders scores.
* Thomas high school maintained a high overall pass percentage of 90.6% in the 'scores by spending' category, the overall average of all schools being at 63%.
* In the 'school by size category' and 'school by type' Thomas high school maintained the overall pass percentage at 90.6%, the overall average of all schools being at 91%.

* With ninth graders data -

![ths-before](https://github.com/divitaN-dev/School-District-Anaysis/blob/main/resources/ths_before.png)

* Without ninth-graders data after re-analysis - 

![ths-after](https://github.com/divitaN-dev/School-District-Anaysis/blob/main/resources/ths_after.png)

## Summary

* The math and reading percentages and the overall passing percentage of Thomas High School did not appear to be significantly different after removing ninth grader scores.
