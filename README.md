# Explaining Puns: Enhancing Computational Humor Understanding with Large Language Models

Authors: Yingchen Ma, Nemath Ahmed, Rajvi Parekh

### Summary

In this project, we used **fine-tuning** and **few-shot prompting** techniques to **improve the ability of large language models (LLMs) to understand humor**. Focusing on **puns** (a specific category of humor), we conducted experiments to investigate if these techniques allow the LLM to generate explanations for these puns that c**losely resemble human-produced explanations** and **effectively communicate their humor**. Subsequently, we performed human annotation to evaluate the **clarity, completeness, relevance, and insightfulness** of the LLM-produced explanations. Through both quantitative and qualitative evaluations, we demonstrate that **both fine-tuning and few-shot prompting techniques improve** a Llama-2-7b model's ability to generate high-quality explanations for puns.

The full project report, alongside the code and data, can be found in this repository.

This was a course final project for CS 8803 LLM (Large Language Models).

### Directory structure

- `annotations/`: human annotations for the quality of the LLM-produced explanations.
- `data/`: folder for input data.
- `experiments/`: notebooks containing all code.
- `results/`: files containing results.
