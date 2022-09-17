# Wine-Quality-Predictor

![wine3](https://user-images.githubusercontent.com/100641752/190864152-3d2f5147-21fc-47fc-b847-c124c4909745.jpg)

#### Project Description/Outline
Our team was looking to create a machine learning model to determine the quality of red variants of the Portuguese "Vinho Verde" wine based on certain characteristics of the wine.

We pulled the following dataset from Kaggle to use for this project. This dataset includes a total of 12 columns, 11 of them are the characteristics of wine and one column is the quality of the wine.

https://www.kaggle.com/code/nugrahapurnamaaji/regression-clustering-wine-quality-dataset/data

#### Steps for Analysis
1. Created a database and table within PostgresSQL and uploaded the CSV file into the table
2. Pulled the data from PostgresSQL into Python
3. We checked for null values or missing data to ensure that the data was cleaned and ready for analysis.
4. Created the model using the cleaned data
5. Uploaded the CSV file, we created some images in Tableau

#### Conclusion
Based on our dataset, we decided to use a Supervised learning model. We looked into multiple Supervised learning models to determine the best one to use for the project. After reviewing the models and their summary scores, we determined that the best model to use was Support Vector Classifier. Based on the analysis, we could see that there only a few characteristics of the wine that can help determine the quality.

In this repository, we have the Jupyter notebook with the data and the model, the CSV file within the Resources folder, the schema that was used to create the table in PostgresSQL, an Images folder for images that were created in Tableau, and our powerpoint for the presentation.

Team Members: Derek Mast, Rolly Costillas, Erin Buday, Muhammad Malik

Dataset to be Used

https://www.kaggle.com/code/nugrahapurnamaaji/regression-clustering-wine-quality-dataset/data
