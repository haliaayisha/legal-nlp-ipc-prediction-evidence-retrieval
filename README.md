# Legal NLP: IPC Section Prediction and Evidence Retrieval

## Project Overview

An NLP-based legal case analysis system that predicts relevant Indian Penal Code (IPC) sections from case descriptions and retrieves supporting evidence sentences from a legal case database.

The system integrates Sentence Transformers, semantic embeddings, multi-label classification, and evidence retrieval through an interactive Gradio web interface.

## Key Features

- Legal case text analysis
- Sentence Transformer-based semantic embeddings
- Multi-label IPC section classification
- Supporting evidence sentence retrieval
- Prediction confidence visualisation
- Interactive Gradio web application

## Technology Stack

- Python
- Sentence Transformers
- PyTorch
- Scikit-learn
- Pandas and NumPy
- Gradio
- Matplotlib

## Model Workflow

1. Dataset loading and preprocessing
2. Sentence embedding generation
3. Multi-label classifier training
4. Model evaluation
5. Model saving
6. Semantic evidence retrieval
7. Gradio interface deployment

## Gradio Web Application

The application allows users to submit legal case descriptions, predict relevant IPC sections, visualise prediction confidence, and retrieve supporting evidence sentences.

![Legal NLP Gradio Interface](screenshots/gradio_interface.png)

## Model Evaluation Results

| Metric | Score |
|---|---:|
| Subset Accuracy | 27.62% |
| Macro Precision | 52.09% |
| Macro Recall | 80.17% |
| Macro F1-Score | 62.77% |
| Micro F1-Score | 61.86% |
| Hamming Loss | 16.33% |

### Per-Class F1-Score

| IPC Section | F1-Score |
|---|---:|
| IPC 420 | 0.86 |
| IPC 376 | 0.81 |
| IPC 498A | 0.69 |
| IPC 147 | 0.64 |
| IPC 302 | 0.62 |
| IPC 201 | 0.46 |
| IPC 506 | 0.33 |

## How to Run

1. Open the notebook using Google Colab.
2. Install dependencies from `requirements.txt`.
3. Configure the dataset path.
4. Execute the notebook cells sequentially.
5. Launch the Gradio interface.

## Disclaimer

This project is intended for academic and research purposes. Its predictions are not a substitute for professional legal advice or judicial interpretation.


## Disclaimer
This project is intended for academic and research purposes. Predictions should not be considered professional legal advice.


