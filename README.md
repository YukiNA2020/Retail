# RFM客户分析与聚类

基于零售数据的客户价值分群项目，使用RFM模型和K-means聚类识别不同客户群体。

## 分析内容

- **RFM指标计算**：最近购买时间(Recency)、购买频率(Frequency)、消费金额(Monetary)
- **数据预处理**：标准化处理、异常值剔除
- **客户分群**：使用K-means聚类将客户分为4个价值群体
- **可视化分析**：箱线图展示各群体特征差异

## 技术栈

- Python (pandas, numpy)
- 机器学习：scikit-learn (KMeans, StandardScaler)
- 数据可视化：matplotlib, seaborn

## 文件说明

- `superstore.csv`：原始零售数据
- RFM分析代码：包含完整数据处理、建模和可视化流程

## 应用价值

识别高价值客户、潜在流失客户，为精准营销和客户关系管理提供数据支持。
