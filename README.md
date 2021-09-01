# ExploratoryDataAnalysis_Haberman
Analyzing data set to summarize their main characteristics, often with visual methods.
The dataset used above is available here [data](https://www.kaggle.com/gilsousa/habermans-survival-data-set).


Goal: To understand correlation between features and class labels





Conclusion:
Observation: Simple EDA is not conclusive enough to witness any strong correlation between features and class labels.By looking at the graphs generated, all we can say is Class label is not lineraly seprable. Heatmap shows some correation between 'axil_nodes' and 'survival_status'.

One of the discrepancy can be seen in class labels category itself as '1' stands for people who lived for 5 or more years and '2' stands for person died within 5 years of being operated. A better parameter would have been cause of death as the person who lost their lives within 5 years may have some other reason as a contributing factor. Apart from this category '1' specificalls is confusing as person may or may not be alive so there is an uncertainty about the current status of the patients who belong to category '1'.
