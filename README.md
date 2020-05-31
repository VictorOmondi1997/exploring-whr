# Exploring the World Happiness Report

<center> Data Cleaning, Data Aggregation and Data Visualization</center>

World Happiness Report is an annual report created by the UN Sustainable Development Solutions Network with the intent of guiding policy. The report assigns each country a happiness score based on the answers to a poll question that asks respondents to rank their life on a scale of 0 - 10.

It also includes estimates of factors that may contribute to each country's happiness, including economic production, social support, life expectancy, freedom, absence of corruption, and generosity, to provide context for the score. Although these factors aren't actually used in the calculation of the happiness score, they can help illustrate why a country received a certain score.

# Questions

The following are the list of questions we need to find out in the dataset.

* How can aggregating the data give us more insight into happiness scores?
* How did world happiness change from 2015 to 2017?
* Which factors contribute the most to the happiness score?

# Findings

Checkout the notebook [here](exploring_whr.ipynb)

# Data set

You can download the dataset [here](https://www.kaggle.com/unsdsn/world-happiness)

The data set is a CSV file called [`World_Happiness_2015.csv`](https://www.kaggle.com/unsdsn/world-happiness). Below are descriptions for columns:

|**Column**|**Description**|
|---|---|
|**`Country`**|Name of the country.|
|**`Region`**|Name of the region the country belongs to.|
|**`Happiness Rank`**|The rank of the country, as determined by its happiness score.|
|**`Happiness Score`**|A score assigned to each country based on the answers to a poll question that asks respondents to rate their happiness on a scale of 0-10.|
|**`Family`**|The estimated extent to which family contributes to the happiness score.|
|**`Freedom`**|The estimated extent to which freedom contributes to the happiness score.|
|**`Generosity`**|The estimated extent to which generosity contributes to the happiness score.|
