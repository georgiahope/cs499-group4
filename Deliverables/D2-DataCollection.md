# D2. Data Collection

## 1. Research Question(s)
  * RQ1: How many pull requests have a specific number of users made on Github?
  * RQ2: Of those pull requests, how many have been accepted?

## 2. Data Set
For RQ1 we created a script in Python that displays the total number of pull requests for 5 users on Github using the project facebook/react. Using this data, we can see how many contributions were made by various users. For RQ2 we take those pull requests and see how many of them are accepted. This then gives us an idea of how many of those contributions were significant to a project.

## 3. Data Collection
### Add here links to the scripts or instruments that you are using to collect your data.

## 4. Filtering and validity check
### Explain how you are filtering or validating the data that you collect to make sure that you are processing valid data. Remember, garbage in, garbage out.
Filtering our Data:
- Something that we need to filter out of our data is the time that the user joined GitHub. A way to remove this is in the env-filter in python. 

![Screen Shot 2021-09-25 at 3 34 24 PM](https://user-images.githubusercontent.com/75430495/134788475-2336f022-93db-4ff9-ac8d-58960858c7ee.png)

Validating our Data:
- In order to make sure the data we are collecting are valid, we will be:
  - Using reliable data resources; PyGithub, GitHub API
  - Align our key factors and paraments
  - Use automated and computerized programs; graph makers

## 5. Characteristics of your data
### You should have some data at this point but you can continue to collect data later. Present here some descriptive statistics about your data set.

## 6. Preliminary data
### Provide a link to your preliminary data
https://api.github.com/repos/facebook/react-native/pulls?state=closed 
