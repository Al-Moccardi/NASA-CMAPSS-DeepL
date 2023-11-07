# NASA-CMAPSS-DeepL
--- 
## Introduction:
The ability to predict the remaining useful lifetime (RUL) of components, known as prognostics, plays a crucial role in intelligent maintenance systems. However, developing data-driven prognostics models often requires run-to-failure datasets, which are typically scarce in real-world applications due to the infrequent occurrence of failures in safetycritical systems. In order to facilitate the advancement of prognostics methods. This work delves into the realm of predictive maintenance, investigating state-of-the-art techniques and leveraging the CMAPP -NASA dataset to unravel valuable insights and advancements in fault detection and health analysis.



![Screenshot 2023-11-07 203510](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/57d696d8-e948-4b35-9b51-3cb90c2070fd)


Firstly, an Exploratory Data analysis of the popular dataset N-CMAPSS is conducted then a Remaining useful life prediction (RUL) using Piecewise Linear degradation model through three different 'classical' methodologies is implemented.

Links to the colab: 


Exploratory data analysis:

-Inspection

-Statistical data analysis

-Survival Analysis

-Stationarity Analysis (FD002-FD004)

-Perturbation Analysis (FD001-FD003)

EDA

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lcxx4sd7ZbBMeA2bPLIBfU8WEecqNxQq?usp=drive_link)


During the EDA an unsupervised methodology is applied is conducted on multimodal datasets (FD002-FD004) using DBSCAN (Density-Based Spatial Clustering of Applications with Noise) for Anomaly detection.
![Screenshot 2023-11-07 203706](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/ecd8609f-6b61-4ae0-b11b-bb02fed78044)

For the prediction task three specific algorithm are selected, trained the results are compared:

- LSTM
- ABGRU (Attention Based Gated Recurrent Unit)
- 1D-CNN


![Screenshot 2023-11-07 193316](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/09d8d558-4166-450d-9d95-5b4068398ab6)

Links to the colab: 

1D-CNN:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1knkH7Oz_FysNQuJJOoP_rpx1feHEBEba?usp=drive_link)

LSTM
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DKRShd10M_hjmiUv0IagCU-2zV4gqPAu?usp=drive_link)

ABGRU
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19IntflwfVQ_bmGKempFigxdJjUVMqtiL?usp=drive_link)

The results clearly shows advancements with the usage of Attention mechanism in regression tasks for Time series analysis

![Screenshot 2023-11-07 193404](https://github.com/Al-Moccardi/NASA-CMAPSS-DeepL/assets/150179413/ab8d626a-1903-4f41-b446-d76cdc7069ec)

For further information on CMAPSS datasets and data generation (Reference: A. Saxena, K. Goebel, D. Simon, and N. Eklund, Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation, in the Proceedings of the 1st International Conference on Prognostics and Health Management (PHM08), Denver CO, Oct 2008.
Alternatively the dataset can be downloaded from https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
