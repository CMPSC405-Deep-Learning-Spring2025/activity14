# Activity 14
## Due: 9am on March 26, 2025

## Objectives
- Apply character-level RNNs to classification and text generation by completing PyTorch tutorials, analyzing how sequential data is processed and learned.
- Compare the impact of different modeling approaches by summarizing key findings on how embeddings differ from simple n-gram techniques.
- Evaluate the role of hidden states, temperature in sampling, and the vanishing gradient problem by connecting theoretical insights from D2L to practical observations in the tutorials.

## Tasks

1. Complete [NLP From Scratch: Classifying Names with a Character-Level RNN](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html) tutorial.
2. Complete [https://pytorch.org/tutorials/intermediate/char_rnn_generation_tutorial.html](https://pytorch.org/tutorials/intermediate/char_rnn_generation_tutorial.html) tutorial.
3. Answer discussion questions on conceptual and practical connections.

## Discussion

1. The [D2L chapter 9.4](https://d2l.ai/chapter_recurrent-neural-networks/rnn.html) introduces the concept of hidden states in RNNs, where each hidden state captures the information from previous time steps. In the PyTorch tutorial, the model generates text character by character using its hidden state. How does the quality of generated text change when the hidden state is initialized differently (e.g., with zeros vs. random initialization)? What might this tell us about the role of hidden states in sequence generation?

TODO

2. The PyTorch text generation tutorial allows you to change the `temperature` when sampling characters. Based on the [D2L chapter 9.4](https://d2l.ai/chapter_recurrent-neural-networks/rnn.html) discussion of probability distributions, how does increasing or decreasing the temperature affect the diversity of generated text?

TODO

3. The [D2L chapter 9.5](https://d2l.ai/chapter_recurrent-neural-networks/rnn-scratch.html) discusses the vanishing gradient problem in standard RNNs. When running the PyTorch text generation tutorial, did you notice any difficulties in generating long, coherent text? How might this be related to the limitations of simple RNNs?

TODO

## Assessment

To receive a point for this activity, submit a modified README with your answers under "Discussion" and modified `Classification.py` and `Generation.py` with completed code from the tutorials.
