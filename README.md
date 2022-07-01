# School_District_Analysis

### Project Overview
The school board has notified that the "students_complete.csv" file shows evidence of academic dishonesty on "reading" and "math" grades for Thomas High School ninth graders which appears to have been altered.

Also, the school board does not know the full extent of the academic dishonesty, so they want to hold on state-testing standards and need help to solve this problem. Their requirement is to make Thomas High School with NaNs, so that rest of the data will remain intact.

### Purpose
The purpose of this project is to analyze the School District data on basis of school budget, student scores as per their grades and to learn new insights which will give us clear view of results on each school's performance.

### Requirements:
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size
- School performance based on the type of school

### Resources
- Jupyter Notebook
- Python 3.7.6
- Dependencies
  - Python Pandas library
  - Python Numpy library

### Results:

How is the district summary affected?

  - All scores changed by less than 0.5 percentage points(or changed by less than 0.5%) - there is no changes on school or student count.

  - The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN.

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Disctrict%20Summary.png)


How is the school summary affected?

  - No changes according to ranks , but Thomas High School's scores did change by less than 1 percentage point (or changed by less than 1%) for each metric.

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/School%20Summary.png)


Top 5 performing schools:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Top%205%20Performing%20Schools.png)


Bottom 5 performing schools:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Bottom%205%20Performing%20Schools.png)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - The overall passing percentage for Thomas High School fell to 65%
  - The overall passing percentage for the entire district fell to 64.9%
  - Thomas High School was no longer included on the list of top five schools.

How does replacing the ninth-grade scores affect the following:

  - The overall passing percentages of Thomas High School decreased by 0.11%
  - The average scores of Thomas High School for math and reading increased by 0.06%
  - For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
  - School rankings are unchanged. Thomas High School is still the second-best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

Math scores by grade:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Math%20Scores%20By%20Grade.png)


Reading scores by grade:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Reading%20Scores%20By%20Grade.png)


Scores by school spending:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Scores%20By%20School%20Spending.png)

 
Scores by school size:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Scores%20By%20School%20Size.png)


Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

Scores by school type:

![School_District_Analysis](https://github.com/Lauramasonjar/School_District_Analysis/blob/main/Scores%20By%20School%20Type.png)


Scores by School Type - changes to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

### Summary:
After replacing reading and math scores to NaN for the ninth grade at Thomas High School, some changes occurs in the School district analysis:

- Replacing the ninth graders' scores with NaN, Thomas High School's overall passing percentages and average scores change abruptly.

- The district has had its average math and reading scores decrease, as well as the overall passing percentage for students.

- Thomas High School lost its ranking as a top five school within this District.

- After updating the total student counts and excluding it to the Thomas High School ninth graders and removing their scores from the school data, Thomas High School again reach to its high average scores and regained its position as the number two school in the District.


