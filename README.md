# VerticalSemanticSearchBot

## Overview
Vertical Semantic Search Bot is an ML-powered project that utilizes four different BERT models from Hugging Face to create a semantic search bot. The bot aims to provide accurate and relevant answers to user queries based on the SQuAD dataset. The SQuAD dataset, which stands for Stanford Question Answering Dataset, is employed for training and fine-tuning the some of the BERT models we've used.

## Description
In Contrast to the traditional keyword searching,our implementation of a search engine includes semantic understanding of the query and the context to provide the user with the most relevant answer possible. We have chosen Medical as our vertical for this project. Selecting a vertical emphasizes the need for domain specific search engines for targeted markets,audience and niche job sectors.

## Approach and Methodology
* Finding and retrieving an appropriate dataset. We chose SQuAD.
* Filtering the dataset to cater only to our medical vertical and perform preprocessing.
* Implement already existing Question Answering models like BERT,BioBERT,ClinicalBERT and DistilBERT from HuggingFace on our dataset.
* Fine-tuning of the best pretrained models for QA on our dataset and providing the user with the closest answer from all the above implemented models.

## Results
* Based on the evaluation results, we compared the performance of each fine-tuned model.After careful analysis, **BioBERT** emerged as the top-performing model, showcasing its proficiency in handling medical-related queries and delivering accurate responses. The superior performance of BioBERT validated its suitability for the Semantic Vertical Search Engine's focus on medical-related information retrieval.
* **BERT** was the second best model after BioBERT. It gave us nearly accurate answers. 
* **DistilBERT** and **ClinicalBERT** either provided incorrect answers or weren’t capable of searching for an answer within the context at times. 



