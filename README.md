
# Mask Detection Using TFOD1.x

Just upload an image and find out whether the person is wearing a mask or not




## Highlights


Tensorflow provides a collection of pre-trained models which are trained on COCO dataset, the Kitti dataset, the Open Images dataset, the AVA v2.1 dataset the iNaturalist Species Detection Dataset and the Snapshot Serengeti Dataset. 


Tensorflow Model Zoo : https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md#mobile-models


Do follow the link to understand more about the models.

There are close to 90 classes in the coco dataset for generic usecases.


## Specification


Model - Faster Rcnn Inception Version 2 trained on coco dataset

Dataset - Trained on close to 2000 images annotated using labelimg

GPU - P5000

Epochs - 10000

Training time - Close to 20 minutes






## Installation

To install TFOD 1.x please follow the below article:

https://c17hawke.github.io/tfod-setup/
    
## Run Locally

Clone the project

```python
  git clone https://github.com/akash748/TFOD1.x-Mask-Detector.git
```

Go to the project directory

```bash
  cd Mask-Detector
```

Install dependencies

```python
  pip install -r requirements.txt
```

Start the server




## Demo

Insert gif or link to demo

