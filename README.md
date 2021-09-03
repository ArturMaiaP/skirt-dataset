# skirt-dataset
Subset of DeepFashion dataset

- Z. Liu, P. Luo, S. Qiu, X. Wang and X. Tang, "DeepFashion: Powering Robust Clothes Recognition and Retrieval with Rich Annotations,"
2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016, pp. 1096-1104, doi: 10.1109/CVPR.2016.124.
- http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html

### Dataset Filtering

Firstly, the data set was restricted to skirt images, diminishing the data set to 13,300 images. This
category was chosen because it was one of the highest populated of the data set. Then, it was necessary to perform
a fine revision of the attributes. Attributes that did not belong to skirts were removed, such as sleeve and
collar types. Next, attributes that referred to the same feature, such as "dots" and "dotted", were merged.
Finally, to guarantee a dense data set with a large variety of images for each feature, attributes that were
present in less than 3% of the images were removed, to guarantee a dense data set with a large variety of
images for each feature.

