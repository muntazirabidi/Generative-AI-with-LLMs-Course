## Video Resources:

### IBM Technology Series:

1. [**What is Transformer?**](https://www.youtube.com/watch?v=ZXiruGOCn9s)
2. [**What are auto-encoders?**](https://www.youtube.com/watch?v=qiUEgSCyY5o)
3. [**How LLM works?**](https://www.youtube.com/watch?v=5sLYAQS9sWQ&t=1s)
4. [**What are Generative AI Models?**](https://www.youtube.com/watch?v=hfIUstzHs9A&t=227s)
5. [**How to produce Enterprise-ready Foundations Models**](https://www.youtube.com/watch?v=eHPqfNLeous)

### Google Cloud Tech
6. [**What is Generative AI?**](https://www.youtube.com/watch?v=G2fqAlgmoPo&list=RDLVeHPqfNLeous&index=21)

---
### Explainable AI
7. [**Explainabgle AI in FInancial Services**](https://www.youtube.com/watch?v=5gPpI993Wjg)

--- 
## Attention is all yours

"Attention is All You Need" is a research paper published in 2017 by Google researchers, which introduced the Transformer model, a novel architecture that revolutionized the field of natural language processing (NLP) and became the basis for the LLMs we  now know - such as GPT, PaLM and others. The paper proposes a neural network architecture that replaces traditional recurrent neural networks (RNNs) and convolutional neural networks (CNNs) with an entirely attention-based mechanism. 

The Transformer model uses self-attention to compute representations of input sequences, which allows it to capture long-term dependencies and parallelize computation effectively. The authors demonstrate that their model achieves state-of-the-art performance on several machine translation tasks and outperform previous models that rely on RNNs or CNNs.

The Transformer architecture consists of an encoder and a decoder, each of which is composed of several layers. Each layer consists of two sub-layers: a multi-head self-attention mechanism and a feed-forward neural network. The multi-head self-attention mechanism allows the model to attend to different parts of the input sequence, while the feed-forward network applies a point-wise fully connected layer to each position separately and identically. 

The Transformer model also uses residual connections and layer normalization to facilitate training and prevent overfitting. In addition, the authors introduce a positional encoding scheme that encodes the position of each token in the input sequence, enabling the model to capture the order of the sequence without the need for recurrent or convolutional operations.

![Transformer Architecture](./figures/full-transformer.png)

