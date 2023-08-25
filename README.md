# School-District-Metrics

For this project, I used Python Pandas library to analyze district-wide standardized test results and aggregated data to show trends in school performance. This was a project for the UCI Data Analytics Bootcamp. 

![education](https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/bad26034-f5ec-4719-bdcd-f56264702897)



# Analysis

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

# Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

# District Summary
Create a high-level snapshot of the district's key metrics in a DataFrame, including the following:

Total schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# School Summary
Create a DataFrame that summarizes key metrics about each school, including the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Highest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the top-5 performing schools based on % Overall Passing. Include the following metrics:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Lowest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the bottom-5 performing schools based on % Overall Passing. Include the following metrics:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Math Scores by Grade
Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# Scores by School Size
Create a table that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
Create a table that breaks down school performance based on school type (district or charter).

# Findings

1. Looking at the District Summary, we can conclude that over the 15 schools, the average reading score (81.9%) is higher than the average math score (78.9%). 
2. When we break the average and math reading scores down further, we can see that Cabrera High School has the highest combined average of math and average reading scores, while Rodgriguez High School has the lowest combined average of math and average reading scores. 
3. When we look closer at both Cabrera High School and Rodriguez High School, we can see that the average math and reading scores are close across all grades.
4. I would recommend focusing on improving the math scores at the schools with the lowest average scores, beginning with Cabrera High School. 
