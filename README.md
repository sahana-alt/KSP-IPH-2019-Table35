# KSP-IPH-2019-Table35
MoRTH 
The git repository contains the approaches we have used for the prediction and analysis of data.
The final csv file namely FINAL.CSV.xlsx was preprocessed and constructed using al the data given to us.
There were 13 datasets given to us for analysis and all of the tabes were inter related.
Establishing the relations between the tables was a huge and a tedious task.
The tables(csv files) were sent into the dataiken platform individually and relations between the tables were 
considered to join the tables.
The join operation was a huge and a tedious task and hence the data preprocessing was done using using the local host
server such as XXamp. Using XXamp all the tables were related as in the details given in the readme file of the dataset.
The constraints were specified in the database locally created and the final table with all the joined and related attributes were obtained .
Data preprocessing was again done where the unwanted attributes were identified and removed.
The final dataset is uploaded to the git repository and is used by the Naive_Bayes_Classifier.

The approach used to build the naive_bayes_classifier is specified in the file naive_bayes.ipynb .This
contains the code for the implementation of the naive_bayes_classifier. This model predicted an accuracy of about 52% which is considerable based on 
the parameters we had.
The alternative approach to predict accuracy was using the artificial neural networks.This model used the dataset FINAL.xls for the analysis.
This xls file was also generated using the table joins as specified earlier.This artificial neural networks is the core of the neural networks.

The apriori algorithm was used to generate frequently occuring pattern in the dataset. Based on the occurrence of the patterns, certain rules were 
generated. The apriori algorithm used the Accident_Information.csv to perform the task of generating frequent itemsets.( https://drive.google.com/open?id=1MLRfXy4Vt5yVidjRiTdUb-v6ZZ4Ulb6k.)
This is the dataset link. 

We have also considered satellite imagery to perform anaysis and prediction.
