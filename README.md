# Shakespeare-Style Text Generation using GPT From Scratch

## Overview
This repository contains a ground-up implementation of the GPT (Generative Pre-trained Transformer) architecture for generating Shakespeare-style text. Every component of the transformer architecture is implemented from scratch, providing a deep understanding of the underlying mechanisms of large language models.

## Project Highlights
- Complete from-scratch implementation of GPT architecture
- Trained on Shakespeare's complete works
- Character-level tokenization
- Custom implementation of multi-head attention
- Transformer blocks built from fundamental components

## Model Architecture
All components are implemented from scratch, including:
1. **Multi-Head Attention**
   - Scaled dot-product attention
   - Parallel attention head processing
   - Custom attention masks
   
2. **Transformer Block**
   - Self-attention mechanism
   - Feed-forward network
   - Layer normalization
   - Residual connections

3. **Position Embeddings**
   - Learnable position encodings
   - Token embeddings

4. **Layer Normalization**
   - Custom implementation with affine parameters


## Dataset
The model is trained on a comprehensive collection of Shakespeare's works:

## Requirements
```
python>=3.8
pytorch>=1.9.0
numpy
tqdm
matplotlib
```

## Installation
```
git clone https://github.com/HarshGosula/GPT_from_Scratch.git
```
