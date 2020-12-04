# Summary of social recommendation
This repository summarizes some existing social recommendation papers and open source codes, provides downloads of the papers and attaches the corresponding code addresses.If there are other open source projects that I have not collected about social recommendations, I hope you to contact me.

中文版：

社会化推荐总结

这个仓库总结了一些现有的社会化推荐论文和开源代码，提供了论文的下载并且附上了对应的开源代码地址。如果还有其他我没收集到的关于社会化推荐的开源项目，希望与我联系。(路过的朋友点一下star吧)

另外我有在知乎写一篇关于社会化推荐的文章，欢迎点赞：https://zhuanlan.zhihu.com/p/190944012


* Common dataset:

   FilmTrust: https://guoguibing.github.io/librec/datasets.html

   Epinions:http://www.trustlet.org/epinions.html

   CiaoDVD:https://guoguibing.github.io/librec/datasets.html

   Delicious:https://grouplens.org/datasets/hetrec-2011/

   Yelp: https://www.yelp.com/dataset
  

* SoRec
  
  SoRec Social Recommendation using Probabilistic Matrix Factorization [CIKM 2008]

  Code1 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
  
  Code2 details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: MAE
  
  code: https://github.com/hongleizhang/RSAlgorithms
  
  code: https://github.com/Coder-Yu/RecQ
  
* RSTE
  
  Learning to recommend with social trust ensemble [SIGIR 2009]

  Code1 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
  
  Code2 details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE,MAE

  code1: https://github.com/hongleizhang/RSAlgorithms
  
  code2: https://github.com/Coder-Yu/RecQ
  
* TrustWalker
  
  Trustwalker: a random walk model for combining trust-based and item-based recommendation [SIGKDD 2009]

  Code details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 

  Metrics: RMSE,Coverage,F-Measure

  code: https://github.com/hongleizhang/RSAlgorithms
  
* SocialMF

  A matrix factorization technique with trust propagation for recommendation in social networks [RecSys 2010]

  Code1 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
  
  Code2 details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE

  code: https://github.com/hongleizhang/RSAlgorithms
  
  code: https://github.com/Coder-Yu/RecQ
  
* SocialReg

  Recommender systems with social regularization [WSDM 2011]

  Code1 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
  
  Code2 details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE,MAE

  code1: https://github.com/hongleizhang/RSAlgorithms
  
  code2: https://github.com/Coder-Yu/RecQ  
 
* LOCABAL

  Exploiting local and global social context for recommendation [AAAI 2013]

  Code details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE,MAE

  code: https://github.com/Coder-Yu/RecQ 
  
* SBPR

  Leveraging Social Connections to Improve Personalized Ranking for Collaborative Filtering [CIKM 2014]

  Code details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Matrics: Recall,NDCG,AUC

  code: https://github.com/Coder-Yu/RecQ
  
* TrustSVD
  
  TrustSVD: Collaborative Filtering with Both the Explicit and Implicit Influence of User Trust and of Item Ratings   [AAAI 2015]

  Code1 details:
  
  Dataset:Epinions,FilmTrust,Ciao,Flixster  Environments:Java 1.7

  Code2 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
 
  Metrics: RMSE,MAE

  Author's code: https://github.com/guoguibing/librec/
  
  Another version: https://github.com/hongleizhang/RSAlgorithms
  
* TBPR

  Social Recommendation with Strong and Weak Ties [CIKM 2016]

  Code details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: Recall,Precision,AUC,MAP,MRR

  code: https://github.com/Coder-Yu/RecQ
  
* SocialFD

  A Social Recommender Based on Factorization and Distance Metric Learning [IEEE Access 2017]

  Code details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE,Recall,MAP

  code: https://github.com/Coder-Yu/RecQ
  
* CUNE
  
  Collaborative User Network Embedding for Social Recommender Systems [SDM 2017]

  Code1 details:
  
  Dataset:Epinions,FilmTrust  Environments:Python 3 
  
  Code2 details:
  
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE,AUC
  
  code1: https://github.com/hongleizhang/RSAlgorithms
  
  code2: https://github.com/Coder-Yu/RecQ  
  
* SREE

  Social Recommendation Using Euclidean embedding [IJCNN 2017]

  Code details:
   
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: RMSE

  code: https://github.com/Coder-Yu/RecQ  
  
* SERec

  Collaborative Filtering with Social Exposure: A Modular Approach to Social Recommendation [AAAI 2018]

  Code details:
   
  Dataset:Ciao,Epinions,Douban,LastFM  Environments:Python 2.7 Tensorflow

  Metrics: Recall,MAP,NDCG

  code: https://github.com/Coder-Yu/RecQ  
  
* SREPS

  Social Recommendation with an Essential Preference Space [AAAI 2018]

  Code details:
   
  Dataset:Ciao,Epinions,Flixster,FilmTrust  Environments:python >= 3.4

  Metrics: RMSE,MAE

  code: https://github.com/WSPTTH/SREPS  
  
* Diffnet
  
  A Neural Influence Diffusion Model for Social Recommendation [SIGIR 2019]

  Code details:
   
  Dataset:yelp  Environments:python 2.7 tensorflow-gpu-1.12.0

  Metrics: HR,NDCG

  Author's code: https://github.com/PeiJieSun/diffnet  
  
* EATNN

  An Efficient Adaptive Transfer Neural Network for Social-aware Recommendation [SIGIR 2019] 

  Code details:
   
  Dataset:Ciao,Epinions,Flixster  Environments:python 2.7 Tensorflow

  Metrics: Recall,NDCG

  Author's code: https://github.com/chenchongthu/EATNN  
  
* DANSER

  Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems   [WWW, 2019]

  Code details:
  
  Dataset:Epinions,WeChat  Environments:python 3.6 TensorFlow 1.7.0
  
  Metrics: MAE,RMSE,Precision,AUC
  
  Author's code:https://github.com/echo740/DANSER-WWW-19

* GraphRec

  Graph Neural Networks for Social Recommendation  [WWW, 2019]

  Code details:
   
  Dataset:Ciao,Epinions  Environments:python 3.6 pytorch: 0.2+

  Metrics: RMSE,MAE

  Author's code :  https://github.com/wenqifan03/GraphRec-WWW19
  
  Another version: https://github.com/Wang-Shuo/GraphRec_PyTorch
  
  Another version(improvement): https://github.com/lcwy220/Social-Recommendation
  
* DGRec

  Session-based Social Recommendation via Dynamic Graph Attention Networks [WSDM,2019]

  code details:
   
  Dataset:Douban  Environments:python 2.7 Tensorflow 1.4.1

  Metrics: Recall,NDCG

  Author's code:  https://github.com/DeepGraphLearning/RecommenderSystems/tree/master/socialRec   
  
* SAMN

  Social Attentional Memory Network: Modeling Aspect- and Friend-level Differences in Recommendation [WSDM,2019]

  code details:
  
  Dataset:delicious  Environments:python 2.7 Tensorflow 1.7.0

  Metrics: Recall,NDCG

  Author's code: https://github.com/chenchongthu/SAMN
 
* SIAN

  Social Influence Attentive Neural Network for Friend-Enhanced Recommendation [ECML-PKDD 2020]
  
  code details:
  
  Dataset:FWD,yelp  Environments:python 2.7 Pytorch 0.4.1

  Metrics:AUC,F1,Accuracy
  
  code: https://github.com/rootlu/SIAN
  
 
