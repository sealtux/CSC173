# CSC173 — Activity 03: Computer Vision on My Own Photos

## 1. Overview

I completed the computer vision notebook using my own photographs. The activity covered image representation, convolution, pooling, pretrained CNNs, feature maps, Grad-CAM, Vision Transformer patches, and transfer learning.

## 2. Photos and Dataset

For Parts 1–6, I used my own photos of everyday objects, including a chair, clock, electric fan, inverter, and keys.

For Part 7, I created a dataset containing two classes:

- **Ballpen:** 20 original photos
- **Sunglasses:** 20 original photos

I photographed the objects from different angles, distances, and positions. The dataset contained 40 photos, with 30 used for training and 10 for validation.

## 3. Results

I trained a classifier using pretrained MobileNetV2 with its original layers frozen and a new classification layer.

- Transfer learning validation accuracy: **100%**
- CNN trained from scratch validation accuracy: **60%**
- Transfer learning trainable parameters: **2,562**
- CNN from scratch parameters: **23,714**

I also tested the transfer learning model on a new ballpen photo that was not included in the dataset. The model correctly classified it as a ballpen with a displayed confidence of 100%.

## 5. Tools and Assistance

- **Google Colab:** Used to execute the notebook.
- **Python, TensorFlow/Keras, NumPy, Matplotlib, and Pillow:** Used for image processing, model training, and visualization.
- **ChatGPT (OpenAI):** Used to help understand CNN and Vision Transformer concepts, complete notebook TODOs, explain code, and interpret model outputs .

All photographs were taken by me. I performed the experiments and reviewed the results using my own dataset.

