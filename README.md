# fundamentalsdataanalysis
# Assignment for Fundamentals of Data Analysis
# Submission Date - 29th November 2019
# Lecturer - Ian McLoughlin
# Objective - 
# As per Assignment sheet, marks to be awarded in conjuction with;-

# Description - Uses descriptive statistics and plots to describe the tips dataset. This part is worth 30%.
# Regression: Analyse whether there is a relationship between the total bill and tip amount. Also 30%.
# Analyse: Analyse the relationship between the variables within the dataset, in any way. 40% of mark.

# To complete assignment the following base plan was created.
# a) Learn how to create a jupyter notebook and detail steps.
# b) Create the notebook and add to git repository.
# c) Expand on previous learnings of Python including the newer lecture content concerning the numpy.random package.
# d) Use new learnings, utilize the various packages and the jupyter notebook to complete the tasks.
# e) Complete Assignment to a suitable standard as per requirements outlined in the assignment sheet within the repository.

# Key Steps for Completion of Assignment;
# Create Notebook.
# Add to Github.
# Gain and Anyalyse Sources.
# Research Tips Set.
# Add to Notebook.
# Create Description.
# Input various codings, explanations and graphs.
# Research Regression.
# Compose regression learnings on Tips set and relevant workings.
# Analyse tips set uniquely.
# Complete the assignment to standard.

# Structure of the Assignment

# Introduction of Tips Data-set, Types of Data Visualization to be used on the key tasks: Descriptive Statistics, Regression and Analysis.
# Descriptive Statistics Section of Tips Data-set
# Regression Section on Tip Data-set
# Analysis of Tip Data-set
# Conclusion
# Reference List 

# Visited Michael Waskoms' github account to view repositories.

# Key Words
# Jupyter - "a loose acronym meaning Julia, Python, and R" (Datacamp, 2019) - The base languages jupyter was created to include but it now includes various other languages, including Python.
# Notebook - jupyter notebook versions allow the inclusion of code, graphs, figures, etc. in a single document repository and Datacamp (2019) state these document holdings "are the ideal place to bring together an analysis description, and its results, as well as, they can be executed perform the data analysis in real time".
# The Jupyter Notebook App - allows running the program on a web browser with the kernel and dashboard the primary components. The kernel deals with the code inputted by the user. The dashboard shows the high level of this access and allows creation or editing of notebooks and managing of kernels on the system you are using.
# Descriptive statistics - "are brief descriptive coefficients that summarize a given data set, which can be either a representation of the entire or a sample of a population" Investopedia (2019).
# ROWS, VARIABLES - data inputs. In this data set it is the measurements compiled by Waskom.
# ATTRIBUTES, CLASSES - the attributes are the specifications.
# DATASET - in this case it is the Tips dataset which is imported in the script from the Maskons preloaded Seaborn tips.csv file.
# MACHINE LEARNING - allows "computers the ability to learn without being explicitly programmed" (Athur Samuel). Allows processing of BIG DATA.
# DATA ANALYSIS - is the inspection and modelling of data to discover information and conclusions which may aid the process of decision making.
# DATA MINING - is the examination of existing databases in order to produce new information.
# MULTIVARIATE ANALYSIS: two or more forms of variables for analysis.
# UNIVARIATE ANALYSIS: one variable for analysis.
# MEAN: the average of a set of numbers.
# STANDARD DEVIATION: the variance from the mean. It can be a low or high variance depending on the distribution of differences from the mean.
# HISTOGRAM: a bar chart type graph showing distribution of inputs.
# SCATTER, DISTPLOT, BOXPLOT, LINEPLOT, VIOLIN, PAIRPLOT: examples of graphs showing the attributes for analysis.

# Key parameters within seaborn package from Seaborn Tutorial;
# x, y : names of variables in data or vector data, optional, must be numeric. Either data or columns in data.
# hue : name of variables in data or vector data, optional
# size : name of variables in data or vector data, optional either categorical or numeric.
# style : name of variables in data or vector data, optional, a numeric dtype but will always be treated as categorical.
# data : DataFrame, each column is a variable and each row is an observation.
# palette : palette name, list, or dict, optional, Colors to use for the different levels of the hue variable
# hue_order : list, optional, order of the hue variable levels, otherwise they are determined from the data. Not needed when numeric
# hue_norm : tuple or Normalize object, optional, applied to the hue variable when it is numeric. Not relevant if it is categorical.
# sizes : list, dict, or tuple, optional, how sizes are chosen when size is used.
# size_order : list, optional. Not relevant when the size variable is numeric.
# size_norm : tuple or Normalize object, optional. When the size variable is numeric.
# markers : boolean, list, or dictionary, optional. Setting to True will use default markers. Setting to False will draw marker-less lines.
# style_order : list, optional. Not relevant when the style variable is numeric.
# legend : “brief”, “full”, or False, optional. How to draw the legend. If “brief”, numeric hue and size variables will be represented with a sample of evenly spaced values. If “full”, every group will get an entry in the legend. If False, no legend data is added and no legend is drawn.
# ax : matplotlib Axes, optional. Axes object to draw the plot onto, otherwise uses the current Axes.
# kwargs : key, value mappings. Other keyword arguments are passed down to plt.scatter at draw time.

# Reference List
# Class Content, Background Reading and Python Learning Tutorials were preliminary references supplemented by the following list of references;
# Python Software Foundation. Accessed online at: https://www.python.org/
# GitHub Guides. Mastering markdown. https://guides.github.com/features/mastering-markdown/
# w3Schools.com Tutorials. Accessed online at: https://www.w3schools.com
# Python by Programiz Tutorials. Accessed online at: https://www.programiz.com/
# Pandas: Python Data Analysis Library. Accessed online at: https://pandas.pydata.org.
# NumPy.org. Accessed online at: http://www.numpy.org.
# Seaborn (2019) Official Seaborn Tutorial. Accessed online at: https://seaborn.pydata.org/tutorial.html
# Stack Overflow - Various queries for comparison and improving code output. Accessed online at: https://stackoverflow.com.
# Git (2019) Git Book. Accessed online at: https://git-scm.com/book/en/v2
# SciPy.org (2019) Quickstart Tutorial. Accessed online at: https://docs.scipy.org/doc/numpy/user/quickstart.html
# matplotlib (2019) Pyplot Tutorial. Accessed online at: https://matplotlib.org/3.1.1/tutorials/introductory/pyplot.html
# Project jupyter. https://jupyter.org/. 
# Waskom, M. (2019) seaborn. Accessed online at: https://seaborn.pydata.org/.
# Waskom, M. (2019) Tips data set. Accessed online at: https://github.com/mwaskom/seaborn-data/blob/master/tips.csv.
# Waskom, M. (2019) Github Account. Accessed online at: https://github.com/mwaskom?tab=repositories.
# Waskom, M. (2019) Bio NYU. Accessed online at: https://www.cns.nyu.edu/~mwaskom/index.html
# Seaborn (2019) Visualizing statistical relationships. Accessed online at: https://seaborn.pydata.org/tutorial/relational.html
# Marsland, S. (2015) Machine Learning: An Algorithmic Perspective. Taylor and Francis Group.
# Investopedia (2019) Descriptive Statistics. Accessed online at: https://www.investopedia.com/terms/d/descriptive_statistics.asp
# Doshi, S. (2019) Analyze the data through data visualization using Seaborn. Towards Data Science. Accessed online at: https://towardsdatascience.com/.analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e
# Hackernoon (2018) What Is Data Visualization? Definition, History, and Examples. Accessed online at: https://hackernoon.com/what-is-data-visualization-definition-history-and-examples-e51ded6e444a.
# Olkin, I. and Sampson, A. R. (2001) Multivariate Analysis: Overview, in International Encyclopedia of the Social & Behavioral Sciences. Accessed online at: https://www.sciencedirect.com/topics/medicine-and-dentistry/multivariate-analysis.
# Taylor, J. (2011) Stats 202: Data Mining. Stanford Univeristy. Accessed online at: http://statweb.stanford.edu/~jtaylo/courses/stats202/visualization.html.
# Michalski, R. S., Carbonell, J. G. and Mitchel, T. M. (2014) Machine Learning: An Artificial Intelligence Approach, Volume 1.
# Han, J. (2006) Data Mining: Concepts and Techniques. Accessed online at: http://rizalespe.lecture.ub.ac.id/files/2015/10/DM-04-1-Klasifikasi.pdf
# Python Charts (2019) A Short Intro to Seaborn. Accessed online at: https://www.pythoncharts.com/2019/04/15/intro-to-seaborn/
# Willems, K (2017) Python Seaborn Tutorial For Beginners. Accessed online at: https://www.datacamp.com/community/tutorials/seaborn-python-tutorial.