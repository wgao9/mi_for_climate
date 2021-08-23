# mi_for_climate
This is the repository of **Mutual Information** estimators for climate data processing. 

**Input**: random variable X with size n, random variable Y with size n.

**Output**: mutual information I(X;Y).

**Methods**:

| Method in paper  | Function in code |
| ------------- | ------------- |
| Quantization  | mutual_info.py/mutual_information_2d()  |
| KDE  | stats_model.py/mutualinfo_kde()  |
| KNN | knnie.py/kraskov_mi() |
| Noisy KNN | mixed.py/Noisy_KSG() |
| Mixed MI | mixed.py/Mixed_KSG() |

For questions, please contact Weihao Gao *wgao9@illinois.edu*
