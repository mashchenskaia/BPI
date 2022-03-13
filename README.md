# BPI
The tenth International Business Process Intelligence Challenge (BPI) was co-located with ICPM. This challenge provides participants with a real-life event log, and challenges them to analyze these data using whatever techniques available, focusing on one or more of the process owner’s questions or proving other unique insights into the process(es) captured in the event log.

# Task description 
Based on the log data from the reimbursement process at TU/e the participants had to discover the bottle necks and the ways of their optimisation in the algorythm of requests processing.

# Used approach
Our teem divided the work process with the log data into several steps:
*   Initial logs preprocessing: missing values processing, descriptive statistical measures calculation, outliers detection
*   Time-series analysis: time spent on the different applications types for the whole cycle processing (from the inital request opening till money refund)
*   Tokens replay analysis: comparison of the real logs order with the ideal process order
*   Clustering for the groups of cases based on the calculated featues (number of steps, cycles detected (a-b-a, a-b-a-b, a-b-b and etc), presence of stages using dummy variables)   

# Publication
[Final report](https://icpmconference.org/2020/wp-content/uploads/sites/4/2020/10/ICPM_2020_paper_124.pdf) for the submission and results description is avaliable 
