# Data-Visualization
Fundamentals, design, data visualization tools and creating dashboards


It's important to gain insights on data which will help us to make the right decisions.
Usually, the most compelling way to communicate information about data id visually. But creating good visualizations really combines two skills -
First, there is a design and artistic component to create something that is beautiful and compelling.
And then, there is a strong scientific and mathematical component in being able to deliver the right insights.

So it's important to build data visualizations and do so in a way that is engaging and informative.

There are two major areas of focus :
Why are data visualizations more useful for delivering insight than just using summary statistics?
What plot do you build in a given situation?



Categorical variable
Categorical variables contain a finite number of categories or distinct groups. Categorical data might not have a logical order. For example, categorical predictors include gender, material type, and payment method.
Discrete variable
Discrete variables are numeric variables that have a countable number of values between any two values. A discrete variable is always numeric. For example, the number of customer complaints or the number of flaws or defects.
Continuous variable
Continuous variables are numeric variables that have an infinite number of values between any two values. A continuous variable can be numeric or date/time. For example, the length of a part or the date and time a payment is received.
Ordinal variable
An ordinal variable is a categorical variable for which the possible values are ordered. Ordinal variables can be considered “in between” categorical and quantitative variables. Example: Educational level might be categorized as. 1: Elementary school education. 2: High school graduate.


UNIVARIATE PLOTS
What visualizations we use not only depends on the type of data but also on how many columns in your dataset you want to look at in a single plot.

If you are only interested in one column in your dataset this is called univariate analysis where the uni stands for one. 

Before we talk about comparing variable to one another, it's important to know which plots to create for univariate analysis. For univariate quantitative data both continuous and discrete the most common plot to visualize the data is known as a histogram. There are rare cases in which you might use a plot other than histogram. For univariate categorical data the most common plot is a bar chat. A bar chat is like a histogram but the bands are based on the set category and not based on the range the chart creator can change.

SCATTER PLOTS
Scatter plots are a common visual for comparing two quantitative variables. A common summary statistic that relates to a scatter plot is the correlation coefficient commonly denoted by r.

Though there are a few different ways to measure correlation between two variables, the most common way is with Pearson's correlation coefficient. Pearson's correlation coefficient provides the:

Strength
Direction
of a linear relationship. Spearman's Correlation Coefficient does not measure linear relationships specifically, and it might be more appropriate for certain cases of associating two variables.

Correlation Coefficients
Correlation coefficients provide a measure of the strength and direction of a linear relationship.

We can tell the direction based on whether the correlation is positive or negative.

A rule of thumb for judging the strength:
![alt text](https://github.com/venkyg88/Data-Visualization/blob/master/cf-formula.png)


It can also be calculated in Excel and other spreadsheet applications using CORREL(col1, col2), where col1 and col2 are the two columns you are looking to compare to one another.

Recap
In this lesson:

You motivated the need for data visualization by showing that summary statistics don't tell the full story. You saw datasets where the summary statistics were the same, but the actual data were very different!


You did a review of data types. In general there are quantitative and categorical variables. Quantitative variables can be either discrete or continuous, while categorical variables are either ordinal or nominal. 


You looked at univariate plots. In most cases a histogram should be used for quantitative data, while a bar chart should be used for categorical data. There are some cases where you might use one of the other plots.


You then looked at bivariate plots, where you were comparing two variables to one another. Scatter plots are the most common way to visualize two quantitative variables, while a line chart is common for data that you are watching over time. If you are comparing two categorical variables, the best choice is probably a side-by-side bar chart.


You learned about correlation coefficients, which provide the strength and direction of linear relationships. You learned a rule of thumb for determining whether the relationship between two quantitative variables is strong, moderate, or weak.


You then looked at cases where we had more than two variables. You learned that using these plots effectively is about building the plot that helps you see the insight that answers the question you have.


You gained some insight into visual encodings and data dashboards, which will be a part of the next lessons!


DESIGN

![alt text](https://github.com/venkyg88/Data-Visualization/blob/master/design.png)

You can see one of Cole's seminars here![alt text](https://www.youtube.com/watch?v=8EMW7io4rSI). She stresses that six lessons of communicating with data:

Understand the context - this means knowing your audience and conveying a clear message about what you want your audience to know or do with the information you are providing.

Choose an appropriate visual display - this was covered in the last lesson. Check out the lesson titled recap in the previous section if you need a quick refresher. 

Eliminate clutter - you should only provide information to the user that helps convey your message.

Focus attention where you want it - build visualizations that pull attention to the message you want to highlight. 

Think like a designer - you will learn a number of design principles in this lesson to assist as you start to put together your own data visualizations.

Tell a story - your visualizations should give the audience a story. The most powerful data visualizations move people to take action.
