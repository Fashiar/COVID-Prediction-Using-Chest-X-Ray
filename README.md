# COVID-Prediction-Using-Chest-X-Ray

This Notebook Demonstrate the Calssification of Covid and Normal Cases Using Chest X-ray (CXR) Images. 
This notebook contains three major section:

1. Building and Train the VGG16 model
2. Loading the saved model and converting it into JSON format
3. Infererencing the program (future use)

The data folder contains a dummy set of images. 

The original datset is downloaded from kaggle COVID-19 radiography database (https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)

The images in the dummy dataset folder are the cropped ROI regions from the original images.

The folders are organized as follows

                covid_vs_nor
                  |--train
                      |--images
                      |--masks
                  |--val
                      |--images
                      |--masks
                  |--test
                      |--images
