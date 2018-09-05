# Data Visualization

## Motivation for Data Visualization


## Exploratory and Explanatory Analysis

There are two main reasons for creating visuals using data:

1. **Exploratory** Analysis is done when you are searching for insights. These visualizations don't need to be perfect. You are using plots to find insights, but they don't need to be aesthetically appealing. You are the consumer, and you need to be able to find the answer to your question from these plots.


2. **Explanatory** Analysis is done when you are providing your results for others. These visualizations need to be surrounded be a story that points the readers to an insight that answers the question. They should be accurate, insightful, and visually appealing.

The five steps of the data analysis process:

1. **Extract** - Obtain the data from a spreadsheet, SQL, the web, etc.

2. **Clean** - Fix missing values, determine which columns to keep, round values or perform some other tricks to get the data in a way that you an analyze it. Here we could use exploratory visuals.

3. **Explore** - Here we use exploratory visuals.

4. **Analyze** - Here we might use either exploratory or explanatory visuals.

5. **Share** - Use visuals to tell the story of the finding ans what it means. They motivate the actions and move your audience forward. Here is where explanatory visuals live.


## Python Data Visualization Libraries

In this course, you will make use of the following libraries for creating data visualizations:

* [matplotlib](https://matplotlib.org/): a versatile library for visualizations, but it can take some code effort to put together common visualizations.
* [seaborn](https://seaborn.pydata.org/): built on top of matplotlib, adds a number of functions to make common statistical visualizations easier to generate.
* [pandas](https://pandas.pydata.org/): not just for working with data in a numeric capacity, this library also includes some convenient methods for visualizing data.
All together, these libraries will allow you to visualize data in a balance of productivity and flexibility, for both exploratory as well as explanatory analyses.



## Course Structure

As this course covers a broad range of ways that data visualizations can be used in the data analysis process, there will also be a large number of topics that will be touched upon. Below is a summary of topics that will be covered in the remaining lessons in this course.

### Lesson 2: Design of Visualizations

Before getting into the actual creation of visualizations later in the course, this lesson introduces design principles that will be useful both in exploratory and explanatory analysis. You will learn about different data types and ways of encoding data. You will also learn about properties of visualizations that can impact both the clarity of messaging as well as their accuracy.

### Lessons 3-5: Exploration of Data

These lessons systematically present core visualizations in exploratory data analysis. Exploration starts with univariate visualizations to identify trends in distribution and outliers in single variables. Bivariate visualizations follow, to show relationships between variables in the data. Finally, multivariate visualization techniques are presented to identify complex relationships between three or more variables at the same time.

### Lesson 6: Explanatory Visualizations

This lesson describes considerations that should be made when moving from exploratory data analysis to explanatory analysis. When polishing visualizations to present to others, you will need to consider what findings you want to focus on and how to use visualization techniques to highlight your main story. This lesson also provides tips for presentation of results and how to iterate on your presentations.

### Lesson 7: Visualization Case Study

In this lesson, you will bring together everything from the previous lessons in an example case study. You will be presented with a dataset and perform an exploratory analysis. You will then take findings from that analysis and polish them up for presentation as explanatory visualizations.

### Lesson 8: (Optional) Supplemental Topics

In this optional lesson, you can learn about topics that don’t quite fit into the rest of the course. Here, you can read about alternative Python plotting libraries and visualization types. In particular, you may be interested in this lesson if you want to generate plots based on maps.