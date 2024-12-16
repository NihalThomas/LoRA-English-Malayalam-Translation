# Fine-Tune GEMMA 2B for Bilingual Translation (English to Malayalam) with LoRA

This repository contains a Jupyter Notebook that provides a general workflow for fine-tuning the GEMMA 2B model for bilingual translation tasks. Specifically, it focuses on translating between English and Malayalam using the Low-Rank Adaptation (LoRA) method.

## Overview

The notebook covers the following key aspects:

- **Model Introduction**: Overview of the GEMMA 2B model and the benefits of using LoRA for efficient fine-tuning.
- **Data Requirements**: Guidelines on preparing a parallel corpus for English-Malayalam translation tasks.
- **Fine-Tuning Workflow**: Step-by-step instructions for:
  - Loading the pre-trained GEMMA 2B model.
  - Applying LoRA for efficient parameter updates.
  - Running the fine-tuning process.
- **Evaluation**: BLEU technique is used to assess the performance of the fine-tuned model.

## Steps in the notebook :
   - Preprocess your dataset. [Used dataset is given below]
   - Configure the GEMMA 2B model with LoRA.
   - Fine-tune and evaluate the model.

## Dataset

This notebook uses the [English-Malayalam Translation Dataset](https://www.kaggle.com/datasets/nihalthomas15/lang-trans-eng-malayalam) from Kaggle. Ensure that you download and preprocess the dataset before beginning the fine-tuning process.

## Contributions

Feel free to contribute by submitting issues or pull requests to enhance the notebook or its documentation.

## License

This project is licensed under the Apache 2.0. See the `LICENSE` file for more details.

---

Enjoy fine-tuning!
