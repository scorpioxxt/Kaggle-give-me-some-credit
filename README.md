# Kaggle-give-me-some-credit
根据Kaggle信用评分数据集，尝试使用不同的特征选择和模型建立方式得到预测结果

dataprocess 中对数据进行预处理和探索性分析

machine learning 中使用RF 和 XGB进行特征选择，并使用多种分类器对训练集进行训练，最后采用blending进行简单的模型融合

WOE-IV中使用决策树对特征进行分箱，并求出woe和iv值，在此基础上进行特征选择和LR训练
