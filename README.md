# Deepstream Smart Shop Analytics

Face Detection and Face Mask Detection and Tracking on Jetson Nano using DeepStream and Python.

## DeepStream Installation

- Deepstream: 5.1
- Jetpack 4.6

### Steps to run the demo:

1. Convert VIDEO from mp4 to h264
```
$ ffmpeg -i /path_to_your_video.mp4 -an -vcodec libx264 -crf 23 /path_to_your_video.h264
```

2. Run
```
$ python3 main.py path_to_your_video.h264
```
