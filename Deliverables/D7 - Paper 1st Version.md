# Title:

## Abstract

## Intro
The career ladder of a software developer consists of three levels: junior, middle, and senior. In order to determine salary level and responsibilites, the industry will refer to this terminology to understand and assign different degrees of qualification. Software developers are assigned to a degree of qualification based off their level of expertise in terms of: technical knowledge, day-to-day duties, independent work, and contributions to various software development projects. Being able to make this distinction between developers improves efficiency for interaction and interal communication. This means that companies search for developers with senior levels because it helps set more accurate expecations for a particular engineer. The easiest way to identify a senior level developer is by finding how many significant contributions they have made to a particular software project. However, newcomers in software development have difficulty contributing to projects due to their lack of experience.

Junior level developers gain knowledge being involved with projects, however they lack in making significant contributions. Previous work like the 'Theory of software developer expertise' has shown that concepts of "expert" and "expertise" within the field of software development and discovers additional findings on why senior-level developers may contribute more on GitHub compared to first-time developers. This is because more experience and knowledge for software developers are considered more in pull requests on GitHub. The tech industry is starting to have a shortage of software developers. This is because employers are faced by many challenges like software developers having a lack of experience, lack of technical skills, and lack of soft skills. Many software developers are still new to the tech industry and companies expect consistent high-quality history of software development skills. New software developers without the reputation and portfolio have to prove their place to get a job in this industry. Even if new software developers are inexperienced, it may be a good place where even for a small project on GitHub can serve them to be reliable. If we are able to solve this problem, new software developers will be able to get the experience they need, companies will no longer struggle with the massive shortage of programmers and software engineers, and there won't be a gap between first-time developers and senior-level developers on GitHub. From this study of the problem, first-time developers and the tech industry will benefit from it.

This paper seeks to provide an increased understanding of the average development path of junior level developers, by considering how the amount of time a developer has been contributing to open-source projects correlates to the rate at which their contributions are accepted. This addresses the problems by setting a baseline for the development of open-source contributors. This can highlight which developers need additional experience, encouraging them to seek out open-source projects to contribute to.

RQ 1: How many pull requests have been created on a particular Github project? This will give us an idea of how many contributions are being made by various users on Github. From here, we will choose a few users at random to look further into their github history. RQ 2: Refering to specific users, how many pull requests of theirs have been accepted? This will give us data on how many pull requests a specific user has made on a project and how many of those have been accepted. This then tells us how many contributions were actually deemed significant to a project and we will compare the number of significant contributions between various users.

Our goal is to provide a better understanding of how the overall amount of time a developer has been contributing to open-source software relates to the number of contributions made by that developer, as well as how many of those contributions are considered to be “useful” enough to be accepted. This study will look at a number of pull requests made on open-source projects on GitHub. For each request, the experience of the user behind it (measured as the amount of time elapsed since the first GitHub contribution made by the user), the number of contributions made by that user, and whether the pull was merged will all be considered.

This research will give developers a frame of reference for how their own development compares to that of others in their field. This would be useful both to the developers themselves and to any professionals considering hiring them, as it would allow them to compare their own experience to the experience of the average developer. This would show which candidates have a history of high or low performance in open-source contributions.
## Related Works
This section presents the existing research in open source software communities. There are different approaches by researchers and organizations to understand the factors affecting pull requests and code quality.

### Background
Previous research papers have looked into the relationships between developer experience, code acceptance, and code quality present in pull requests. In particular, these papers have found several factors that seem to impact the likelihood of a pull request being accepted and merged into a repository [1][3][4][5]. They also considered how pull request acceptance can itself impact future behavior [2], and how certain factors can also impact the amount of time it takes for a pull request to be accepted or rejected [6]. These begin to show the ways in which the factors surrounding a pull request and the user making the request interact with one another.

The following section will discuss each of these papers individually, including the methods and findings highlighted in each.

### Related Work
Tresa Rose [1] were one of the researchers that studied open source software (OSS) communities. They performed two types of studies, qualitative and quantitative, which investigated pull request merges of Shopify projects available in its public repository, Active Merchant. They performed a quantitative study by data mining on the project's GitHub repository to see the types of merges followed by Shopify developers. Their qualitative study was performing a survey on the Shopify developers who contributed to Active Merchant. They found that "pull request size, number of people involved in discussion, commits count, and organization of the contributor" are all factors affecting the decision to merge pull requests.

Legay, Decan, and Mens [2] studied the impact of pull request decisions on future contributions in GitHub. They had to consider the potential effects of rejections or ignored pull requests on further contributions. They did this by studying three large projects on GitHub, obtaining data through GitHub API using pull request data, and performing analyses to investigate pull requests decisions. They found that continued contribution to a project correlates with a higher pull request acceptance rate and pull requests rejections lead to fewer future contributions.

Soares, Lima, Murta, and Plastino [3] studied rejection factors of pull requests filed by core team developers in software projects with high acceptance rates. They extracted association rules from pull request data stored in software repositories in order to find factors that may have influenced these decisions. A qualitative analyses was performed to help them understand the patterns from the association rules. "Inexperience with pull requests, complexity of contributions, as well as the locality of the artifacts that have been modified, and the contribution policy of the projects" were the key factors found that increased the changes of having internal contributions rejected.

Lenarduzzi, Nikkola, Saarimäki, and Taibi [4] conducted a case study among 28 Java open-source projects to find out if code quality affect pull requests. They analyzed the correlation of 4.7 million code quality flaws in 36,000 pull requests by applying logistic regression and six machine learning techniques. They found that these code quality flaws did not affect the acceptance of a pull request at all. However, the reputation of the maintainer and the importance of delivered feature were the factors of pull request acceptance.

Dey and Mockus [5] did a study on which pull requests get accepted and why. In order to answer this, they modeled the probability that a pull request will be accepted within a month of being created using a Random Forest model using 483,988 pull rquests from 4,218 popular NPM packages. As a result, an AUC-ROC value of 0.95 was achieved to predict pull request acceptance. They tested the utility of the Random Forest model in practical scenarios. They had to train it with historical data from the NPM package bootstrap and predict if in the future, any pull request that is submitted will be accepted.

Yu, Wang, Filkov, Devanbu, and Vasilescu [6] studied the determinants of pull request evaluation latency on GitHub. They did a quantitative study that tries to resolve which factors affected pull request evaluation latency in GitHub. To extract data from a sample of GitHub projects, they used a regression model and the Travis-CI continuous integration service. They found that pull requests with "more discussion, consisting of more commits, and adding more lines of code" are factors associated with longer evaluation latencies.

### Comparisons to our study
Overall, all the previous related research papers show the factors surrounding pull request acceptance and the users making those requests. Our research paper is designed to do similar while taking it a step further. Meaning that within our study, we will look at specific projects and what contributions have been made and why. Previous studies mainly focus on our first research topic: pull request acceptance and why. Our study incorporates two research topics: different level developers and pull request acceptance. Continuing to identify what factors are applied to pull requests acceptance, we find a big difference in different levels of expertise in developers. In comparison to other research, our research dives a bit deeper into why different levels of expertise affect pull request acceptance. Ultimately finding a solution for low level developers to begin to contribute to significant parts on projects.Overall, all the previous related research papers show the factors surrounding pull request acceptance and the users making those requests. Our research paper is designed to do similar while taking it a step further. Meaning that within our study, we will look at specific projects and what contributions have been made and why. Previous studies mainly focus on our first research topic: pull request acceptance and why. Our study incorporates two research topics: different level developers and pull request acceptance. Continuing to identify what factors are applied to pull requests acceptance, we find a big difference in different levels of expertise in developers. In comparison to other research, our research dives a bit deeper into why different levels of expertise affect pull request acceptance. Ultimately finding a solution for low level developers to begin to contribute to significant parts on projects.
## Method
In this paper, we sought to gather information about the relationship between the acceptance rate of pull requests on GitHub and the experience level of the associated contributor. This was accomplished by analyzing pull requests for a number of popular GitHub projects.

### Project Selection
The GitHub projects to be analyzed were selected from the list of trending GitHub repositories over the last month [7]. This method was selected in order to maximize the number of pull requests to be analyzed. Additionally, as these repositories are featured prominently on GitHub, there is an increased likelihood of open-source developers of varying experience levels encountering and contributing to these projects. The first five entries in this list were included in the study. The following repositories were included: facebook/react-native [8] goplus/gop [9] louislam/uptime-kuma [10] HashLips/hashlips_art_engine [11] TechXueXi/TechXueXi [12]
### Data Collection
The relevant data was collected from these projects through the use of a Python script, using the PyGithub library [7]. For each repository, a limit of fifty pull requests was set, up to which all available requests were collected and stored. Each repository and pull request was then cycled through, and for each the account creation date of the user and whether or not the pull request was merged were written as a new row in a .csv file. In total, data from 231 pull requests was collected.
### Data Analysis
After collecting all the data relevant to the research topic, the data can be viewed in a .csv file. In this .csv file, different columns represent different attributes that have been deemed significant in order to adequately answer the research questions. The data is analyzed through R Studio and is represented by different types of graphs. Scatterplots and bar graphs are used in order to identify a pattern between how old user accounts are versus how many of the user's contributions are merged for a project. In addition, a boxplot using the same data are used to identify potential outliers that exist.
## Results
### RQ 1: Referring to pull requests, how old is the account of the associated contributor?

![Screen Shot 2021-11-07 at 9 42 52 AM](https://user-images.githubusercontent.com/75430495/140653894-07e57706-739e-4269-9cf8-90d7a74d9b08.png)

#### Figure 1: .csv Results of GitHub Pull Requests from 231 contributors

In figure 1, we show a part of our .csv results file which had up to 231 contributors' pull requests. Here we have the date and time that the contributors from 5 repositories joined GitHub and if their pull request was merged or not. The contributors on these 5 repositories created accounts as early as from the year 2008 until 2021. 

### RQ 2: How does the age of the contributor’s account relate to the likelihood of pull request acceptance?

![Screen Shot 2021-11-07 at 9 43 35 AM](https://user-images.githubusercontent.com/75430495/140654352-dbc89e48-9450-4b8e-8a72-b073e87fcdf3.png)

#### Figure 2: Scattorplot of .csv Results

![Screen Shot 2021-11-07 at 10 02 56 AM](https://user-images.githubusercontent.com/75430495/140654457-24563a51-0862-4dca-82ab-82e20bafaf90.png)

#### Figure 3 : Bar Graph Results of Merged and Not Merged Pull Requests

![final_boxplot](https://user-images.githubusercontent.com/75430495/141659948-203b62bd-6e18-454d-8908-c388cd107c3c.png)

Of the 231 pull requests analyzed, 125 requests had been merged, while 106 had not been merged.

#### Figure 4 : Boxplot of Account Creation Date and PR status 

Based off of figure 3, within the total of 231 contributors, there were 125 pull requests merged and 106 pull requests not merged. As we can see, there was a close number between these two numbers. We began to use RStudio for our third data set which indicates the time the contributor has made their GitHub account and if their pull request got merged or not on a project. In figure 2, we identified that there is an even split between pull requests merged from accounts that were older and newer. However, since these results are very close, we used a boxplot to identify potential outliers, as seen in figure 4. There weren't any outliers that affected the results. Also, in figure 5, there is the summary table of the results. The earliest year a pull request was not merged was in 2008, while 2010 was the earliest that was merged. The lastest that was both merged and not merged is in 2021. 

#### Figure 5: Summary Table of Results
|         | Merged | Not Merged |
|---------|--------|------------|
| Minimum | 2010   | 2008       |
| Q1      | 2010   | 2010       |
| Median  | 2011   | 2014       |
| Q3      | 2016   | 2020       |
| Maximum | 2021   | 2021       |
| Mean    | 2013   | 2014       |

The above table provides summary statistics about pull requests, seperated into two groups based on merge status. The oldest account associated with a merged pull request, made in 2010, was two years younger than the oldest account associated with a pull request which was not merged, made in 2008. The median value for merged requests was an account made in 2011, while requests not merged had an account which was created in 2014. The youngest account in both categories was made in 2021. The mean value for accounts with merged pull requests was a creation year of 2013, while for those with unmerged requests it was 2014.
## Discussion

## Threats to Validity

## Conclusion
In this paper, we investigated the overall amount of time a developer has been contributing to open-source software relates to the number of contributions made by that developer, as well as how many of those contributions are considered to be “useful” enough to be accepted. This study looked at a number of pull requests made on open-source projects on GitHub. For each request, the experience of the user behind it (measured as the amount of time elapsed since the first GitHub contribution made by the user), the number of contributions made by that user, and whether the pull was merged will all be considered. We aimed to answer two research questions: RQ1 focused on how many pull requests have been created on a particular Github project and RQ2 focused on those specific users by seeing how many pull requests of theirs have been accepted. 

For RQ1, our results showed that our .csv results file had up to 231 contributors' pull requests. Here we have the date and time that the contributors from 5 repositories joined GitHub and if their pull request was merged or not. The contributors on these 5 repositories created accounts as early as from the year 2008 until 2021. For RQ2, our results showed that within the total of 231 contributors, there were 125 pull requests merged and 106 pull requests not merged. So, there was a close number between these two numbers. Overall, no matter the age of the contributor's account, it doesn't relate to the likelihood of a pull request acceptance. 

The results presented in this paper brings us closer to the understanding of how the average development path of junior level developers, by considering how the amount of time a developer has been contributing to open-source projects correlates to the rate at which their contributions are accepted. By doing so, we have the opportunity to bring knowledge to new software developers, specifically helping them to understand what to expect from their first steps of programming in a new community on GitHub.

# References
[1] Rose, T. (2017). Towards understanding what factors aECT by Tresa rose a ... Retrieved October 14, 2021, fromhttps://curve.carleton.ca/system/files/etd/4d6605dd-eed2-4b0f-b1e1-1b92f6dea244/etd_pdf/d102ad239b0371a72a1c5c43978d82bd/rose-towardsunderstandingwhatfactorsaffectpull.pdf.

[2] Legay, D., Decan, A., & Mens, T. (2018, December 15).On the impact of pull request decisions on future contribu-tions. Retrieved October 14, 2021, from https://arxiv.org/abs/1812.06269.

[3] Soares, D. M., De Lima, M. L., Murta, L., & Plastino,A. (2015, December 9). Rejection factors of pull requestsfiled by CORE team developers in software projects withhigh  acceptance  rates.  Retrieved  October  14,  2021,  fromhttps://ieeexplore.ieee.org/abstract/document/7424445.

[4] Lenarduzzi, V., Nikkola, V., Saarimäki, N., & Taibi, D.(2020, August 28). Does code quality affect pull request accep-tance? an empirical study. Retrieved October 14, 2021, fromhttps://www.sciencedirect.com/science/article/pii/S0164121220302090.

[5] Dey, T., & Mockus, A. (2020, March 2). Which pull re-quests get accepted and why? A study of popular NPM Pack-ages. Retrieved October 14, 2021, from https://arxiv.org/abs/2003.01153.

[6] Yu, Y., Wang, H., Filkov, V., Devanbu, P., & Vasilescu, B.(2015). Wait for it: Determinants of pull request evaluationlatency on github. 2015 IEEE/ACM 12th Working Conferenceon Mining Software Repositories. https://doi.org/10.1109/msr.2015.42

[7] GitHub. (n.d.). Retrieved November 7, 2021, from https://github.com/trending?since=monthly.

[8] facebook/react-native. GitHub. (n.d.). Retrieved No-vember 7, 2021, from https://github.com/facebook/react-native.

[9] goplus/gop. GitHub. (n.d.). Retrieved November 7, 2021,from https://github.com/goplus/gop.

[10] louislam/uptime-kuma. GitHub. (n.d.). Retrieved No-vember 7, 2021, from https://github.com/louislam/uptime-kuma.

[11] HashLips/hashlips_art_engine. (n.d.) Retrieved No-vember 7, 2021, from https://github.com/HashLips/hashlips_art_engine.

[12] TechXueXi/TechXueXi. (n.d.) Retrieved November 7,2021, from https://github.com/TechXueXi/TechXueXi.

[13]  PyGithub/PyGithub.  (n.d.)  Retrieved  November  7,2021, from https://github.com/PyGithub/Pygithub.
