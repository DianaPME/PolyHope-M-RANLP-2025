# 🕊️ PolyHope-M: Bridging Hope Speech Detection Across Multiple Languages
Hope Speech Detection in Social Media Texts 
Welcome to the repository for the PolyHope-M Shared Task at RANLP 2025! This repository contains the implementation and resources developed for tackling the challenge of detecting and classifying hope in social media texts across English, Spanish, German and Urdu

## 🌟 Task Overview
The PolyHope shared task focuses on analyzing the nuanced expression of hope in social media. It aims to promote research in inclusive language technologies, enhance understanding from psychological perspectives, and develop computational models for fine-grained detection of hope across languages.

## 🔍 Subtasks
The challenge is divided into two main subtasks:

Subtask 1: Binary Hope Speech Detection 

Subtask 1.a: English

Subtask 1.b: Spanish 

Subtask 1.c: German

Subtask 1.d: Urdu

👉 Classify texts into:

Hope: Tweets expressing hope, expectation, or desire.

Not Hope: Tweets without hopeful sentiment.

Subtask 2: Multiclass Hope Speech Detection 

Subtask 2.a: English

Subtask 2.b: Spanish 

Subtask 2.c: German

Subtask 2.d: Urdu

👉 Classify texts into:

Generalized Hope: Broad, non-specific hope.

Realistic Hope: Hope grounded in plausible outcomes.

Unrealistic Hope: Hope for highly unlikely outcomes.

Not Hope: No hope expressed.

## 📂 Repository Contents
This repository includes:

Folder / File Description

data_cleaning/ Scripts for cleaning and preprocessing raw tweet data.
data_augmentation/ Code for augmenting the dataset to address class imbalance.
few_shot_samples/ Scripts for extracting few-shot samples for low-resource settings.
roberta_binary_classification/ Code for fine-tuning and predicting binary labels with XLM-RoBERTa model.
roberta_multiclass_classification/ Code for fine-tuning and predicting multiclass labels with XLM-RoBERTa model.
README.md This readme file.

## ✅ If you require access to the dataset, please visit the official competition page: 
👉 https://www.codabench.org/competitions/5635/

Note: The dataset is provided by the PolyHope-M shared task organizers and may require registration or agreement to specific terms of use.
