# Car Detection using YOLOv5 and Detectron2
This repository contains a project that demonstrates how to train object detection models for car detection using YOLOv5 and Detectron2. The main goal is to fine-tune pre-trained YOLOv5 and Detectron2 models on a custom dataset of car images to improve their performance for detecting cars in images specific to the use case.

## Overview
The project is organized into the following steps:

Preparation of the custom car dataset: Splitting the dataset into training and validation sets, and converting the annotations into formats suitable for use with YOLOv5 and Detectron2.
Training YOLOv5 and Detectron2 on the custom car dataset: Running the training scripts with the necessary parameters, such as image size, batch size, number of epochs, dataset configuration files, and pre-trained weights.
Validating the trained YOLOv5 and Detectron2 models: Running the validation scripts with the necessary parameters, such as dataset configuration files, trained weights, image size, IOU threshold, and whether to use half-precision inference.
By following these steps, the project aims to achieve better-performing car detection models fine-tuned for the specific use case.

## Usage
To use this project, clone the repository and follow the instructions in the Jupyter notebook to prepare the custom dataset, train the YOLOv5 and Detectron2 models, and validate their performance.

## Requirements
This project requires Python 3.6 or later and the following Python libraries:

- YOLOv5
- Detectron2
- OpenCV
- NumPy
- Pandas
Additionally, a GPU with CUDA support is recommended for faster training and inference.

To install the required libraries, you can use the following command:

```bash
pip install -r requirements.txt
```
## Acknowledgements
This project is based on the YOLOv5 repository by Ultralytics and the Detectron2 repository by Facebook AI Research (FAIR).
