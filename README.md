# INFO6101-Spam-Classifier
Implementing a Spam Classifier using Naive Bayes and Spark


The datasets for this project can be downloaded from the below links:
1. 1998 dataset - https://drive.google.com/open?id=1QtoxpJmd1lys7c7LaYXiOjbzMdMOpeVX
2. trec07p dataset - https://drive.google.com/open?id=1xaJL1eoccrCyS45xgF23dVY_KCER-oAD


The project is divided into three notebooks :
Part-1 Structuring data: This part reads the text files containing the emails and parses all email fields 
like To, From, Subject, Body etc into a pandas dataframe and saves it as "structured.xlsx"

Part-2 Exploratory data analysis: This part deals with reading the "structured.xlsx" into a dataframe, exploring 
the data to find various features and get an insight into the data.

Part-3 Feature Extraction, Prediction: This part is used to extract the features from the dataset and train, test 
a Multinomial Naive Bayes model and calculate the model's accuracy. 


Packages/Modules needed to run this project are :
nltk, wordcloud, xlrd, numpy, pandas, spark, xlsxwriter, BeautifulSoup, matplotlib, findspark.

Spark 2.3.1 pre-built can be downloaded from here - https://drive.google.com/open?id=1iFVW0RxqL1VNrIOrfJXrDkPHF8ewXH49
To install spark, untar the downloaded file and set the SPARK_HOME environment variable to the spark-2.3.1-bin-hadoop2.7 folder. 


To run the project:
1. Download and untar the datasets in the same directory as the python notebooks.
2. Make sure you have all dependent packages listed above installed.
3. Run Part_1_Structuring_data.ipynb. It will save an excel "structured.xlsx" in the directory.
4. Run Part_2_Exploratory_data_analysis.ipynb.
5. Run Part_3_Feature_Extraction,_Prediction.ipynb.