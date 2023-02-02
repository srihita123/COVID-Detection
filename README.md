# PredictCOVID
Built various ML models to detect COVID using blood test results and predict the severity of COVID for a given patient.

We first classified blood test data taken from patients in a hospital in Brazil from March 28 to April 3 2020. The data consists of the blood test data as well as a COVID test result. Then, we cleaned the data by setting a threshold for the number of NaN data points and normalized the remaining data. We used Scikit-Learn to test different ML models on this data to see which models yielded the highest accuracy. The models we tried included Random Forest, Naive Bayes, K Nearest Neighbors, MLP, and more. After testing all the ML models by using a training and testing set, we created confusion matrices to visualize the model's accuracy on the testing set. The Gaussian Process Model proven to have the highest accuracy for COVID detection while the Random Forest model had the highest accuracy for COVID severity detection. 


Google Colab Link to my code contribution to this project : https://colab.research.google.com/drive/1dCCliUZI3wmcwQ2qY3p4y8bwOilRuid1?usp=sharing 

Acknowledged in https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009719#abstract0 
