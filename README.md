# School_District_Analysis

## Project Overview
The local school board of a city requested an analysis of standardized test scores from the fifteen high schools in the district. The analysis will be used by the school board to make decisions about budgets. The analysis focused on top and bottom-performing schools, average math and average reading scores for each grade level at each school, and school performance based on school size, the type of school, and the budget per student. 

After the initial project was completed, evidence of academic dishonesty was found specifically for ninth graders at Thomas High School. Therefore, the school board asked for the reading and math scores to be replaced with NaNs and then to reanalyze the rest of the data without altering it. 

## Resources
- Data: schools_complete.csv, students_complete.csv
- Python 3.9.7

## Challenge Results
To redo the analysis after removing the reading and math scores for ninth graders at Thomas High School, the analysis was completed in two parts. The first, Deliverable 1, involved replacing the ninth-grade reading and math scores. The second, Deliverable 2, was when the school district analysis was repeated. 

### Deliverable 1 - Replacing Reading and Math Scores for Thomas High School Ninth Graders 

Adjusted Analysis - Snippet of DataFrame 

<img width="644" alt="Deliverable 1" src="https://user-images.githubusercontent.com/103774401/169716727-8230f50a-574a-43fa-aa96-a1b93e727fd3.png">

### Deliverable 2 - Repeating the School District Analysis
The school district analysis was repeated after recalculating the total student count by removing the number of Thomas High School ninth grade students. 

#### District Summary
Overall, the district summary did not change that much once the total student count was recalculated. The scores barely decreased after the Thomas High School ninth grade scores were removed.

Original Analysis

<img width="916" alt="Original District Summary" src="https://user-images.githubusercontent.com/103774401/169716737-cf565bed-125a-4caa-909e-78279ac27a9a.png">

Adjusted Analysis

<img width="944" alt="Adjusted District Summary" src="https://user-images.githubusercontent.com/103774401/169716746-3d83ed35-0989-432a-9f01-e0ce4962ab59.png">

The following changes are observed:
- The average math score decreased from 79.0 to 78.9.
- The average reading score did not change - it remained at 81.9. 
- The passing math percentage decreased from 75% to 74.8%.
- The passing reading percentage decreased from 86% to 85.7%. 
- The overall passing percentage decreased from 65% to 64.9%. 

#### School Summary
Overall, the school summary did not change significantly after excluding the Thomas High School ninth grade scores. 

Original Analysis

<img width="976" alt="Original School Summary" src="https://user-images.githubusercontent.com/103774401/169716756-c286cf1b-3432-4e48-9ae1-b4e97813724e.png">

Adjusted Analysis

<img width="969" alt="Adjusted School Summary" src="https://user-images.githubusercontent.com/103774401/169716764-74447f64-7041-469b-9293-c2665bd4e9f2.png">

The following changes are observed:
- The average math score decreased from 83.42 to 83.35.
- The average reading score increased from 83.85 to 83.90.
- The passing math percentage decreased from 93.27% to 93.19%.
- The passing reading percentage decreased from 97.31% to 97.02%.
- The overall passing percentage decreased from 90.95% to 90.63%.

#### Thomas High School Performance Compared to Other Schools
Even though the average math score decreased and the passing math percentage, the passing reading percentage, and the overall passing percentage decreased, it did not impact Thomas High School's ranking compared to other schools. Thomas High School remained second overall compared to the other schools in the district. 

Original Analysis

<img width="996" alt="Original Top Schools" src="https://user-images.githubusercontent.com/103774401/169716782-04596299-bd3a-48fb-838a-6b29e53b4d84.png">

Adjusted Analysis

<img width="995" alt="Adjusted Top Schools" src="https://user-images.githubusercontent.com/103774401/169716795-2fba61a9-b767-48c2-ae73-05e0f26c5ce0.png">

#### The Effect of Replacing Ninth-Grade Scores

#### Math and Reading Scores by Grade
Before the Thomas High School ninth grade scores were removed, the average math score for ninth graders at Thomas High School was 83.6 and the average reading score for ninth graders at Thomas High School was 83.7. In the revised analysis, their scores were replaced by NaN. 

Original Analysis - Math Scores

<img width="751" alt="Original Average Math Scores" src="https://user-images.githubusercontent.com/103774401/169716804-61290f02-9af5-467f-bdd0-e2e88e0d4e72.png">

Adjusted Analysis - Math Scores

<img width="762" alt="Adjusted Average Math Scores" src="https://user-images.githubusercontent.com/103774401/169716817-fdf2903a-3822-49ad-a7b0-07f93ed7de7a.png">

Original Analysis - Reading Scores

<img width="840" alt="Original Average Reading Scores" src="https://user-images.githubusercontent.com/103774401/169716825-d039ed9a-6952-438a-8f84-f34e2f31a8bd.png">

Adjusted Analysis - Reading Scores

<img width="826" alt="Adjusted Average Reading Scores" src="https://user-images.githubusercontent.com/103774401/169716829-2c35dbaf-0748-4842-993c-b5c0dcbc2616.png">

#### Scores by School Spending
The scores by school spending changed slightly the Thomas High School ninth grade scores were removed. 

Original Analysis

<img width="826" alt="Original Scores by School Spending" src="https://user-images.githubusercontent.com/103774401/169717260-69775911-dc6e-4ebe-beb6-ca27cc6f5666.png">

Adjusted Analysis

<img width="815" alt="Adjusted Scores by School Spending" src="https://user-images.githubusercontent.com/103774401/169716848-1e1b7351-4958-4e4a-96da-7e40e9f2d333.png">

#### Scores by School Size
The scores by school size did not change after the Thomas High School ninth grade scores were removed.

Original Analysis

<img width="756" alt="Original Scores by School Size" src="https://user-images.githubusercontent.com/103774401/169716857-374eaac6-fe0b-4580-9d24-3b5683ae06a6.png">

Adjusted Analysis

<img width="761" alt="Adjusted Scores by School Size" src="https://user-images.githubusercontent.com/103774401/169716867-48657f84-b682-4e83-a3fc-e1a38a46ec80.png">

#### Scores by School Type
The scores by school type did not change after the Thomas High School ninth grade scores were removed.

Original Analysis

<img width="711" alt="Original Scores by School Type" src="https://user-images.githubusercontent.com/103774401/169716880-8cc6ec8f-7d31-4f46-ad21-a4a51db4bfea.png">

Adjusted Analysis 

<img width="709" alt="Adjusted Scores by School Type" src="https://user-images.githubusercontent.com/103774401/169716889-366eea5d-0870-44ed-8af8-a3f41746bd6e.png">

## Challenge Summary
Four main changes can be observed between the original school district analysis and the adjusted school district analysis:
- The overall district average math score, passing math percentage, passing reading percentage, and overall passing percentage decreased. The overall district reading score did not change. 
- For Thomas High School, the average math score, passing math percentage, passing reading percentage, and overall passing percentage decreased whereas the average reading score increased. 
- Although the average math score, passing math percentage, passing reading percentage, and overall passing percentage decreased in the adjusted analysis, Thomas High School remained second overall in the district. 
- The replacement of the Thomas High School ninth grade scores with NaN slightly changed the scores by school spending, but did not change the scores by school size and the scores by school type. 

Overall, replacing the Thomas High School ninth grade scores with NaN minimally changed the scores and percentages.
