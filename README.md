### Hi, welcome to mnist_ML

This repository contains a Jupyter Notebook that performs an analysis of several machine learning models for classifying handwritten digits from the MNIST dataset. The analysis explores a variety of models ranging from t-SNE for dimensionality reduction to deep learning with ResNet-9.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Running the Notebook](#running-the-notebook)
- [Models Analyzed](#models-analyzed)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project is focused on comparing different machine learning models to classify the MNIST dataset, a well-known benchmark for handwritten digit classification. The models analyzed include:
- t-SNE (t-Distributed Stochastic Neighbor Embedding) for dimensionality reduction
- Traditional Machine Learning models such as Random Forest
- Deep learning models including ResNet-9

The results are visualized through various plots to assess the performance of each model and compare their effectiveness in classifying the digits.

---

## Requirements

To run the notebook, you'll need the following libraries installed:

```
matplotlib
numpy
pandas
seaborn
tensorflow
openTSNE
scipy
scikit-learn
```

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kyracho/mnist-classification.git
   cd mnist-classification
   ```

2. **Set up a virtual environment (optional)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

Alternatively, install the packages manually:
   ```bash
   pip install matplotlib numpy pandas seaborn tensorflow openTSNE scipy scikit-learn
   ```

---

## Running the Notebook

1. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

2. **Open the `mnist_classification.ipynb` file** from the Jupyter interface.

3. **Run the cells** in the notebook to train and evaluate various machine learning models.
