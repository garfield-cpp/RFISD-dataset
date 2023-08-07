# RFISD-dataset
## Overview
The dataset is aimed for ship detection in SAR images with radio frequency interference (RFI). It contains 11988 SAR images whose sizes are 800*800. The intensity of RFI ranges from -2.5 dB to 5 dB, with step size 0.5 dB.
## Label format
The labels of our dataset is written in txt format. Each line of the txt file correspondes to a single ship. The dataset is labelled in horizontial bounding box (HBB). The format is label_index，center_x， center_y，width，height.

|Item|Description|
|-|-|
|label_index|set to 0|
|center_x|The x coordinate of the center point of the ship|
|center_y|The y coordinate of the center point of the ship|
|width|The width of the ship|
|height|The height of the ship|

The signal-to-interference-and-noise ratios are written in the xlsx file. The first column is the index of the image and the second column is the SINR of the image.
The corresponding image without RFI is put in the folder 'clean'.
** After the publication of the paper, the dataset will be made public. **
