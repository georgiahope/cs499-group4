# Research method: 
You should explain the data collection and data analyzes 
procedures. 
## Data collection: 
### Method
In this paper, we sought to gather information about the relationship between the acceptance rate of pull requests on GitHub and the experience level of the associated contributor. This was accomplished by analyzing pull requests for a number of popular GitHub projects.

### Project Selection
The GitHub projects to be analyzed were selected from the list of trending GitHub repositories over the last month [1]. This method was selected in order to maximize the number of pull requests to be analyzed. Additionally, as these repositories are featured prominently on GitHub, there is an increased likelihood of open-source developers of varying experience levels encountering and contributing to these projects. The first five entries in this list were included in the study. The following repositories were included:
facebook/react-native [2]
goplus/gop [3]
louislam/uptime-kuma [4]
HashLips/hashlips_art_engine [5]
TechXueXi/TechXueXi [6]
### Data Collection
The relevant data was collected from these projects through the use of a Python script, using the PyGithub library [7]. For each repository, a limit of fifty pull requests was set, up to which all available requests were collected and stored. Each repository and pull request was then cycled through, and for each the account creation date of the user and whether or not the pull request was merged were written as a new row in a .csv file. In total, data from 231 pull requests was collected.

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

## References
1. GitHub. (n.d.). Retrieved November 7, 2021, from https://github.com/trending?since=monthly.
2. facebook/react-native. GitHub. (n.d.). Retrieved November 7, 2021, from https://github.com/facebook/react-native
3. goplus/gop. GitHub. (n.d.). Retrieved November 7, 2021, from https://github.com/goplus/gop
4. louislam/uptime-kuma. GitHub. (n.d.). Retrieved November 7, 2021, from https://github.com/louislam/uptime-kuma
5. HashLips/hashlips_art_engine. (n.d.) Retrieved November 7, 2021, from https://github.com/HashLips/hashlips_art_engine
6. TechXueXi/TechXueXi. (n.d.) Retrieved November 7, 2021, from https://github.com/TechXueXi/TechXueXi
7. PyGithub/PyGithub. (n.d.) Retrieved November 7, 2021, from https://github.com/PyGithub/Pygithub
