# telecom-customer-churn-rate
数据集为kaggle上的电信客户流失率数据集：“WA_Fn-UseC_-Telco-Customer-Churn”，针对该数据集的特点提出一种改进的KNN算法提高准确率。

数据集：WA_Fn-UseC_-Telco-Customer-Churn.csv为原始的电信客户流失率数据集；

数据集：prepare_trandition_data.csv为KNN和Gauss-KNN算法的输入数据集。数据集中将离散定序特征进行了特征映射，将离散定类特征进行了one-hot编码；

数据集：prepare_new_data.csv为Improve-KNN和Improve-Gauss-KNN算法（即改进算法）的输入数据集。数据集中将离散定序特征进行了特征映射，将离散定类特征也进行了特征映射，映射后好求VDM距离；

数据集：all_algorithms_result.csv为四种knn算法的十折交叉验证的平均预测率；
