# DataMiningProject
https://www.kaggle.com/competitions/detecting-french-texts-difficulty-level-2022

## Data 
Under this file, you will find our 3 core documents: 
<br><br>
1. sample_submission.csv is the base document to submit the predictions
2. training_data.csv is the first document we are training our models on
3. unlabelled_test_data.csv is the second document we use in our program to submit our preditions
<br><br>

## Code 
Under this file, you will find all our program, from V0.0 to V1.8.2

### 1. DataProjectV0.0
This is our 1st iteration.
1. discover the data and the project
2. only 4 models (no alternativ model like requested) -> LogisticRegression, KNN, Decision Tree, Random Forest
3. Test-size = 0,2 
4. random state = 0
5. No data cleaning
6. Best model is logistic regression (results below) -> cv=5, number of iteration=1000 and random state=0

### 2. DataProjectV1.0
This is our 2nd iteration
1. Same goal as the first iteration
2. implementing 3 news models: support vector classifier, adaboost classifier and MLPC Classifier
4. best model stay Logistic Regression

Regarding our model choices for this part, here are some advantages and disavantages for each: 
#### SVC

#### ADA

#### MLPC


### 3. DataProjectV1.5
This is our 3rd iteration
1. In this one, we introduce DataCleaning, to get better in the leaderboard. 
2. We lower the word of each sentences, both in the training and unlabelled datas
3. Every other aspect stay the same
4. As we can see, the datacleaning process alone does not help our performance.

### 4. DataProjectV1.6(sw)
This is our 4th iteration
1. As datacleaning does not help, we begin the real text analysis
2. we delete the frech stopwords from both databases
3. as we train the 7 models we see that this does not help us at all either. 

### 5. DataProjectV1.7(sw-dc)
This is our 5th iteration
1. To test if the datacleaning had an impact on our previous results, we removed the datacleaning part from DataProjectV1.6(sw).
2. It improve the result slightly, but we did not improved our score.  

### 5. DataProjectV1.8.0
This is our 6th iteration
1. Now, this is the big deal. From now on, we concentrated our efforts to improve the score
2. We introduce tokenization and lemmatization, and we removed punctuation and stopwords
3. Score stay the same, without real amelioration

### 5. DataProjectV1.8.1
This is our 7th iteration
1. basis is the same as DataProjectV1.8.0
2. we introduce text preparation
3. finally, general accuracy scores are improving
4. best accuracy comes from SVC

### 5. DataProjectV1.8.2
This is our 8th iteration
1. basis is the same as DataProjectV1.8.1
2. we introduce bag of word, but we did not achieve to make it running. 
3. to get a better result, we played with the test size and random state: test_size=0.15, random_state=50 seems to get better results

## Approach to the project
Before getting more creative, we followed the course 9 and 10 on Text Analysis. 
To get a little bit of background on our group, Ahmed and myself are totally novice in coding. 
I personnaly have some basics in python due to the fact that the MScIS is my second master, the first one being the MScF from HEC Lausanne. 
We have both a very generic approach to coding. At first, copy-pasting what we have seen in class, before understanding what changes change what. 
We both are fanatics of the "learning by doing" methods. 

## Summary of the results 
Under this section, you will find the tables resuming our results from all iterations: 

### 1. DataProjectV0.0


### 2. DataProjectV1.0


### 3. DataProjectV1.5


### 4. DataProjectV1.6(sw)


### 5. DataProjectV1.7(sw-dc)


### 6. DataProjectV1.8.0


### 7. DataProjectV1.8.1


### 8. DataProjectV1.8.2


## Link to the explainatory video 
