# The impact of data balancing and Pre-processing on CNNs Applied to chest x-ray images
Short sample code of data loading, processing, neural network training and testing available here on colab notebook.
The study makes use of 5 fold cross validation, not present in this code.

Sample of images before after edge sharpening:
<img src="https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/before.png" width="100">

![image after](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/after.png | width=100)

This work utilizes Xception Neural network composed of 14 blocks of separable convolutions like so:

![xception block](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/XceptionModule.png)

Folowing this workflow:

![scheme](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/scheme.png)

There was four experiments, one without neither pre-processing nor balancing, one with balancing, one with pre-processing and finally with both.
Results of ROC curves for all four experiments, respectively:


![roc4](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/ROC_RNB_1.png)
![roc3](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/ROC_RB_1.png)
![roc2](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/ROC_IENB_1.png)

Proposed method:

![roc1](https://github.com/hector6298/The-Impact-of-Data-Balancing-and-Pre-processing-on-CNNs-Applied-to-CNNs/blob/master/assets/ROC_IEB_1.png)

More details on sample paper inside assets folder.
