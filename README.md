# 📩 AT&T Spam Detector – Deep Learning Project

## Context
AT&T faces a large volume of SMS spam impacting user experience and security.
This project builds an automated spam detection system using Deep Learning.

## Objectives
- Classify SMS messages as ham or spam
- Compare a baseline LSTM model with a Transformer-based model (DistilBERT)
- Provide business-oriented recommendations

## Dataset
- 5,572 SMS messages
- Labels: ham / spam
- Public dataset provided by Jedha

## Models
### Baseline
- Embedding + BiLSTM
- Accuracy ≈ 98%
- AUC ≈ 0.99

### Transfer Learning
- DistilBERT fine-tuned
- Accuracy ≈ 99%
- AUC ≈ 0.999

## Evaluation
- Accuracy, AUC
- Confusion matrices
- ROC curves

## Key Takeaways
- LSTM is fast and lightweight
- DistilBERT offers superior contextual understanding
- Best choice depends on performance vs cost trade-off

## Business Recommendation
- Deploy DistilBERT with A/B testing
- Adjust decision threshold based on false positive tolerance
- Consider hybrid architecture

## Tech Stack
Python, TensorFlow, Keras, PyTorch, HuggingFace Transformers, Scikit-learn

## 👤 Author
Faycel Faddaoui
