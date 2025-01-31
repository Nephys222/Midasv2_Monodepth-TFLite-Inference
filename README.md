# Midas v2.1 & other Monocular Depth TFLite Inference
 Python scripts to perform monocular depth estimation using Python with the Midas v2.1 small Tensorflow Lite model. Tested on Windows 10, Tensorflow 2.8.0 (Python 3.7).

# Requirements

 * **OpenCV**, **Numpy** and **tflite (or tensorflow)**. **pafy** and **youtube-dl** are required for youtube video inference. 
 
# Installation
```
pip install numpy opencv-python tflite tensorflow
pip install pafy youtube-dl
```

# Midas v2.1 small ([link](https://tfhub.dev/intel/lite-model/midas/v2_1_small/1/lite/1))

 * **Input**: RGB image of size 256 x 256 pixels.
 * **Output**: Inverse relative depth map with 256 x256 pixels.
 * **Inference speed**: - 30 FPS on Iphone 11 NPU and 22 FPS on OnePlus8 GPU (Snapdragon 865).
 
# Examples

 * **Image inference**:
 
 ```
 python imageDepthEstimation.py 
 ```
 
  * **Webcam inference**:
 
 ```
 python webcamDepthEstimation.py
 ```
 
  * **Video inference**:
 
 ```
 python videoDepthEstimation.py
 ```
 
 # [Inference video Example](https://youtu.be/e161_lZps9c)
 
 Original video: https://youtu.be/TGadVbd-C-E (by Nagasaki Biopark)
 
 
