# D5 - Preliminary Results

## Research Questions
In the interest of our research topic, the following questions have been created:
1. Referring to specific users, how old is the account of the associated contributor?
2. How does the age of the contributor's account relate to the likelihood of pull request acceptance?

## Method

### Collecting Data
In order to collect the relevant data for this research question, we need to adhere to the following protocol:
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
With this .csv file, we will be analyzing the data through R and representing it with a graph. It will show the date created and if it was accepted or rejected.
</br>
![Screenshot (490)](https://user-images.githubusercontent.com/87094800/139736383-603434c0-20f6-4c97-8170-52e72451bc0d.png)

## Results
This first figure is a bargraph that shows us that overall 125 pull requests were merged and 106 were not merged.
![Screenshot (487)](https://user-images.githubusercontent.com/87094800/139737138-9a856b6e-2005-4341-9ee2-f8a109995ce5.png)
![Screenshot (489)](https://user-images.githubusercontent.com/87094800/139737151-7e883c93-c29e-4636-97d0-756bb8b64856.png)
</br>In order to analyze the data further, we need to identify a pattern on the status of a pull request in regards to when that request was made. This next figure shows a scatterplot of all the pull requests made from the chosen 5 repositories. Dates range from newest to oldest and there is a color legend to show the status of each request. From this plot can identify clusters of merged versus not merged requests and analyze further whether there is an actual casaution relation, not just a correlation, between the date of creation and whether that pull request was merged.  
![Rplot03](https://user-images.githubusercontent.com/87094800/139738181-66f926ce-40c8-4b1f-9ae3-9bfbd36f0019.png)
</br>Lastly, we have included a boxplot over this data in order to identify potential outliers.
![Rplot04](https://user-images.githubusercontent.com/87094800/139738259-f317014a-a97a-47c9-b409-66aa7a85bf04.png)


