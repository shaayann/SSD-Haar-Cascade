# SSD-Haar-Cascade

## 1. Titles and Sections:

### Single Shot MultiBox Detector (SSD):
Explores object detection using the SSD MobileNet V2 model, which is loaded from TensorFlow Hub.

### Face Detection using Haar Cascades: 
Implements face detection using Haar Cascade classifiers with OpenCV.

## 2. Libraries Used:

### Core Libraries:
tensorflow, tensorflow_hub, numpy

### Visualization: 
matplotlib, IPython

### Image Processing: 
cv2

## 3. Key Code Snippets:

Loading the SSD MobileNet V2 model from TensorFlow Hub for object detection tasks.

Preprocessing images (resizing and expanding dimensions) to fit the model's input requirements.

Running object detection and extracting bounding boxes, class IDs, and confidence scores.

Filtering detections based on a confidence threshold and visualizing results with bounding boxes.

Converting images from BGR to RGB for visualization using matplotlib.

Using Haar Cascade classifiers for grayscale image-based face detection.

Saving and displaying detected face images using cv2 and IPython.display.
