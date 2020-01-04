# Style-transfer
Neural style transfer modifies the style of one image with respect to the other.

This project implements the style transfer that has been discussed in the paper: 
https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf 

VGG19 network is used as a feature extractor for both the content and style representation. 
Content and style images are given as inputs, the output image has the content from the content image and style from the 
style image. The goal is to get the content and style in the target image as close as possible to the actual content and style. 

