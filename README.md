# Character-level RNN Shakespeare Text Generator

A project using a Recurrent Neural Network (RNN) to generate text. The model is trained to predict the next character in a sequence of text. A separate generation function then uses the trained model to repeatedly predict the next character, sampling probabilistically, until a specified number of words has been generated.

## Key Findings

The generated text follows the script structure well, with character names, colons, and line breaks matching the original format. The actual wording doesn't fully make sense; real words show up here and there, but they are mixed with invented ones, and sentences don't hold together grammatically.

## Tools

Python, PyTorch
