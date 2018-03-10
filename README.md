# Housing Sale Prices in Ames, Iowa

## Domain
The problem is drawn from the study of data related to the sales of individual residential properties in Ames, Iowa from 2006 to 2010.

## Problem Statement
We will use supervised learning to develop a cluster model, and to group similarly sold properties by a number of features. As an essential part of this process we will determine the most important features that should be included in the model.

## Dataset
The Ames, Iowa data set has 2930 observations and a total of 80 explanatory variables, including the target of sale price.

For the detailed description of data refer to the document in the data folder.

## Solution
For this project, we will use Principal Component Analysis (PCA) to form a hypothesis, and develop a clustering model that groups like property sales together.

## Benchmark Model
A naive benchmark would be to select to most common class for an observation.

## Performance Metric
We can measure the success of our model using the F score, to consider both precision and recall.