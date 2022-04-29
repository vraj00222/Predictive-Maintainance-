# Predictive-Maintainance-
This is my 6 semester machine learning project based on research paper

project defination:-
project definition is predictive maintenance, In which we find the need of maintenance in a car before even having damage or 
issue in hardware or software part from the data of sensors we get from different systems.


->Install


    This project requires Python and the following Python libraries installed:

    NumPy

    Pandas

    matplotlib

    scikit-learn
Dataset Details :-

 i have used a predictive maintenance dataset from kaggle. It has 10,000 data points in it and  features :-

	Air temperature
	process temperature 
	rotational speed  
	torque  
	tool wear 

 it is about when failure occurs which means when there is a need of maintenance so for that it has binary data of 0 and 1 and in 1 there are 6 types of different classes for failures like :-

	heat dissipation failure
 	no failure 
 	overstrain failure 
 	power failure 
 	random failure 
 	tool wear failure 


->predictive_maintaince.csv :- Is my dataset for the project it has 10,000 data points it is a dataset of cars when it needs the 
				maintainence and when not it is referred as failure in dataset as binary numbers as 0( no need of maintaince or No failure ) and 1
				( need of maintaince or failure)

->project knn :- Is the file in which i have applied knn algorithm on my project to predict the target class and each class individually and by accuracy and 
		confusion matrix we can easily see that is the code is baised towards the 0 or 1 and that problem is solved by oversampling.  	

-> project RF :- In this file i have applied random forest to the target class for predicting the failure or not but for predicting the failure of 
		each class individual i have individual file ,  i have applied random forest on each of them like , heatdissiption_projectRf , overstrain_projectRF ,
		Toolwearfailure_projectRF , Powerfailure_projectRF , Randomfailure_projectRF this are the code files in which i have find the accuracy of 
		predicting each class. 
		
-> SVM project :- Is the file in which i have applied SVM algorithm on my project to predict the target class and each class individually and by accuracy and 
		confusion matrix report we can easily see that is the code is baised towards the 0 or 1 and that problem is solved by oversampling. 
		
By applying three different algorithms on same dataset i have learned that how it predict for the class by using different algorithms and how it gives different values like imbalanced data
was not much effecting in Random forest but it was effecting in different algorithms so we needed to do the over sampling on data set so it can give output without being baised 
