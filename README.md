# Deep_Leaning_and_Applied_AI_Project

**Project Title**: *Fine-Tuning a Large Language Model (LLM) for Italian-to-Neapolitan Dialect Translation*
**Author:** Aur Marina Iuliana  
**Student ID:** 1809715  

## Project Overview
The project focuses on **fine-tuning a Large Language Model (LLM)** to enhance its ability to understand and generate text in **Neapolitan dialect**.

## Dataset
The dataset used is sourced from [HuggingFace](https://huggingface.co/datasets/efederici/mt_nap_it). It contains a comprehensive collection of traditional Neapolitan songs from [napoligrafia](https://www.napoligrafia.it/) translated into Italian language.

## Data Fields
- **url**: Source URL of the text.
- **napoletano**: Text in the Neapolitan dialect.
- **italiano**: Corresponding text in standard Italian.
  
## Model
Gemma is a family of lightweight, state-of-the-art open models from Google, built from the same research and technology used to create the Gemini models. They are text-to-text, decoder-only large language models, available in English, with open weights for both pre-trained variants and instruction-tuned variants. Specifically, `Gemma-2-2B-it` is an instruction-tuned large language model (LLM) designed for dialogue scenarios, making it as an ideal candidate for our project, where we aim to finetune the model to enhance its understanding and generation of the Neapolitan dialect.

## Repository Structure
 - `nap-dialect-gemma-2-2b-it-finetuning`: the folder containing the Fine-Tuned `Gemma-2-2B-it` Model and its configuration.
 - `Data_Analysis.ipynb`: the jupyter notebook used for the Exploratory Data Analysis (EDA).
 - `Fine_Tuning.ipynb`: the jupyter notebook used for Fine-Tuning `Gemma-2-2B-it` Model.
 - `Performance_Evaluation.ipynb`: the jupyter notebook used for Evaluating Model Performance using metrics like Perplexity, BLEU score, ROUGE score and BERT score.
 - `report.pdf`: the final report summarizing the project findings.

## Results
The outcomes and visualizations derived from the experiments conducted in this project can be examined at the following link: [Weights & Biases Project](https://wandb.ai/marinaaur-sapienza/nap-dialect-finetuning?nw=nwusermarinaaur).
