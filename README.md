# shakespeare-text-generation

Character level RNN that generates a shakespearean-like prose following the given input string.
Compared the outputs of using an LSTM and a GRU as the character level RNN.

Problem Statement: Given a character or sequence of characters, we want to predict the next character at each time step. Model is trained to follow a language similar to the works of Shakespeare.

Dataset used: TinyShakespeare (https://github.com/karpathy/char-rnn/tree/master/data/tinyshakespeare).  The original stanford dataset can be found at https://cs.stanford.edu/people/karpathy/char-rnn/shakespeare_input.txt. Created the training data as a pair of character sequences, with the input being a sequence of a certain length anf target being the same sequence shifted to the right.




Run on Google Collab for GPU. 
