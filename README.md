<div align="center">

## ORC: Network Group-based Knowledge Distillation using Online Role Change
  
[![PWC](https://img.shields.io/badge/arXiv-2111.13353-fed000.svg)](https://arxiv.org/abs/2206.01186)

</div>

> **Network Group-based Knowledge Distillation using Online Role Change**<br>
> [Junyong Choi](https://github.com/NaJaeMin92), Hyeon Cho, Seockhwa Jeong, Wonjun Hwang<br>
> In ICCV 2023.<br><br/>


> **Abstract:** *Recent unsupervised domain adaptation methods have utilized vicinal space between the source and target domains. However, the equilibrium collapse of labels, a problem where the source labels are dom- inant over the target labels in the predictions of vicinal instances, has never been addressed. In this paper, we propose an instance-wise minimax strategy that minimizes the entropy of high uncertainty instances in the vicinal space to tackle the stated problem. We divide the vicinal space into two subspaces through the solution of the minimax prob- lem: contrastive space and consensus space. In the contrastive space, inter-domain discrepancy is mitigated by constraining instances to have contrastive views and labels, and the consensus space reduces the confusion between intra
domain categories. The effectiveness of our method is demonstrated on public benchmarks, including Office-31, Office-Home, and VisDA-C, achieving state-of-the-art performances. We further show that our method outperforms the current state-of-the-art methods on PACS, which indicates that our instance-wise approach works well for multi-source domain adaptation as well.*

## Introduction


## Requirements
- Linux
- Python >= 3.7
- PyTorch == 1.7.1 
- CUDA (must be a version supported by the pytorch version)

## Getting Started
to be updated 

#### Training process.
to be updated

## Contact
For questions, please contact: chldusxkr1@gmail.com

## Citation
If you use this code in your research, please cite:
```bibtex  
@article{choi2023orc,
  title={Network Group-based Knowledge Distillation using Online Role Change},
  author={Choi, Junyong and Cho, Hyeon and Jeong, Seockhwa and Hwang, Wonjun},
  journal={arXiv preprint arXiv:2206.01186},
  year={2023}
}
```
