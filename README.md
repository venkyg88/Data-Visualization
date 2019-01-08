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

You can see one of Cole's seminars [here!](https://www.youtube.com/watch?v=8EMW7io4rSI). She stresses that six lessons of communicating with data:

Understand the context - this means knowing your audience and conveying a clear message about what you want your audience to know or do with the information you are providing.

Choose an appropriate visual display - this was covered in the last lesson. Check out the lesson titled recap in the previous section if you need a quick refresher. 

Eliminate clutter - you should only provide information to the user that helps convey your message.

Focus attention where you want it - build visualizations that pull attention to the message you want to highlight. 

Think like a designer - you will learn a number of design principles in this lesson to assist as you start to put together your own data visualizations.

Tell a story - your visualizations should give the audience a story. The most powerful data visualizations move people to take action.


There are two main reasons for creating visuals using data:

Exploratory analysis is done when you are searching for insights. These visualizations don't need to be perfect. You are using plots to find insights, but they don't need to be aesthetically appealing. You are the consumer of these plots, and you need to be able to find the answer to your questions from these plots.


Explanatory analysis is done when you are providing your results for others. These visualizations need to provide you the emphasis necessary to convey your message. They should be accurate, insightful, and visually appealing.

The five steps of the data analysis process:

Extract - Obtain the data from a spreadsheet, SQL, the web, etc.

Clean - Here we could use exploratory visuals.

Explore - Here we use exploratory visuals.

Analyze - Here we might use either exploratory or explanatory visuals.

Share - Here is where explanatory visuals live.

What makes a visual bad?
Visuals can be bad if they:
Don't convey the message.
Are misleading.
This seems straightforward, but often visuals are created that do one or both of these unintentionally. There is an entire book that was published aimed at misleading visuals: ![How to Lie with Statistics](http://faculty.neu.edu.cn/cc/zhangyf/papers/How-to-Lie-with-Statistics.pdf).

What experts say about visual encodings?

Experts and researchers have determined the visual patterns that allow humans to `best` identify certain patterns. In general, humans are able to best understand data encoded with positional changes (differences in x- and y- position as we see with scatterplots) and length changes (differences in box heights as we see with bar charts and histograms).

Alternatively, humans `struggle` with understanding data encoded with color hue changes (as is commonly used as an additional variable encoding in scatter plots - this is coming up in the next concepts) and area changes (as we see in pie charts).

Chart Junk

Chart junk refers to all visual elements in charts and graphs that are not necessary to comprehend the information represented on the graph or that distract the viewer from this information.

Examples of chart junk you saw in this video include:

Heavy grid lines
Unnecessary text
Pictures surrounding the visual
Shading or 3d components
Ornamented chart axes

DATA-INK RATIO
(https://github.com/venkyg88/Data-Visualization/blob/master/data-ink-ratio.png)

The data-ink ratio, credited to Edward Tufte, is directly related to the idea of chart junk. The more of the ink in your visual that is related to conveying the message in the data, the better.

Limiting chart junk increases the data-ink ratio.
