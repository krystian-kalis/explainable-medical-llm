# Explainable Medical LLM Assistant

## Overview
This repository contains a comprehensive evaluation and testing framework for Large Language Models (LLMs) applied to the medical domain. The project focuses on prompt engineering, assessing the diagnostic quality of generated responses, and analyzing the interpretability (Explainable AI / XAI) of LLMs when acting as medical assistants.

## Key Objectives
* **Clinical Case Evaluation:** Testing LLMs against a structured dataset of medical cases to evaluate their diagnostic reasoning and safety.
* **Prompt Engineering:** Designing, refining, and testing various prompt architectures (zero-shot, few-shot, chain-of-thought) to optimize the accuracy and reliability of medical outputs.
* **Interpretability & XAI:** Analyzing why and how the models arrive at specific medical conclusions, ensuring the decision-making process is transparent and hallucination-free.
* **Comparative Analysis:** Benchmarking the performance of two distinct language models (Model 1 vs. Model 2) across initial and optimized prompt iterations.

## Repository Structure
The project files are organized to document the entire pipeline, from raw inputs to final analytical reports:

* **`code.ipynb`**: The core Jupyter Notebook containing the Python implementation. This includes API integrations, prompt engineering pipelines, and the logic for parsing and evaluating model responses.
* **`cases.csv`**: The input dataset containing the clinical medical scenarios and patient descriptions used to prompt the models.
* **`data_1.csv` & `data_1_initial.csv`**: The generated outputs, extracted entities, and evaluation metrics for the first LLM (comparing the initial prompt run vs. the optimized run).
* **`data_2.csv` & `data_2_initial.csv`**: The corresponding output data and metrics for the second LLM.
* **`report.pdf`**: A comprehensive technical report detailing the evaluation methodology, metric outcomes, and deep-dive analysis into the models' interpretability.
* **`presentation.pdf`**: An executive slide deck summarizing the project's goals, key findings, and business/clinical takeaways.

## Authors
Krystian Kaliś, Barbara Jankowska