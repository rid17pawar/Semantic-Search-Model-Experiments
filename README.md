# Semantic-Search-Model-Experiments

## Dataset Used For Semantic Search/ Information Retrieval: 
[CISI Dataset - Kaggle](https://www.kaggle.com/datasets/dmaso01dsta/cisi-a-dataset-for-information-retrieval)
</br></br>

## Experiments:
#### Experiment-1. Using BM-25 Algorithm and Parameter Tuning For Semantic Search

*BM-25 Algorithm variations used:*
- BM25Okapi
- BM25L
- BM25Plus
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/4b061f8d-8626-4f5e-8270-1aaefecb5ad7)
</br>
*BEST MODEL: BM25Plus*
</br></br>

#### Experiment-2. Using Mean of Word Vectors (MWV) with Pretrained Embeddings For Semantic Search

*BM-25 Algorithm variations used:*
- word2vec
- GloVe
- FastText
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/885b4171-b6d7-4176-8226-c92c4828597a)
</br>
*BEST MODEL: word2vec*
</br></br>

#### Experiment-3. Using LDA Topic Modelling For Semantic Search

#### Result:
*Performs worst than BM-25*
</br></br>

#### Experiment-4. Using Universal Sentence Encoder (USE) For Semantic Search

*USE Model variations used:*
- Transformer Encoder
- Deep Averaging Network(DAN) Encoder
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/30f4a784-f121-403c-8dfe-95ad4c638a01)
</br>
*BEST MODEL: USE-Transformer*
</br></br>

#### Experiment-5. Using Pretrained and Finetuned Sentence Transformers (SBERT) For Semantic Search

#### Result:
![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/0d96bc97-6620-490d-ac3d-46b41021eb46)
</br>
*BEST MODEL: Finetuned SBERT*
</br></br>

#### Final Result:
![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/3d3094a6-0234-45ee-9ef1-b86ad68dc37e)

![image](https://github.com/rid17pawar/Semantic-Search-Model-Experiments/assets/47048717/2d00cdf3-a0d5-4cd7-8945-4df601138813)
</br>
**Overall Best Model: Finetuned SBERT**
</br></br>
