# Sentence Classification using CNN

## The word embeddings have been created using spaCy (english language model)

## The CNN used is quite simple 
*  Layer 1 has 15 filters of size 5 x 35 , with stride 1
    * followed by ReLU and Maxpool
*  Layer2 has 30 filters of size 5x5 with stride 1
    * followed by RelU and  Maxpool
* This is followed by dropout for regularisation
* ### followed by 3 densely connected layers


## The results are not very accurate and I will be working on improving both the network and hyperparamters

