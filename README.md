# DSND_Capstone_Arvato

CONTENT - TBD

1. [Project Introduction](#intro)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)
5. [Feedback](#fb)

## Project Introduction<a name="intro"></a>

In this project, I analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information
for the general population. I've used unsupervised learning techniques (k-nearest neighbo) to perform customer segmentation, identifying the parts of the
population that best describe the core customer base of the company. Then, I applied what I've learned on a third dataset with demographics 
information for targets of a marketing campaign for the company, and used a model to predict which individuals are most likely to convert into 
becoming customers for the company. This model was then submitted into a [Kaggle Competition](https://www.kaggle.com/c/udacity-arvato-identify-customers/).


## File Descriptions <a name="files"></a>

Unfortunately, the dataset offered by **AZ Direct GmbH** cannot be published. The analysis and other data can be found under:

- Arvato_Project_Workbook.ipynb: The main notebook, where the complete analysis can be found
- DIAS_Attributes_Values_2017.xlsx: a detailed mapping of data values for each feature in alphabetical order
- DIAS_Information_Levels_Attributes_2017.xlsx: a top-level list of attributes and descriptions, organized by informational category

## Results<a name="results"></a>

- Segementation part:    
Using PCA and KMeans, I got the results as follows.
    - The population who tend to be customer: The people who may be adults and usually shop online.
    - The population who might not be customer: The people who are not rich, nor focusing on the brand of cars. However, they tend to use cars often. Some of them might have some anti-society characteristics.    

- Supervised Learning Prediction part:    
The results were not good. For the three models (logistic regression, random forest and k-NN), none of them has good precision even used GridSearch.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Everything need to follow Udacity's Terms of Use and other policies. The use of the **AZ Direct GmbH** data is solely to
complete the data mining task which is part of the **Unsupervised
Learning** and **Capstone** projects for the Udacity Data
Science Nanodegree program. Using the **AZDirect GmbH** data in any other context is prohibited.

## Feedback<a name="fb"></a>

If you have any comments, ideas or feedback, feel free to leave your message either here or the post at [medium](https://medium.com/@musictenors/udacity-data-scientice-nano-degree-capstone-project-create-customer-segmentation-report-for-852d3e6d3180). And thank your in advance !
