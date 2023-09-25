## Acknowledgement

This repo is the fork of [wkentaro/labelme](https://github.com/wkentaro/labelme).

## New Feature

- Save binary mask image separately for each class in an annotated image.
  - save_mask function added to label_file.py. It gets called when save button/option is clicked to save json file containing polygon points' information. Example of output filename: mask_1_P3164031.jpg where mask_1_ represent mask image of class/label 1 and P3164031 is the original filename of image being annotated. 
