# Heart-Disease-Prediction-Machine-Learning
Predict aniographic vessel diameter narrowing 

This data set is from the UCI Machine Learning library and can be found here: http://archive.ics.uci.edu/ml/datasets/Heart+Disease 

Description: 

This data set currently contains 303 instances, some of which aren't complete (some features may be missing for a certain instance). In the case that this happens, the instance has been removed. There are 14 relevant features which have been extracted, from a maximum of 76 in the total dataset. 

While this is a very small dataset and therefore is not at all a robust model, it serves as a great exercise to get a classifier set up on a laptop very quickly with some interesting data.

The target variable is feature number 14, which is a narrowing in any major blood vessel due to cholesterol and plaque deposits, as detected through the use of an angiogram. More info about coronary heart disease can be found here: https://www.mayoclinic.org/diseases-conditions/coronary-artery-disease/symptoms-causes/syc-20350613

Feature #14 has also been reduced to a binary problem to detect the presence of any vessel narrowing. In the unprocessed data set, the range of values for that feature are from 0 to 4, indicating which vessel(s) are narrowing. 

Performance Specs: 

Random Forest Classifier - 83% accuracy
