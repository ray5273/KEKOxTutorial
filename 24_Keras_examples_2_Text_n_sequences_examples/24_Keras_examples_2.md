## 케라스 예제 2(Keras examples)
[원문 링크](https://github.com/keras-team/keras/tree/master/examples)
> 현 디렉토리에는 케라스를 활용한 예제들 중 test, sequence를 다루는 코드들이 있습니다. rnn, lstm 등 모델들의 이론을 알고있는 전제하에 실제 구현에 초점을 맞춰져 있으므로 코드에 첨가된 주석 외 정보는 직접 찾아보셔야 합니다.

* keras
* rnn
* lstm
* seq2seq

### Text & sequences 예제

[addition_rnn.py](addition_rnn.py)
Implementation of sequence to sequence learning for performing addition of two numbers (as strings).

[babi_rnn.py](babi_rnn.py)
Trains a two-branch recurrent network on the bAbI dataset for reading comprehension.

[babi_memnn.py](babi_memnn.py)
Trains a memory network on the bAbI dataset for reading comprehension.

[imdb_bidirectional_lstm.py](imdb_bidirectional_lstm.py)
Trains a Bidirectional LSTM on the IMDB sentiment classification task.

[imdb_cnn.py](imdb_cnn.py)
Demonstrates the use of Convolution1D for text classification.

[imdb_cnn_lstm.py](imdb_cnn_lstm.py)
Trains a convolutional stack followed by a recurrent stack network on the IMDB sentiment classification task.

[imdb_fasttext.py](imdb_fasttext.py)
Trains a FastText model on the IMDB sentiment classification task.

[imdb_lstm.py](imdb_lstm.py)
Trains an LSTM model on the IMDB sentiment classification task.

[lstm_stateful.py](lstm_stateful.py)
Demonstrates how to use stateful RNNs to model long sequences efficiently.

[lstm_seq2seq.py](lstm_seq2seq.py)
Trains a basic character-level sequence-to-sequence model.

[lstm_seq2seq_restore.py](lstm_seq2seq_restore.py)
Restores a character-level sequence to sequence model from disk (saved by [lstm_seq2seq.py](lstm_seq2seq.py)) and uses it to generate predictions.

[pretrained_word_embeddings.py](pretrained_word_embeddings.py)
Loads pre-trained word embeddings (GloVe embeddings) into a frozen Keras Embedding layer, and uses it to train a text classification model on the 20 Newsgroup dataset.

[reuters_mlp.py](reuters_mlp.py)
Trains and evaluate a simple MLP on the Reuters newswire topic classification task.

----