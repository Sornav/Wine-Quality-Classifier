# Wine-Quality-Classifier
Wine Quality Classification using Random Forest Classifiers and K-Folds Cross Validation on the wine-red data set,in the first step we performed all the visualization to find the features which affect the output the most,then we preprocessed the data set and assigned quality as per a specific range followed by which we used label encoder and standard scalar to standardize the data,after which the dataset was ready to be fed into the classifier,we found that in the data set the number of Bad Quality wines are much more than the Good Quality ones,So we specifically chose a Random Forest Classifier because a Tree based classifier works best with higly Unbalanced data,which is the case here,upon fitting with a Random Forest Classifier with 120 estimators we found the accuracy to be around 88%,so we tried to optimize it futher using K-Folds Cross Validation Technique with 10 folds upon which the accuracy increased to around 91%,thereafter we implemented an Artificial Neural Network to see if we can improve the estimations,but Neural Network also did not help us to improve much,so we applied drop out regularization technique to eliminate over/under fitting which gave good results,after that to optimize further we used Hyper Parameter Tuning on our Neural Network.


          
          
          
          ***important****

*Note:I usually visualize my data by using Plotly Library,so if you are having trouble viewing them in the GitHub viewer, you are free to clone my repository on your local machine and check them out in jupyter notebook,other wise follow the step below.

*Please copy the Notebook URL and paste it on:-http://nbviewer.jupyter.org/

            ******Peace Out*******
