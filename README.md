# PyTorch implementation of  [**Change Detection in Synthetic Aperture Radar Images Using a Dual Domain Network**](https://arxiv.org/pdf/2104.06699.pdf). 

## in *IEEE Geoscience and Remote Sensing Letters*, 2021.

by Xiaofan Qu, Feng Gao, Junyu Dong, Qian Du, Heng-Chao Li



Our code is tested on the [Google Colab](https://colab.research.google.com/) with free GPU. We will provide Google Colab demo as soon as possible. 



If you have any questions, please contact us. Email: 17864195195@163.com , gaofeng@ouc.edu.cn



## Introduction

Change detection from synthetic aperture radar (SAR) imagery is a critical yet challenging task. Existing methods mainly focus on feature extraction in spatial domain, and little attention has been paid to frequency domain. Furthermore, in patch-wise feature analysis, some noisy features in the marginal region may be introduced. To tackle the above two challenges, we propose a Dual-Domain Network. Specifically, we take features from the discrete cosine transform domain into consideration and the reshaped DCT coefficients are integrated into the proposed model as the frequency domain branch. Feature representations from both frequency and spatial domain are exploited to alleviate the speckle noise. In addition, we further propose a multi-region convolution module, which emphasizes the central region of each patch. The contextual information and central region features are modeled adaptively. The experimental results on three SAR datasets demonstrate the effectiveness of the proposed model.

![](https://gaopursuit.oss-cn-beijing.aliyuncs.com/2021/files/20210422000148.jpg)



