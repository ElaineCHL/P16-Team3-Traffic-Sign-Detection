Samples of 100.zip contains 100 traffic sign images taken from the Chinese Traffic Sign Database, which will be used to be fed into the traffic sign detection pipeline.

image_coordinates.txt contains the information of the 100 images in "Samples of 100.zip". It contains the filename, size of image, and ground truth of the traffic sign bounding box coordinates.


/*
 * ## Acknowledgement
 * 
 * Code in calc_IOU function is adapted from:
 * [1] A. Rosebrock, “Intersection over Union (IoU) for object detection,” PyImageSearch, Nov. 07, 2016.
 * https://pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/
‌
 * 
 * Author: Adrian Rosebrock
 * Title of the Post: "Intersection over Union (IoU) for object detection"
 * Platform: pyimagesearch
 * Date Published: Nov. 7, 2016
 * Online Availability: https://pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/
 * Date Accessed: Sep. 5, 2024
 * /


/* Code in mask_image function is adapted from:
 * [1] M. Maulion, "Color image segmentation [image processing]," Medium, Jun. 23, 2020. [Online].
 * Available: https://mattmaulion.medium.com/color-image-segmentation-image-processing-4a04eca25c0. [Accessed: Jul. 31, 2024].
 * 
 * Author: M. Maulion
 * Title of the Post: "Color image segmentation [image processing]"
 * Platform: Medium
 * Date Published: Jun. 23, 2020
 * Online Availability: https://mattmaulion.medium.com/color-image-segmentation-image-processing-4a04eca25c0
 * Date Accessed: Jul. 28, 2024
 * /