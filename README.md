# Marine Mammal Classification By Sound

## Overview

This project aims to classify marine mammals based on the sound recordings in the Watkins Marine Mammal Sound Database. We use a Convolutional Neural Network (CNN) to classify different marine mammal species based on their unique acoustic signatures.

## Dataset

The dataset is sourced from the [Watkins Marine Mammal Sound Database](https://whoicf2.whoi.edu/science/B/whalesounds/index.cfm). The dataset consists of audio files from various marine mammal species, including dolphins, whales, and seals. Below is a list of the species included in the dataset:

- **Clymene Dolphin**
- **Killer Whale**
- **Spotted Seal**
- **Leopard Seal**
- **Northern Right Whale**
- **Ross Seal**
- **Dusky Dolphin**
- **Melon-Headed Whale**
- **Long-Finned Pilot Whale**
- **False Killer Whale**
- **Bearded Seal**
- **Finback Whale**
- **Ribbon Seal**
- **Gray Whale**
- **Boutu Amazon River Dolphin**
- **Pantropical Spotted Dolphin**
- **Sea Otter**
- **Common Dolphin**
- **Fraser's Dolphin**
- **Striped Dolphin**
- **Tucuxi Dolphin**
- **Rough-Toothed Dolphin**
- **Blue Whale**
- **Gray Seal**
- **Bottlenose Dolphin**
- **White-Sided Dolphin**
- **Harp Seal**
- **Ringed Seal**
- **Heaviside's Dolphin**
- **Grampus Risso's Dolphin**
- **Sperm Whale**
- **Southern Right Whale**
- **White-Beaked Dolphin**
- **Dall's Porpoise**
- **Narwhal**
- **Juan Fernandez Fur Seal**
- **Short-Finned (Pacific) Pilot Whale**
- **Commerson's Dolphin**
- **Harbour Seal**
- **Humpback Whale**
- **Finless Porpoise**
- **Weddell Seal**
- **Long-Beaked (Pacific) Common Dolphin**
- **Minke Whale**
- **West Indian Manatee**
- **Hooded Seal**
- **New Zealand Fur Seal**
- **Bowhead Whale**
- **Walrus**
- **Spinner Dolphin**
- **Steller Sea Lion**
- **Atlantic Spotted Dolphin**
- **Beluga White Whale**
- **Harbor Porpoise**
- **Irawaddy Dolphin**

## Problem Statement

The goal is to build a machine learning model capable of identifying the species of a marine mammal based on its sound. The model should be able to classify audio recordings into one of the species listed above.

## Approach

We will use a Convolutional Neural Network (CNN) to process the audio data. The process involves the following steps:

1. **Preprocessing**:
    - Convert audio files into spectrograms or Mel-frequency cepstral coefficients (MFCCs).
    - Normalize the data to ensure consistent input to the model.

2. **Model Architecture**:
    - Design and train a CNN architecture that is suitable for audio classification tasks.
    - Implement dropout, batch normalization, and other regularization techniques to prevent overfitting.

3. **Training**:
    - Use a training-validation split to train and evaluate the model's performance.
    - Experiment with different hyperparameters such as learning rate, batch size, and number of layers.

4. **Evaluation**:
    - Evaluate the model using accuracy, confusion matrices, and F1 scores to assess its performance in classifying marine mammal sounds.

## Results

After training the model, we will report the following metrics:

- Accuracy
- Precision, Recall, and F1 Score for each species
- Confusion Matrix

## Future Work

Future improvements could involve:

- Exploring other neural network architectures like recurrent neural networks (RNNs) or transformers for sequential data.
- Expanding the dataset with more samples for underrepresented species.
- Investigating transfer learning from pre-trained models for sound classification tasks.

## References

- [Watkins Marine Mammal Sound Database](https://whoicf2.whoi.edu/science/B/whalesounds/index.cfm)
