# ESTMC
Official implementation of our TPAMI work:

**“Anchors Crash Tensor: Efficient and Scalable Tensorial Multi-view Subspace Clustering”**

**📄 [Paper with Appendix](./Manuscript%20with%20Appendix.pdf)**

# Datasets

This repository provides five multi-view datasets: NGs, BBCSport, CCV, HW, and BDGP_fea. Additional datasets are available from [this collection](https://github.com/wangsiwei2010/large_scale_multi-view_clustering_datasets).

### Note on sample ordering

**The datasets provided here are pre-sorted by class, with samples from the same class grouped together.** This ordering can favor certain tensor-based clustering methods, particularly those that apply the FFT along the sample mode. We therefore recommend evaluating these methods under randomly shuffled sample orders to assess their robustness to sample permutations.

For further discussion of sample-order sensitivity and methods designed to address it, please refer to the following works:

- [SE-FTMC](https://github.com/jijintian/SE-FTMC) (ACM MM 2025)
- [Cor-SVD](https://github.com/jijintian/Cor-SVD) (NeurIPS 2026)
- [GFT-TMC](https://github.com/jijintian/GFT-TMVC)

# Citation
If you find our repository useful, please consider citing "Anchors Crash Tensor: Efficient and Scalable Tensorial Multi-view Subspace Clustering"
``` js
@article{ji2025anchors,
  title={Anchors Crash Tensor: Efficient and Scalable Tensorial Multi-view Subspace Clustering},
  author={Ji, Jintian and Feng, Songhe},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year={2025},
  publisher={IEEE}
}

```
