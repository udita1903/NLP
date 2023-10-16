# Abstractive text summarizer tool
It iss built using an Encoder-Decoder architecture, the final state of the LSTM will be the input for the decoder.
Attention Mechanism is employed to increase the importance of certain words or sequences to get the desired target.
A bidirectional LSTM enables the production of better context vector hence obtaining a better semantic meaning.
Beam search is used instead of the greedy algorithm to pick the word with the maximum probability.
