# Brain Tumor Image-Segmentation
The Tumor Segmentation Dataset is designed specifically for the TumorSeg Computer Vision Project, which focuses on Semantic Segmentation. The project aims to identify tumor regions accurately within Medical Images using advanced techniques.

we use U-net to Image-Segmentation

we also use yolov8 to do this project and the details in yolo folder

## Install
* python = 3.8

* numpy = 1.19.2

* tensorflow-gpu = 2.6.0

* matplotlib = 3.4.0

1.
```
git clone https://github.com/gndd1221/Brain-Tumor-Image-Segmentation.git
cd Brain-Tumor-Image-Segmentation
```
2.
```
conda env create --file environment.yaml --name <name>
```

## Usage

run the main.ipynb

## result

| Accuracy |   Loss   | Val Accuracy | Val Loss |
|----------|----------|--------------|----------|
| 0.9791   | 0.1996   | 0.9804       |  0.1849  |

| Train dice | Val dice  | test dice |
|------------|-----------|-----------|
| 0.6875     | 0.7027    | 0.6967    |
