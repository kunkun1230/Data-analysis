# Data-analysis
Data analysis through jupyter notebook

18年计划转能源方面的数据挖掘岗位，准备了一些项目。

### 1. [光伏Pr衰减分析](https://github.com/kunkun1230/Data-analysis/tree/master/%E5%85%89%E4%BC%8FPr%E8%A1%B0%E5%87%8F%E5%88%86%E6%9E%90)  
1.分析历年的光伏发电量数据与辐照度，气温等因素的关系；  
2.获得光伏组件的功率衰减曲线并计算组件的Pr值

### 2. [Titanic survived predict from kunkun (Classfy)](https://github.com/kunkun1230/Data-analysis/blob/master/Titanic%20survived%20predict%20from%20kunkun.ipynb)
1.常规的数据分析流程（观察数据，数据预处理，特征工程，建立模型，结果分析等）  
2.预测Titanic生还者的数据

### 3. [renewable_Solar_wind_power_predict(Regression)](https://github.com/kunkun1230/Data-analysis/blob/master/renewable_Solar_wind_power_predict.ipynb)
1.以德国16年的光伏和风电发电量为结果，分析其与天气，风速等一系列因素的关系;  
2.构建线性回归模型，旨在通过17年和18年的气象数据，预测这两年的发电量信息

### 4. [国内某地产中介的销售分组信息（替地产领域的朋友做的分析）](https://github.com/kunkun1230/Data-analysis/tree/master/%E6%A5%BC%E7%9B%98%E5%88%86%E7%BB%84%E9%94%80%E5%94%AE%E5%BB%BA%E6%A8%A1)  
1.给定44个地产楼盘，按照销量，库存率等信息划分成10组  
2.分配给不同的销售组进行销售工作

### 5. [AB测试验证两种键盘打字的错误率（双样本独立检验）](https://github.com/kunkun1230/Data-analysis/tree/master/AB%E6%B5%8B%E8%AF%95%E5%88%86%E6%9E%90) 
1.设计实验，获取数据  
2.描述统计分析，获得一般特征  
3.推论统计分析，确定置信区间，进行假设检验及效应量  
4.编制分析报告  
  
### 6. [斯特鲁普效应存在分析（相关配对检验)](https://github.com/kunkun1230/Data-analysis/tree/master/%E6%96%AF%E7%89%B9%E9%B2%81%E6%99%AE%E6%95%88%E5%BA%94%E5%88%86%E6%9E%90)
1.设计实验，获取数据（流程与5一致）    
2.描述统计分析，获得一般特征  
3.推论统计分析，确定置信区间，进行假设检验及效应量  
4.编制分析报告  

### 7. [基于K-means聚类的用户用电行为分析](https://github.com/kunkun1230/Data-analysis/tree/master/%E5%9F%BA%E4%BA%8EK-means%E8%81%9A%E7%B1%BB%E7%9A%84%E7%94%A8%E6%88%B7%E7%94%A8%E7%94%B5%E8%A1%8C%E4%B8%BA%E5%88%86%E6%9E%90)
1.通过Python中的SQL模块读取数据  
2.分析数据结构，并对时间列进一步细化处理  
3.通过数据透视表的形势对时间进行分列处理    
4.导入K-means模块，并构建聚类可视化类，进行可视化处理  

### 8. [叶片运输问题总结](https://github.com/kunkun1230/Data-analysis/blob/master/%E5%8F%B6%E7%89%87%E8%BF%90%E8%BE%93%E9%97%AE%E9%A2%98%E6%80%BB%E7%BB%93.ipynb)
1.基于运筹学中的运输问题，调用python的pulp模块进行线性优化   
2.依据叶片运输问题，构建数据集    
3.建立数学模型，添加约束条件      
4.求解各个路径分配的运输量，并总结一般问题的结题思路   

### 9. [稀疏矩阵转化与压缩](https://github.com/kunkun1230/Data-analysis/blob/master/sparse_matrix.ipynb)
1.基于用户对商品的评分，获得用户-商品评分矩阵  
2.对于数据量巨大的矩阵，必定需要压缩来减少空间占用  
3.因此调用了python的scipy.parse模块对矩阵分别进行了COO、CSR、CSC三种形式的压缩

