# ExploratoryDataAnalysis_Haberman
Analyzing data set to summarize their main characteristics, often with visual methods.<br />
The dataset used above is available here [data](https://www.kaggle.com/gilsousa/habermans-survival-data-set).<br />


Goal: To understand correlation between features and class labels<br />

### Probabilty Distribution of 'Survival' based on 'Age' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_1.png)<br />
###  Probabilty Distribution of 'Survival' based on 'Operated Year' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_2.png)<br />
###  Probabilty Distribution of 'Survival' based on 'axil_nodes' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_3.png)<br />
### Box plot 'Age'![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_4.png)<br />
### Box Plot 'Operated Year' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_5.png)<br />
### Box Plot 'axil_nodes' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/survive_6.png)<br />
### Violin plot for 'Age' ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/download%20(1).png)<br />
### Violin plot for 'Operated Year'![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/download%20(2).png)<br />
### Violin plot  for 'axil_nodes'![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/download%20.png)<br />
### Scatter plot explaining relationship between various fields present in data ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/2D-scatter-plot.png)<br />

### Heatmap explaining the correlation between features and class label. ![Alt text](https://github.com/n-e-e-l/ExploratoryDataAnalysis_Haberman/blob/master/img/download%20(3).png)<br />





Conclusion:
Observation: Simple EDA is not conclusive enough to witness any strong correlation between features and class labels.By looking at the graphs generated, all we can say is Class label is not lineraly seprable. Heatmap shows some correation between 'axil_nodes' and 'survival_status'.

One of the discrepancy can be seen in class labels category itself as '1' stands for people who lived for 5 or more years and '2' stands for person died within 5 years of being operated. A better parameter would have been cause of death as the person who lost their lives within 5 years may have some other reason as a contributing factor. Apart from this category '1' specificalls is confusing as person may or may not be alive so there is an uncertainty about the current status of the patients who belong to category '1'.
