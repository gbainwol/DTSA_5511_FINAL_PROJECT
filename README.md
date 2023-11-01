# DTSA_5511_FINAL_PROJECT
The repository for my final project for DTSA 5511 Introduction to Deep Learning. 
# Facial Expression Recognition Machine Learning Model Comparisons

A repository dedicated to comparing the performance of various machine learning models, both with and without weights, on a specific dataset.

## Table of Contents
- [Introduction](#introduction)
- [Models Evaluated](#models-evaluated)
- [Key Findings](#key-findings)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This repository focuses on the analysis of the performance of different machine learning models. It is important to compare and understand the efficiency and accuracy of models to determine the most suitable one for a particular application.

## Models Evaluated
- ANN (Artificial Neural Network)
- CNN (Convolutional Neural Network)
- SVM (Support Vector Machine)
- VGG16

## Key Findings
- CNN models (both with and without weights) demonstrate the highest accuracy among all.
- ANN and SVM models lag in performance in comparison to VGG16 and CNN models.
- The incorporation of weights seems to significantly affect the performance of some models, while others remain relatively unaffected.
- [For a detailed breakdown, check here](link-to-detailed-breakdown.md)

## Usage
To run the models and compare the results:

```bash
git clone <repository-link>
cd path-to-repo
pip install -r requirements.txt
python main.py
