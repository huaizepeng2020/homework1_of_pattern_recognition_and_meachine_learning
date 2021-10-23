# 简介
作者：槐泽鹏

内容：《模式识别和机器学习-博士课程》的第一次大作业——《参数法和非参数法分类器》

# 参考
参考：https://github.com/pamela0530/bayes

原来代码有两处错误：

1 判别函数少了“协方差矩阵行列式”此项。

2 MQDF算法中计算修正的协方差矩阵时，直接输出了原矩阵，并且代码逻辑较为混乱，因此进行了重新改写。

# 内容
实现四种参数法高斯分类器LDF、QDF、RDA、MQDF和一种非参数分类器parzen windows。

运行环境： Python >3 

requirenments：
pandas，sklearn，matplotlib，numpy

# 使用
1 不需在联网环境下获取数据

2 LDF、QDF、RDA、MQDF方法调用接口为gaussianlinear.py 
  
3 parzen windows 方法接口文件为bayes.py
