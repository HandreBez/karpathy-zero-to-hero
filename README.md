# Neural Networks: Zero to Hero

This repository tracks my progress and code implementations as I work through Andrej Karpathy's "Neural Networks: Zero to Hero" lecture series. The goal is to build a robust, from-scratch understanding of deep learning fundamentals, moving from basic backpropagation up to modern GPT architectures.

## Repository Structure

The repository is organized chronologically by lecture module:

* **`001_Micrograd/`**: Building a scalar-valued autograd engine and a simple neural network library from scratch.
* **`002_Makemore_Bigrams/`**: Introduction to language modeling using a bigram character-level model.
* **`003_Makemore_MLP/`**: Implementing a Multi-Layer Perceptron (MLP) for character-level language modeling.
* **`004_Makemore_BatchNorm/`**: Adding Batch Normalization and understanding network activations.
* **`005_Makemore_BackpropNinja/`**: Manual implementation of backpropagation for the MLP.
* **`006_Makemore_WaveNet/`**: Scaling the model using a dilated causal convolutional architecture (WaveNet).
* **`007_GPT/`**: Building a Transformer-based language model.
* **`008_minBPE/`**: Implementing Byte-Pair Encoding (BPE) for tokenization.
* **`009_GPT2/`**: Replicating and training the GPT-2 architecture.
* **`data/`**: Shared datasets (e.g., `names.txt`) used across the different modules.
