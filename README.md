# NEAT: Nonlinear Parameter-efficient Adaptation of Pre-trained Models

This repository contains the official implementation of the paper **"NEAT: Nonlinear Parameter-efficient Adaptation of Pre-trained Models"**. NEAT is a novel parameter-efficient fine-tuning (PEFT) method designed to enhance model adaptation for both NLP and vision tasks while maintaining computational efficiency.

## Key Features

- **Nonlinear Fine-tuning:** Introduces a lightweight neural network to model weight updates, allowing for the capture of complex, nonlinear patterns in the weight space.
- **Parameter Efficiency:** Achieves competitive or superior performance compared to Low-Rank Adaptation (LoRA) with fewer trainable parameters.
- **Broad Applicability:** Demonstrated performance improvements on 20+ datasets across NLP and vision benchmarks.

## Paper Abstract

Fine-tuning pre-trained models is crucial for adapting large models to downstream tasks, often delivering state-of-the-art performance. However, fine-tuning all model parameters is resource-intensive, leading to the emergence of parameter-efficient fine-tuning (PEFT) methods. While PEFT techniques such as LoRA are effective, they struggle to capture complex, nonlinear interactions in the weight space. NEAT addresses these limitations by introducing a lightweight neural network that learns nonlinear transformations of pre-trained weights. The method demonstrates superior expressivity and efficiency, outperforming existing approaches across multiple benchmarks.

For more details, please refer to the [paper](https://arxiv.org/abs/2410.01870).

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/NEAT.git
   cd NEAT
