# **Text Generation**

## **Main Components**
The transformer architecture consists of encoder and decoder components.

## **Example: Translation Task**
* **Objective:** Original objective of transformer architecture was sequence-to-sequence tasks like translation.
* **Process:**
    1. Tokenize input words using the same tokenizer used during training.
    2. Feed tokens into encoder.
    3. Data passes through:
        - Embedding layer
        - Multi-headed attention layers
        - Feed-forward network
    4. Data from the encoder is a deep representation of input sequence's structure and meaning.
    5. This data influences the decoder's self-attention mechanisms.
    6. Add a start of sequence token to decoder input.
    7. Decoder predicts next token using contextual understanding from encoder.
    8. Continue until end-of-sequence token is predicted.
    9. Detokenize the final sequence to produce the output.

## **Understanding Different Transformer Varieties**

### **Encoder-only models:**
* Can act as sequence-to-sequence models.
* Input and output sequences have the same length.
* **Example:** BERT
* Adaptations can perform tasks like sentiment analysis.

### **Encoder-decoder models:**
* Perform well on tasks where input and output sequences differ in length.
* Can be used for text generation tasks.
* **Examples:** BART and T5.

### **Decoder-only models:**
* Have scaled and now generalize to most tasks.
* **Examples:** The GPT family, BLOOM, Jurassic, LLaMA, etc.

## **Key Takeaways:**
* Transformers can be used in various configurations for different tasks.
* Translation, as demonstrated, uses both encoder and decoder.
* You don't need to dive deep into the architecture for general use. Instead, understanding the broader concepts helps in model usage and reading documentation.
* **Prompt engineering:** Focus on interacting with transformer models using natural language and creating prompts with words.

---
# Explanation of Encoder and Decoder

Imagine you're trying to send a secret message. You'd first convert (or "encode") the message into a code that only you and your friend understand. Then, when your friend receives it, they'd convert (or "decode") that code back into the original message to understand it.

In the context of machine learning:

- Encoder: It takes the input information (like a sentence in English) and compresses it into a more compact, meaningful representation, almost like a "code" that captures the essence of the input.

- Decoder: It takes that compact "code" produced by the encoder and expands it into a new form of information (like translating it into a sentence in French).

So, the encoder captures the important features of the input, and the decoder uses those features to produce a desired output.
