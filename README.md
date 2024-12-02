# Example workflow of synaptic plasticity and RRP estimation 
A computational model for investigating presynaptic short-term plasticity is impaired in Aux-KO mice

## Author
- [Ben-Zheng Li](https://github.com/libenzheng) @ [Klug lab](https://www.kluglab.org/)

## Prerequisites

| Package            | Version     | 
| :----------------------- | :---------------- | 
|python | 3.8.12 |
|[brian2](https://github.com/brian-team/brian2)                |   2.5.1
|scikit-learn |  1.0.2
|numpy                  |            1.21.2
|pandas                  |           1.3.5
|scipy                     |         1.7.3
|matplotlib            |             3.5.0

## Usage and Example
- Details in "Cheng, Xi, Yu Tang, D. J. Vidyadhara, Ben-Zheng Li, Michael Zimmerman, Alexandr Pak, Sanghamitra Nareddula, Paige Alyssa Edens, Sreeganga S. Chandra, and Alexander A. Chubykin. "Impaired pre-synaptic plasticity and visual responses in auxilin-knockout mice." Iscience 26, no. 10 (2023)."

## Functions  
- [Signal_Processing.py]: smooth and detrend patch-clamp recordings in visual cortex
- [TM_Model.py]: [Tsodyks-Markram model](https://doi.org/10.1162/089976698300017502) with fitted utilization of synaptic efficacy and recovery time constant
- [SMN_Method.py]: [Schneggenburger-Meyer Neher method](https://doi.org/10.1016/S0896-6273(00)80789-8) for estimating readily releasable pool size and replenishment rate


## Citation
- Cheng, Xi, Yu Tang, D. J. Vidyadhara, Ben-Zheng Li, Michael Zimmerman, Alexandr Pak, Sanghamitra Nareddula, Paige Alyssa Edens, Sreeganga S. Chandra, and Alexander A. Chubykin. "Impaired pre-synaptic plasticity and visual responses in auxilin-knockout mice." Iscience 26, no. 10 (2023).


## License
This project is licensed under the MIT license ([LICENSE](https://github.com/libenzheng/dendritic_spine_processing_example/blob/main/LICENSE)).
