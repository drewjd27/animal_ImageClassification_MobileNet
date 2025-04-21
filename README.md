# Multiple Class Image Classification 🐄🐈🐔 | 95% Accuracy

## About
This project demonstrates a multiple-class image classification model trained using MobileNet V2. The dataset consists of 10 classes of animal images. The model was trained using Kaggle's T4 x2 GPU to accelerate the training process. The final model achieves 95% accuracy on both the training and test datasets.

The project includes exporting the trained model into multiple formats:
- TensorFlow SavedModel
- TensorFlow Lite (TFLite)
- TensorFlow.js (TFJS)

## Setup Environment

### Using Anaconda
```bash
conda create --name main-ds python=3.11.9
conda activate main-ds
pip install -r requirements.txt
```

### Using Shell/Terminal
```bash
mkdir multi_class_image_classification
cd multi_class_image_classification
pipenv install
pipenv shell
pip install -r requirements.txt
```

## How to Re-run the Project

### Running the Notebook
1. Open the `notebook.ipynb` file in your Jupyter Notebook or JupyterLab environment.
2. Execute all the cells sequentially to train or evaluate the model.

### Running Inference
1. Open the `inference.ipynb` file in your Jupyter Notebook or JupyterLab environment.
2. To test the model with a new image:
   - Copy the image to the `images for inference` folder.
   - Update the `image_path` variable in the notebook with the path to your image:
     ```python
     image_path = "images for inference/YOUR_IMAGE.jpg"
     ```
   - Run the cells in the notebook to perform inference.

## Project Structure
```
inference.ipynb               # Notebook for running inference
notebook.ipynb                # Main notebook for training and evaluation
README.md                     # Project documentation
requirements.txt              # Python dependencies
saved_model.keras             # Saved Keras model
images for inference/         # Folder for images used during inference
saved_model/                  # TensorFlow SavedModel format
tfjs_model/                   # TensorFlow.js model files
tflite/                       # TensorFlow Lite model files
```

## Results
The model achieves 95% accuracy on both the training and test datasets. You can visualize the confusion matrix and other evaluation metrics in the `notebook.ipynb`.

## Notes
- Ensure that all dependencies listed in `requirements.txt` are installed before running the notebooks.
- For inference, you can use any image of your choice by placing it in the `images for inference` folder and updating the `image_path` variable in `inference.ipynb`.
````
This documentation provides a clear overview of the project, setup instructions, and steps to re-run the project.
