# Multiple Class Image Classification 🐄🐈🐔 | 95% Accuracy

## About
I trained a Mobile Net V2 for multiple class (10 classes) image classification. The images on the dataset is about animals. I also use the T4 x2 GPU from Kaggle to trained the model to make the training time faster. I also demonstrate how to perform callbacks during training, and export the model into TF-Lite, Tensorflow JS, and Saved Model. The accuracy on the train and test dataset is 95%.

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.11.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir multi_class_image_classification
cd multi_class_image_classification
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run the inference in the inference.ipynb
```
Re-run the inference.ipynb notebook file. You can also copy a new image to folder "images for inference" and change the image path value in the inference.ipynb
```
