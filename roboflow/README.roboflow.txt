
Chicken Detection - v6 2022-11-09 4:50pm
==============================

This dataset was exported via roboflow.com on November 9, 2022 at 1:28 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 368 images.
Chicken are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 50 percent of the image
* Random rotation of between -15 and +15 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random Gaussian blur of between 0 and 1 pixels
* Salt and pepper noise was applied to 5 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Randomly crop between 0 and 20 percent of the bounding box


