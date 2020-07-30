# Transport Monte Carlo

Example code for using Transport Monte Carlo --- using random transport plan and optimization to rapidly estimate the posterior distribution

1. Sampling from a Normal Mixture:
https://nbviewer.jupyter.org/github/leoduan/TransportMonteCarlo/blob/master/gaussianMixtureTMC.ipynb

2. Sampling from a multi-modal distribution (Liang 2005):
https://nbviewer.jupyter.org/github/leoduan/TransportMonteCarlo/blob/master/MultimodalTMC.ipynb

3. High-dimensional regression using the regularized horseshoe prior (Piironen and Vehtari 2017) :
https://nbviewer.jupyter.org/github/leoduan/TransportMonteCarlo/blob/master/regularizedHorseshoe.ipynb

4. Binary adjacency matrix estimation under degree regularization:
https://github.com/leoduan/TransportMonteCarlo/blob/master/edgeSamplingUnderDegreeReg.ipynb


For other target distribution, simply modify the log-prior-likelihood function.

For reference, see
Leo L. Duan. Transport Monte Carlo 2019+. http://arxiv.org/abs/1907.10448

