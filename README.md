This repository will no longer be edited.

# ACM Research Coding Challenge (Fall 2020)

## No Collaboration Policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed to use Internet documentation. If you _do_ use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Submission Procedure

Please follow the below instructions on how to submit your answers.

1. Create a **public** fork of this repo and name it `ACM-Research-Coding-Challenge`. To fork this repo, click the button on the top right and click the "Fork" button.
2. Clone the fork of the repo to your computer using . `git clone [the URL of your clone]`. You may need to install Git for this (Google it).
3. Complete the Challenge based on the instructions below.
4. Email the link of your repo to research@acmutd.co with the same email you used to submit your application. Be sure to include your name in the email.

## Question One

![Image of Cluster Plot](ClusterPlot.png)
<br/>
Given the following dataset in `ClusterPlot.csv`, determine the number of clusters by using any clustering algorithm. **You're allowed to use any Python library you want to implement this**, just document which ones you used in this README file. Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file.

## Question Solution Explanation
Prior to this project, I had little experience with Python, but by researching K-Means and other clustering algorithms, I determined that the elbow method would be a proper way to find the number of clusters with the provided data. I went through many different iterations of code that had varying degrees of success, but I was able to create a successful program using the tutorial found here: https://youtu.be/imtvI5CQLm4 I programmed the project in Jupyter Notebook. At the beginning of the program, I imported the pandas module that reads in data from the file and helps the program print out data tables. Then, I imported the matplotlib in order to be able to print out the scatterplot with the .csv file's data. Lastly, I imported the MinMaxScaler and KMeans functions of the sklearn module in order to use the file's data to calculate the number of clusters. I created an object using the pandas module to read the cluster plot data, and then created a DataFrame of it. Next, I created an array followed by a for loop that created the graph determining the number of clusters. Lastly, I put the centroids into a data table and displayed them. Overall, this project was a great learning experience for me, and I'm happy to have stepped up to the challenge! Thank you for this opportunity.
