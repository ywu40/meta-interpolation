# SAVFI - Meta-Learning for Video Frame Interpolation

#### Myungsub Choi, Janghoon Choi, Sungyong Baik, Tae Hyun Kim, Kyoung Mu Lee

Source code for CVPR 2020 paper "Scene-Adaptive Video Frame Interpolation via Meta-Learning"

[Project](https://myungsub.github.io/meta-interpolation) | [Paper](https://arxiv.org/abs/2004.00779)

<a href="https://arxiv.org/abs/2004.00779" rel="Video"><img src="./figures/SAVFI_paper_thumb.jpg" alt="Paper" width="100%"></a>


## Model

<center><img src="./figures/fig_1.png" width="90%"></center>

- Download pretrained models from [[Here](https://www.dropbox.com/sh/4pphxdw8k3j34dq/AABRr61SSw09zVgfjYXlaHe3a?dl=0)]


## Dataset Preparation

- [ [Vimeo90K Septuplet dataset](http://toflow.csail.mit.edu/) ]
- [ [Middlebury-OTHERS dataset](http://vision.middlebury.edu/flow/data/) ] - download `other-color-allframes.zip` and `other-gt-interp.zip`
- [ [HD dataset](https://github.com/baowenbo/MEMC-Net#hd-dataset-results) ] - download the original ground truth videos [[here](https://merced-my.sharepoint.com/:u:/g/personal/wbao2_ucmerced_edu/EU-1cwJsIGJLmGsIz6a30sEBo-Jv2DWcw65qElR5xwh6VA?e=spBaNI)]


## Results

- Qualitative results for VimeoSeptuplet dataset

<center><img src="./figures/fig_qual.png" width="100%"></center>

- Qualitative results for Middlebury-OTHERS dataset

<center><img src="./figures/fig_qual_supp_middlebury.png" width="100%"></center>

- Qualitative results for HD dataset

<center><img src="./figures/fig_qual_supp_hd.png" width="100%"></center>


### Additional Results Video

<center><a href="https://www.dropbox.com/s/6h4hyeiuoulzyk7/07235-supp-video.mp4" rel="Video"><img src="./figures/thumb.png" alt="Video" width="70%"></a></center>


## Citation

If you find this code useful for your research, please consider citing the following paper:

``` text
@inproceedings{choi2020meta,
    author = {Choi, Myungsub and Choi, Janghoon and Baik, Sungyong and Kim, Tae Hyun and Lee, Kyoung Mu},
    title = {Scene-Adaptive Video Frame Interpolation via Meta-Learning},
    booktitle = {CVPR},
    year = {2020}
}
```

## Acknowledgement

The main structure of this code is based on [MAML++](https://github.com/AntreasAntoniou/HowToTrainYourMAMLPytorch).
Training scripts for each of the frame interpolation method is adopted from: [[DVF](https://github.com/lxx1991/pytorch-voxel-flow)], [[SuperSloMo](https://github.com/avinashpaliwal/Super-SloMo)], [[SepConv](https://github.com/sniklaus/sepconv-slomo)], [[DAIN](https://github.com/baowenbo/DAIN)], [[CAIN](https://github.com/myungsub/CAIN)]
We thank the authors for sharing the codes for their great works.
