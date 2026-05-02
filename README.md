TIMELINE 2 PIPELINES:
- Identify the "shape" of the housing data. Perform a technical distribution audit (Histograms/Box Plots) and identify the impact of the house value "cap" at $500,001.

TIMELINE 3:
- investigate ocean proximity, redundancies in data, outliers in data, regional logic, market caps
- PIPELINES:
- --> TIMELINE3_MarketCaps.knwf
- --> TIMELINE3_RedundancyandOutliers.knwf
- --> TIMELINE3_OceanProximity.knwf
- --> TIMELINE3_FaithLogic.knwf

TIMELINE 4:
- construct pipeline, bias check, target swap sub-model
- PINEPINES:
- --> TIMELINE4_BiasCheck.knwf
- --> TIMELINE4_LinearRegression.knwf
- --> TIMELINE4_PipelineConstruction.knwf
- --> TIMELINE4_RegressionSubModel.knwf

TIMELINE 5:
- Address overprediction, work on skew mititgation, error reduction, and complete classification task
- PIPELINES:
- --> TIMELINE5_Classification.knwf
- --> TIMELINE5_ErrorReductionRandomForest.knwf
- --> TIMELINE5_Overprediction.knwf
- --> TIMELINE5_Skew.knwf

TIMELINE 6:
- Final Workflow presentation
- PIPELINES:
- --> TIMELINE6_FINALWORKFLOW.knwf

Project - Contribution Log
Project Title: California Housing Market
Group 14: Amanda Elkhair, Faith Yi, Assmaa Hassan  | Course: Introduction to Data Mining
1. Contribution Log

NAME: Amanda Elkhair
RESPONSIBILITY/NODES & DELIVERABLES: Random forest regression model architect, visualization, outliers
Random forest model, final report: 33%
NAME: Faith Yi
RESPONSIBILITY/NODES & DELIVERABLES: Team Lead, Linear regression model architect, Linear regression model, final report, 34%
NAME: Assmaa Hassan
RESPONSIBILITY/NODES & DELIVERABLES: Data pre-processing, fairness assessment, ocean proximity, logistic regression analysis, Cleaning logic, final report, 33%

3. Version Control & Infrastructure
Primary Communication Platform:
Instagram


Weekly Sync Checklists
WEEK 1
1. Group Information

Member 1
Amanda Elkhair
aelkhair@charlotte.edu
Member 2
Faith Yi
fyi1@charlotte.edu
Member 3
Assmaa Hassan
ahassa17@charlotte.edu

2. Operational Norms
Preferred Mode of Communication: (Please check one as the main one)
[ X ] Other: Instagram

Software Sharing Infrastructure: (Please check one)
[ X ] GitHub (Recommended: provides professional version control)
GitHub Link: https://github.com/aelkhair21/Data-Mining-Project.git

Weekly Sync:
Scheduled Meeting Time: 
Monday, 11:00 a.m. - 12:00 p.m.
IN-PERSON MEETINGS

4. Submission Proof & Requirements
SEE GOOGLE DOC:
https://docs.google.com/document/d/1WWSF1JdamNkXLCEPoGY34MagcTt2e2t7_NDiOGE2n2A/edit?usp=sharing
A. Communication & GitHub Verification:
SEE GOOGLE DOC:https://docs.google.com/document/d/1WWSF1JdamNkXLCEPoGY34MagcTt2e2t7_NDiOGE2n2A/edit?usp=sharing


WEEK 2
Use this checklist at the start of every meeting to ensure you are meeting the "Green-to-Gold" requirements and project milestones.
1. Infrastructure & Accountability (Start-of-Meeting)
[X ] GitHub Sync: Did everyone pull the latest changes from main?
[X ] Contribution Log: Has the README.md been updated to reflect progress made this week?
[X ] Blocking Issues: Is anyone currently "blocked" by a KNIME node error or a data issue? (If yes, resolve this first!)
2. Current Sprint Focus (Check the Week)
Week 2 (EDA): Are your distributions analyzed? 
Week 3 (Prep): Is your feature matrix complete? 
Week 4 (Modeling): Is your data analysis or predictive pipeline running end-to-end?
Week 5 (Fairness): Have you compared at least two corrective strategies (e.g., threshold adjustment vs. oversampling)?
Week 6 (Presentation): Does your workflow run "Green-to-Gold" on new data?
3. Technical Quality Assurance (The "Green-to-Gold" Audit)
[X ] Automation: Does the workflow run from File Reader to Output without changing settings?
[X ] Annotation: Are your primary logic steps (e.g., normalisation, optimization) explained in a Metanode Annotation?
[X ] Evidence: Is every chart/table in your report directly linked to a specific KNIME node output?
4. Action Items (End-of-Meeting)
Who is doing what before next week?
Task
Assignee
Deadline
Scatter Plots
Amanda
Saturday
Box Plots
Faith
Saturday
Histogram
Assmaa
Saturday

Pro-Tips for Success
The "Two-Hour Rule": If a group member spends more than 2 hours fighting a single KNIME node, stop and ask the instructor or a TA. Do not waste an entire week on a technical hurdle.
Clinical Context: If your model's accuracy is 90% but your Recall for female patients is below 70%, you have failed the fairness audit. Prioritize finding the "why" behind that gap.
Reproducibility: If it’s not in your GitHub repository, it doesn't count as finished work.

WEEK 3
Group Name/Number: The Three Musketeers | Date: 4/5/26
Use this checklist at the start of every meeting to ensure you are meeting the "Green-to-Gold" requirements and project milestones.
1. Infrastructure & Accountability (Start-of-Meeting)
[X ] GitHub Sync: Did everyone pull the latest changes from main?
[X ] Contribution Log: Has the README.md been updated to reflect progress made this week?
[X ] Blocking Issues: Is anyone currently "blocked" by a KNIME node error or a data issue? (If yes, resolve this first!)
2. Current Sprint Focus (Check the Week)
Week 2 (EDA): Are your distributions analyzed? 
Week 3 (Prep): Is your feature matrix complete? 
Week 4 (Modeling): Is your data analysis or predictive pipeline running end-to-end?
Week 5 (Fairness): Have you compared at least two corrective strategies (e.g., threshold adjustment vs. oversampling)?
Week 6 (Presentation): Does your workflow run "Green-to-Gold" on new data?
3. Technical Quality Assurance (The "Green-to-Gold" Audit)
[X ] Automation: Does the workflow run from File Reader to Output without changing settings?
[ X] Annotation: Are your primary logic steps (e.g., normalisation, optimization) explained in a Metanode Annotation?
[ X] Evidence: Is every chart/table in your report directly linked to a specific KNIME node output?
4. Action Items (End-of-Meeting)
Who is doing what before next week?
Task
Assignee
Deadline
Objective 1 & 5
Assmaa
Sunday
Objective 2 & 3
Amanda
Sunday
Objective 4
Faith
Sunday

Pro-Tips for Success
The "Two-Hour Rule": If a group member spends more than 2 hours fighting a single KNIME node, stop and ask the instructor or a TA. Do not waste an entire week on a technical hurdle.
Clinical Context: If your model's accuracy is 90% but your Recall for female patients is below 70%, you have failed the fairness audit. Prioritize finding the "why" behind that gap.
Reproducibility: If it’s not in your GitHub repository, it doesn't count as finished work.

WEEK 4
Group Name/Number: three musketeers | Date: 4/21/26
Use this checklist at the start of every meeting to ensure you are meeting the "Green-to-Gold" requirements and project milestones.
1. Infrastructure & Accountability (Start-of-Meeting)
[X ] GitHub Sync: Did everyone pull the latest changes from main?
[ ] Contribution Log: Has the README.md been updated to reflect progress made this week?
[ ] Blocking Issues: Is anyone currently "blocked" by a KNIME node error or a data issue? (If yes, resolve this first!)
2. Current Sprint Focus (Check the Week)
Week 2 (EDA): Are your distributions analyzed? 
Week 3 (Prep): Is your feature matrix complete? 
Week 4 (Modeling): Is your data analysis or predictive pipeline running end-to-end?
Week 5 (Fairness): Have you compared at least two corrective strategies (e.g., threshold adjustment vs. oversampling)?
Week 6 (Presentation): Does your workflow run "Green-to-Gold" on new data?
3. Technical Quality Assurance (The "Green-to-Gold" Audit)
[x ] Automation: Does the workflow run from File Reader to Output without changing settings?
[ x] Annotation: Are your primary logic steps (e.g., normalisation, optimization) explained in a Metanode Annotation?
[ x] Evidence: Is every chart/table in your report directly linked to a specific KNIME node output?
4. Action Items (End-of-Meeting)
Who is doing what before next week?
Task
Assignee
Deadline
Pipeline construction
faith
sunday
Bias check
assmaa
sunday
Target swap
Amanda
sunday

Pro-Tips for Success
The "Two-Hour Rule": If a group member spends more than 2 hours fighting a single KNIME node, stop and ask the instructor or a TA. Do not waste an entire week on a technical hurdle.
Clinical Context: If your model's accuracy is 90% but your Recall for female patients is below 70%, you have failed the fairness audit. Prioritize finding the "why" behind that gap.
Reproducibility: If it’s not in your GitHub repository, it doesn't count as finished work.

WEEK 5
Group Name/Number: The Three Musketeers | Date: 4/19/25
Use this checklist at the start of every meeting to ensure you are meeting the "Green-to-Gold" requirements and project milestones.
1. Infrastructure & Accountability (Start-of-Meeting)
[X ] GitHub Sync: Did everyone pull the latest changes from main?
[X ] Contribution Log: Has the README.md been updated to reflect progress made this week?
[X ] Blocking Issues: Is anyone currently "blocked" by a KNIME node error or a data issue? (If yes, resolve this first!)
2. Current Sprint Focus (Check the Week)
Week 2 (EDA): Are your distributions analyzed? 
Week 3 (Prep): Is your feature matrix complete? 
Week 4 (Modeling): Is your data analysis or predictive pipeline running end-to-end?
Week 5 (Fairness): Have you compared at least two corrective strategies (e.g., threshold adjustment vs. oversampling)?
Week 6 (Presentation): Does your workflow run "Green-to-Gold" on new data?
3. Technical Quality Assurance (The "Green-to-Gold" Audit)
[X ] Automation: Does the workflow run from File Reader to Output without changing settings?
[ X] Annotation: Are your primary logic steps (e.g., normalisation, optimization) explained in a Metanode Annotation?
[ X] Evidence: Is every chart/table in your report directly linked to a specific KNIME node output?
4. Action Items (End-of-Meeting)
Who is doing what before next week?
Task
Assignee
Deadline
Error reduction
Amanda
Due date
Classification task
Assmaa
Due date
Overprediction, skew mitigation
Faith
Due date

Pro-Tips for Success
The "Two-Hour Rule": If a group member spends more than 2 hours fighting a single KNIME node, stop and ask the instructor or a TA. Do not waste an entire week on a technical hurdle.
Clinical Context: If your model's accuracy is 90% but your Recall for female patients is below 70%, you have failed the fairness audit. Prioritize finding the "why" behind that gap.
Reproducibility: If it’s not in your GitHub repository, it doesn't count as finished work.


Github Repository Link
https://github.com/aelkhair21/Data-Mining-Project.git
3. Workflow Documentation
KNIME Workflow Overview: A brief description of the final pipeline.
Final Workflow:

Key Annotations:
Preprocessing steps (missing value, number to string, one-to-many, etc.)
Annotations are written on the final workflow.
Histogram → shows the skewness in data before applying transformation
Math Formula → used to address the overprediction in houses over 400k value.
Known Limitations: [Students: List any issues or edge cases the model does not handle well]
Although we addressed the overprediction, we did not implement a method using log transformation to properly address the issue. 
Even though total_bedrooms and total_rooms show a strong correlation, we found that the model still works better when we use both of them as predictors. Our adj-R2 does not penalize us for using both of these variables.
4. Group Agreement & Attestation
By signing below, all team members confirm that the work contained within this repository is the result of a collaborative effort and that all individual contributions are fairly represented in the log above.
Member 1: Amanda Elkhair,  Date: 5/2/26
Member 2: Faith Yi, Date: 5/2/26
Member 3: Assmaa Hassan, Date: 5/2/26


