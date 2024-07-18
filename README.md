# STFCropNet

## Abstract
Remote sensing-based classification of crops is the foundation for the monitoring of food production and management. A range of remote sensing images, encompassing spatial, spectral, and temporal dimensions, has facilitated the classification of crops. However, prevailing methods for crop classification via remote sensing focus on either temporal or spatial features of images. These unimodal methods often encounter challenges posed by noise interference in real-world scenarios, and may struggle to discriminate between crops with similar spectral signatures, thereby leading to misclassification over extensive areas. To address the issue, we propose a novel approach termed Spatio-Temporal Fusion-based Crop Classification Network (STFCropNet), which integrates high-resolution (HR) images with medium-resolution Time Series (TS) images. STFCropNet consists of a temporal branch, which captures seasonal spectral variations and coarse-grained spatial information from TS data, and a spatial branch that extracts geometric details and multiscale spatial features from HR images. By integrating features from both branches, STFCropNet achieves fine-grained crop classification while effectively reducing salt and pepper noise. We evaluate STFCropNet in two study areas of China with diverse topographic features. Experimental results demonstrate that STFCropNet outperforms state-of-the-art models in both study areas. STFCropNet achieves an overall accuracy (OA) of 83.2\% and 90.6\%, representing improvements of 3.6\% and 4.1\%, respectively, compared to the second-best baseline model.


![image text](https://github.com/DMLL-001/STFCropNet/blob/main/image/network.png "DBSCAN Performance Comparison")


