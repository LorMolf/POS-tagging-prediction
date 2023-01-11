# POS-tagging-prediction
NLP ~ POS tagging using neural architectures with LSA analysis for retrieving the embedding of OOV words.

This repository contains a description of the POS tagging task and some proposals for tackling it. Specifically, we show the performances and results of some Recurrent Neural Networks (like LSTM and GRU), aware of the existence of the most recent approaches based on BERT that are state of the art.

The main notebook ("POS-Tagging-Problem") contains all the aforementioned descriptions and the gotten results while "LSA-Embedding-Analysis" carries out a Latent Semantic Analysis on the dataset to retrieve a set of similar terms for each of the Out Of Vocabulary terms. Such a procedure is performed in order to determine coherent embeddings that avoid introducing biased representations in the model's latent domain. 

To reproduce the results, please note that the files contained in the "files2import" folder need to be imported. The data required by the main and secondary notebooks are those contained in the "R2python" and "python2R" folders, respectively.



Credits for this work go to ___Memona Shah___, ___Alessandro Rizzo___, ___Vito Parisi___ and ___Lorenzo Molfetta___. 
