# Machine-Learning-Practice

## m1 Linear Regression
- Dataset: sns.load_dataset('tips')
- EDA: 
>- describe statistics
>- correlation
>- graphical summary
- OLS Regression
- Multiple Linear Regression
- Diagnostic and collineari

## m2 Linear Regression
- Dataset: sns.load_dataset('diamonds')
- Understand domain knowledgde

## m3 Classification
- Dataset: bankloan.csv
- Variance inflation factor (check multicolliearity)
- Model Interpretation
- Train test split
- Validation (accuracy score)
- Normalization (to avoid bias)
- KNN

## m4 KNN & Decision Tree
- Dataset: white_wine.csv
- KNN: finding best K
- Decision tree 

## m5 Generalization
- Dataset: bankloan.csv
- Splitting data: train set & test set
- Manual hyperparameter tuning for KNN, Decision Tree, Ridge, Lasso

## m6 Data Preparation & Feature Engineering
- Dataset: sns.load_dataset('tips')
- Preprocessing
- Scaling
- Encoding
- Data transformation
- Model Properties: coefficient

## m7 Imputer
- Dataset: melb_data.csv
- Simple imputer

## m8 Binning Effect
- Dataset: disk.csv
- Binning with pd.cut & KBinsDiscretizer
- Feature selection
- Feature Importance

## m9 Model Evaluation
- Dataset: white_wine.csv
- Confusion matrix
- Metric evaluation

## m10 Cross Validation & Hyperparameter Tuning
- Dataset: bankloan.csv
- Stratified K Fold
- Grid search and Randomized search

## m11 Imbalance Dataset
- Dataset: bankloan.csv
- Threshold optimization
- Resampling: Undersampling & Oversampling

## m12 Ensemble Model
- Dataset: white_wine.csv
- Voting Classifier
- Random Forest
- Decision Boundaries

## m13 Boosting
- Dataset: adult.csv
- Adaptive Boosting
- Gradient Boosting
- Extreme Gradient Boosting (XGBoost)

## m14 Unsupervised Learning
- Dataset: Mall_Customers.csv
- PCA
- K-Means
>- Elbow method
>- Silhoutte score

## m15 Agglomerative, K-Means, & DBScan Clustering
- Dataset: Mall_Customers.csv
- Dendrogram

## m16 Text Mining
- Dataset : sms_spam_collection.csv
- Preprocessing 1:
>1. converting to lower case
>2. contraction
>3. remove or convert number into text
>4. remove punctuation
>5. remove white spaces
>6. remove stopwords and particular words
- Preprocessing 2:
>1. Stemming (mengubah kata berimbuhan menjadi kata dasar)
>2. Lemmatization (mengubah kata berimbuhan/kata yg telah berubah menjadi kata yg ada di dalam kamus)
- Text Exploration
>1. Text frequency
>2. Word Cloud
>3. Length of sentence (number of character)
- TF-IDF (Term Frequency - Inverse Document Frequency)
- DTM (Document Term Matrix)

## m17 Recommendation System
- Dataset : Anime.csv
- Cosine similarity
- Tokenization with CountVectorizer (convert a collection of text documents to a vector of term/token counts)
- Content Based Filtering
- Movie Scoring/User Feature Vector

## m18 Recommendation System Multiple User
