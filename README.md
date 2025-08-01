<img width="1201" height="606" alt="image" src="https://github.com/user-attachments/assets/3dabea7e-0647-4b35-8178-82dbc4876c61" />
** Vision Transformer (ViT) – From Scratch**
This repository contains a complete implementation of the Vision Transformer (ViT) architecture from scratch using PyTorch. Vision Transformers are a novel deep learning architecture that applies transformer models, originally developed for NLP tasks, to image classification by dividing images into patches and treating them as sequences.

**🚀 Overview**
Unlike traditional CNNs, Vision Transformers:

Split images into fixed-size patches.

Flatten and embed these patches.

Add positional encodings.

Pass the sequence through transformer encoders.

Use the output corresponding to the [CLS] token for classification.

This project recreates this pipeline from first principles, with minimal reliance on high-level libraries — allowing you to deeply understand the core mechanics behind ViT.

📦 Dataset
By default, the model is trained on MNIST. You can easily swap in another dataset by modifying the data loader.

🧱 Model Architecture
Key components implemented from scratch:

Patch Embedding Layer: Converts image patches into linear embeddings.

Positional Encoding: Injects spatial information into embeddings.

Multi-Head Self-Attention: Computes attention over patch tokens.

Transformer Encoder Blocks: Includes LayerNorm, MLP, and residual connections.

Classification Head: Uses [CLS] token for final output prediction.
