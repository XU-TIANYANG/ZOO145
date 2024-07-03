


# ZOO145

145 video sequences with 20 categories from the zoo, forming a new test set for animal tracking, coined ZOO145.

## [Learning Adaptive Spatio-Temporal Inference Transformer for Coarse-to-Fine Animal Visual Tracking: Algorithm and Benchmark](https://link.springer.com/article/10.1007/s11263-024-02008-8). (IJCV 2024)

## 🦙🐻🐦‍⬛🐫🦫🐱🦌🐶🐘🦊🦢🐎🐪🐵🕊️🦝🦡🦏🐯🦓

### 🐂Illustrations🐈

<div align='center'>
<img src="https://github.com/XU-TIANYANG/cakes/blob/master/ZOO145.png" width=100%>
</div>

### 🐒Statistics Analysis🐅

We list the number of videos (#Videos), number of images (#Images), average number of images per video (#ImagesPerVideo), average object size (AvgSize), standard deviation of object size (SDSize), average motion change (AvgMC), standard deviation of motion change (SDMC), average scale change (AvgSC), standard deviation of scale change (SDSC).

|       Dataset       | #Videos | #Images | #ImagesPerVideo |   AvgSize  |  SDSize  | AvgMC |  SDMC | AvgSC | SDSC |
| ------------------- | ------- | ------- | --------------- | ---------- | -------- | ----- | ----- | ----- | ---- |
| Camouflaged Animals |    9    |  0.84K  |       93        |      -     |     -    |   -   |   -   |   -   |   -  |
|         MoCA        |   141   |  37.3K  |       264       | (382, 291) | (16, 13) | 19.38 | 28.06 | 1.08  | 0.15 |
|      AnimalSOT      |   162   | 312.9K  |      1967       | (234, 192) | (14, 12) | 5.91  | 9.99  | 1.04  | 0.45 |
|        ZOO145       |   145   | 278.1K  |      1918       |  (71, 62)  |  (8, 7)  | 3.22  | 3.94  | 1.05  | 0.72 |

### 🦌Description and Download Links for ZOO145🦓
Though the collected AnimalSOT dataset exhibits comparable volume in terms of videos and images against existing general tracking benchmarking datasets, e.g., OTB2015, UAV123, and TC128, most of the videos are collected from the internet, lacking coverage of specific animal habitats or gathering. To this end, we further captured 145 videos from the local zoo for a particular description of the animals. The average size of ZOO145 is 71 × 62 pixels, with an average motion change and scale change being 3.22 pixels and 1.05, respectively. ZOO145 reflects more challenging factors in terms of object size, diverse scale change, and similar appearance clutters. As shown in the above figure, we collected 20 species of animals. The total number of images in ZOO145 is 278.1K, with an average of 1918 frames per video. Besides, we manually annotated the bounding boxes for the first 600 images in each video, providing accurate ground truth for animal tracking evaluation. 5 experts are involved in the annotation process. Each sequence was annotated by 1 expert, and verified and corrected by other 2 experts.

1. You can download ZOO145 from [Google Drive](https://drive.google.com/file/d/1gxWK6t0bp6UjhdBoqiPiPdPxW2173IEA/view?usp=sharing_eil_se_dm&ts=668299fb).

2. You can download ZOO145 from [Baidu Netdisk](https://pan.baidu.com/s/1Ce7TkimTJoxTKLq0TiUA5w) (Extraction code:ZOO0).

### 🦊Description and Download Links for AnimalSOT🦢
This dataset contains 159 video sequences from existing tracking test datasets, i.e., 9 videos from OTB2015, 133 videos from LaSOT Test, 13 videos from VOT2016, and 7 from VOT2018. There are 312.9K frames totally, with an average of 1967 frames per video, providing more possible animal appearance variations than Camouflaged Animals and MoCA. The average size of AnimalSOT is $234\times 192$ pixels, with an average motion change and scale change being 5.91 pixels and 1.04, respectively.

1. You can download AnimalSOT from [Google Drive](https://drive.google.com/file/d/1sCNtzeMQjCPOK36VjLW6Nqzmx5m7pHHX/view?ts=6684a08f).

2. You can download AnimalSOT from [Baidu Netdisk](https://pan.baidu.com/s/19Qj_BpCydmfo0aSzgH8Qiw) (Extraction code:asot).

### 🙊Structure🐼

```
ZOO145 
├── list.txt
├── ZOO145.json
├── /alpaca1/
│  ├── /color/
│  │  ├── 00000001.jpg
│  │  ├── 00000002.jpg
│  │  ├── ... ...
│  │  └── 00003000.jpg
|  ├── alpaca1.txt
|  ├── alpaca1_rect.txt
|  ├── groundtruth_rect.txt
|  ├── init_rect.txt
├── ... ...
└── /zebra6/
   ├── /color/
   │  ├── 00000001.jpg
   │  ├── 00000002.jpg
   │  ├── ... ...
   │  └── 00001500.jpg
   ├── zebra6.txt
   ├── zebra6_rect.txt
   ├── groundtruth_rect.txt
   ├── init_rect.txt

```

## 🐾Citing ZOO145🐾

```
@article{xu2024learning,
  title={Learning Adaptive Spatio-Temporal Inference Transformer for Coarse-to-Fine Animal Visual Tracking: Algorithm and Benchmark},
  author={Xu, Tianyang and Kang, Ze and Zhu, Xuefeng and Wu, Xiao-Jun},
  journal={International Journal of Computer Vision},
  volume={132},
  pages={2698--2712},
  year={2024},
  publisher={Springer}
}
```
