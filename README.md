# JSIA-ReID

This is the official implementation for JSIA-ReID(AAAI2020). Please refer our paper for more details:

**[[Paper](https://github.com/wangguanan/JSIA-ReID/blob/master/materials/paper.pdf), [Poster](https://github.com/wangguanan/JSIA-ReID/blob/master/materials/final_poster.png?raw=true)] Cross-Modality Paired-Images Generation for RGB-InfraredPerson Re-Identification** 

Guan'an Wang, Tianzhu Zhang, Ynag Yang, Jian Cheng, Jianlong Chang, Xu Liang and Zengguang Hou

![](https://github.com/wangguanan/JSIA-ReID/blob/master/materials/framework.png?raw=true)


## Bibtex

If you find the code useful, please consider citing our paper:
```
@InProceedings{Wang_2020_AAAI,
author = "Guan-An {Wang} and Tianzhu {Zhang} and Yang {Yang} and Jian {Cheng} and Jianlong {Chang} and Xu {Liang} and Zengguang {Hou}",
title = {RGB-Infrared Cross-Modality Person Re-Identification via Joint Pixel and Feature Alignment},
booktitle = {AAAI-20 AAAI Conference on Artificial Intelligence},
year = {2020}
}
```


## Dependencies
* [Anaconda (Python 3.7)](https://www.anaconda.com/download/)
* [PyTorch 1.1.0](http://pytorch.org/)
* GPU Memory >= 20G
* Memory >= 20G


## Dataset Preparation
* SYSU-MM01 Dataset [[link](https://github.com/wuancong/SYSU-MM01)]


## Train
```
# train, please replace sysu-mm01-path with your own path
python main.py --dataset_path sysu-mm01-path --mode train
```


## Experimental Results

* Settings
  * We trained our model with 2 GTX1080ti GPUs.

* Comparison with SOTA
![](https://github.com/wangguanan/JSIA-ReID/blob/master/materials/results.png?raw=true)


## Contacts
If you have any question about the project, please feel free to contact with me.

E-mail: guan.wang0706@gmail.com
