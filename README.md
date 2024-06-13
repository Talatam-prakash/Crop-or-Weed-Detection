## Crop or Weed Detection using Yolo and Roboflow

1. Download the dataset from Kaggle using the command: `kaggle datasets download -d ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes`.
2. Create a new dataset using the Roboflow computer vision tools. Roboflow takes images and labels as input.
3. Roboflow performs data preprocessing and augmentation, and creates a new dataset with YOLO model weights and data.
4. Import the dataset using the Roboflow API key and import the YOLOv8 algorithm through Ultralytics.
5. Train the YOLOv8 model using `data.yaml` and training data.
6. Test the model using test and validation data.
7. Predict the test images with bounding boxes and class names.

Note:1. All implementation is done in Google Colab. I use session storage for data location. 
2. A 'runs' directory is created when the YOLO model is performing.

