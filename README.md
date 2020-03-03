# NLP-beginner
新加入本实验室的同学，请按要求完成下面练习，并提交报告  

`TIPS:虽然会给大家提供参考，但是要想自己彻彻底底弄清楚还是最好不要看`  

参考：  
1，[深度学习上手指南](DeepGuide.md)  
2，[神经网络与深度学习](https://nndl.github.io/)  
3，Google

## 任务一：基于机器学习的文本分类
实现基于logistic/softmax regression的文本分类
- 参考
    - [文本分类](doc/TextClassify.md)
    - 《[神经网络与深度学习](https://nndl.github.io/)》第2/3章
- 数据集：[Classify the sentiment of sentences from the Rotten Tomatoes dataset](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews)
- 实现要求：Numpy
- 需要了解知识点：
    - 文本特征表示：Bag-of-Word，N-gram
    - 分类器：logistic/softmax regression，损失函数、（随机）梯度下降、特征选择
    - 数据集：训练集/验证集/测试集的划分
- 实验
    - 分析不同的特征、损失函数、学习率对最终分类性能的影响
    - shuffle、batch、mini-batch
- 时间：两周
## 任务二：基于深度学习的文本分类
