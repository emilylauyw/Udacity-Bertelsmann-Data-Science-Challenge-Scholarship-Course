# Udacity Bertelsmann Data Science Challenge Scholarship Course Notes

## Statistics

### Intro To Statistical Research Methods

#### Constructs
Difficult to define and measure. It can be defined and measured in many different ways.

#### Operational Definitions
A way of turning constructs into variables we can measure.

- Volume is a construct. It is the space that takes up something but we have not define how we are measuring that space. (i.e. liters, gallons) Volume in liters is not a construct because it is operationally defined. Minutes is already operationally defined; there is no ambiguity in what we are measuring.

#### Population & Sample
Larger sample size is better with a good mix. In a random sample each subject has an equal chance of being selected, and it’s more likely to approximate the population.

- Population: all the individuals in a group
- Sample (n): some of the individuals in a group
- Parameter: a characteristic of the population
- Statistic: a characteristic of the sample
- μ: mean of a population
- x̄ bar: mean of a sample
- Sampling Error (μ - x̄): difference between the sample average & population average.


#### Observational Studies & Controlled Experiment

- In an experiment, the way the researchers handle subjects is called a treatment. Researchers are specifically interested in how different treatments might get different results. Researcher manipulates independent variable, measures changes in the dependent variable and controls lurking variables.
- An observational study is when an experimenter watches a group of subjects and does not introduce a treatment. A survey is an observational study.

#### Survey
Surveys are being use in social and behavioral science.

| Advantages | Disadvantages|
|------      |------        |
| Easy to get info on a population| Untruthful responses|
|------                           |------               |
| Relatively inexpensive| Biased responses|
|------                 |------           |
| Conducted remotely| Respondents not understanding the qn|
|------|------|
| Anyone can access & analyze survey results| Respondents refuse to answer|

| This | is   |
|------|------|
|   a  | table|

| This | is   |
|------|------|
|   a  | table|

#### Correlation does not imply Causation.
- Show Relationships: Observational studies (i.e Survey)
- Show Causation: Controlled experiment
- A variable is a value that may change or differ between individuals in an experiment.
- Hypotheses are statements about the relationships between variables.
- Independent Variable (aka predictor variable) is the variable that experimenters choose to manipulate. It is usually plotted along the x-axis of a graph.
- Dependent Variable (aka outcome) is the variable that experimenters choose to measure during an experiment; it is usually plotted along the y-axis of a graph.  
- Extraneous factors (aka Lurking variables) are things that can impact the outcome of data analysis. It’s difficult to account for every extraneous factor. Can minimize the effect of certain variables on results of a experiment via random assignment.
- Treatment Group is the group of a study that receives varying levels of the independent variable. These groups are used to measure the effect of a treatment.
- Control Group is the group of a study that receives no treatment. This group is used as a baseline when comparing treatment groups.
- Placebo is something given to subjects in the control group so they think they are getting the treatment, when in reality they are getting something that causes no effect. (i.e. sugar pill)
- Blinding is a technique used to reduce bias. Double blinding ensures that both those administering treatments and those receiving treatments do not know who is receiving which treatment.

### Visualizing Data

- Always organize the data based on the questions you want to answer.

**Frequency Table:** is constructed by arranging collected data values with their corresponding frequencies.
**Frequency (f):** a particular data value is the number of times the data value occurs.
**Relative Frequency (aka Proportion p):** fraction of counts over total (frequency/total number). All proportions are always between or equal to 0 and 1. Sum is 1.
**Percentage(%):** Relative Frequency * 100. Percentage are always between or equal to 0 and 100. Sum is 100.
**Sum (Σ):** The total sum. The sign is the Greek letter capital sigma.
**Interval/bin/bucket**: Range of values

**Histogram:**
is a graphical representation of the distribution of data.

- Good for visualizing the shape of a distribution.
- x-axis has the variable you're interested in, broken down into bins.
- y-axis has the frequency of values in that bin.
- Intersection of the axes is origin. Its Cartesian coordinates are (0,0) if we go zero & up in both axes.
- Bigger bin size means frequency gets bigger (more values will fall inside the bin).

**Comparison between Historgram & Bar Graph**

![Histogram vs Bar Graph](Screenshots/01.png "Histogram vs Bar Graph")

| Histogram | Bar Graph|
|-------------------------|----------------------------|
| No space between each bar| Some space between each bar|
|-----------------------|-----------------------|
| Shape is very important| Shape is not important|
|----------------------------------------------|-------------------------------------------------|
| Variable on x-axis is numerical & quantitative| Variable on x-axis is categorical or qualitative|
|----------------------------------------------------|---------------------|
| Order matters, it goes from low to high along x-axis| Order doesn't matter|

### Skewed distribution

- Negative Skewed: shorter bins on the left and taller bins on the right.
- Positive Skewed: shorter bins on the right and taller bins on the left.
- Symmetric (Normal Distribution): can draw a line down the middle and the right side mirrors the left side.

![Positive vs Negative Skew](Screenshots/02.png "Positive vs Negative Skew")

### Central Tendency

Mean
Average is a statistic that rests at a specific spot in the middle of the distribution

Median
The value in the middle of the distribution is called the median

Mode
The value at which the frequency is highest is called the mode.



## Python
-

## SQL
-
