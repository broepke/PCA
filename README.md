# 2 Beautiful Ways to Visualize PCA
 
**Principal Component Analysis** or **PCA** is a *dimensionality reduction technique* for data sets with many features or dimensions. It uses linear algebra to determine the most important features of a dataset. After these features have been identified, you can use only the most important features, or those that *explain the most variance*, to train a machine learning model and improve the computational performance of the model without sacrificing accuracy.

PCA finds the axis with the maximum variance and projects the points onto this axis. PCA uses Linear Algebra concepts known as **Eigenvectors** and **Eigenvalues**. There is a post on [Stack Exchange](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues/140579) which beautifully explains it.

Recently I wrote about how PCA can be used for **image compression** (This repo also).  This time I want to talk about some of the fundamentals of PCA through visualization.  As I was learning about PCA and how powerful it is as a tool in your Machine Learning toolbox, I came across two different ways to **visualize PCA** that finally made it click for me. I thought I would share those two ways with you and take it further and show how models perform *with* and *without* dimensionality reduction. The two methods are:

1. **Explained Variance Cumulative Plot**: This is simple but powerful. It immediately tells you how much of the variance in the data is explained by each component and how they combinations of the different components add up to the total variance.
2. **Principal Components Overlayed with the Original Data**: This one is my absolute favorite. You can see the progression of how each principal component brings in slightly more information, and in turn, it becomes hard to distinguish between the different components. This plot is a perfect companion to the Explained Variance Cumulative Plot.

Read more here: https://www.dataknowsall.com/pcavisualized.html
