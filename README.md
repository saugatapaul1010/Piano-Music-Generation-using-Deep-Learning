# Music-Generation-using-Deep-Learning-LSTM-

In this repository, I will build a simple AI which generates piano music. A special type of Recurrent Neural Networks called LSTM is used for this software. The two most important concepts covered in this case study are time distributed dense layer and stateful RNNS. The documentation will be updated in some days.


# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).

### Requirements

This code is written in Python 2, and it requires the [Keras](https://keras.io) deep learning library.

### Usage

All input data should be placed in the `data/` directory. The example `input.txt` is taken from the [Nottingham Dataset (Cleaned)](https://github.com/jukedeck/nottingham-dataset).

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py 100
```

Training loss/accuracy is stored in `logs/training_log.csv
