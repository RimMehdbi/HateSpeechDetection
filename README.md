# HateSpeechDetection
In this project three vector representation baselines were compared to a novel proximity-based feature engineering technique for the task of hate speech detection.
The compared vector represenation techniques are: 

 * Bag Of Word (BOW) with Term frequency (TF) weightning scheme
 * Character N-grams with TF weightning scheme 
 * Bert Word Embedding
 * The proposed approach: a proximity-based term frequency feature extraction wherein words surrounding hate lexicon words are given higher frequency

These vector representations were compared using two classification machine learning models:

* Logistic regression model 
* SVM 

Two data sets were considered to compared the results: 

* Dataset1:  This dataset is composed of 25296 tweets which are labeled (through crowdsourcing) as either hate speech, offensive but not hate speech and non-hate speech. Since
we focused on binary classification (hate speech or non-hate speech), tweets originally
labeled as offensive were re-labeled as non-hate speech. Experiments using this data are found in <a href="https://github.com/RimMehdbi/HateSpeechDetection/tree/main/ExperimentsDataSet1"> Experiments Dataset1</a> 
* Dataset2: The second dataset contains a set of comments and conversations taken
from Gab social network. This data has 33775 records that were manually labeled as hate speech or not. Experiments using this data are found in Experiments using this data are found in <a href="https://github.com/RimMehdbi/HateSpeechDetection/tree/main/ExperimentsDataset2">Experiments Dataset2</a> 
