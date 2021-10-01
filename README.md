# Introduction

Speech is the most natural way of interaction between humans. Speech based devices are used in our daily lives and are a boon for people with speech related disabilities. Speech signals are a function of time variable which is independent and are random sig- nals. Speech signal contains information about speech style, words, expression, accent type, emotion, sex, age, speaker’s identity, the state of health of the speaker etc. Here we are more interested in extracting emotions in speech. In applications like professional driving or flying, or anything that requires continuous monitoring of a persons emotion could use computers to encourage detection of emo- tions, so as to upgrade the recognition procedure and to utilize such data to help improve decisions and to support the basic leadership process. Up until this point, results emerging from machine feeling acknowledgment indicated better execution when contrasted with human feeling acknowledgment.

# Dataset 

We Have used Emo-db dataset in our experiment. It contains about 535 utterances spoken by actors in a happy, angry, anxious, fearful, bored and disgusted way as well as in a neutral version. Source: https://www.kaggle.com/piyushagni5/berlin-database-of-emotional-speech-emodb

# Preprocessing

The Emo-db database before being fed into our classifiers needs to be modified in order to obtain the desired output. Firstly, we need to split the datasets into train and test and then start the proceedings. MFCC imposes a maximum length of the 32,000 ms for input, thus we have to pad the speech wave forms accordingly. If the length is less than the maximum length, the remainder is divided into two halves and padded at the start and end of the speech signal. If the length is more than maximum length, then the extra portion is removed from the start and end.

# Training

We have divided our dataset into training and test set as per 80:20 ratio.For deep learning models class labels has been converted to categorical data. For training of deep learning models we have devoted a validation set of 20% from training set and have made use of callbacks for early stopping to avoid overfitting.

# Results

We computer the confusion matrices for all of our models and got the highest accuracy using Convolutional Neural Networks (86.76%). 

# Conclusion

Four emotion states(Anger, Happy, Sad and Neutral) have been analyzed and tried to be predicted in the speech signals using the features extracted by MFCC. We have noticed that Happy emotion has recorded the least in precision and recall values across all classifiers, indicating that people express happiness in numerous ways which is more individualistic and cannot be ascertained a pattern. However, Angry, Neutral and Sad have consistently been predicted well showing that these emotion states have followed vocal and acoustic pitch patterns that can be identified well. CNN proves to be marginally better as in deep learning method it includes layer processing with less time and the weights are assigned in a way to perform with better accuracy. We also have seen why MFCC is widely used in automatic speech and speaker recognition, it’s capability to accurately represent and extract the useful features have been demonstrated.
