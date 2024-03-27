<p align="center" width="100%">
<img src="assets/interactive3d.png"  width="30%" height="30%">
</p>
<div align="center">
    <a href='https://scholar.google.com/citations?user=Pee4FRsAAAAJ&hl=en' target='_blank'>Shaocong Dong<sup>1*</sup></a>&emsp;
    <a href='https://dinglihe.github.io/' target='_blank'>Lihe Ding<sup>2,4*</sup></a>&emsp;
    <a>Zhanpeng Huang<sup>3</sup></a>&emsp;
    <a>Zibin Wang<sup>3</sup></a>&emsp;
    </br>
    <a href='https://tianfan.info/'> Tianfan Xue<sup>2</sup></a>
    <a href='https://www.danxurgb.net/'> Dan Xu<sup>1,†</sup></a>&emsp;
</div>
<div>

<div align="center">
    <sup>1</sup>
    <a> The Hong Kong University of Science and Technology</a>&emsp;
    </br>
    <sup>2</sup> <a>The Chinese University of Hong Kong</a>
    </br>
    <sup>3</sup> <a> SenseTime </a>
    <sup>4</sup> <a> Shanghai AI Laboratory </a></br>
    <sup>*</sup> Equal Contribution&emsp;
    <sup>†</sup> Corresponding Author&emsp;
</div>

-----------------

### Interactive3D: Create What You Want by Interactive 3D Generation
[![arXiv](https://img.shields.io/badge/arxiv-2312.04963-b31b1b?style=plastic&color=b31b1b&link=https%3A%2F%2Farxiv.org%2Fabs%2F2312.04963)](https://arxiv.org/abs/2312.04963)
[![website](https://img.shields.io/badge/Project-Website-brightgreen)](https://interactive-3d.github.io/)

### NEWS
- 🔥 Interactive3D got accepted by CVPR24.
- Code will be released soon.

<p align="left" width="100%">
<img src="assets/results.png"  width="100%" height="100%">
</p>

### Framework 
Interactive3D contains two stages with distinct 3D representations: (I) Gaussian Splatting for flexible user interactions such as add/remove parts; geometry transformation; deformable or rigid dragging and semantic editing, (II) the Gaussian blobs are converted to InstantNGP using NeRF distillation and fine-tined by our Interactive Hash Refinement Module.

<p align="left" width="100%">
<img src="assets/arc.png"  width="100%" height="100%">
</p>

## Citation
If the paper and the code are helpful for your research, please kindly cite:
```
@inproceedings{dong2024interactived,
    title={Interactive3D: Create What You Want by Interactive 3D Generation},
    author={Shaocong, Dong and Lihe, Ding and Zhanpeng, Huang and Zibin, Wang and Tianfan, Xue and Dan, Xu},
    booktitle={Conference on Computer Vision and Pattern Recognition 2024},
    year={2024}
}
```
