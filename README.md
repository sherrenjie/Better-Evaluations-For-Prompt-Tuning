# Better Evaluation for Prompt Tuning

## Overview

This project was developed as part of the Microsoft AI Studio program to address the challenges of evaluating and optimizing prompts for open-source language models. The aim is to create a systematic approach for comparing human-written prompts with optimized ones and enhancing the quality of AI-generated responses.

## Objectives

- Compare the performance of human-written prompts versus optimized prompts.
- Develop evaluation metrics to measure prompt effectiveness.
- Improve prompt optimization techniques for Large Language Models (LLMs).
- Enhance AI-generated responses to better meet user needs.

## Key Features

- **Model Integration**: Utilized multiple open-source models such as `Phi3 instruct`, `flan-t5`, `falcon`, and `gpt-neo-125M`.
- **Evaluation Metrics**: Employed BLEU scores to measure output quality, with plans for additional metrics for qualitative evaluation.
- **Dataset Utilization**: Leveraged the SummEval dataset and dynamic prompt tuning for evaluation.

## Achievements

1. Defined a structured project framework and clear objectives.
2. Selected and integrated models for testing and development.
3. Conducted prompt evaluations using BLEU scores and compared model performances.
4. Addressed technical challenges, such as limited resources in Google Colab and API execution errors.

## Challenges and Solutions

- **Google Colab Limitations**: Managed GPU availability dynamically and upgraded to the Pro version for better performance.
- **Prompt Complexity**: Optimized prompt files and limited dataset size to improve runtimes.
- **Model Issues**: Switched to pretrained models to address output quality issues.

## Results

- Generated and analyzed outputs from multiple models to compare their performance.
- Identified key insights:
  - Phi3: Consistent, slightly longer outputs.
  - Flan-T5: Shortest and most consistent outputs, ideal for concise tasks.
  - Falcon: Moderate variability but some logical errors.
  - GPT-Neo: High output variation with inconsistent relevance.

## Next Steps

1. Experiment with a broader range of prompts and models.
2. Conduct additional exploratory data analysis (EDA) and statistical visualizations.
3. Refine evaluation metrics to better measure qualitative aspects like coherence and creativity.
4. Develop guidelines for prompt design and training datasets.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/sherrenjie/Better-Evaluations-For-Prompt-Tuning.git
   cd better-prompt-evaluation
2. Install the required dependencies
    ```bash
    pip install -r requirements.txt
3. Set up the environment in Google Colab or a local Jupyter Notebook.
4. Run the evaluation scripts:
   ```bach
   python evaluate_prompts.py
