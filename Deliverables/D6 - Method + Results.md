# Research method: 
You should explain the data collection and data analyzes 
procedures. 
## Data collection: 
Which projects did you select? What was the criteria for 
selecting projects? How did you collect them? What are the 
characteristics/distribution of your data set (demographic information about 
the projects)? Which kind of data have you collected? How have you 
inspected/cleaned/filtered the data to avoid incorrect assumptions? What kind 
of additional data wrangling have you done do to answer the research questions? 
Tables and figures are welcome in this section.
## Data analysis: 
After collecting all the data relevant to the research topic, the data can be viewed in a .csv file. In this .csv file, different columns represent different attributes that have been deemed significant in order to adequately answer the research questions. The data is analyzed through R Studio and is represented by different types of graphs. Scatterplots and bar graphs are used in order to identify a pattern between how old user accounts are versus how many of the user's contributions are merged for a project. In addition, a boxplot using the same data are used to identify potential outliers that exist.
# Results: 
### RQ 1: Referring to pull requests, how old is the account of the associated contributor?

![Screen Shot 2021-11-07 at 9 42 52 AM](https://user-images.githubusercontent.com/75430495/140653894-07e57706-739e-4269-9cf8-90d7a74d9b08.png)

#### Figure 1: .csv Results

In figure 1, we show a part of our .csv results file which had up to 231 contributors' pull requests. Here we have the date and time that the contributors from 5 repositories joined GitHub and if their pull request was merged or not. The contributors on these 5 repositories created accounts as early as from the year 2008 until 2021. 

### RQ 2: How does the age of the contributor’s account relate to the likelihood of pull request acceptance?

![Screen Shot 2021-11-07 at 9 43 35 AM](https://user-images.githubusercontent.com/75430495/140654352-dbc89e48-9450-4b8e-8a72-b073e87fcdf3.png)

#### Figure 2: Scattorplot of Results

![Screen Shot 2021-11-07 at 10 02 56 AM](https://user-images.githubusercontent.com/75430495/140654457-24563a51-0862-4dca-82ab-82e20bafaf90.png)

#### Figure 3 : Bar Graph Results

![Screen Shot 2021-11-07 at 9 43 47 AM](https://user-images.githubusercontent.com/75430495/140654776-ef2f709b-b34b-4b90-999d-4b6a3fe329da.png)

#### Figure 4 : Boxplot to Identify Potential Outliers 

Based off of figure 3, within the total of 231 contributors, there were 125 pull requests merged and 106 pull requests not merged. As we can see, there was a close number between these two numbers. We began to use RStudio for our third data set which indicates the time the contributor has made their GitHub account and if their pull request got merged or not on a project. In figure 2, we identified that there is an even split between pull requests merged from accounts that were older and newer. However, since these results are very close, we used a boxplot to identify potential outliers, as seen in figure 4. In the year 2010, there were a few outliers, but no outliers in the other years. So, it seems to be that no matter the age of the contributor's account, it doesn't relate to the likelihood of a pull request acceptance. 
