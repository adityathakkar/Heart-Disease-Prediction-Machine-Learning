# Heart-Disease-Prediction-Machine-Learning
Predict aniographic vessel diameter narrowing with a variety of machine learning algorithms  

This data set is from the UCI Machine Learning library and can be found here: http://archive.ics.uci.edu/ml/datasets/Heart+Disease 

Description: 

This data set currently contains 303 instances, some of which arent't complete (some features may be missing for a certain instance). In the case that this happens, the instance has been removed. There are 14 relevant features which have been extracted, from a maximum of 76 in the total dataset. 

The target variable is feature number 14, which is a narrowing in any major blood vessel due to cholesterol and plaque deposits, as detected through the use of an angiogram. More info about coronary heart disease can be found here: https://www.mayoclinic.org/diseases-conditions/coronary-artery-disease/symptoms-causes/syc-20350613

Feature #14 has also been reduced to a binary problem to detect the presence of any vessel narrowing. In the unprocessed data set, the range of values for that feature are from 0 to 4, indicating which vessel(s) are narrowing. 

Performance Specs: 

Random Forest Classifier - 83% accuracy
Neural Net - 84% accuracy 

Note About Neural Nets: 

With this kind of problem, neural nets should be obtaining 95%+ accuracy scores, but will require thousands of data points to train them, which this data set does not contain. Further work and exploration on this project could include some kind of memory augmented neural net, such as Neural Turing Machines, which has shown to perform well at learning from a small data set (also called 'one shot learning'). 
