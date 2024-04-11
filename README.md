# YOLO Custom Classification with State Farm Distracted Driver Detection Dataset
This repository contains code for training a YOLO (You Only Look Once) model on a custom dataset using the State Farm Distracted Driver Detection Dataset. The trained model is capable of classifying images into the following categories:

- c0: normal driving
- c1: texting - right
- c2: talking on the phone - right
- c3: texting - left
- c4: talking on the phone - left
- c5: operating the radio
- c6: drinking
- c7: reaching behind
- c8: hair and makeup
- c9: talking to passenger


## Dataset
The dataset used for training the model is available on Kaggle and can be accessed <a href="https://www.kaggle.com/competitions/state-farm-distracted-driver-detection/data" style="color: blue;">here</a>. It contains labeled images of distracted drivers in various scenarios, which are categorized into the classes mentioned above.

## Training Notebook
The notebook train_yolo_custom.ipynb provided in this repository demonstrates how to train the YOLO v8 model using the custom dataset.
