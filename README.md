# pandas-challenge Week 4 Challenge Assignment

                    REPORT ON PYSCHOOLS CITY DATA ANALYSIS
The PyCity Schools assignment included a review and analysis of data for 15 schools, comprising of 39,170 students.
The dataset was analysed along the following lines:

    1. District Summary highlighting the total budget, average math and reading scores, as well as percentage of students who passed either subject and percentage of students which passed both.
    2. School Summary highlighting the total number of students per school, budget per student, average test scores per school, number of schools with passing rates above 70  and overall passing rates.
    3. Highest and Lowest performing schools by overall percentage pass rates.
    4. Scores by school spending (budget).
    5. Scores by School size (student population), and finally
    6. Scores by School type (District vs Charter)
    
    
The analysis revealed some very interesting conclusions, two of which were:

    1. The top 5 performing schools by overall passing percentage rate were all charter schools while the lowest 5 performing schools were district schools. Interestingly, the budget per student was higher in the lowest performing schools than in the highest performers.
    
    2. School size is a major contributing factor to the overall passing rate of schools, as the top performing schools fall in the small and medium student population categories. The ideal student population size appears to be around 1650 students (which is the average size of the top performing schools). All the low performing schools belong to the large category, with their average student population being around 3,850 students.
    
    
Notes to the Grading Team:    
- There was a type error in line 34 of my code, (per_school_summary) and when I reached out to the Learning Assistant, he suggested removing the square brackets which fixed the issue.
- I encountered a key error in line 41, (school_spending), and the Learning Assistant explained that I needed to pick the data from a previous series with an integer data type. The one I'd been referencing had been formatted to a string when I added $.
 - I had used the groupby method instead of the set index method to get school_types in line 17 which caused line 50 to error, and got help from a Learning Assistant to resolve it.