# Large-scale: MCM, LS-MCM, SVM, LS-SVM
This is large scale Minimal complexity machines and Least squares minimal complexity machines code using SGD, with both multiclass classification and multi-targer regression functionality. The code uses multiclass loss by weston and watkins for MCM, Crammer and Singer's rule for LS-MCM and uses Bi and Bennet's rule for performing regression. You can select non-mercer kernels as well for SVM, MCM ,LS-MCM and LS-SVM and perform L1, L2 and elastic net penalty. The updates are done in primal and one can use kernel features or random fourier features and Nystrom features for learning non-linear hyperplanes. Thus, to scale up kernel methods it uses fixed size kernel using quadratic renyi entropy or kmeans.

## Code
The code is written in Python 3.6 and requires the following packages
* sklearn,
* scipy,
* numpy 
* pandas

All packages except can be found in Anaconda python installation.

## Examples
To run on test dataset for classification run
1) classification_2D_MCM2.py 
The toolbox gives only two options for algo_type, but choosing C1 = 0 for both MCM and LS-MCM and choosing 'l2' as reg_type results in SVM primal and LS-SVM primal respectively

To run on test dataset for regression run
1) regression_2D_MCM2.py  (to be uploaded soon)


## Citation
If you use the code please cite the following papers using the bibtex entry:

```
@article{sharma2017large,
  title={Large-Scale Minimal Complexity Machines Using Explicit Feature Maps},
  author={Sharma, Mayank and Soman, Sumit and Pant, Himanshu and others},
  journal={IEEE Transactions on Systems, Man, and Cybernetics: Systems},
  volume={47},
  number={10},
  pages={2653--2662},
  year={2017},
  publisher={IEEE}
}

@article{sharma2018ultra,
  title={Ultra-Sparse Classifiers Through Minimizing the VC Dimension in the Empirical Feature Space},
  author={Sharma, Mayank and Soman, Sumit and Pant, Himanshu and others},
  journal={Neural Processing Letters},
  pages={1--33},
  year={2018},
  publisher={Springer}
}

```

## Research Paper
The papers for the same are available at:

http://ieeexplore.ieee.org/abstract/document/7942005/
https://link.springer.com/article/10.1007/s11063-018-9793-9
