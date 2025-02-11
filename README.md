# Object-Detection-using-SSD-MobileNet-v3
This project implements object detection using the SSD MobileNet v3 model with OpenCV's Deep Neural Network (DNN) module. The model is capable of detecting objects in both images and videos in real time.

# Features
- Detects objects in images and videos.
- Uses SSD MobileNet v3 trained on the COCO dataset.
- Supports real-time detection with webcam.
- Displays bounding boxes and class labels.

# Requirements
Ensure you have the following installed before running the project:

- Python 3.x
- OpenCV (latest version)
- Matplotlib
- SSD MobileNet v3 model files

# Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aravindhaloshan/Object-Detection-using-SSD-MobileNet-v3.git
   cd object-detection

2. Install dependencies:
pip install opencv-python opencv-python-headless matplotlib


## Model Files

Download the following model files and place them in the project directory:

- frozen_inference_graph.pb
- ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt
- labels.txt


## Usage

### Detect objects in an image

1.Place an image in the project directory.

2.Update img_path in the script with the correct path to your image.

3.Run the script:
python object_detection.py

4.The detected objects will be displayed with bounding boxes and labels.


### Detect objects in a video

1.Place a video file in the project directory.

2.Update cap = cv2.VideoCapture('your_video.mp4') with the correct path.

3.Run the script:

python object_detection.py

4.The detected objects will be displayed in real-time.



