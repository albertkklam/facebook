# facebook

## Overview
The goal of this [Kaggle competition](https://www.kaggle.com/c/facebook-v-predicting-check-ins) is to predict which place a person would like to check in to. Facebook created an artificial world consisting of more than 100,000 places located in a 10 km by 10 km square. For a given set of coordinates, the task is to return a ranked list of the most likely places. Data was fabricated to resemble location signals coming from mobile devices, giving you a flavor of what it takes to work with real data complicated by inaccurate and noisy values. Inconsistent and erroneous location data can disrupt experience for services like Facebook Check In.

## Approach
Various approaches in Python and R have been discussed at length [here](https://www.kaggle.com/c/facebook-v-predicting-check-ins/kernels). The purpose of this repository is to implement a solution in Apache Spark and its various libraries. I've chosen to use [Spark Notebook](http://spark-notebook.io/), which provides good interactive features for data exploration.

> The Spark Notebook is an open source notebook aimed at enterprise environments, providing Data Scientists and Data Engineers with an interactive web-based editor that can combine Scala code, SQL queries, Markup and JavaScript in a collaborative manner to explore, analyse and learn from massive data sets

## Installing Spark Notebook
Follow instructions [here](https://github.com/spark-notebook/spark-notebook/blob/master/docs/quick_start.md)

## Resources

### Kaggle
1. [Facebook V: Predicting Check Ins](https://www.kaggle.com/c/facebook-v-predicting-check-ins)

### Spark
1. [What is Apache Spark?](https://www.supergloo.com/spark-tutorial/)
2. [Spark Tutorials with Scala](https://www.supergloo.com/spark-tutorial/spark-tutorials-scala/)
3. [Mastering Apache Spark 2](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/)
4. [Spark SQL, DataFrames, and Datasets Guide](http://spark.apache.org/docs/latest/sql-programming-guide.html)
5. [Interactive Analysis with the Spark Shell](http://spark.apache.org/docs/latest/quick-start.html)
