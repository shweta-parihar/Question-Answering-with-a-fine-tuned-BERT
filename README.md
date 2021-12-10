# Question-Answering-with-a-fine-tuned-BERT

# About BERT

BERT is a Bidirectional Encoder Representations from Transformers. The transformer encoder uses attention (Multi-Headed Self Attention) mechanism that learns contextual relations between words (or sub-words) in text. BERT alleviates the unidirectionality constraint by using a 'masked language model' (MLM) pre-training objective. The MLM model randomly masks some of the tokens from the input, and the objective is to predict the masked word based on its surroundings (left and right of the word). Because of its bidirectionality, it can understand the intent behind the query asked, thus obtaining a deeper sense of language context and flow.

#

I have used a fine-tuned BERT model from the Hugging Face Transformers library to answer questions based on the context. Objective of question answering system (QA) is to generate concise answer of arbitrary question asked in natural language. This kind of information retrieval and text summarization is required with growth of digital information.
