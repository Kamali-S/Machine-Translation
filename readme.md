![Screenshot](MT.jpg)

Machine Translation Project - Application of Natural Language Processing
- Used Transfromers with Attention mechanism
- Gated Recurrent Units are also added in building the model as it solves the problem of Vanishing Gradient during backpropagation
- Attention Mechanism helps in better summarization of encoded text by using 3 things namely: 
  - Alignment Score: To predict next word in decoding, what all words to focus in the encoded text is done using this score
  - Attention Weights: Softmax of alignment scores
  - Context Vector: Weighted sum of Attention weights
 - Attention Mechanism is used in Decoder as we need it while decoding alone
 - Finally, the translated text is converted to audio using gTTS library
