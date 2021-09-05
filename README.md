# Image-object-detection-and-draw-
Detect objects in an image and draw bounding boxes, boundaries around objects.

## Execution

python Run me.py 

Note:
1. The python file and image file should be in the same folder
2. Change the image file path in this statement before running the python file
   image = cv2.imread('/content/drive/MyDrive/AI_ML_Git/baboon.png')

### Approach to draw borders and contours

The pixels present in an image background form contour. The boundary pixels with same color and intensity are Contours.

We utilise the chain_approx_simple computer vision algorithm to detect contours and draw them.

### LIMITATIONS

Contour detection fails if the image background has same brightness. Unwanted contours and lines are clustered in background. The pixels in background are scattered, clustered, incomplete and multiple incorrect clusters will be present in background.

The Contour detection algorithms work fine for black and white images and images with darker backgrounds and images which are stretched.

If the pixels are of same intensity, interest. The background pixels are clustered.


