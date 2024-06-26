## Notebook Summary

This notebook develops a YOLOv8 model for detecting football players. The main steps include:

1. **Dataset Creation**: Using Roboflow to create and annotate the dataset.
2. **Model Training**: Training the YOLOv8 model on Google Colab.
3. **Results**: Evaluating the trained model's performance on test images.
4. **Final Detection**: Applying the trained model to detect football players in a video.


# YOLOv8 Football Player Detection

This repository contains the code and instructions for detecting football players using the YOLOv8 object detection model.

## Introduction

YOLOv8 (You Only Look Once version 8) is the latest iteration of the object detection and image segmentation model developed by Ultralytics. It is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and image segmentation tasks.

## Dataset Creation

The dataset was created and annotated using [Roboflow](https://roboflow.com/). Roboflow facilitates the preparation and annotation of images for training object detection models.

## Model Training

The YOLOv8 model was trained on Google Colab. Google Colab provides a cloud-based computation environment, allowing the use of GPUs to accelerate model training.


## Results

### Model Performance

The trained model was evaluated on test images to verify its performance.

*Training curves:*
![results](https://github.com/ChristianthomasBADOLO/yolo-v8-football-player-detection/assets/167626485/ad471afd-b05c-4e8b-841a-740c231704b1)

*Confusion matrix*
![confusion_matrix](https://github.com/ChristianthomasBADOLO/yolo-v8-football-player-detection/assets/167626485/24365e33-0612-4355-a8ea-c08fc32a0440)

*Example:*
![results_box](https://github.com/ChristianthomasBADOLO/yolo-v8-football-player-detection/assets/167626485/83ed2a0e-d571-43c1-bcef-d1bacbc9b86d)

### Final Detection in a Video

The trained model was used to detect football players in a video. Here is an example of the detection output:

*Final Detection Video:*

https://github.com/ChristianthomasBADOLO/yolo-v8-football-player-detection/assets/167626485/5fd2d486-8e75-4c4e-a2cd-9c53c7aeedbf

## References

- [YOLOv8 Documentation](https://github.com/ultralytics/ultralytics)
- [Blog Post on Training YOLOv8](https://blog.roboflow.com/how-to-train-yolov8-on-a-custom-dataset)
- [YouTube Tutorial](https://youtu.be/wuZtUMEiKWY)
