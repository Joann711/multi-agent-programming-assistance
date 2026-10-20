# Single-Agent Programming Assistant

## Overview

This is a baseline single-agent programming assistant using Qwen2.5-Coder 7B through Ollama. The model receives Python code and a problem description, find errors, and returns corrected code and the total number of errors.

## Requirements

- Python 3.10 or later
- Jupyter Notebook
- Ollama
- Qwen2.5-Coder 7B

## Setup Instructions

### 1. Install Ollama

Download and install Ollama from https://ollama.com/download.

### 2. Download the model

Open a terminal and run:

    ollama pull qwen2.5-coder:7b

Make sure Ollama is running before executing the notebook.

### 3. Run the notebook

Open the Jupyter Notebook and run the cells in order. The notebook loads the datasets from Hugging Face, defines the single-agent model function, and runs the model on the selected examples.

## Model Configuration

- Model: Qwen2.5-Coder 7B
- Framework: Ollama
- Temperature: 0
- Response time: Measured for each model call

## Output

The model returns:
- Corrected Python code
- Total number of errors

### Try the Model

You can test the model with your own Python code by running the last cell in the notebook.

**Note:** The `input()` function accepts one line at a time, so paste the code you want to check for errors.
