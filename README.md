# YOLOv8 Object Detection with Camera and Video Input

This project uses the trained best.pt model from the [3.ipynb](https://github.com/alinavirabyan/CNN/blob/main/3.ipynb) notebook to perform real-time object detection.

## Features:

Uses the best.pt weights trained in the 3.ipynb file.
Performs object detection using a webcam if available.
If no webcam is detected or accessible, it allows selecting a video file and performs detection on the chosen video.
This flexible approach ensures detection works both in live camera environments and with prerecorded videos.

## Results:

The model was trained for 200 epochs and achieved very good detection accuracy.
Even though training stopped halfway, the model performs well on the images and videos tested.
