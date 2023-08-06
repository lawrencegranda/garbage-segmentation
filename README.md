# Garbage Segmentation - Machine Learning & Computer Vision Model
## Project Overview
The Garbage Detector is a machine learning and computer vision project aimed at detecting and segmenting litter objects from images. The project focuses on enhancing environmental sustainability efforts by efficiently identifying waste and promoting cleaner environments.


## Model Architecture
The garbage detection model is built using Python and leverages popular deep learning frameworks - Keras and TensorFlow. The core of the model is based on the [uNet architecture](https://arxiv.org/abs/1505.04597), which has 3,850,629 parameters for precise and accurate segmentation. To expedite the training process and improve performance, the model employs a pretrained EfficientNetB3 backbone with weights pretrained on the [ImageNet](https://www.image-net.org/) dataset.


## Model Performance
After hours of rigorous training, the model achieved impressive results with an Intersection over Union (IoU) score of 0.52 and an F1 score of 0.62. These metrics demonstrate the model's ability to accurately identify and segment litter objects in images, making it a valuable tool for waste detection.


## Acknowledgments
Special thanks to the authors of the [EfficientNet](https://arxiv.org/pdf/1905.11946.pdf) and [uNet](https://arxiv.org/abs/1505.04597) papers, as well as the developers of Keras and TensorFlow for providing powerful deep learning tools.


## Author Information
Name: Lawrence Granda Zarzuela

Project Duration: May 2022 to Jul 2022

Google Colab Link: [Garbage Segmentation Colab](https://colab.research.google.com/drive/1PzKaSvqqe3_QX2fM6iEfWb7Z3rgf9CtR?usp=sharing)
