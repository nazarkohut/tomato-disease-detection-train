# tomato-disease-detection-train
Repository containing code used for training object detection models for tomato🍅 disease identification. 

## Notebooks

**Model training notebooks:**
- train_yolov1.ipynb
- tomato_disease_detection_yolov8_nano.ipynb
- tomato_disease_detection_yolov8_small.ipynb
- Roboflow_EfficientDet_v2.ipynb
- Roboflow_Custom_Detectron2.ipynb

**Results aggregation notebooks:**
- Metrics_for_different_models.ipynb

### YOLO

#### YOLOv1
We used `train_yolov1.ipynb` notebook to train YOLOv1 model, but model training took a lot of time compared to other notebooks, so we were able to train on a small number of epochs and did not include this model in the benchmark.

#### YOLOv8

We trained nano and small versions of YOLOv8 using `tomato_disease_detection_yolov8_nano.ipynb` and `tomato_disease_detection_yolov8_small.ipynb` notebooks respectively. 
The notebooks use ultralitics CLI to perform the task.

### EfficientDet
We used `Roboflow_EfficientDet_v2.ipynb` notebook to train EfficientDet model. The notebook is a slightly changed version of the official Roboflow tutorial notebook.

### Roboflow_Custom_Detectron2
Notebook named `Roboflow_Custom_Detectron2.ipynb` has been used to train and evaluate Faster-RCNN model. Note: GitHub repository downloaded in that notebook has been changed slightly, so you may encounter some problems with different devices.

## Related work
- [Source code](https://github.com/nazarkohut/tomato-disease-detection) for mobile application.
- [Model weights](https://github.com/nazarkohut/tomato-disease-detection-models) trained with these notebooks.



