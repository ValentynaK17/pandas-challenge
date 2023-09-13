# pandas-challenge
Manipulations with Pandas DataFrames to analyze school and standardized test data
This repository contains Jupyter Notebook script to analyze the district-wide standardized test results in order to help the school board and mayor make strategic decisions regarding future school budgets and priorities
## Repository Structure
* PyCitySchools directory contains the PyCitySchools_starter.ipynb script, which includes the analysis summary, and resources.
## Installation
* Clone this repository to your local machine.
## Usage
* Navigate to the PyCitySchools directory.
* Run the PyCitySchools_starter.ipynb script using Jupyter Notebook
* The summary of analysis added as a Markdown at the top of the script and duplicated below.
## Summary of the analysis
 Based on the data from 15 High Schools of Charter and District types, with overall budgeting 24,649,428 dollars and 39170 students we received the following metrics:
 * Average Math Score: ~78.99
 * Average Reading Score: ~81.88
 * Math passing rate: ~74.98%
 * Reading pass rate: ~85.81%	
 * Overall (Math AND Reading) pass rate: ~65.17%
 * Highest performing school (Cabrera High School) has the overall pass rate ~91.33%. 
 While the lowest performing school (Rodriguez High School) has the overall pass rate ~52.99%.
 
 ## Comparisons from the calculations 
 * There is no noticeable difference in performance between grades for both math and reading across District and Charter schools. 
 * However, for District schools, there is an obvious difference between math and reading scores, where math scores are lower than reading scores: 
   * Avg math score is ~76.96 when the avg. reading score is ~80.97. 
   * The passing rates are: math 66.55`%` and reading 80.80`%`. <br>
 Charter schools, on the other hand, have no significant difference between average math and reading scores (83.47`%` in math and 83.90`%` in reading). However, they have a little less passing math rate, which is 93.62`%`, than passing reading rate, which is 96.59`%`. <br>
 * There is also no significant difference in performance for District type schools (overall passing rate around 53`%`), regardless of budgeting. What is interesting, that the school with highest size in this type (4976 students) has the lowest budgeting per student(`$`628), but slightly highest overall passing rate 54.64`%`. <br>
 * Similarly there is no significant difference in performance for Charter type of schools (overall passing rate in range ~89`%`-91`%`), regardless of budgeting. However, the highest overall performance here (91.3`%`) has a school with `$`582 budgeting per student, in comparison to 90.9`%` overall performance with the highest budgeting in a category, which is `$`638. <br>
 When looking into the merged set of schools then we can see obvious tendency that the lower spending per student the higher is overall pass rate. I assume, this is a little misleading and affected by the fact that the higher is count of district schools in considered rande the worse is overall performance (e.g. there is some correlation with type of school rather then budget). However all the above suggests the same hypothesis "more spending per student doesn't necessarily result in better overall performance" <br>
 It worth to add that District schools receive a little higher budgeting per student (mostly >`$`630), rather than Charter schools (mostly <`$`630), but overall performance of District schools is lower than Charter schools: 90.43`%` for Charter schools and 53.67`%` for District schools. This is wierd and triggers to analyse deeper specifics of District school budgeting vs Charter schools budgeting.<br>
* Based on analysis of the whole set of schools we can see a tendency that the smaller the school's size the higher performance it has. However, when split the set of schools into two sets (District and Charter), there will no be such obvious dependency: <br>
  * all District schools are Large size (2K-5K), so hard to say how the size affects District schools. However, we could suggest the hypothesis, that the reason of bad performance of District schools is not due their Large size, because Charter school from same Large size sub-category has pretty high overall passing score, which is 90.58`%`. <br>
  * For Charter schools, Medium sized schools seem to have the highest performance (overall passing 90.62`%`) and the worst is 89.88`%` for Small schools. But it's not really a big difference between them, so hard to say about a correlation between school size and its performance.
 
## Conclusions from the calculations
 District schools are large size and have higher per student budgeting than Charter schools, which are mostly small and medium sized. However District schools have lower performance than Charter schools, especially they are worse in math scores.

---
