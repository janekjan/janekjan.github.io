+++
title = 'Classification of Pedestrian Activity via Computer Vision'
date = 2022-05-01T15:00:00+02:00
+++

Classification of Pedestrian Activity via Computer Vision is my university 3rd year project. It tackles the problem of real-time temporal video classification. The problem could be decomposed into the following goals:
* Create a video recognition model that takes into account temporal data, which means that the classification considers how the object changes over time rather than each frame separately
* The model has to be performant - possibly able to process close to or above 25 frames per second on a consumer-grade GPU. At the time, no such open source model was available.
* The system should easily adapt to different models, which should ideally be plug-and-play

The project has mostly reached these goals. The end result is a 3-step pipeline that by default uses YOLOv3 for object detection, SORT for object tracking and a small bespoke 3D-CNN for classification. On test footage (160x120 30fps) it reached accuracy of 70,5% when classifying from among 6 activities and speed of above 25fps for up to dozens of objects.

Final report of the project is available to download as a PDF here: **[PDF](/report-computer-vision.pdf)**

You can view the model and try it for yourself here: (soon)

If you want to improve or discuss the project, please do let me know!

## Related blog posts

