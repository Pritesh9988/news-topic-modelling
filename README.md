Project title - Topic Modeling on News Articles

Problem statement – 
              Identify major Topics/themes across a collection of BBC news articles using different topic modeling techniques.

Data Description – 
•	Dataset has total 2225 rows and 2 columns.
•	In that articles are given in news column and article types are given in type column.
•	Both columns have object data type.
•	There is no null value in dataset.

Data Analysis –
•	There are five types of news in our dataset which are business, entertainment, politics, sport and tech. 
•	In that highest number of news are from sport category having count 505. 
•	Business category also has higher count with 503 which is very close to sport category. • Tech category contains lowest count is 347.

Data Processing-
•	Removing HTML tags and url.
•	Removing Numbers and Special Characters.
•	Removing Stopwords.
•	Removing punctuations.
•	Applying Lemmatization.

Models Used – 
•	Latent Dirichlet  Allocation (Gensim) 
•	Latent Dirichlet Allocation (LDA) (Sklearn) with TF-IDF vectorizer 
•	Latent Dirichlet Allocation (Sklearn) with count-vectorizer and Bi-gram 
•	Latent Semantic Analysis (LSA)

Conclusion –
•	LDA (Sklearn) with TF-IDF vectorizer along with NMF 
Were best to identify the 5 given clusters.
•	Scope of implementing neural network in future. 
•	As a future work, using one of the topic modeling 
algorithms, we can implement various applications for 
recommending research articles, analyzing news articles 
etc., which can be used for segregation of documents 
from topic.
