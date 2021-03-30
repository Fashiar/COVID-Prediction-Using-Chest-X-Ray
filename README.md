# COVID-Prediction-Using-Chest-X-Ray

This Projects Demonstrate the Calssification of Covid and Normal Cases Using Chest X-ray (CXR) Images. 
This projects expalin the following major concepts:

1. Building and Train the VGG16 model
2. Loading the saved model and converting it into JSON format
3. Infererencing the program (future use)
4. Build the feature prediction model uisng transfer learning
5. Generating Class Activation Maps

The data folder contains a dummy set of images. 

The original datset is downloaded from kaggle COVID-19 radiography database (https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)

The images in the dummy dataset folder are the cropped ROI regions from the original images.

The folders are organized as follows

                covid_vs_nor
                  |--train
                      |--covid
                      |--normal
                  |--val
                      |--covid
                      |--normal
                  |--test
                      |--covid
                      |--normal
