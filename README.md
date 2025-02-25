# LT4Rec

This is the PyTorch Implementation for the paper [LT4Rec: Long-Tail Contrastive Learning for Knowledge-Enhanced Recommendation]:

## Environment Requirement

The code has been tested running under Python 3.8.0. The required packages are as follows:

- pytorch == 1.10.1
- networkx == 2.5.1
- numpy == 1.22.4
- pandas == 1.4.3
- scikit-learn == 1.1.1
- scipy == 1.7.0
- torch == 1.9.0
- torch-cluster == 1.5.9
- torch-scatter == 2.0.9
- torch-sparse == 0.6.12

## Dataset

We provide three processed datasets: Book-Crossing, MovieLens-1M, and Last.FM.

We follow the paper " [Ripplenet: Propagating user preferences on the knowledge
graph for recommender systems](https://github.com/hwwang55/RippleNet)." to process data.


|                       |               | Book-Crossing | MovieLens-1M | Last.FM |
| :-------------------: | :------------ | ----------:   | --------: | ---------: |
| User-Item Interaction | #Users        |      17,860   |    6,036  |      1,872 |
|                       | #Items        |      14,910   |    2,347  |      3,846 |
|                       | #Interactions |     139,746   |  753,772  |     42,346 |
|    Knowledge Graph    | #Entities     |      77,903   |    6,729  |      9,366 |
|                       | #Relations    |          25   |        7  |         60 |
|                       | #Triplets     |   19,793      |   20,195  |     15,518 |



## Reference 
- We partially use the codes of [KGIN](https://github.com/huangtinglin/Knowledge_Graph_based_Intent_Network).
