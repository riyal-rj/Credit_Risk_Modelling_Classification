Project : Credit Risk Modelling using Machine Learning

Datasets: Real life Dataset from a renowned bank 
		1) Internal details dataset
		2) cbil dataset

Aim of the Project : To classify the persons into 4 classification P1,P2,P3,P4 based on the about 72 features

Various sorts Data Preprocessing is and done and the two excel files are joined on the common feature PROSPECTID

Analyzing the dependency of Numerical Features  with the Target Variable using Chi square Test

Analysing the Multicollinearity of the Categorical Features using VIF. 

Checking the association of Categorical Features and  Target Variable and selecting those satisfying the criteria using ANOVA.

Finetuning the final dataset with 8classification Models using GridSearchCV

Models Used are: Logistic Regression
		 KNN
		 SVM
		 Adaboost
		 XgBoost
		 Random Forest
		 Decison Trees
		 LightGBM

For all these models we calculated the accuracy and Confusion Matrix and came to final conclusion that the XgBoost Model was performing the best with 78% accuracy


We also came to conclusion that the model before and after Standardization has no improvement in the accuracy.

And finally saved the model into a pickle file which can be used later for deployment.
