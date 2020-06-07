# Recommendation---NeuralMF-Content-embed

This is modified implementation for the paper:

Xiangnan He, Lizi Liao, Hanwang Zhang, Liqiang Nie, Xia Hu and Tat-Seng Chua (2017). Neural Collaborative Filtering. In Proceedings of WWW '17, Perth, Australia, April 03-07, 2017.

Three collaborative filtering models: Generalized Matrix Factorization (GMF), Multi-Layer Perceptron (MLP), and Neural Matrix Factorization (NeuMF). To target the models for implicit feedback and ranking task, optimize was done with negative sampling.

Collaborative filtering is simple and effective method, but it has 'cold-start' problem
With small amount of user-item interaction, we don't have sufficient information to recommend the new item properly.
To deal with problem, hybrid method of Collaborative filtering, and Content-based Recommendation is used.

![추천시스템1](https://user-images.githubusercontent.com/48465250/83963122-807b6d00-a8de-11ea-8cf0-f2108032430d.PNG)

I think that NeuralMF model can be expanded to implement this hybrid method, so I Implement it on the task of recommending paper to read.

![추천시스템2](https://user-images.githubusercontent.com/48465250/83963125-82ddc700-a8de-11ea-940a-be9c308f9910.PNG)

This new model imporved previous recommendation accuracy on the Hit ratio(HR 10), and NDCG(NDCG 10)

![추천_res](https://user-images.githubusercontent.com/48465250/83963269-9c334300-a8df-11ea-8be2-fe77a543d4c1.PNG)

Qualitive analysis also show that the recommendation gives proper result compare to previous method

![quality_res](https://user-images.githubusercontent.com/48465250/83963283-a9e8c880-a8df-11ea-9826-8c19cdd3bc96.PNG)
