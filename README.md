# Course Name: Neural Networks and Application [EC61409]
## LSTM Architecture for Human Activity Recognition - Course Project: Prof. Debashish Sen [Aug’21-Nov’21]      


(This is an implementation project)

This project finds the opportunity for applying the LSTM architecture from recurrent neural network (RNN) to real world problem. The objective of the project is to predict six human activities like walking, sitting, upstairs, downstairs, standing, laying using the data obtain from Accelerometer (Acceleration measurement) and Gyroscope (Angular Velocity measurement) sensors used in smartphone or smart watches. Our dataset is public domain UCI data set[2]. The LSTM architecture which is used to solve the problem with only one layer of LSTM, which effectively avoiding the gradient vanishing problem.  

Without using handcrafted engineered features and trying out various classical machine learning technique, this LSTM model gives accuracy more than 90%. It increases if the dataset is huge. 

Finally the accuracy, loss and confusion matrix of UCI data set was analysed. From the confusion matrix it is showing the excellent classification of data points amongst six classes. Also from the loss plot of training and testing it is clear that our model is converging.
