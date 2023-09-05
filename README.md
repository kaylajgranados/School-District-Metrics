# School-District-Metrics

For this project, I used the Python Pandas library to analyze district-wide standardized test results and I aggregated data to show trends in school performance. This was a project for the UCI Data Analytics Bootcamp. 

![education](https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/bad26034-f5ec-4719-bdcd-f56264702897)


# Analysis

I conducted an analysis of school district math and reading scores to ascertain which schools have the highest-performing students on tests. 

# District Summary

To start, I looked at summary statistics at the district level, including the total number of schools, total number of students, total budget, average math score, average reading score, percentage of students passing math, percentage of students passing reading, and percentage of students passing math and reading. 

I used the len and unique functions to count the unique school names. 

<img width="578" alt="Screen Shot 2023-09-04 at 9 50 44 PM" src="https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/8f4b5d9b-5e80-4bd5-9868-2031f0cce48c">

I used the count, sum, and mean functions to calculate the total number of students, total budget, and average math and reading scores. 

<img width="523" alt="Screen Shot 2023-09-04 at 9 53 37 PM" src="https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/65bceda8-4ab6-4f0f-ad0c-c277ae62bb79">


# School Summary
Then, I analyzed data for the distinct schools in the district, creating a data frame with the total number of students, total school budget, per student budget, average math score, average reading score, percentage passing math, percentage passing reading, and percentage passing math and reading. 

I used the loc and groupby functions to determine the percentage of students who achieved passing grades in both math and reading at each school. This allowed me to compute the number of learners with passing grades and then calculate the overall percentage for each school.  

<img width="1077" alt="Screen Shot 2023-09-04 at 9 56 51 PM" src="https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/242f9b56-bf57-471e-936d-ef0ff69eaabc">

I also examined the data based on school grade level. I used loc, groupby, and mean functions to analyze the math scores and the reading scores by grade. 

<img width="679" alt="Screen Shot 2023-09-04 at 10 02 53 PM" src="https://github.com/kaylajgranados/School-District-Metrics/assets/83734241/05c626e5-e029-4b6b-8ef4-04337c9109e3">

# Findings

1. We can conclude that, across all 15 schools, 74.9% of students received passing math scores, 85% received passing reading scores, and 65% received passing math and reading scores. 
3. When we look at the school summary statistics, we can see that Cabrera High School has the highest overall passing percentage, while Rodgriguez High School has the lowest passing percentage.  
4. When we look at the analysis by grade level, we can see that the math and reading scores are consistent across all grade levels at both Cabera High School and Rodriguez High School. 
5. I would recommend focusing on improving the math scores at the schools with the lowest percentage passing, beginning with Rodriguez High School.


