# Notebooks of Large Language Models used in Astronautics
A collection of notebooks showcasing the usage of LLMs for Space Engineering, space operations and astronautics at large.

## 1. Evaluations of LLMs

### 1.1 Evaluating an open-source Mistral model on a benchmark task dataset (AstroMCQA)
<a target="_blank" href="https://colab.research.google.com/github/patrickfleith/astro-llms-notebooks/blob/main/Evaluate_an_HuggingFace_LLM_on_a_Domain_Specific_Benchmark_Dataset.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- Formatting of an existing dataset hosted on huggingface to feed an LLM for evaluation
- Load an huggingface LLM and collect its outputs
- Evaluating the LLM based on multiple scoring strategies
    - string character-based distance
    - embedding-based distance
    - f1 and exact match
    - LLM-as-a-Judge
