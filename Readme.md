# Pedestrian Detection using YOLO CNN Model

This project implements pedestrian detection using a YOLO (You Only Look Once) convolutional neural network model. The YOLO model is a state-of-the-art object detection system that is efficient and accurate.

## Getting Started

To run this project, follow these steps:

1. **Clone the repository** to your local machine.
2. **Install dependencies** by running `pip install -r requirements.txt`.
3. **Download YOLO Weights**: Download the YOLOv3 pre-trained weights from [here](https://pjreddie.com/media/files/yolov3.weights) and place the weights file in the same directory as your project files.
4. **Understand the Code**: Go through the provided Python code in the `people.ipynb` Jupyter Notebook. This notebook loads the YOLOv3 model with pre-trained weights and performs pedestrian detection on either a custom image or a default video.
5. **Run the Code**: Open the `people.ipynb` Jupyter Notebook and run all the cells in the notebook.
6. **Deployment**: In the last cell, you have two options:
   - If you want to use the default pedestrian video provided in the project, enter "default".
   - If you want to use your own photo or video for pedestrian detection, enter "custom" and provide the path to your photo or video when prompted.


## Files Included

- `test/`: Directory containing test files.
- `coco.names`: File containing the names of the COCO dataset classes.
- `people.ipynb`: Jupyter Notebook containing the code for pedestrian detection.
- `working.mov`: Default pedestrian video provided for testing.
- `yolov3.cfg`: YOLOv3 model configuration file.
- `yolov3.weights`: Pre-trained YOLOv3 model weights.

## Usage

You can use this project for various applications such as pedestrian detection in surveillance systems, autonomous vehicles, and more.



