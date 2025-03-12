# SFDI-net

SFDI-net is built using a convolutional neural network (CNN) architecture inspired by the U-net framework suitable for image-to-image translation.

# Data Description

## Data Files

The data is stored in **[.bmp]** format and is located in the folder **[Demonstration]**.

The **[TrainDATA]** folder contains the complete dataset used for model training, saved in **[.zip]** format. Upon decompression, a **[.mat]** file is obtained, which is used for training the model.

# Code Description

## main.py

This script generates the two-dimensional results of MTF (Modulation Transfer Function) and physiological parameters.

## SFDI-net.py

This file defines the architecture of the SFDI-net model.

## Three_phase.py

This module provides the functionality for MTF demodulation.

## my_model_SFDInet.h5

This file contains the trained weights for the SFDI-net model.
