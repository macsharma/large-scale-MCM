# large-scale-MCM
This is large scale Minimal complexity machines code using SGD, with both multiclass classification and multi-targer regression functionality. The code uses multiclass loss by weston and watkins and uses Bi and Bennet's rule for performing regression. You can select non-mercer kernels as well for SVM and MCM, perform L1, L2 and elastic net penalty. The updates are done in primal and one can use kernel features or random fourier features and Nystrom features for learning non-linear hyperplanes.

## Code
The code is written in Python 3.6 and requires the following packages
* sklearn,
* scipy,
* numpy 
* pandas

All packages except can be found in Anaconda python installation.

## Examples
To run on test dataset for classification run
1) classification_2D_MCM1.py 
To run on test dataset for regression run
1) regression_2D_MCM1.py 


## Citation
If you use the code please cite the following paper using the bibtex entry:

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

```

## Research Paper
The paper for the same is available at:

http://ieeexplore.ieee.org/abstract/document/7942005/
