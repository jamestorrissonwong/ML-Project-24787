# ML-Project-24787

Contains the data and code used for the 24787 final project. 

Authors: James Wong, Dailyn Despradel, and Luigi Burda

## Contents
Filtering and Featurization contains the code related to processing the raw EMG signals, filtering them, and extracting features. It also has the raw data and filtered data.  

Classifiers contains all code related to tuning hyperparameters, training the classifiers, and visualizing the results. It also contains pickled files with our featurized data for each of the data sets

## Purpose 
Daily hand movements are used when training upper limb individuals whether through physical or virtual environments. Electromyogram signals are electrical signals acquired from muscles that allow for generated movement classification due to the distinct signature of each movement. The classification of electromyography (EMG) while a participant performs basic hand movements allows for personalized rehabilitation training approaches that could enhance motor performance. Thus, this study proposes the use of machine learning (ML) to select a classifier that best discriminates EMG patterns of a set of muscles while performing grasping movements within a virtual and physical environment. This work concluded that there is a substantial difference between EMG signals in real and virtual environments. All the tested classifiers showed an accuracy on the test set higher than 97\% when classifying in two environments. Given its computational efficiency, this study selected logistic regression as the classifier that best discriminated EMG patterns during object manipulation within the physical and virtual environment.     

