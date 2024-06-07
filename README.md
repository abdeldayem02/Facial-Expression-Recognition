# Facial Expression Recognition using Vision Transformer (ViT)

## Project Overview

This project implements a Facial Expression Recognition (FER) system using the Vision Transformer (ViT) architecture. The system is capable of classifying facial expressions into seven categories: happy, sad, angry, fearful, disgusted, surprised, and neutral. With the Vision Transformer, we achieved a 90% accuracy in recognizing these expressions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Introduction

Facial expression recognition is a crucial task in computer vision, with applications ranging from human-computer interaction to psychological research. This project leverages the Vision Transformer (ViT) architecture, which has shown superior performance in various image classification tasks.

## Features

- **High Accuracy**: Achieved 85% accuracy in facial expression recognition.
- **ViT Architecture**: Utilizes the latest Vision Transformer model for efficient image classification.
- **Seven Expression Classes**: Recognizes seven different facial expressions.
- **Pre-trained Models**: Uses pre-trained weights for faster convergence and improved performance.


## Dataset

The model is trained on a standard facial expression dataset such as FER-2013, MMI Facial Expression Database and AffectNet. Ensure the datasets are downloaded and properly formatted. Here is an example of the dataset directory structure:

```
dataset/
    train/
        happy/
        sad/
        ...
    val/
        happy/
        sad/
        ...
    test/
        happy/
        sad/
        ...
```

## Model Architecture

The Vision Transformer (ViT) architecture is used for this project. ViT divides the input image into patches, linearly embeds each patch, and feeds the sequence of linear embeddings into a transformer encoder. The transformer processes the sequence and outputs class probabilities for facial expressions.

## Results

Our model achieved the following results on the test set:

- **Accuracy**: 85%
- **Precision**: 82%
- **Recall**: 81%
- **F1 Score**: 80%


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Mohammed Abdeldayem  
[LinkedIn](https://www.linkedin.com/in/mohammed-abdeldayem)  
