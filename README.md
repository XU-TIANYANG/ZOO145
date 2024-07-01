


# ZOO145

145 video sequences with 20 categories from the zoo, forming a new test set for animal tracking, coined ZOO145.

## [Learning Adaptive Spatio-Temporal Inference Transformer for Coarse-to-Fine Animal Visual Tracking: Algorithm and Benchmark](https://link.springer.com/article/10.1007/s11263-024-02008-8). (IJCV 2024)

## 🦙🐻🐦‍⬛🐫🦫🐱🦌🐶🐘🦊🦢🐎🐪🐵🕊️🦝🦡🦏🐯🦓


### 🐂Illustrations🐈

<div align='center'>
<img src="https://github.com/XU-TIANYANG/cakes/blob/master/ZOO145.png" width=100%>
</div>

#### 🐒Statistics Analysis🐅

We list the number of videos (#Videos), number of images (#Images), average number of images per video (#ImagesPerVideo), average object size (AvgSize), standard deviation of object size (SDSize), average motion change (AvgMC), standard deviation of motion change (SDMC), average scale change (AvgSC), standard deviation of scale change (SDSC).

|       Dataset       | #Videos | #Images | #ImagesPerVideo |   AvgSize  |  SDSize  | AvgMC |  SDMC | AvgSC | SDSC |
| ------------------- | ------- | ------- | --------------- | ---------- | -------- | ----- | ----- | ----- | ---- |
| Camouflaged Animals |    9    |  0.84K  |       93        |      -     |     -    |   -   |   -   |   -   |   -  |
|         MoCA        |   141   |  37.3K  |       264       | (382, 291) | (16, 13) | 19.38 | 28.06 | 1.08  | 0.15 |
|      AnimalSOT      |   162   | 312.9K  |      1967       | (234, 192) | (14, 12) | 5.91  | 9.99  | 1.04  | 0.45 |
|        ZOO145       |   145   | 278.1K  |      1918       |  (71, 62)  |  (8, 7)  | 3.22  | 3.94  | 1.05  | 0.72 |

### 🦌Download Links🦓

1. You can download ZOO145 from [Google Drive](https://drive.google.com/file/d/1gxWK6t0bp6UjhdBoqiPiPdPxW2173IEA/view?usp=sharing_eil_se_dm&ts=668299fb).

2. You can download ZOO145 from [Baidu Netdisk](https://pan.baidu.com/s/1Ce7TkimTJoxTKLq0TiUA5w) (Extraction code:ZOO0).

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
