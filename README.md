# AE-HCN Datasets (ICASSP 2019) 
Data for the paper "Contextual Out-of-Domain Utterance Handling with Counterfeit Data Augmentation" by [Sungjin Lee](https://www.microsoft.com/en-us/research/people/sule/) and [Igor Shalyminov](https://ishalyminov.github.io) [[Paper]](https://ieeexplore.ieee.org/document/8683019) [[Slides]](https://drive.google.com/open?id=1ZOqaYIofgM_F2Lp_BS-FpPqgXImcsnT6)

![](dialog.jpg)

# Datasets:

- `babi_task6` - clean version of bAbI Dialog Task 6 for Hybrid Code Network training
- `babi_task6_ood_0.2_0.4` - bAbI Dialog Task 6, version with OOD augmentations. OOD turns distributed as follows: OOD turn sequence starts with a probability `p_start=0.2` and keeps going with `p_cont=0.4`. Every OOD sequence ends up with a _segment-level_ OOD turn. For more detail on data augmentation, check out our papers: [1](https://ieeexplore.ieee.org/document/8683019) and [2](https://arxiv.org/abs/1811.12148)
- Google datasets - coming soon

Data augmentation code can be found in  [this repo](https://github.com/ishalyminov/ood_robust_hcn)
