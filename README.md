# Colour_Selection_for_Lane_Findings

The script [ColorSelection.py](https://github.com/hamza9305/Colour_Selection_for_Lane_Findings/blob/main/ColorSelection.py) is able to find lane markings on an input image using colour boundaries 

 

![conversion](https://github.com/hamza9305/Fisheye-to-Cylindrical/blob/main/data/conversion.gif)

 

## Description

The script read a fisheye image, projects it to 3D space using the intrinsics and extrinsics parameters and then maps it to a cylindrical panorama using the projection matrix of a cylindrical projection. For this project particularly I have used the [WoodScape](https://github.com/valeoai/WoodScape) dataset which is one of the first publically avaialble fisheye dataset. The dataset also provides the intrinsics and extrinsics parameters of the camera which are used for the project. These parameters can be changed if a different imageset is used and similar results can be obtained.

 

I have also given a detailed explanation on how to change these parameters for a new dataset in ths Scripts section.
