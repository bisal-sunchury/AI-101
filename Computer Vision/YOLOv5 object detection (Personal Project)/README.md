
YOLOv5 object detection

Key Features

- Uses **YOLOv5s pre-trained model** for object detection.  
- Validates the model on COCO 2017 dataset.  
- Detects multiple objects in custom images with **bounding boxes and confidence scores**.  
- Demonstrates the full workflow from **setup → validation → prediction**.

---

How It Works

Notebook 1: Setup&Validation_YOLOv5.ipynb
1. Clones the YOLOv5 repository and installs required packages.  
2. Downloads the COCO 2017 validation dataset.  
3. Evaluates the YOLOv5s pre-trained model on COCO images.  
4. Runs detection on sample COCO images and optionally on user-uploaded images.

Notebook 2: Image_Prediction.ipynb
1. Loads the YOLOv5s pre-trained model using PyTorch Hub.  
2. Uploads custom images from your computer.  
3. Predicts objects in the images, printing detected classes with confidence scores.  
4. Displays images with bounding boxes highlighting detected objects.

---

Requirements

```text
torch
torchvision
opencv-python
matplotlib
pandas
PyYAML
tqdm
seaborn




(Use pip install -r requirements.txt to install all dependencies.)





How to Run

Open "Setup\_and\_Validation.ipynb" to download YOLOv5 and validate on COCO dataset.
Open "Image\_Prediction.ipynb" to run predictions on your own images.
Replace images in the "images/" folder with your own if needed.



