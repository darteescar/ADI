### Linear Regression
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.687 | 0.623 | 4.873 | 2.207 | -0.09 | 0.009 |
| Most Frequent | Sim | Não | Table Partitioner | 0.687 | 0.644 | 4.882 | 2.21 | -0.042 | 0.009 |
| Most Frequent | Não | Sim | Table Partitioner | 0.685 | 0.648 | 4.915 | 2.217 | -0.154 | 0.009 |
| Most Frequent | Não | Não | Table Partitioner | 0.686 | 0.629 | 4.896 | 2.213 | -0.147 | 0.009 |
| Delete Row | Sim | Sim | Table Partitioner | 0.665 | 0.637 | 4.897 | 2.213 | -0.072 | 0.009 |
| Delete Row | Sim | Não | Table Partitioner | 0.666 | 0.657 | 4.892 | 2.212 | 0.025 | 0.009 |
| Delete Row | Não | Sim | Table Partitioner | 0.666 | 0.637 | 4.882 | 2.21 | -0.06 | 0.009 |
| Delete Row | Não | Não | Table Partitioner | 0.666 | 0.643 | 4.894 | 2.212 | -0.041 | 0.009 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.716 | 0.613 | 4.242 | 2.06 | -0.036 | 0.009 |
| Most Frequent | Sim | Não | X-Partitioner | 0.717 | 0.616 | 4.242 | 2.06 | -0.022 | 0.009 |
| Most Frequent | Não | Sim | X-Partitioner | 0.716 | 0.614 | 4.246 | 2.06 | -0.045 | 0.009 |
| Most Frequent | Não | Não | X-Partitioner | 0.716 | 0.616 | 4.244 | 2.06 | -0.027 | 0.009 |
| Delete Row | Sim | Sim | X-Partitioner | 0.71 | 0.614 | 4.384 | 2.094 | -0.051 | 0.009 |
| Delete Row | Sim | Não | X-Partitioner | 0.711 | 0.612 | 4.384 | 2.094 | -0.065 | 0.009 |
| Delete Row | Não | Sim | X-Partitioner | 0.71 | 0.619 | 4.39 | 2.095 | -0.047 | 0.009 |
| Delete Row | Não | Não | X-Partitioner | 0.71 | 0.614 | 4.393 | 2.096 | -0.076 | 0.009 |

### RProp MLP (100 iterações, 1 camada, 10 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.671 | 0.764 | 5.125 | 2.264 | -0.065 | 0.011 |
| Most Frequent | Sim | Não | Table Partitioner | 0.107 | 2.681 | 13.922 | 3.731 | -0.049 | 0.107 |
| Most Frequent | Não | Sim | Table Partitioner | 0.672 | 0.734 | 5.105 | 2.259 | -0.011 | 0.01 |
| Most Frequent | Não | Não | Table Partitioner | 0.429 | 1.88 | 8.897 | 2.983 | 0.026 | 0.027 |
| Delete Row | Sim | Sim | Table Partitioner | 0.647 | 0.786 | 5.169 | 2.274 | -0.047 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.069 | 2.669 | 13.622 | 3.691 | -0.139 | 0.039 |
| Delete Row | Não | Sim | Table Partitioner | 0.638 | 0.786 | 5.303 | 2.303 | -0.044 | 0.011 |
| Delete Row | Não | Não | Table Partitioner | 0.446 | 1.701 | 8.114 | 2.849 | 0.164 | 0.025 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.706 | 0.717 | 4.399 | 2.097 | 0.012 | 0.01 |
| Most Frequent | Sim | Não | X-Partitioner | 0.438 | 1.861 | 8.41 | 2.9 | 0.031 | 0.027 |
| Most Frequent | Não | Sim | X-Partitioner | 0.7 | 0.749 | 4.489 | 2.119 | 0.007 | 0.011 |
| Most Frequent | Não | Não | X-Partitioner | 0.418 | 1.893 | 8.706 | 2.951 | -0.048 | 0.028 |
| Delete Row | Sim | Sim | X-Partitioner | 0.695 | 0.724 | 4.619 | 2.149 | 0.012 | 0.01 |
| Delete Row | Sim | Não | X-Partitioner | 0.322 | 2.132 | 10.271 | 3.205 | -0.002 | 0.031 |
| Delete Row | Não | Sim | X-Partitioner | 0.694 | 0.745 | 4.628 | 2.151 | 0.01 | 0.011 |
| Delete Row | Não | Não | X-Partitioner | 0.462 | 1.753 | 8.147 | 2.854 | 0.018 | 0.026 |

### RProp MLP (200 iterações, 1 camada, 10 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.675 | 0.692 | 5.069 | 2.251 | -0.062 | 0.01 |
| Most Frequent | Sim | Não | Table Partitioner | 0.526 | 1.539 | 7.382 | 2.717 | 0.013 | 0.022 |
| Most Frequent | Não | Sim | Table Partitioner | 0.673 | 0.704 | 5.094 | 2.257 | -0.033 | 0.01 |
| Most Frequent | Não | Não | Table Partitioner | 0.463 | 1.717 | 8.378 | 2.859 | -0.104 | 0.025 |
| Delete Row | Sim | Sim | Table Partitioner | 0.634 | 0.752 | 5.351 | 2.313 | -0.033 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.5 | 1.566 | 7.32 | 2.706 | 0.096 | 0.023 |
| Delete Row | Não | Sim | Table Partitioner | 0.649 | 0.814 | 5.136 | 2.266 | -0.017 | 0.011 |
| Delete Row | Não | Não | Table Partitioner | 0.534 | 1.418 | 6.82 | 2.611 | 0.005 | 0.021 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.709 | 0.667 | 4.36 | 2.088 | 0.001 | 0.009 |
| Most Frequent | Sim | Não | X-Partitioner | 0.504 | 1.538 | 7.416 | 2.723 | -0.034 | 0.022 |
| Most Frequent | Não | Sim | X-Partitioner | 0.705 | 0.678 | 4.42 | 2.102 | -0.003 | 0.01 |
| Most Frequent | Não | Não | X-Partitioner | 0.534 | 1.496 | 6.976 | 2.641 | 0.004 | 0.022 |
| Delete Row | Sim | Sim | X-Partitioner | 0.707 | 0.654 | 4.44 | 2.107 | -0.001 | 0.009 |
| Delete Row | Sim | Não | X-Partitioner | 0.537 | 1.455 | 7.007 | 2.647 | -0.02 | 0.021 |
| Delete Row | Não | Sim | X-Partitioner | 0.7 | 0.686 | 4.549 | 2.133 | 0.009 | 0.01 |
| Delete Row | Não | Não | X-Partitioner | 0.53 | 1.485 | 7.124 | 2.669 | -0.007 | 0.022 |

### RProp MLP (100 iterações, 5 camadas, 10 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.659 | 0.81 | 5.317 | 2.306 | -0.046 | 0.011 |
| Most Frequent | Sim | Não | Table Partitioner | 0.395 | 1.958 | 9.427 | 3.07 | -0.145 | 0.029 |
| Most Frequent | Não | Sim | Table Partitioner | 0.661 | 0.809 | 5.3288 | 2.3 | -0.044 | 0.011 |
| Most Frequent | Não | Não | Table Partitioner | 0.416 | 1.9 | 9.103 | 3.017 | 0.05 | 0.028 |
| Delete Row | Sim | Sim | Table Partitioner | 0.639 | 0.788 | 5.289 | 2.3 | 0.013 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.319 | 12.092 | 9.96 | 3.156 | -0.042 | 0.031 |
| Delete Row | Não | Sim | Table Partitioner | 0.637 | 0.881 | 5.309 | 2.304 | -0.021 | 0.012 |
| Delete Row | Não | Não | Table Partitioner | 0.487 | 1.613 | 7.508 | 2.74 | -0.009 | 0.023 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.699 | 0.743 | 4.502 | 2.122 | 0.009 | 0.011 |
| Most Frequent | Sim | Não | X-Partitioner | 0.459 | 1.789 | 8.09 | 2.844 | -0.02 | 0.026 |
| Most Frequent | Não | Sim | X-Partitioner | 0.699 | 0.765 | 4.505 | 2.122 | 0.003 | 0.011 |
| Most Frequent | Não | Não | X-Partitioner | 0.376 | 2.013 | 9.334 | 3.055 | 0.021 | 0.03 |
| Delete Row | Sim | Sim | X-Partitioner | 0.693 | 0.763 | 4.645 | 2.155 | -0.01 | 0.011 |
| Delete Row | Sim | Não | X-Partitioner | 0.425 | 1.888 | 8.714 | 2.952 | 0.041 | 0.028 |
| Delete Row | Não | Sim | X-Partitioner | 0.694 | 0.764 | 4.636 | 2.153 | 0.014 | 0.011 |
| Delete Row | Não | Não | X-Partitioner | 0.458 | 1.773 | 8.213 | 2.866 | 0.031 | 0.026 |

### RProp MLP (200 iterações, 5 camadas, 10 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.654 | 0.851 | 5.393 | 2.322 | -0.05 | 0.012 |
| Most Frequent | Sim | Não | Table Partitioner | 0.506 | 1.574 | 7.696 | 2.774 | 0.017 | 0.023 |
| Most Frequent | Não | Sim | Table Partitioner | 0.656 | 0.789 | 5.363 | 2.316 | -0.049 | 0.011 |
| Most Frequent | Não | Não | Table Partitioner | 0.662 | 0.858 | 5.261 | 2.294 | -0.01 | 0.012 |
| Delete Row | Sim | Sim | Table Partitioner | 0.645 | 0.807 | 5.199 | 2.28 | -0.019 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.558 | 1.338 | 6.47 | 2.544 | -0.006 | 0.019 |
| Delete Row | Não | Sim | Table Partitioner | 0.65 | 0.793 | 5.123 | 2.236 | -0.019 | 0.011 |
| Delete Row | Não | Não | Table Partitioner | 0.598 | 1.158 | 5.882 | 2.425 | -0.019 | 0.017 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.704 | 0.724 | 4.422 | 2.103 | 0.002 | 0.01 |
| Most Frequent | Sim | Não | X-Partitioner | 0.647 | 1.076 | 5.276 | 2.297 | -0.013 | 0.015 |
| Most Frequent | Não | Sim | X-Partitioner | 0.694 | 0.773 | 4.585 | 2.141 | 0.009 | 0.011 |
| Most Frequent | Não | Não | X-Partitioner | 0.651| 1.02 | 5.225 | 2.286 | 0.01 | 0.015 |
| Delete Row | Sim | Sim | X-Partitioner | 0.681 | 0.761 | 4.838 | 2.199 | 0.01 | 0.011 |
| Delete Row | Sim | Não | X-Partitioner | 0.565 | 1.303 | 6.588 | 2.567 | 0.021 | 0.019 |
| Delete Row | Não | Sim | X-Partitioner | 0.686 | 0.768 | 4.754 | 2.18 | 0.006 | 0.011 |
| Delete Row | Não | Não | X-Partitioner | 0.585 | 1.215 | 6.283 | 2.507 | 0.015 | 0.018 |

### RProp MLP (100 iterações, 1 camada, 15 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.664 | 0.783 | 5.236 | 2.288 | -0.089 | 0.011 |
| Most Frequent | Sim | Não | Table Partitioner | 0.482 | 1.693 | 8,068 | 2.84 | -0.005 | 0.025 |
| Most Frequent | Não | Sim | Table Partitioner | 0.664 | 0.895 | 5.548 | 2.356 | -0.045 | 0.013 |
| Most Frequent | Não | Não | Table Partitioner | 0.375 | 1.941 | 9.739 | 3.121 | -0.033 | 0.028 |
| Delete Row | Sim | Sim | Table Partitioner | 0.654 | 0.799 | 5.062 | 2.25 | -0.018 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.252 | 2.27 | 10.945 | 3.308 | 0.033 | 0.252 |
| Delete Row | Não | Sim | Table Partitioner | 0.646 | 0.862 | 5.178 | 2.276 | -0.005 | 0.012 |
| Delete Row | Não | Não | Table Partitioner | 0.427 | 1.802 | 8,386 | 2.896 | -0.026 | 0.026 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.702 | 0.75 | 4.465 | 2.113 | 0.013 | 0.011 |
| Most Frequent | Sim | Não | X-Partitioner | 0.413 | 1.905 | 8.789 | 2.965 | -0.021 | 0.028 |
| Most Frequent | Não | Sim | X-Partitioner | 0.696 | 0.778 | 4.544 | 2.132 | -0.023 | 0.011 |
| Most Frequent | Não | Não | X-Partitioner | 0.458 | 1.811 | 8.117 | 2.849 | -0.013 | 0.027 |
| Delete Row | Sim | Sim | X-Partitioner | 0.696 | 0.758 | 4.596 | 2.144 | 0.007 | 0.011 |
| Delete Row | Sim | Não | X-Partitioner | 0.433 | 1.825 | 8.437 | 2.905 | -0.005 | 0.027 |
| Delete Row | Não | Sim | X-Partitioner | 0.688 | 0.798 | 4.721 | 2.173 | -0.001 | 0.011 |
| Delete Row | Não | Não | X-Partitioner | 0.446 | 1.811 | 8.395 | 2.897 | -0.008 | 0.027 |

### RProp MLP (200 iterações, 1 camada, 15 neurónios)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.674 | 0.725 | 5.089 | 2.256 | -0.055 | 0.01 |
| Most Frequent | Sim | Não | Table Partitioner | 0.452 | 1.727 | 8.542 | 2.923 | -0.106 | 0.025 |
| Most Frequent | Não | Sim | Table Partitioner | 0.68 | 0.71 | 4.985 | 2.233 | -0.029 | 0.01 |
| Most Frequent | Não | Não | Table Partitioner | 0.629 | 1.084 | 5.782 | 2.405  | 0.189 | 0.016 |
| Delete Row | Sim | Sim | Table Partitioner | 0.642 | 0.815 | 5.233 | 2.288  | -0.021 | 0.011 |
| Delete Row | Sim | Não | Table Partitioner | 0.577 | 1.253 | 6.192 | 2.488  | -0.059 | 0.018 |
| Delete Row | Não | Sim | Table Partitioner | 0.585 | 0.821 | 6.076 | 2.465  | 0.01 | 0.012 |
| Delete Row | Não | Não | Table Partitioner | 0.63 | 0.945 | 5.412 | 2.326  | -0.035 | 0.013 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.706 | 0.667 | 4.403 | 2.098 | -0 | 0.009 |
| Most Frequent | Sim | Não | X-Partitioner | 0.604 | 1.25 | 5.925 | 2.434 | 0.008 | 0.018 |
| Most Frequent | Não | Sim | X-Partitioner | 0.696 | 0.722 | 4.547 | 2.132 | 0.007 | 0.01 |
| Most Frequent | Não | Não | X-Partitioner | 0.595 | 1.283 | 6.067 | 2.463 | 0.038 | 0.019 |
| Delete Row | Sim | Sim | X-Partitioner | 0.699 | 0.711 | 4.551 | 2.133 | -0.007 | 0.01 |
| Delete Row | Sim | Não | X-Partitioner | 0.599 | 1.263 | 6.078 | 2.465 | -0.035 | 0.018 |
| Delete Row | Não | Sim | X-Partitioner | 0.692 | 0.748 | 4.665 | 2.16 | 0.018 | 0.01 |
| Delete Row | Não | Não | X-Partitioner | 0.595 | 1.275 | 6.132 | 2.476 | 0 | 0.018 |

### Polynomial Regression (2 graus)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.696 | 0.498 | 4.736 | 2.176 | -0.074 | 0.007 |
| Most Frequent | Sim | Não | Table Partitioner | 0.694 | 0.543 | 4.764 | 2.183 | 0.008 | 0.007 |
| Most Frequent | Não | Sim | Table Partitioner | 0.693 | 0.497 | 4.792 | 2.189 | -0.27 | 0.007 |
| Most Frequent | Não | Não | Table Partitioner | 0.697 | 0.493 | 4.728 | 2.174 | -0.092 | 0.007 |
| Delete Row | Sim | Sim | Table Partitioner | 0.68 | 0.489 | 4.685 | 2.165 | -0.07 | 0.007 |
| Delete Row | Sim | Não | Table Partitioner | 0.68 | 0.493 | 4.687 | 2.165 | -0.088 | 0.007 |
| Delete Row | Não | Sim | Table Partitioner | 0.681 | 0.508 | 4.676 | 2.162 | -0.013 | 0.007 |
| Delete Row | Não | Não | Table Partitioner | 0.68 | 0.509 | 4.683 | 2.164 | -0.023 | 0.007 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.728 | 0.472 | 4.064 | 2.016 | -0.061 | 0.006 |
| Most Frequent | Sim | Não | X-Partitioner | 0.729 | 0.473 | 4.061 | 2.015 | -0.046 | 0.006 |
| Most Frequent | Não | Sim | X-Partitioner | 0.728 | 0.472 | 4.066 | 2.016 | -0.063 | 0.006 |
| Most Frequent | Não | Não | X-Partitioner | 0.728 | 0.475 | 4.068 | 2.017 | -0.047 | 0.006 |
| Delete Row | Sim | Sim | X-Partitioner | 0.722 | 0.471 | 4.203 | 2.05 | -0.064 | 0.006 |
| Delete Row | Sim | Não | X-Partitioner | 0.722 | 0.469 | 4.207 | 2.051 | -0.077 | 0.006 |
| Delete Row | Não | Sim | X-Partitioner | 0.722 | 0.476 | 4.208 | 2.051 | -0.055 | 0.006 |
| Delete Row | Não | Não | X-Partitioner | 0.722 | 0.47 | 4.211 | 2.052 | -0.091 | 0.006 |

### Polynomial Regression (3 graus)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.696 | 0.498 | 4.736 | 2.176 | -0.074 | 0.007 |
| Most Frequent | Sim | Não | Table Partitioner | 0.693 | 0.509 | 4.779 | 2.186 | -0.18 | 0.007 |
| Most Frequent | Não | Sim | Table Partitioner | 0.696 | 0.533 | 4.74 | 2.177 | -0.06 | 0.007 |
| Most Frequent | Não | Não | Table Partitioner | 0.695 | 0.519 | 4.747 | 2.179 | -0.07 | 0.007 |
| Delete Row | Sim | Sim | Table Partitioner | 0.682 | 0.536 | 4.647 | 2.156 | 0.034 | 0.007 |
| Delete Row | Sim | Não | Table Partitioner | 0.679 | 0.564 | 4.703 | 2.169 | 0.058 | 0.008 |
| Delete Row | Não | Sim | Table Partitioner | 0.68 | 0.521 | 4.686 | 2.165 | -0.035 | 0.007 |
| Delete Row | Não | Não | Table Partitioner | 0.681 | 0.525 | 4.671 | 2.161 | -0.04 | 0.007 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.727 | 0.493 | 4.087 | 2.022 | -0.039 | 0.007 |
| Most Frequent | Sim | Não | X-Partitioner | 0.727 | 0.5 | 4.078 | 2.019 | -0.021 | 0.007 |
| Most Frequent | Não | Sim | X-Partitioner | 0.727 | 0.485 | 4.086 | 2.021 | -0.072 | 0.007 |
| Most Frequent | Não | Não | X-Partitioner | 0.727 | 0.49 | 4.092 | 2.023 | -0.05 | 0.007 |
| Delete Row | Sim | Sim | X-Partitioner | 0.721 | 0.494 | 4.223 | 2.055 | -0.06 | 0.007  |
| Delete Row | Sim | Não | X-Partitioner | 0.721 | 0.489 | 4.23 | 2.057 | -0.074 | 0.007 |
| Delete Row | Não | Sim | X-Partitioner | 0.721 | 0.495 | 4.227 | 2.056 | -0.049 | 0.007 |
| Delete Row | Não | Não | X-Partitioner | 0.72 | 0.491 | 4.233 | 2.057 | -0.083 | 0.007 |

### Random Forest (500 modelos)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.626 | 1.132 | 5.999 | 2.449 | 0.014 | 0.016 |
| Most Frequent | Sim | Não | Table Partitioner | 0.625 | 1.132 | 6.006 | 2.451 | -0.008 | 0.016 |
| Most Frequent | Não | Sim | Table Partitioner | 0.609 | 1.203 | 6.261 | 2.502 | 0.02 | 0.017 |
| Most Frequent | Não | Não | Table Partitioner | 0.609 | 1.202 | 6.263 | 2.503 | -0 | 0.017 |
| Delete Row | Sim | Sim | Table Partitioner | 0.623 | 1.085 | 5.65 | 2.377 | 0.022 | 0.016 |
| Delete Row | Sim | Não | Table Partitioner | 0.623 | 1.083 | 65.658 | 2.379 | -0.004 | 0.016 |
| Delete Row | Não | Sim | Table Partitioner | 0.606 | 1.165 | 5.9 | 2.429 | 0.036 | 0.017 |
| Delete Row | Não | Não | Table Partitioner | 0.605 | 1.164 | 5.908 | 2.431 | 0.01 | 0.017 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.653 | 1.064 | 5.19 | 2.278 | 0.041 | 0.015 |
| Most Frequent | Sim | Não | X-Partitioner | 0.653 | 1.064 | 5.195 | 2.279 | 0.021 | 0.015 |
| Most Frequent | Não | Sim | X-Partitioner | 0.637 | 1.144 | 5.43 | 2.33 | 0.041 | 0.017 |
| Most Frequent | Não | Não | X-Partitioner | 0.637 | 1.143 | 5.435 | 2.331 | 0.021 | 0.017 |
| Delete Row | Sim | Sim | X-Partitioner | 0.648 | 1.07 | 5.324 | 2.307 | 0.048 | 0.015 |
| Delete Row | Sim | Não | X-Partitioner | 0.648 | 1.069 | 5.329 | 2.309 | 0.022 | 0.015 |
| Delete Row | Não | Sim | X-Partitioner | 0.633 | 1.151 | 5.56 | 2.358 | 0.049 | 0.017 |
| Delete Row | Não | Não | X-Partitioner | 0.633 | 1.149 | 5.563 | 2.359 | 0.023 | 0.017 |

### Random Forest (200 modelos)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.623 | 1.141 | 6.041 | 2.458 | 0.017 | 0.016 |
| Most Frequent | Sim | Não | Table Partitioner | 0.622 | 1.141 | 6.049 | 2.46 | -0.005 | 0.016 |
| Most Frequent | Não | Sim | Table Partitioner | 0.608 | 1.21 | 6.278 | 2.505 | 0.014 | 0.017 |
| Most Frequent | Não | Não | Table Partitioner | 0.608 | 1.21 | 6.282 | 2.506 | -0.006 | 0.017 |
| Delete Row | Sim | Sim | Table Partitioner | 0.621 | 1.094 | 5.671 | 2.381 | 0.025 | 0.016 |
| Delete Row | Sim | Não | Table Partitioner | 0.621 | 1.091 | 5.674 | 2.382 | -0.003 | 0.016 |
| Delete Row | Não | Sim | Table Partitioner | 0.602 | 1.183 | 5.956 | 2.441 | 0.032 | 0.017 |
| Delete Row | Não | Não | Table Partitioner | 0.601 | 1.184 | 5.972 | 2.444 | 0.006 | 0.017 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.65 | 1.073 | 5.23 | 2.287 | 0.044 | 0.016 |
| Most Frequent | Sim | Não | X-Partitioner | 0.65 | 1.073 | 5.235 | 2.288 | 0.025 | 0.016 |
| Most Frequent | Não | Sim | X-Partitioner | 0.635 | 1.157 | 5.457 | 2.336 | 0.039 | 0.017 |
| Most Frequent | Não | Não | X-Partitioner | 0.635 | 1.156 | 5.462 | 2.337 | 0.019 | 0.017 |
| Delete Row | Sim | Sim | X-Partitioner | 0.647 | 1.079 | 5.352 | 2.314 | 0.053 | 0.016 |
| Delete Row | Sim | Não | X-Partitioner | 0.646 | 1.077 | 5.358 | 2.315 | 0.026 | 0.016 |
| Delete Row | Não | Sim | X-Partitioner | 0.63 | 1.161 | 5.61 | 2.369 | 0.052 | 0.017 |
| Delete Row | Não | Não | X-Partitioner | 0.629 | 1.16 | 5.612 | 2.369 | 0.026 | 0.017 |

### Gradient Boosted Trees (profundidade 5, modelos 100, rate 0.1)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.669 | 0.715 | 5.161 | 2.272 | -0.158 | 0.01 |
| Most Frequent | Sim | Não | Table Partitioner | 0.669 | 0.715 | 5.161 | 2.272 | -0.158 | 0.01 |
| Most Frequent | Não | Sim | Table Partitioner | 0.669 | 0.719 | 5.167 | 2.273 | -0.156 | 0.01 |
| Most Frequent | Não | Não | Table Partitioner | 0.669 | 0.719 | 5.167 | 2.273 | -0.157 | 0.01 |
| Delete Row | Sim | Sim | Table Partitioner | 0.657 | 0.712 | 5.013 | 2.239 | -0.155 | 0.01 |
| Delete Row | Sim | Não | Table Partitioner | 0.657 | 0.712 | 5.012 | 2.239 | -0.155 | 0.01 |
| Delete Row | Não | Sim | Table Partitioner | 0.658 | 0.714 | 5.011 | 2.239 | -0.153 | 0.01 |
| Delete Row | Não | Não | Table Partitioner | 0.658 | 0.715 | 5.011 | 2.238 | -0.154 | 0.01 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.709 | 0.671 | 4.355 | 2.087 | -0.149 | 0.009 |
| Most Frequent | Sim | Não | X-Partitioner | 0.709 | 0.671 | 4.354 | 2.087 | -0.149 | 0.009 |
| Most Frequent | Não | Sim | X-Partitioner | 0.71 | 0.668 | 4.341 | 2.084 | -0.152 | 0.009 |
| Most Frequent | Não | Não | X-Partitioner | 0.71 | 0.668 | 4.34 | 2.083 | -0.152 | 0.009 |
| Delete Row | Sim | Sim | X-Partitioner | 0.704 | 0.672 | 4.488 | 2.118 | -0.159 | 0.009 |
| Delete Row | Sim | Não | X-Partitioner | 0.704 | 0.672 | 4.49 | 2.119 | -0.16 | 0.009 |
| Delete Row | Não | Sim | X-Partitioner | 0.704 | 0.667 | 4.48 | 2.117 | -0.156 | 0.009 |
| Delete Row | Não | Não | X-Partitioner | 0.704 | 0.668 | 4.482 | 2.117 | -0.156 | 0.009 |

### Gradient Boosted Trees (profundidade 5, modelos 200, rate 0.05)
| Missing Values | Filtros | Normalizado | Partição | R² | MAE | MSE | RMSE | MSD | MAPE |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Most Frequent | Sim | Sim | Table Partitioner | 0.668 | 0.717 | 5.179 | 2.276 | -0.168 | 0.01 |
| Most Frequent | Sim | Não | Table Partitioner | 0.668 | 0.717 | 5.179 | 2.276 | -0.168 | 0.01 |
| Most Frequent | Não | Sim | Table Partitioner | 0.668 | 0.721 | 5.17 | 2.274 | -0.168 | 0.01 |
| Most Frequent | Não | Não | Table Partitioner | 0.668 | 0.722 | 5.17 | 2.274 | -0.169 | 0.01 |
| Delete Row | Sim | Sim | Table Partitioner | 0.658 | 0.704 | 4.999 | 2.236 | -0.154 | 0.01 |
| Delete Row | Sim | Não | Table Partitioner | 0.658 | 0.703 | 4.998 | 2.236 | -0.155 | 0.01 |
| Delete Row | Não | Sim | Table Partitioner | 0.657 | 0.701 | 5.012 | 2.239 | -0.156 | 0.01 |
| Delete Row | Não | Não | Table Partitioner | 0.657 | 0.701 | 5.013 | 2.239 | -0.157 | 0.01 |
| Most Frequent | Sim | Sim | X-Partitioner | 0.71 | 0.666 | 4.333 | 2.082 | -0.153 | 0.009 |
| Most Frequent | Sim | Não | X-Partitioner | 0.71 | 0.664 | 4.335 | 2.082 | -0.153 | 0.009 |
| Most Frequent | Não | Sim | X-Partitioner | 0.71 | 0.665 | 4.339 | 2.083 | -0.152 | 0.009 |
| Most Frequent | Não | Não | X-Partitioner | 0.71 | 0.666 | 4.341 | 2.083 | -0.152 | 0.009 |
| Delete Row | Sim | Sim | X-Partitioner | 0.704 | 0.67 | 4.484 | 2.117 | -0.157 | 0.009 |
| Delete Row | Sim | Não | X-Partitioner | 0.704 | 0.67 | 4.485 | 2.118 | -0.157 | 0.009 |
| Delete Row | Não | Sim | X-Partitioner | 0.703 | 0.674 | 4.496 | 2.12 | -0.158 | 0.009 |
| Delete Row | Não | Não | X-Partitioner | 0.703 | 0.674 | 4.497 | 2.121 | -0.159 | 0.009 |



