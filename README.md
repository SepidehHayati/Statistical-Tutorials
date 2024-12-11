# Introduction to Statistics

This repository contains my drafts, practice notes, and tutorial sheets for reviewing and understanding key concepts in statistics. These notes are a work in progress and are meant to help me (and hopefully others) solidify foundational concepts in statistics.
The content is based on online educational courses and university programs I have completed.

----------------------------------------------------------------------------------------------


## Types of Statistics
Statistics is broadly divided into two main types:

#### **1. Descriptive Statistics**
`Descriptive statistics` are used to summarize, organize, and describe the main features of a dataset. They are often used for EDA to focus on presenting data clearly and understandably through measures.
The goal is to provide an overall summary of the data without making predictions or inferences about the population.

#### **2. Inferential Statistics**
`Inferential statistics` use sample data to make generalizations, predictions, or inferences about a larger population. This involves hypothesis testing, confidence intervals, regression analysis, and other statistical tests to conclude the observed data.

----------------------------------------------------------------------------------------------

## Type of Analysis:
#### **1. EDA (Exploratory Data Analysis) **
belongs under `Descriptive Statistics`, which focuses on summarizing and exploring the data (e.g., mean, median, variance, and visualizations like Q-Q plots).
#### **2. HT (Hypothesis Testing)** 
falls under `Inferential Statistics`, as it involves testing assumptions about the population (e.g., normality tests, comparisons like K-S and KLD).

----------------------------------------------------------------------------------------------

## General Comparison & Overlap

#### **EDA vs. HT:**
- `EDA` often sets the foundation by summarizing and exploring the data.
- `HT` builds on EDA by using statistical tests to confirm or reject assumptions.

#### **Descriptive vs. Inferential:**
- `Descriptive` Summarizes, organizes, and describes the main features of a dataset without concluding the population.
- `Inferential` Uses sample data to make generalizations, predictions, or conclusions about a larger population. Includes hypothesis testing and statistical modeling.

----------------------------------------------------------------------------
## 1. General Concepts
These are the foundational concepts and methods used across both Descriptive and Inferential Statistics.

#### Population and Sample
1. Population: The entire group of individuals or items you want to study
2. Target Population: A specific subset of the population you're focusing on.
3. Available Population: The part of the population that is accessible for sampling
4. Sample: The subset of the target population that you can access for your study.

#### Moments: 
1. Mean (Central Tendency), average of data points. Includes:
    1. Median: Middle value of the data. 
    2. Mode: Most frequent value.
    3. Trimmed Mean: calculates the average by removing a percentage of the highest and lowest values to reduce the impact of outliers.
3. Variance (Dispersion): Measures how spread out the data is. Includes:
     1. Standard Deviation: The square root of variance, showing data spread in the same units.
     2. Coefficient of Variation: Ratio of the standard deviation to the mean, useful for comparing variability between different datasets.
5. Skewness: Measures the asymmetry of data distribution
6. Kurtosis: Measures the "tailedness" of the data distribution (how extreme the outliers are).

#### Five-Number Summary
1. Min: The smallest data point.
2. Q1: The first quartile (25th percentile).
3. Median: The middle value (50th percentile).
4. Q3: The third quartile (75th percentile).
5. Max: The largest data point.

#### Distributions
1. Normal (Gaussian): Symmetrical distribution where most data points are near the mean.
2. Uniform: All outcomes have equal probability.
3. Bernoulli (Failure/Success): Distribution with two possible outcomes (failure/success)
4. Binomial: Distribution for a fixed number of independent trials, each with a success/failure outcome.
5. Multinomial: Generalization of binomial for more than two possible outcomes.

#### Statistical Comparison Metrics
1. Q-Q Plot: A graphical tool to compare two data distributions. It visually shows how well the data fits the reference distribution, without providing numerical results
2. Kullback-Leibler Divergence (KLD): Measures the difference between two probability distributions. A value close to zero means the distributions are similar. It’s not used to test normality.
3. Kolmogorov-Smirnov (K-S) Test: Compares sample data to a reference distribution (e.g., normal) to test if the data fits. It provides a p-value to assess the goodness of fit.
4. Shapiro Test: Tests if a dataset follows a normal distribution. It provides a p-value and does not compare multiple datasets.

## 2. Specific Concepts
These are methods and tools specifically tied to EDA (Exploratory Data Analysis) or HT (Hypothesis Testing):

#### Sampling Methods
  - Simple Random Sampling: Every member of the population has an equal chance of being selected.
  - Systematic Sampling: Selecting every "n-th" item from a list.
  - Stratified Sampling: Dividing the population into subgroups and sampling from each subgroup.
  - Cluster Sampling: Dividing the population into clusters, then randomly selecting entire clusters to study.
#### Sample Size
  - 10 %: A common guideline for choosing sample size in some studies (can vary depending on context).
  - Confidence Level, Confidence Interval: The confidence level shows the probability that a population parameter lies within the confidence interval.
  - Subtopic: Placeholder for other methods related to sample size.
#### Data Types
  - Numerical: Data that represents measurable quantities
      1. Continuous: Data that can take any value in a range (e.g., height, weight).
      2. Discrete: Data that can only take specific values (e.g., number of people).
  - Categorical: Data that represents categories.
      1. Nominal: Categories without a specific order (e.g., colors).
      2. Ordinal: Categories with a meaningful order but no fixed difference between them (e.g., ratings from 1 to 5).




