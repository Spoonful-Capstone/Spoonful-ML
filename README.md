# Spoonful-ML

This is part of Bangkit 2024 Spoonful Capstone Projects. Here is our documentation of the ML Parts 

## Food Recognition
The models is trained on [Indonesian Food Classification Dataset](https://universe.roboflow.com/bangkit/indonesian-food-pedsx) on Roboflow. The training stage can be seen on this [notebook](https://colab.research.google.com/drive/17vwft3NtaE2tfWTiHliZxBnqm7EDBV-R#scrollTo=v7jcy5ixYJeI) 

### Model Zoo 
Naming convention file of models corresponds to the configuration (img_size)-(model_type)-(dense_layer)-(quantized?)-(dataset)
<center>
  
|  Model  |  Size  | Avg Accuracy|
|  ---------- | ------- | ---------- |
|  [256-inception-1024-quantized-Indonesian Food](https://drive.google.com/file/d/1vj7jtxbpfVNUfzXL_7e4i20bGsG2g-A_/view?usp=sharing) | 311,2 MB | 93% |
|  [256-inception-512-Indonesian Food](https://drive.google.com/file/d/1YAioZqoeAE92L5ZuahOkAuMzw-uiIdVh/view?usp=sharing) | 328,2 MB  | 89% |
|  [256-inception-512-quantized-Indonesian Food](https://drive.google.com/file/d/1LeSouGbk_Cbl07Gf3LpB9vIyIr-dwr-s/view?usp=sharing) | 164,2 MB  | 87% |
|  [256-inception-256-Indonesian Food](https://drive.google.com/file/d/1Qak8FBCTj1i5U_qv1D_Ke2Y7jCaWT4D4/view?usp=sharing) | 181,2 MB | 85% |
|  [256-inception-256-quantized-Indonesian Food](https://drive.google.com/file/d/17N9xh3ZqF2ZvXomIDVWf-dV4IK1eXrRD/view?usp=sharing) | 90,6 MB | 84% |
|  [256-inception-128-Indonesian Food](https://drive.google.com/file/d/1GYLBPtUmgNb7Ws4HgJIF2gS8Y9x28Xa5/view?usp=sharing) | 107,7 MB | 83% |
|  [256-inception-128-quantized-Indonesian Food](https://drive.google.com/file/d/1gvdpVJE2tTVUsrESSIhTN7ln0J00Xm7F/view?usp=sharing) | 53,9 MB | 82% |

</center>

## Food Recommender
The models is trained on [Indonesian Food and Drink Nutrition Dataset](https://www.kaggle.com/datasets/anasfikrihanif/indonesian-food-and-drink-nutrition-dataset) on Kaggle. The training stage can be seen on this [notebook](https://colab.research.google.com/drive/1PNFcuP_6eNZCoIU2s4ZEzqBfs1wv77t-?usp=sharing#scrollTo=PE3KU_CDbs96) 
