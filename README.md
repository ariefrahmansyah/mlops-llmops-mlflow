# MLOps and LLMOps with MLflow

This repository contains examples of how to use MLflow to manage the machine learning lifecycle.

## Getting started

### Prerequisites

- Python
- uv

### Install dependencies

```bash
uv sync
```

### Run MLflow Tracking Server

```bash
mlflow server
```

## Check the examples

1. [Autologging](./examples/autolog/) -- Quick start with MLflow autologging.
2. [Tensorflow](./examples/tensorflow/) -- Log the training of a Tensorflow MNIST model.
3. [Regression recipes](./examples/regression_recipes/) -- NYC Taxi Fare regression use case with MLflow Recipes.
4. [Classification recipes](./examples/classification_recipes/) -- Wine classification use case with MLflow Recipes.
5. [OpenAI Evaluation](./examples/openai_chat_completions/) -- Evaluate OpenAI models with MLflow Evaluation.
6. [Local LLM](./examples/local_llm/) -- Build local LLM from Huggingface model with MLflow.
