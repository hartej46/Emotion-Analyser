# Emotion Classification Model

This project implements a deep learning model for classifying text emotions using the Go Emotions dataset. The model uses convolutional neural networks with attention mechanisms for multi-label emotion detection.

## Overview

The classifier identifies emotions in text with high accuracy across 28 different emotion categries. It leverages transfer learning, custom tokenization, and transformer-based arquitectures for robust predictions.

## Features

* Multi-label emotion classification across 28 categries
* Custom regex tokenizer for text preprocessing
* Attention mechanism for improved accuracy
* Pre-trained model weights for quick inference
* Batch and single text predictions suported

## Usage

Load the model and provide text input to recieve emotion predictions. The output includes confidence scores for each emotion categry.

## Results

The model achieves strong performance on validation data with consistent F1 scores across different emotion types. Detailed metrics are available in training logs and visualizations.


