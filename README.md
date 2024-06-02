# Tensorflow Chatbot

## Overview
This repository contains the full code for implementing a chatbot using TensorFlow's Sequence to Sequence (Seq2Seq) model. The chatbot is trained on the Cornell Movie Dialogue dataset and is capable of holding engaging conversations after a few hours of training.

## Dependencies
Ensure the following Python libraries are installed:

- `numpy`
- `scipy`
- `six`
- `tensorflow`

Use `pip` to install any missing dependencies:
```bash
pip install numpy scipy six tensorflow
```

## Usage

### Training the Chatbot
To train the chatbot, modify the `seq2seq.ini` file to set the mode to `train`:
```ini
mode = train
```
Then, run the training script:
```bash
python execute.py
```

### Testing the Chatbot
To test the chatbot during or after training, modify the `seq2seq.ini` file to set the mode to `test`:
```ini
mode = test
```
Then, run the testing script:
```bash
python execute.py
```

By following these steps, you can train and interact with the chatbot to experience its conversational capabilities.
