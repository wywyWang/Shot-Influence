# Shot Influence

## Update
This repo has been moved to [CoachAI Projects](https://github.com/wywyWang/CoachAI-Projects) and will no longer be maintained.

## Introduction
This repository contains the source code for the paper accepted in ICDM'21: *Exploring the Long Short-Term Dependencies to Infer Shot Influence in Badminton Matches*

## Getting started
### Prerequisites
- python3==3.6.9
- numpy==1.17.2
- pandas==0.24.2
- tensorflow-gpu==2.0.0
- keras_self_attention
- [ProSeNet](https://github.com/rgmyr/tf-ProSeNet)
- [DeepMoji](https://github.com/bfelbo/DeepMoji)
- [ON-LSTM](https://github.com/CyberZHG/keras-ordered-neurons)
- [Transformer](https://github.com/CyberZHG/keras-transformer)

### Install
Download the project
- with CMD
```
git clone https://github.com/yao0510/Shot-Influence.git
```

## Usage
### Train a model
```=python
python training.py
```

### Evaluate a model
```=python
python evaluate.py
```
