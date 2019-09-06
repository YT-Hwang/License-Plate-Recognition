# License-Plate-Reader

## Objective
1) Develop an image processing program that detects the bounding boxes of the vehicles’
license plates in the context images. Use the meta data for validation. The algorithm
should be able to define the rectangular area around the license plate at a similar level of
accuracy as the original LPR system.
Evaluation Metric: Number of test samples where the complete license number is
enclosed in the computed bounding box. The perfect score is 100%.

2) Develop a recognition algorithm to extract the license numbers (Vehicle Registration
Number, VNR) from the ir_patch images. Use the meta data for validation. The original
LPR system made a few mistakes. You should correct those mistakes; and validate against
the corrected labels.
Evaluation Metric: Average of Levenshtein Edit Distance between actual and predicted
VNR over test samples. The perfect score is 0.


## Dataset
The data set comprises 1839 images from a single license-plate-reader (LPR) over a period of
several days. There are three files for each vehicle: The “context” image showing the vehicle,
the “ir_patch” with the cropped license plate, and an XML file with metadata.

