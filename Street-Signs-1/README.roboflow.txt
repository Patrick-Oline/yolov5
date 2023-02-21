
Street Signs - v1 2023-02-20 2:15pm
==============================

This dataset was exported via roboflow.com on February 20, 2023 at 10:16 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 92 images.
Street-Signs are annotated in YOLOv5 Oriented Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:

The following transformations were applied to the bounding boxes of each image:
* Random rotation of between -25 and +25 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically


