# D5 - Preliminary Results

## Research Questions
This part of the presentation will help us remember your research and check
whether your results really answer the research questions. You can refine your research questions based
on the results (you can even add/remove RQs if needed). Remember that research is an iterative process.
- RQ 1: Referring to specific users, how old is the account of the associated contributor?
- RQ 2: How does the age of the contributor's account relate to the likelihood of pull request acceptance?

## Method
Explain how you collected and analyzed your data, detailing each step. This part will help us
understand what you did and check for possible biases in the data collection/analysis.
### Collecting Data
1. Set a desired number of pulls to be retrieved
2. Create GitHub object with access token 
3. Get repository 
4. Get list of  pulls for the repository
5. Set up CSV writer
    a. Open csv file
    
    b. Write inside file
    
    c. See if pulls are merged or not
    
    d. Get user and account created
6. Close file
### Analyzing Data
With the .csv file, we will be analyzing the data through R and representing it with a graph. It will show the date created and if it was accepted or rejected.

## Results
Present the results, organized per research question. You can present numbers, graphs, tables,
etc.
