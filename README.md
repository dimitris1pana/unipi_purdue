# AI in Smart Cities and Energy Management

## DUAL MSc IN GLOBAL APPLIED ARTIFICIAL INTELLIGENCE - University Of Piraeus & PURDUE University

This directory contains the student laboratory material for the lecture series on artificial intelligence in smart cities and energy management. The notebooks provide structured examples for supervised learning, neural networks, and explainable AI using synthetic energy-related data.

## Course Materials

Available lesson notebooks:

- `single_neuron_perceptron_energy.ipynb`
- `nn.ipynb`
- `nnXAI.ipynb`

## Software Setup

Complete the following setup before opening the notebooks.

### 1. Install Visual Studio Code

Install Visual Studio Code on your local machine.

### 2. Install the Required VS Code Extensions

Install the following extensions from the VS Code Extensions panel:

- `Python`
- `Jupyter`

### 3. Create a Python Environment

Use either Conda or a standard virtual environment.

Conda example:

```bash
conda create -n smart-energy-ai python=3.11
conda activate smart-energy-ai
```

`venv` example:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 4. Install the Project Requirements

From the project root, install the required packages:

```bash
pip install -r requirements.txt
```

### 5. Open the Notebooks

Open the following files in VS Code:

- `single_neuron_perceptron_energy.ipynb`
- `nn.ipynb`
- `nnXAI.ipynb`

After opening a notebook, select the active Python kernel that matches the environment created in the previous step.

## Lesson 1: Energy Data Management

This lesson introduces a single-neuron perceptron for binary classification using synthetic energy-style data.

Topics covered:

- synthetic feature generation
- feature normalization
- perceptron-based classification
- model training
- classification evaluation

## Lesson 2: Neural Networks for Energy Classification

This lesson introduces a multi-layer neural network for the same energy-management context.

Topics covered:

- feature scaling with `StandardScaler`
- hidden layers and nonlinear modeling
- neural-network training with `MLPClassifier`
- classification performance evaluation

## Lesson 3: Explainable AI with SHAP

This lesson introduces explainability for neural-network predictions using SHAP.

Topics covered:

- global feature importance
- local explanation of individual predictions
- SHAP value interpretation
- explainability in energy-management applications

## Academic Context

The examples in this directory use synthetic data for instructional purposes. The notebooks are designed to support conceptual understanding, method implementation, and classroom discussion before transition to real-world datasets and applied case studies.
