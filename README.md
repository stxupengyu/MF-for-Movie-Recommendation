# MF-for-Movie-Recommendation
使用矩阵分解方法进行电影推荐的评分预测。The matrix factorization method is used to predict the rating of movie recommendation.  
## 需求
- surprise
## 任务
首先，进行原始数据集（较大，未提供）的预处理，得到rating.csv。  
之后，使用KNN方法和SVD方法进行评分预测和评价指标的计算。  
接着，用每名用户的均值填充原始的评分矩阵（由参数控制填充程度）。得到新的评分矩阵rating_new.csv，之后再使用SVD方法进行评分预测和评价指标的计算。  
## 文件结构
- movie_recomendation.ipynb：代码（可以直接用colab打开）。   
- rating.csv：用户、物品、评分数据。
- rating_new.csv：经过填充后的数据。  
