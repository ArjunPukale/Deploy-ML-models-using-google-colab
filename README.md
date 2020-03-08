# Deploy-ML-models-using-google-colab
How to deploy ML,DL models in google colab

@uthor: Arjun Pukale
contact: arjunpukale@gmail.com
Linkedin: www.linkedin.com/in/arjunpukale

Steps:
1.Train your machine learning/ deep learning model and save the model to your google drive.
2.Create a new colab notebook for the client, which will contain the following:
 .Mount clients drive to the colab
 .Create a new folder in theclients drive for the project.
 .Now download and move the saved model from your google drive to clients drive using the saved model files sharable id
 .Load the saved model from clients drive to the colab noebook
 .Create an appropriate predict function for taking input from client and using the saved model make predictions and give output.
 Note: all these steps are illustrated in the .ipynb notebook given
3.Give this Colab notebook to your client.(The client can now use the model without any dependency issues)

