# NASA-CMAPSS-DeepL
Exploratory Data Analysis of the popular dataset N-CMAPSS and Remaining useful life prediction (RUL) using Piecewise Linear degradation model through three different 'classical' methodologies.

![Screenshot 2023-11-07 203510](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/57d696d8-e948-4b35-9b51-3cb90c2070fd)

Exploratory data analysis:
-Inspection
-Statistical data analysis
-Survival Analysis
-Stationarity Analysis (FD002-FD004)
-Perturbation Analysis (FD001-FD003)

Moreover an Anomaly detection is conducted on multimodal datasets (FD002-FD004) using DBSCAN (Density-Based Spatial Clustering of Applications with Noise) 
![Screenshot 2023-11-07 203706](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/ecd8609f-6b61-4ae0-b11b-bb02fed78044)


Specifically three algorithm will be used and results are compared:

- LSTM
- ABGRU (Attention Based Gated Recurrent Unit)
- 1D-CNN


![Screenshot 2023-11-07 193316](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/09d8d558-4166-450d-9d95-5b4068398ab6)

Links to the colabs: 
EDA:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Dsk2yj3YxytGyOUYRkwsJZfev2POU46W]
1D-CNN:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Dsk2yj3YxytGyOUYRkwsJZfev2POU46W]
LSTM
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Dsk2yj3YxytGyOUYRkwsJZfev2POU46W]
ABGRU
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Dsk2yj3YxytGyOUYRkwsJZfev2POU46W]

The results clearly shows advancements with the usage of Attention mechanism in regression tasks for Time series analysis

![Screenshot 2023-11-07 193404](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/ab8d626a-1903-4f41-b446-d76cdc7069ec)

For further information on CMAPSS datasets and data generation (Reference: A. Saxena, K. Goebel, D. Simon, and N. Eklund, Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation, in the Proceedings of the 1st International Conference on Prognostics and Health Management (PHM08), Denver CO, Oct 2008.
Alternatively the dataset can be downloaded from https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
