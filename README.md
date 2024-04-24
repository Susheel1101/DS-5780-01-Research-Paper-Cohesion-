# DS-5780-01-Research_Paper-Cohesion
# Distinguishing the Author: An NLP Analysis of Cohesion
in Human vs. AI-Generated Essays


## Purpose

The purpose of this study is to investigate the capability of linguistic features to differentiate essays as either AI-generated or composed by second language (L2) writers. We aim to determine whether AI can replicate the coherence and linguistic nuances that are emblematic of human writing. By examining semantic, lexical, and referential cohesion within essays, we hypothesize that human texts, particularly from distinct first language (L1) backgrounds, will showcase higher levels of cohesion.

## Data

The dataset used in this study is meticulously curated to examine the subtleties of AI and human-generated essays. It includes:

- Essays from high-proficiency English L2 learners with Hindi, Chinese, and Spanish L1 backgrounds.
- AI-generated essays using advanced AI writing tools responding to the same prompts as the human essays.
- A balanced collection of roughly 1,488 essays spanning various subjects.

Each essay is labeled with:

- The full essay text.
- The specific prompt addressed.
- The native language of the human essay writers.
- A binary label indicating whether the essay is human-generated (0) or AI-generated (1).

This structure is essential for analyzing textual cohesion and for the machine learning classification task.

## Code

The code written for this analysis includes:

- Feature extraction using the spaCy library.
- Quantitative analyses to explore cohesion differences.
- A Random Forest classifier trained on linguistic features to assess the model’s accuracy in discerning the provenance of the essays.

The code also includes visualization and statistical validation of the findings, offering insights into the subtleties of human and AI-generated language.

## Analysis

The analysis focuses on:

- Classification accuracy based on the L1 of the L2 writers.
- The effect of different writing prompts on the model’s predictive power.
- The interaction between L1 backgrounds and prompts and their combined influence on classification accuracy.

By focusing on high proficiency English essays from native Hindi, Chinese, and Spanish speakers, the study enhances robustness and allows for an exploration of cross-linguistic influences on cohesion.


*This README file is part of the supplementary materials submitted along with the paper titled "Analysis of Linguistic Features in AI-Generated and L2 Writer Essays".*
