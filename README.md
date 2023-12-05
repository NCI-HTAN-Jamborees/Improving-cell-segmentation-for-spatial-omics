# Improving-cell-segmentation-for-spatial-omics
## Problem statement 
Spatial-omics are widely used in biological research to investigate various aspects of biological systems such as identifying key cellular groups that co-occur in a tissue. First key step to answer such biological questions is to perform segmentation to get the cells. There have been various methods that have been developed to perform the task of cell segmentation in imaging data but they either require manual labels as part of algorithm training or do not generalize well to different datasets. Recently, there have been significant progress made in the field of foundation models such as ChatGPT that have been trained on large amounts of data that are capable of performing various self-supervised tasks. One example of this, Segment Anything Model (SAM) is well-suited for cell-segmentation in imaging data. One major advantage of using SAM is that it does not require ground truth labels as part of its training and can predict segmentation masks based upon prompts such as points or bounding box that assist in object localization within the image. As there are various specialized segmentation models out there such as MESMER and CellPose our goal was to test whether we could use the output of these specialized models as input for SAM to improve the cell segmentation in images. 

## Basic Workflow 

## Tools used

## Future directions

## Team 
