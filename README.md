# -Neural-translation-model
building a neural network that translates from English to German with  tensorflow and encoder decoder model.
 create a neural network that translates from English to German
 custom model consists of an encoder RNN and a decoder RNN
The encoder takes words of an English sentence as input, and uses a pre-trained word embedding to embed the words into a 128-dimensional space. 
The decoder RNN takes the internal state of the encoder network as its initial state. A start token is passed in as the first input, which is embedded using a learned German word embedding.
The decoder RNN then makes a prediction for the next German word, which during inference is then passed in as the following input,
