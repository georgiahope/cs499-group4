# D2. Data Collection

## 1. Research Question(s)
  * RQ1: How many pull requests have been made on specific Github project?
  * RQ2: Of those pull requests, how many have been accepted?

## 2. Data Set
For RQ1 we created a script in Python that displays a specific number of pull requests on Github using the project facebook/react. Using this data, we can see how many contributions were made overall and by which various users. For RQ2 we take those pull requests and see how many of them are accepted. This then gives us an idea of how many of those contributions were significant to a project so we can identify if there is a pattern.

## 3. Data Collection
Links to the scripts or instruments that you are using to collect your data.
* https://pygithub.readthedocs.io/en/latest/introduction.html
* Latest Version of Python and IDLE 
* Script for our preliminary data:
![Screenshot (457)](https://user-images.githubusercontent.com/87094800/134993832-0b8c401b-aa81-47b6-b1ad-108e44f22457.png)


## 4. Filtering and validity check
Filtering our Data:
- Something that we need to filter out of our data is the time that the user joined GitHub. A way to remove this is using the filter() method in python.

![Screen Shot 2021-09-25 at 3 34 24 PM](https://user-images.githubusercontent.com/75430495/134788475-2336f022-93db-4ff9-ac8d-58960858c7ee.png)

Validating our Data:
- In order to make sure the data we are collecting are valid, we will be:
  - Using reliable data resources; PyGithub, GitHub API
  - Aligning our key factors and paraments
  - Using automated and computerized programs; graph makers
  - Matching the data we collected with what is on GitHub

## 5. Characteristics of your data
Slight trend towards pulls of older accounts being merged more often than those of newer accounts
![IMG_0553](https://user-images.githubusercontent.com/75430495/134979589-acf420f3-2e4c-4083-bce7-8c9f3c81b3fa.png)


## 6. Preliminary data
Link to our preliminary data:
* https://api.github.com/repos/facebook/react-native/pulls?state=closed 
