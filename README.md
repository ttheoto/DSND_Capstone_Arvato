### DSND_Capstone_Arvato

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The [xgboost](https://xgboost.readthedocs.io/en/latest/python/) package should be installed, as well as [Imblearn](https://imbalanced-learn.readthedocs.io/en/stable/).
The code should run with no issues using the Anaconda Package (Python versions 3.*.)

## Project Motivation<a name="motivation"></a>

In this project, I analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information
for the general population. I've used unsupervised learning techniques (k-means) to perform customer segmentation, identifying the parts of the
population that best describe the customer base of the company. Then, I applied what I've learned on a third dataset with demographics 
information for targets of a marketing campaign for the company, and used a model to predict which individuals are most likely to convert into customers for the company. This model was then submitted into a [Kaggle Competition](https://www.kaggle.com/c/udacity-arvato-identify-customers/).

## File Descriptions <a name="files"></a>

Unfortunately, the dataset offered by **AZ Direct GmbH** cannot be published. The analysis and meta data can be found under:

- Arvato_Project_Workbook.ipynb: The main notebook, where the complete analysis can be found
- DIAS Information Levels - Attributes 2017.xlsx: a top-level list of attributes and descriptions, organized by informational category
- DIAS Attributes - Values 2017.xlsx: a detailed mapping of data values for each feature in alphabetical order
- DIAS_Attributes_Summary_DSND1.csv: includes attribute data types and missing data mapping

## Results<a name="results"></a>

**Clustering: How do the current customers differ from the population at large?**
* In summary, we notice that older, financially prepared individuals, as well as richer, educated, luxury car owners are more likely to be the mail-order customers. In contrast, financially conservative, suburban families, together with online educated individuals, living in central areas, are less likely to be the company’s customers.

**Prediction Model: Which individuals are most-likely to respond to a marketing campaign and to become customers?**
* A XGBoost Regression Model was used, but led to unsatisfactory results (AUC = 0.57). A detailed analysis can be found in my [Medium post](https://medium.com/@t.theoto/segmenting-customers-and-supporting-a-targeted-marketing-campaign-a-data-science-approach-60fe4eee2b06)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I must give credit to Udacity and Bertelsman Arvato for the data. The use of the **AZ Direct GmbH** data is solely to complete the data mining task which is part of the **Unsupervised Learning** and **Capstone** projects for the Udacity Data Science Nanodegree program. Using the **AZDirect GmbH** data in any other context is prohibited.

Otherwise, feel free to use the code here as you would like! 

If you have any comments or feedback, do not hesitate to contact me via the comment session of my [Medium post](https://medium.com/@t.theoto/segmenting-customers-and-supporting-a-targeted-marketing-campaign-a-data-science-approach-60fe4eee2b06)!
