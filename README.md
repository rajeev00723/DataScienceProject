# DataScienceProject

Unsurprisingly, the role of a data scientist primarily involves exploring and analyzing data. The results of an analysis might form the basis of a report or a machine learning model, but it all begins with data, with Python being the most popular programming language for data scientists.

After decades of open-source development, Python provides extensive functionality with powerful statistical and numerical libraries:

    NumPy and Pandas simplify analyzing and manipulating data
    Matplotlib provides attractive data visualizations
    Scikit-learn offers simple and effective predictive data analysis
    TensorFlow and PyTorch supply machine learning and deep learning capabilities

Usually, a data analysis project is designed to establish insights around a particular scenario or to test a hypothesis.


For example, suppose a university professor collects data from their students, including the number of lectures attended, the hours spent studying, and the final grade achieved on the end of term exam. The professor could analyze the data to determine if there is a relationship between the amount of studying a student undertakes and the final grade they achieve. The professor might use the data to test a hypothesis that only students who study for a minimum number of hours can expect to achieve a passing grade.

Explore data with NumPy and Pandas


Data scientists can use various tools and techniques to explore, visualize, and manipulate data. One of the most common ways in which data scientists work with data is to use the Python language and some specific packages for data processing.

What is NumPy

NumPy is a Python library that gives functionality comparable to mathematical tools such as MATLAB and R. While NumPy significantly simplifies the user experience, it also offers comprehensive mathematical functions.

What is Pandas
Pandas is an extremely popular Python library for data analysis and manipulation. Pandas is like excel for Python - providing easy-to-use functionality for data tables.


Explore data in a Jupyter notebook
Jupyter notebooks are a popular way of running basic scripts using your web browser. Typically, these notebooks are a single webpage, broken up into text sections and code sections that are executed on the server rather than your local machine. This means you can get started quickly without needing to install Python or other tools.

Testing hypotheses
Data exploration and analysis is typically an iterative process, in which the data scientist takes a sample of data and performs the following kinds of task to analyze it and test hypotheses:

    Clean data to handle errors, missing values, and other issues.
    Apply statistical techniques to better understand the data, and how the sample might be expected to represent the real-world population of data, allowing for random variation.
    Visualize data to determine relationships between variables, and in the case of a machine learning project, identify features that are potentially predictive of the label.
    Revise the hypothesis and repeat the process.

Visualize data

Data scientists visualize data to understand it better. This can mean looking at the raw data, summary measures such as averages, or graphing the data. Graphs are a powerful means of viewing data, as we can discern moderately complex patterns quickly without needing to define mathematical summary measures.

Representing data visually
Representing data visually typically means graphing it. This is done to provide a fast qualitative assessment of our data, which can be useful for understanding results, finding outlier values, understanding how numbers are distributed, and so on.

While sometimes we know ahead of time what kind of graph will be most useful, other times we use graphs in an exploratory way. To understand the power of data visualization, consider the data below: the location (x,y) of a self-driving car. In its raw form, it's hard to see any real patterns. The mean or average, tells us that its path was centred around x=0.2 and y=0.3, and the range of numbers appears to be between about -2 and 2.


Examine real world data
Completed
100 XP
3 minutes
Data presented in educational material is often remarkably perfect, designed to show students how to find clear relationships between variables. ‘Real world’ data is a bit less simple.

Because of the complexity of ‘real world’ data, raw data has to be inspected for issues before being used.

As such, best practice is to inspect the raw data and process it before use, which reduces errors or issues, typically by removing erroneous data points or modifying the data into a more useful form.

Real world data issues
Real world data can contain many different issues that can affect the utility of the data, and our interpretation of the results.

It's important to realize that most real-world data are influenced by factors that weren't recorded at the time. For example, we might have a table of race-car track times alongside engine sizes, but various other factors that weren't written down—such as the weather—probably also played a role. If problematic, the influence of these factors can often be reduced by increasing the size of the dataset.

In other situations data points that are clearly outside of what is expected—also known as ‘outliers’—can sometimes be safely removed from analyses, though care must be taken to not remove data points that provide real insights.

Another common issue in real-world data is bias. Bias refers to a tendency to select certain types of values more frequently than others, in a way that misrepresents the underlying population, or ‘real world’. Bias can sometimes be identified by exploring data while keeping in mind basic knowledge about where the data came from.

Remember, real-world data will always have issues, but this is often a surmountable problem. Remember to:

Check for missing values and badly recorded data
Consider removal of obvious outliers
Consider what real-world factors might affect your analysis and consider if your dataset size is large enough to handle this
Check for biased raw data and consider your options to fix this, if found
