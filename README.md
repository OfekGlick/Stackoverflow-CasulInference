# Stackoverflow-CasulInference

## Description
In this causal research we sought to answer the question "<i>Does adding a code sample to a question in Stackoverflow improve its chances of 
receiving an answer? </i>" <br>
The stages of this project were the following:

<ol>
<li> Data extraction - extracing all necessary features needed to conduct the research </li>
<li> Data preprocessing - simple cleaning (null removal, standardization, etc.), feature engineering</li>
<li> Identification of causal setting - determining whether certain conditions are met which allow us to answer causal questions. </li>
<li> Estimation - estimating the causal effect of the treatment variable "<i>code presence in question</i>" on the target variable "<i>question has an answer</i>" </li>
</ol>
For a full explainantion regarding the project, please refer to the `Project Report.pdf` file.

## What does this repo contain?
<br>
This repository contains:
<ul>
<li> Queries used to extract data from Stackoverflow </li>
<li> Data used in analysis </li>
<li> Jupyter notebook containing all code for preprocessing and analysis</li>
<li> Final project report</li>
</ul>


### Data extraction
To extract data from Stackoverflow we used the [Data Explorer](https://data.stackexchange.com/stackoverflow/query/new) and we based our queries based on the
Stackoverflow [Schema](https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede).<br>
The queries used for extraction are saved in the `Data Extraction Query.txt` file.<br>
Question data is saved in the file `All4.csv` and Tag data is saved `TagsCount.csv`

### Data preprocessing and analysis
All files regarding the preprocessing and analysis of the data in the file `Stackoverflow.ipynb` (you can view `Stackoverflow.pdf` for a pdf view of the notebook).<br>
The notebook contains initial preprocessing, feature analysis, identification measures (as required in causal researches) and estimation metrics. Again, for a more detailed explanation please refer to the `Project Report.pdf`

### Full report
The full report, including conclusions and suggestions for future work is all present in the file `Project Report.pdf`




