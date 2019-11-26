# Ballistic_Experiment_Analysis
This first stage of the code is developed in **Jupyter Notebooks**, due the flexibility and ease of management. The program uses a trained model to recognize and locate bullets through frames and further image analysis is done to extract location, inclination and derive velocities and angle. The aim of this program is to help the researchers in the areas of impact dynamics to do faster analysis.

1. Checking MASK RCNN dependency
1. Extracting Images from video
   1. Testing the model in one image
1. Predict Bullet Locations.
   1. Creation of ROI Matrix (X,Y,HEIGHT,WIDTH) of each frame values.
1. ROI Adjustment
   1. Creation of Data_Analysis matrix.(Time,X,Y,Width,Height,Length,Cx,Angle,Distance Traveled,Relative Velocity,Total velocity)

## SETUP FILES

## MASK RCNN
The training of the model to recognize bullets was done using **MASK RCNN**. To use this application is necessary to also clon the **MASK RCNN** repository. Even when the masking property of the algorithm is a good advantage to the application, for this stage was not used, instead of that just the location (bounding box) was implemented. Nevertheles, further improvements will include the masking technique, which was the main reasons why MASK RCNN was choosen.
[MASK RCNN](https://github.com/matterport/Mask_RCNN)
