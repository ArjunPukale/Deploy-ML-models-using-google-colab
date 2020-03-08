# Deploy-ML-models-using-google-colab
How to deploy ML,DL models in google colab<br>

@uthor: Arjun Pukale<br>
contact: arjunpukale@gmail.com<br>
Linkedin: www.linkedin.com/in/arjunpukale<br>

Steps:
1.Train your machine learning/ deep learning model and save the model to your google drive.<br>
2.Create a new colab notebook for the client, which will contain the following:<br>
 .Mount clients drive to the colab<br>
 .Create a new folder in the clients drive for the project.<br>
 .Now download and move the saved model from your google drive to clients drive using the saved model files sharable id<br>
 .Load the saved model from clients drive to the colab noebook<br>
 .Create an appropriate predict function for taking input from client and using the saved model make predictions and give output.<br>
 Note: all these steps are illustrated in the .ipynb notebook given<br>
3.Give this Colab notebook to your client.(The client can now use the model without any dependency issues)<br>

