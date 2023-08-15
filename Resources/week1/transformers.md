# Notes on Transformer Architecture and Natural Language Processing

---

## 1. Historical Context
- **Generative Algorithms:** Not new in NLP. Earlier generation used RNNs (Recurrent Neural Networks).
- **RNNs:** Powerful, but had limitations, especially with large computations. Struggled with longer contextual inputs.
- **Transformer Architecture:** Major advancement. Brought massive improvements in regenerative capability.

---

## 2. Understanding Transformers
- **Key Attribute:** Self-attention.
- **Self-Attention Mechanism:**
    - Learns relevance and context of all words in a sentence.
    - Assigns attention weights to relationships of words to understand context.
    - Allows algorithm to discern specific details, e.g., who possesses an item in a sentence.
    - Uses an attention map to illustrate attention weights between words.

---

## 3. Transformer Model Overview
- **Components:** Divided into Encoder and Decoder.
- **Data Flow:**
    - Inputs at the bottom.
    - Outputs at the top.
    - Inspired by the original paper "Attention is All You Need."

![Transformers Artchitecture Overview](./figures/simple_transformer.png)
---

## 4. Language Processing Steps
1. **Tokenization:**
    - Converts words into numbers.
    - Words represented by a position in a dictionary.
    - Types: Complete words or parts of words.

2. **Embedding Layer:**
    - Converts token IDs into vectors within a high-dimensional space.
    - Each token ID matched to a multi-dimensional vector.
    - Vector captures meaning and context.
    - Used in older models like Word2vec as well.
    - Example: Vector size in original transformer paper = 512.

3. **Positional Encoding:**
    - Added to token vectors.
    - Preserves word order information.
  
4. **Self-Attention Layer:**
    - Analyzes relationships between tokens.
    - Weights are learned during training.
    - Multiple sets of weights learned in parallel = Multi-headed self-attention.
    - Each head learns a different aspect of language.
    - Number of heads can range between 12-100.

5. **Feed-Forward Network:**
    - Processes the output from self-attention.
    - Outputs a vector of logits, each representing a probability score for tokens.
  
6. **Softmax Layer:**
    - Normalizes logits into a probability score.
    - Predicts the most likely next token.

---

## Domain Explanation:

- **RNNs (Recurrent Neural Networks):** Neural networks where connections between nodes form a sequence. Useful for sequential data but can struggle with long sequences due to memory constraints.
  
- **Transformer Architecture:** A newer model architecture that utilizes self-attention mechanisms, allowing it to weigh input tokens differently and capture long-term dependencies in data.
  
- **Self-Attention Mechanism:** Allows the model to weigh the significance of tokens in a sequence, enabling it to focus on the most relevant parts for a given task.
  
- **Tokenization:** The process of converting input text into tokens, which are smaller units of text.
  
- **Embedding Layer:** Represents words as dense vectors of fixed size. The closeness of vectors can represent semantic similarity among the words.
  
- **Positional Encoding:** Adds information about the position of a word within a sequence, necessary since transformers process tokens in parallel and don't have inherent sense of order.
  
- **Softmax Layer:** A function that turns numbers aka logits into probabilities that sum to one. The output of the softmax function is equivalent to a categorical probability distribution.

---
