# Predicting DNA Enhancer with Deep Learning

## Overview
EnhancerNet is a deep learning architecture that combines Bi-LSTM, attention mechanisms, and residual networks to accurately identify DNA enhancer sequences and classify their strength. This model tackles the challenging task of enhancer recognition in genomic sequences by leveraging advanced neural network components.


## Key Features
- End-to-end deep learning pipeline
- Bi-directional LSTM with attention mechanism
- Residual neural network integration
- Dual functionality: enhancer recognition and - - - strength classification
- Fast prediction times (<2s per sample)

## Model Architecture

```
The architecture of EnhancerNet consists of the following components:

1. **Input Layer**: Accepts DNA sequences as input.
2. **Embedding Layer**: Converts nucleotide sequences into dense vectors.
3. **Bi-directional LSTM Layer**: Captures long-range dependencies in both forward and backward directions.
4. **Attention Mechanism**: Focuses on important parts of the sequence.
5. **Residual Network**: Enhances feature extraction and model depth.
6. **Fully Connected Layer**: Maps features to output space.
7. **Output Layer**: Produces final predictions for enhancer presence and strength.

Below is a simplified diagram of the model architecture:
```

```
Input Layer -> Embedding Layer -> Bi-directional LSTM -> Attention Mechanism -> Residual Network -> Fully Connected Layer -> Output Layer
```



## Performance

## Validated through rigorous testing:
5-fold cross validation
10-fold cross validation
Independent testing


Outperformed 19 state-of-the-art methods
Exceptional results in independent testing scenarios

## Technical Requirements

Python 3.x
TensorFlow 2.0
System Requirements:

RAM: 32GB (recommended)
CPU: 2.60GHz (6 cores)
OS: Windows 11 (tested)



## Training Metrics

Training time: ~25 seconds per epoch
Prediction time: <2 seconds per sample



