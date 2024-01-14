# LLM-Model____Detect-AI-Generated-Text


I have implemented BERT transformer model for the Dataset.

# Dataset

Skewed Dataset:
<img width="405" alt="image" src="https://github.com/palswayam5/LLM-Model---Detect-AI-Generated-Text/assets/97727708/0839020f-9395-4ca6-8868-64e26420407e">


# BERT
1. Since it is a Transformer model it consists of two major units which are **Encoder** and **Decoder**
         1. Encoder --> As opposed to directional models, which read the text input sequentially (left-to-right or right-to-left), the Transformer encoder reads the entire                             sequence of words at once. Therefore it is considered bidirectional, though it would be more accurate to say that it’s non-directional. This                                    characteristic allows the model to learn the context of a word based on all of its surroundings (left and right of the word).
         2. Decoder --> Predicts the output. Consists of several layers of connected neural newtwork layer.
   (Note: Encoder creates embedded vector).
   (To know more about BERT read [https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270])
2. 
