# NLP_TASKS_Sentiment_Analyzer
Help customers division to judge if feedback contains negative emotion.

Here is a playground, As I did in competition, stackig tech is used in this notebook.

Tokenizer is Mecab with Neologism dictionary.

Pre-trained W2V is fasttext 300D.

Metric measure to success: F1 (negative examples only takes up 20% of data set)

The models I'm using to stack

Text CNN:

4 different filter size with Covn2D, activation funcation is elu.

LSTM with Attention:

Bidirectional CuDNNLSTM with Atten

GRU with Attention:

Bidirectional CuDNNGRU with Atten

