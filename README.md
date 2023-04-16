## Project Summary - 
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

## Steps Involved:

### Importing Libraries: 
First of all I have imported all libraies requiered for this project.

### Loading the dataset: 
In this step i have loaded the dataset and discovered that our dataset contain 7787 rows and 12 columns.

### Data Set Information:
Here I have checked the information of dataset and discovered that some of variable of dataset contains null values,duplicate value is not present in dataset and dtype of all variables are object except released year.

### Data Wrangling:
In this step,I have changed the date_added column dtype to datetime format and we have extracted year and month from that and made two seperate columns.Also made two seperate dataframe for movies and tvshows and Changed the duration of movies and tvshows dataframe into string.

### EDA on features:
In this step i have performed analysis on dataset starting from Univariate than Bivariate and after that Multivariate Analysis.

### Hypothesis Testing:
Here we have perfomred some hypothesis testing on our dataset.

### Feature Engineering & Data Pre-processing:
In this step i have performed null value treatment and as a part of feature engineering we have done textual data processing which includes:expand contraction, lower casing, removing punctuations and stopwords, normalization,and vectoriztion. We performed data scaling using standardscalar, and dimensionality reduction using PCA.

### Model Implementation:
In this step we perform clustering using different algorithms, we tried K-Means, ElbowCurve, DBSCAN, Dendogram, Agglomerative Clustering.

### Recommendation System:
Lastly we have made content based recommendation sysytem.
