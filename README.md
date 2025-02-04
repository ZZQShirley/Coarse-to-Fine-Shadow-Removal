# Semantic-guided Coarse-to-Fine Diffusion Model for Self-supervised Image Shadow Removal
### [Paper](https://arxiv.org/pdf/2407.01104)

**Semantic-guided Coarse-to-Fine Diffusion Model for Self-supervised Image Shadow Removal**
<br>_Ziqi Zeng, Chen Zhao, Weiling Cai, Yuqing Guo_<br>
In CVM'2025


#### News
* **Feb 04, 2025**: Release the training and testing codes.

## Framework

<p align=center><img width="80%" src="doc/framework.jpg"/></p>

## Requirement
* Python 3.7
* Pytorch 1.7
* CUDA 11.1

## Datasets
* ISTD [[link]](https://github.com/DeepInsight-PCALab/ST-CGAN)  
* ISTD+ [[link]](https://github.com/cvlab-stonybrook/SID)
* SRD [[Training]](https://drive.google.com/file/d/1W8vBRJYDG9imMgr9I2XaA13tlFIEHOjS/view)[[Testing]](https://drive.google.com/file/d/1GTi4BmQ0SJ7diDMmf-b7x2VismmXtfTo/view)
[[Mask]](https://uofmacau-my.sharepoint.com/personal/yb87432_um_edu_mo/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fyb87432%5Fum%5Fedu%5Fmo%2FDocuments%2Fghost%2Dfree%2Dshadow%2Dremoval%2Fsrd%5Fmask%2Ezip&parent=%2Fpersonal%2Fyb87432%5Fum%5Fedu%5Fmo%2FDocuments%2Fghost%2Dfree%2Dshadow%2Dremoval&ga=1)
 (detected by [DHAN](https://github.com/vinthony/ghost-free-shadow-removal))

## References
Our implementation is based on [Mask-ShadowGAN](https://github.com/xw-hu/Mask-ShadowGAN) and [IR-SDE](https://github.com/Algolzw/image-restoration-sde). We would like to thank them.

Citation
-----
Preprint available [here](https://arxiv.org/pdf/2407.01104). 

In case of use, please cite our publication:

Z. Zeng, C. Zhao, W. Cai, Y. Guo, "Semantic-guided Coarse-to-Fine Diffusion Model for Self-supervised Image Shadow Removal" .

Bibtex:
```
@article{zeng2024semantic,
  title={Semantic-guided adversarial diffusion model for self-supervised shadow removal},
  author={Zeng, Ziqi and Zhao, Chen and Cai, Weiling and Dong, Chenyu},
  journal={arXiv preprint arXiv:2407.01104},
  year={2024}
}
```

## Contact
If you have any questions, please contact shirley0323@qq.com.
