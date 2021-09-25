# machine_learning_anomaly_detection
A pyspark project that utilize food reviews from amazon to predict the ratings given by users.
data source:
https://www.kaggle.com/snap/amazon-fine-food-reviews

本项目展示了对一个既包含文字类信息又包含数字型信息的数据集，通过线性回归模型对用户评分进行预测的机器学习过程。
原始数据来源：https://www.kaggle.com/snap/amazon-fine-food-reviews
数据集包含了1999年10月到2012年10月，Amozon 用户对于美食的评论数据。
1，数据处理与导出：在PySpark程序步骤对银行demo数据进行处理并导出；

2.特征提取：在PySpark程序中运用文本特征提取模型，将用户评论数据转换为特征向量；

3.线性回归模型预测：在PySpark程序中针对线性回归模型模型，测试不同的参数组合，最后有最优参数组合的模型以及该模型的预测结果导出；

预测结果的精准性：使用MAE评价指标，得到预测结果的得分为0.97，即在0-5的评分标准中，预测结果与真实结果的绝对误差的平均值为0.71。
