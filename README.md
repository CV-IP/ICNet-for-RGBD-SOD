# ICNet-for-RGBD-SOD
   This project provides the codes and results for 'ICNet: Information Conversion Network for RGB-D Based Salient Object Detection', TIP 2020. [Paper link](https://ieeexplore.ieee.org/document/9024241).
   
   Our code is implemented based on the Caffe of FlowNet2. You should first install and compile the caffe according to the [FlowNet2](https://github.com/lmb-freiburg/flownet2). 
   
# Overview
   ![Image](https://github.com/MathLee/ICNet-for-RGBD-SOD/blob/master/Images/Network_Overview_NEW.png)
   
# Saliency maps and Measure results on 8 Datasets
   We provide [saliency maps](https://pan.baidu.com/s/1Bkl7DYdt97orbQX66BufuQ) (code: bqvj) and [measure results](https://pan.baidu.com/s/1oUImRe0zRna0o3-_JLBlXQ) (code: r0b6) of our ICNet on 5 datasets (STEREO, NJU2K, LFSD, DES and NLPR).
   
   We also provide [saliency maps & measure results](https://pan.baidu.com/s/1S6jRKISkwTELmrEm8QtZsA) (code: ujdp) of our ICNet on DUT-RGBD, SIP and SSD datasets.
   
   You can use the [evaluation tool](http://dpfan.net/d3netbenchmark/) to evaluate the result maps.
     
# Testing
1. `test_RGBD.prototxt/` is under `models/`.
2. Download the [trained model](https://pan.baidu.com/s/1N9kvRjMqNwUL6K1cr8gIGA) (code: 6jz7) (`RGBD_iter_25000.caffemodel`), and put it under `models/`.
3. The datasets are under `datasets/`, we provide some testing examples on DES dataset.
4. Run `test_matlab/test_ICNet.m`.
5. Saliency maps are saved under `salmaps/DES/`.
   
# Related works on RGB-D SOD
   (**ECCV_2020_CMWNet**) [Cross-Modal Weighting Network for RGB-D Salient Object Detection](https://github.com/MathLee/CMWNet).
   
# Citation
        @ARTICLE{Li_2020_ICNet,
                author = {Li, Gongyang and Liu, Zhi and Ling, Haibin},
                title = {ICNet: Information Conversion Network for RGB-D Based Salient Object Detection},
                journal = {IEEE Transactions on Image Processing},
                year = {2020},
                volume = {29},
                number = {},
                pages = {4873-4884},
                doi = {10.1109/TIP.2020.2976689},}

If you encounter any problems with the code, want to report bugs, etc.

Please contact me at lllmiemie@163.com or ligongyang@shu.edu.cn.
