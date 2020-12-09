# Learning Feature Sparse Principal Subspace

This paper presents new algorithms to solve the feature-sparsity constrained PCA problem (FSPCA), which performs feature selection and PCA simultaneously. Existing optimization methods for FSPCA require data distribution assumptions and lack of global convergence guarantee. Though the general FSPCA problem is NP-hard, we show that, for a low-rank covariance, FSPCA can be solved globally (Algorithm 1). Then, we propose another strategy (Algorithm 2) to solve FSPCA for the general covariance by iteratively building a carefully designed proxy. We prove (data-dependent) approximation bound and convergence guarantees for the new algorithms. For the spectrum of covariance with exponential/Zipf’s distribution, we provide exponential/posynomial approximation bound. Experimental results show the promising performance and efficiency of the new algorithms compared with the state-of-the-arts on both synthetic and real-world datasets.

![FSPCA](https://github.com/icety3/FSPCA/raw/master/res/fspca.png)

# Citation
If you find our paper or this project helps your research, please kindly consider citing our paper in your publications.
```bash
@article{tian2020learning,
  title={Learning Feature Sparse Principal Subspace},
  author={Tian, Lai and Nie, Feiping and Wang, Rong and Li, Xuelong},
  journal={Advances in Neural Information Processing Systems},
  volume={33},
  year={2020}
}
```



