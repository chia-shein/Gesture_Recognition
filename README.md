# Gesture_Recognition
* This code mainly wants to train a Skeleton-based recognition model and apply it on Raspberry Pi.
* I chose simple gesture recognition as an example.

## MediaPipe
* An open-source framework developed by Google Research and proposed in June 2019 for building multimedia machine-learning applications.
![](./readme_img/mediapipe.png)
## Environment
```shell
  conda create –n gesture python=3.8.11
  conda activate gesture
```
## Dependencies
```shell
  pip install tensorflow==2.3.0
  pip install tensorflow-gpu==2.3.0
  pip install opencv-python
  pip install mediapipe
  pip install sklearn
  pip install matplotlib
```
## Making libraries code
1. draw_keypoints.py:　Related settings for joint point drawing．
2. get_keypoints.py: Extract the joint points of the left and right hands and bring them together.
3. mediapipe_tool.py: Image joint point prediction.

