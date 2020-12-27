## A-Channel-level-Pruning-Strategy-for-Convolutional-Neural-Networks
This repo shows some code about the pruning strategy in the paper ["A Channel-level Pruning Strategy for Convolutional Neural Networks"](https://www.researchgate.net/profile/Chuang_Zhu/publication/328820451_A_Channel-level_Pruning_Strategy_for_Convolutional_Layers_in_CNNs/links/5dd228bd4585156b351bc7ab/A-Channel-level-Pruning-Strategy-for-Convolutional-Layers-in-CNNs.pdf).  
- The file "prune.ipynb" contains some code about the pruning process. In this file we use SE-BN-Inception for the example. You can download the network structure file and model parameters file in https://github.com/hujie-frank/SENet. We use Caffe to do this work. This is not a complete code but should be enough to show the pruning process.
## Highlights
network pruning based on attention.
## Citations
```
@inproceedings{song2018channel,
  title={A Channel-level Pruning Strategy for Convolutional Layers in CNNs},
  author={Song, Fangzhou and Wang, Ying and Guo, Yao and Zhu, Chuang and Liu, Jun and Jin, Mulan},
  booktitle={2018 International Conference on Network Infrastructure and Digital Content (IC-NIDC)},
  pages={135--139},
  year={2018},
  organization={IEEE}
}
```
