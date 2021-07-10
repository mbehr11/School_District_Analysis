# School_District_Analysis
python week 4
# School_Distict Analysis
An analysis of election data using Python with Pandas and Jupyter notebook

## Overview of School_District Audit:
After working with the Maria and the school board to look at the academic grades in reading and math versus funding across the district, discrepancies were discovered. The analysis showed that Thomas High School has been lying about the 9th grade class scores in math and reading. After discussing with the school board, they wanted us to change the altered math and reading scores and re-run the analysis.
#### The below pseudocode provided us an outline for the analysis: 

1.	The data we need to retrieve.
2.	The district summary.
3.	The school summary
4.	The top 5 and bottom 5 preforming schools, based on overall passing grade. 
5.	The average math score for each grade level from each school.
6.	The average reading score for each grade level from each school.
7.	The scores by school spending per student, by school size and by school type.

### School_District_Audit Results:

•	How is the district summary affected?
The overall passing number is brought down to a 64.9%.
##### ![alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/district%20summary.PNG) #####
•	How is the school summary affected?
##### ![alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/district%20summary.PNG) #####
There is no longer a correlation between budget and performance. 
•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
•	It does not give a true reading of how the resources and funds affect students school grades. 
##### ![alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/TH-Summary.PNG)####
•	How does replacing the ninth-grade scores affect the following:
•	Math and reading scores by grade: 
•	Bailey High School continues to come out on top for reading and math and they have the highest school budget.
•	Scores by school spending: However, we can see Bailey has the worst overall performance. Furthermore, as you can see by the second picture, the schools who had the best overall passing score was <$584.
##### ![ alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/district%20summary.PNG) #####
##### ![ alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/spending_ranges.PNG) #####

•	Scores by school size: This analysis further supports my conclusion above because as you can see from the image below schools that had <1000 students had the best overall passing score of 89.9
•	##### ![alttext](https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/school_size.PNG) #####
•	Scores by school type;
This continues to support my conclusion that the larger district schools do not produce the best test scores. In fact, you can see that charter schools did best with an overall passing of 87% vs the 54% in district schools.
##### ![ alttext]( https://github.com/mbehr11/School_District_Analysis/blob/main/Resources/school_type.PNG) #####

## School Analysis Summary:
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
We can conclude that after the updated analysis that charter schools with budget of less than $584,000 and catered to a school size of 1000 students or less has the best success.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
