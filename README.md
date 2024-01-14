# LLM-Model:Detect-AI-Generated-Text

# Dataset
1. Data 1: [https://www.kaggle.com/competitions/llm-detect-ai-generated-text/data]
2. Data 2: [https://www.kaggle.com/datasets/alejopaullier/daigt-external-dataset/data]

# Removed Skewness of the Dataset
1. Skewed Dataset:
<img width="405" alt="image" src="https://github.com/palswayam5/LLM-Model---Detect-AI-Generated-Text/assets/97727708/0839020f-9395-4ca6-8868-64e26420407e">
<br/>
2. Updated Dataset:
<img width="301" alt="image" src="https://github.com/palswayam5/LLM-Model---Detect-AI-Generated-Text/assets/97727708/c2ac0195-1222-4557-a5c0-995a78456a87">


# BERT
1. Since it is a Transformer model it consists of two major units which are **Encoder** and **Decoder** </br>
         1. Encoder --> As opposed to directional models, which read the text input sequentially (left-to-right or right-to-left), the Transformer encoder reads the entire<br/>             sequence of words at once. Therefore it is considered bidirectional, though it would be more accurate to say that it’s non-directional. This<br/>                             characteristic allows the model to learn the context of a word based on all of its surroundings (left and right of the word).<br/>
         2. Decoder --> Predicts the output. Consists of several layers of connected neural newtwork layer. <br/>
   (Note: Encoder creates embedded vector). <br/>
   (To know more about BERT read [https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270]) <br/>
2. Encoder Layer (Preprocessing layer to mark embeddings to the dataset) ----> Dropout Layer -------> Dense Layer <br/>
