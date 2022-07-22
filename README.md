Abstractive Text Summarization attempts to identify important sections, interpret the context and intelligently generate a summary of all the inputted data.

Designed summaries of ~2000 article pairs in the wikihow dataset. Seq-seq models have been created using LSTM and GRU. Parameters for both these models have been tuned along with the implementation of teacher forcing and simple dot product attention mechanism. Further the attention weights have been plotted and evaluated using criteria like - BLEU, ROUGE, F-Score

Reference:
Dataset-https://arxiv.org/abs/1810.09305
https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html
