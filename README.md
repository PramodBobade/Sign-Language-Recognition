# Sign-Language-Recognition-using-modified-AlexNet

*Alphanumeric ASL signs recognition by using Deep Learning's AlexNet Model.*

## Requirements

Following are all the packages that need to be installed before running this project.

## Installation

numpy

os 

cv2

random

tensorflow

keras

All the above packages can be installed using the following command(Replace packname with appropriate package name, without quotes):
```bash
pip install "packname"
```

## Usage

For training the images has to be imported from the hands directory. Run the realtraining.ipynb file for training the model and this will eventually save the weights to finalweights.h5 in the present working directory.

For prediction, save the images file to predict in the present working directory. Now run the prediction.ipynb file which will eventually uses the weights from fimalweights.h5 file and prints the output of the prediction.


