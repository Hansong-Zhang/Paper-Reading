# Dataset Distillation/Condensation
## Gradient-Matching
+ **Delving into Effective Gradient Matching for Dataset Condensation**
  + *inter and intra class gradient matching*
  + *consider angle*

```bibtex
@article{jiang2022delving,
title={Delving into effective gradient matching for dataset condensation},
author={Jiang, Zixuan and Gu, Jiaqi and Liu, Mingjie and Pan, David Z},
journal={arXiv preprint arXiv:2208.00311},
year={2022}
}
```

+ **[DC] Dataset condensation with gradient matching**
  + *match the gradient of the synthetic dataset and the whole dataset*
  + *simultaneously mimicing the training process, i.e., keep the updating path similar*
```bibtex
@article{zhao2020dataset,
  title={Dataset condensation with gradient matching},
  author={Zhao, Bo and Mopuri, Konda Reddy and Bilen, Hakan},
  journal={ICLR},
  year={2021}
}
```

+ **[DCC;DSAC] Dataset condensation with contrastive signals**
  + *--to do*
```bibtex
@inproceedings{lee2022dataset,
  title={Dataset condensation with contrastive signals},
  author={Lee, Saehyung and Chun, Sanghyuk and Jung, Sangwon and Yun, Sangdoo and Yoon, Sungroh},
  booktitle={ICML},
  pages={12352--12364},
  year={2022},
  organization={PMLR}
}
```

+ **[MTT] Dataset distillation by matching training trajectories**
  + *--matching the model parameters trained on real and synthetic data*
```bibtex
@inproceedings{cazenavette2022dataset,
  title={Dataset distillation by matching training trajectories},
  author={Cazenavette, George and Wang, Tongzhou and Torralba, Antonio and Efros, Alexei A and Zhu, Jun-Yan},
  booktitle={CVPR},
  pages={4750--4759},
  year={2022}
}
```

## Data Augmentation
+ **[DSA] Dataset condensation with differentiable siamese augmentation**
  + *apply data augmentation on both real and synthetic data*
```bibtex
@inproceedings{zhao2021dataset,
title={Dataset condensation with differentiable siamese augmentation},
author={Zhao, Bo and Bilen, Hakan},
booktitle={ICML},
pages={12674--12685},
year={2021}
}
```








# Coreset Selection
+ **Moderate coreset: A universal method of data selection for real-world data-efficient deep learning**
  + *select the samples that are close to the median of certain metric (e.g. intra-class distance)*
```bibtex
@inproceedings{xia2023moderate,
  title={Moderate coreset: A universal method of data selection for real-world data-efficient deep learning},
  author={Xia, Xiaobo and Liu, Jiale and Yu, Jun and Shen, Xu and Han, Bo and Liu, Tongliang},
  booktitle={ICLR},
  year={2023}
}
```

+ **[GraNd-score;EL2N-score] Deep learning on a data diet: Finding important examples early in training**
  + *GraNd-score: points with larger gradient norms*
  + *EL2N-score: data points with larger norms of the error vector that is the predicted class probabilities minus one-hot label encoding*
```bibtex
@article{paul2021deep,
  title={Deep learning on a data diet: Finding important examples early in training},
  author={Paul, Mansheej and Ganguli, Surya and Dziugaite, Gintare Karolina},
  journal={NeurIPS},
  pages={20596--20607},
  year={2021}
}
```

+ **[Forgetting] An empirical study of example forgetting during deep neural network learning**
  + *select data points that are easy to be forgotten during training*
```bibtex
@article{toneva2018empirical,
  title={An empirical study of example forgetting during deep neural network learning},
  author={Toneva, Mariya and Sordoni, Alessandro and Combes, Remi Tachet des and Trischler, Adam and Bengio, Yoshua and Gordon, Geoffrey J},
  journal={ICLR},
  year={2019}
}
```









