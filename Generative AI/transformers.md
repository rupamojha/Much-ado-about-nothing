# Transformers
## RNNs - precursor to transformers
The RNNs are the neural network where at each time step of the input there is an output and a hidden state. The hidden state stores the information of previous time steps and is useful to identify relationships between elements are various time steps. <br>
Drawbacks:<br>
1. The training time is large for large sequences as only one input at a time step.
2. Vanishing or Exploding Gradients<br>

The transformers have two blocks:
- Encoder
- Decoder

The Decoder has two parts:
- Self Attention (which parts to focus on)
- Feed forward neural network (what next word should be)

Steps for getting output:
- Tokenize the input
- Run the model
- Decode the output
