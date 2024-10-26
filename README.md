# Language_modeling
# 📚 LSTM Language Modeling with WikiText-2

Welcome to this **Language Modeling Project** that uses an LSTM network to generate coherent text sequences based on prior context. Built using PyTorch, this project not only implements a straightforward LSTM language model but also explores advanced regularization and optimization techniques, drawing from state-of-the-art research. Our goal? To bring our model’s performance closer to that achieved in Merity et al.'s seminal work on enhancing LSTM language models.

## 🚀 Project Highlights

1. **Model Architecture:** LSTM-based, designed to capture and predict long-term dependencies in text.
2. **Data Source:** The **WikiText-2** dataset—offering high-quality, long-form text ideal for training language models.
3. **Optimization:** Key improvements through regularization and optimization, inspired by the research in Merity et al.’s [paper](https://arxiv.org/abs/1708.02182).

## ✨ Why This Project Stands Out

In addition to a standard LSTM implementation, this project integrates techniques from **Merity et al.'s paper** to optimize the model further:

- **Original Implementation:** The initial code for the LSTM model provided in the repository is a straightforward LSTM language model. It’s effective but has room for improvement, especially in handling overfitting and convergence speed.
- **Optimized Code with Regularization:** The second implementation incorporates Merity et al.'s regularization methods, which significantly reduce overfitting, improve model generalization, and bring the results closer to those reported in the paper. Hyperparameter tuning is also added, leading to better convergence and overall performance.

This dual-approach setup allows users to compare and see firsthand the impact of optimization and regularization in LSTM-based language modeling.

## 📊 Dataset: WikiText-2

The **WikiText-2** dataset is a widely-used corpus for language modeling tasks and contains rich, high-quality text content, ideal for training. You can access and download the dataset [here](https://blog.einstein.ai/the-wikitext-long-term-dependency-language-modeling-dataset/).

## 🛠️ Dependencies

To reproduce the results and experiment with this project, make sure you’re using the following library versions:

- `numpy == 1.26.4`
- `torch == 2.0.0+cu117`
- `torchtext == 0.15.1+cpu`
- `tqdm == 4.66.5`

Install these dependencies by running:

```bash
pip install -r requirements.txt

