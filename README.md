# NEAT: Nonlinear Parameter-efficient Adaptation of Pre-trained Models

This repository contains the implementation of NLP parts of the paper **"NEAT: Nonlinear Parameter-efficient Adaptation of Pre-trained Models"**. 

## Paper Abstract

Neat is a novel parameter-efficient fine-tuning (PEFT) method that introduces nonlinear transformations to enhance model adaptation while maintaining efficiency. Unlike traditional approaches like LoRA, which rely on linear updates, Neat incorporates lightweight neural networks to model cumulative weight updates as functions of pre-trained weights, capturing complex, nonlinear structures in the weight space.

For more details, please refer to the [paper](https://arxiv.org/abs/2410.01870).

## Setup
Neat is built upon the LLM-Adapters framework. You need to install the framework and its dependencies.
For more details about LLM-Adapters, refer to their [GitHub repository](https://github.com/AGI-Edgerunners/LLM-Adapters).

## Training
Example usage to finetune with NEAT for multiple GPUs
```bibtex
bash scripts/finetune.sh
```

## Citation
If you find this work useful, please cite:

```bibtex
@article{zhong2024neat,
  title={Neat: Nonlinear Parameter-efficient Adaptation of Pre-trained Models},
  author={Zhong, Yibo and Jiang, Haoxiang and Li, Lincan and Nakada, Ryumei and Liu, Tianci and Zhang, Linjun and Yao, Huaxiu and Wang, Haoyu},
  journal={arXiv preprint arXiv:2410.01870},
  year={2024}
}


