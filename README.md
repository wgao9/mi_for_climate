# mi_for_climate
This is the repository of **Mutual Information** estimators for climate data processing. 

**Input**: random variable X with size n, random variable Y with size n.

**Output**: mutual information I(X;Y).

**Methods**:

| Method in paper  | Function in code | Copyrights |
| ------------- | ------------- | -------------- |
| Quantization  | mutual_info.py/mutual_information_2d()  | G Varoquaux & R Brette |
| KDE  | stats_model.py/mutualinfo_kde()  | [S Khan et.al. 2007](http://pre.aps.org/abstract/PRE/v76/i2/e026209) |
| KNN | knnie.py/kraskov_mi() | [A Kraskov et. al. 2004](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.69.066138) |
| Noisy KNN | mixed.py/Noisy_KSG() | [W Gao et. al. 2017](https://arxiv.org/pdf/1709.06212.pdf) |
| Mixed MI | mixed.py/Mixed_KSG() | [W Gao et. al. 2017](https://arxiv.org/pdf/1709.06212.pdf) |

For questions, please contact Weihao Gao *wgao9@illinois.edu*
