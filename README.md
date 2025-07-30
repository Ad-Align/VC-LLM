# Adversarial Alignment: Ensuring Value Consistency in Large Language Models for Sensitive Domains

## Overview

This repository introduces the Adversarial Alignment framework, designed to improve value consistency in large language models (LLMs) when applied to sensitive domains such as politics and human rights. The framework integrates continued pre-training, instruction fine-tuning, and adversarial training, where an Attacker generates controversial queries, the Actor produces aligned responses, and the Critic ensures quality.

We train the Value-Consistent Large Language Model (VC-LLM) using this framework, specifically for Chinese sensitive domains, and have constructed a bilingual (Chinese and English) evaluation benchmark to assess value alignment performance across different models.


## Model Access

The VC-LLM is available on Hugging Face for easy access and deployment:

- **Model on Hugging Face:** [CMV-LLM on Hugging Face](https://huggingface.co/gotime/CMV-LLM)
- **Dataset on Hugging Face:** [CMV-LLM-Dataset on Hugging Face](https://huggingface.co/datasets/gotime/CMV-LLM-Dataset)

## Potential Risks and Warnings

- **Bias and Harmful Content:** While VC-LLM aims to align with specific value systems, users should be aware that the training datasets and model may still contain biases or generate harmful content. Caution should be exercised when using the model in sensitive applications.
