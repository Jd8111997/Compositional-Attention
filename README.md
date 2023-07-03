# Compositional-Attention

This repository contains the implementation of the research paper titled "COMPOSITIONAL ATTENTION:
DISENTANGLING SEARCH AND RETRIEVAL" by Mittal et al(https://arxiv.org/pdf/2110.09419.pdf).          

The paper proposes a novel attention mechanism called 'Compositional Attention', that replaces standard Multi Head Attention block in transformers. The proposed mechanism disentangles search and retrieval and composes them in a dynamic, flexible and context-dependent manner through an additional soft competition stage between the query-key combination and value pairing. In the paper, authors showed that this method out performs standard multi-head attention on a variety of tasks including some out of distribution setting. The goal of this project is to apply this method for a character level language modelling task to explore the capabilities of novel 'Compositional Attention' mechanism. For a reference baseline, I utilize the implementation of the multi-head attention mechanism for character-level language modeling, which was originally provided by Andrej Karpathy for his Nano GPT tutorials. All the hyper parameters are kept same as Karpathy's implementation to make a fair comparision.            

The proposed method shows significant drop in train loss(around 95 %) and validation loss(around 96%) compared to the vanilla multi head attention block.

# Reference
- https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing#scrollTo=hoelkOrFY8bN
- https://github.com/sarthmit/Compositional-Attention
