# MachineLearing-Homework

UESTC MachineLearning course homework

# 作业一（Matlab）

1.  假设x=(1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20),y=( 2.94, 4.53, 5.96, 7.88, 9.02, 10.94,  12.14, 13.96, 14.74, 16.68, 17.79, 19.67, 21.20, 22.07, 23.75,  25.22, 27.17,  28.84, 29.84, 31.78).请写出拟合的直线方程，并画图(包括原数据点及拟合的直线)，请打印出来。

2.  请使用线性回归模型来拟合bodyfat数据。数据集介绍可阅读：https://www.mathworks.com/help/nnet/examples/body-fat-estimation.html
在matlab中，在命令行中输入[X,Y] = bodyfat_dataset; 即可获得一个拥有13个属性，252个样本的数据集。使用前200个样本来获得模型，并写出你所获得的模型。使用后52个样本做测试，汇报你所获得的泛化误差。

3.  编程实现对数回归，并给出教材89页上的西瓜数据集3.0上的结果。要求采用4折交叉验证法来评估结果。因为此处一共17个样本，你可以去掉最后一个样本，也可以用所有数据，然后测试用5个样本。在汇报结果时，请说明你的选择。请在二维图上画出你的结果（用两种不同颜色或者形状来标注类别），同时打印出完整的代码。

# 作业二

1.	采用信息增益准则，基于表4.2中编号为1、2、3、6、7、9、10、14、15、16、17的11个样本的色泽、根蒂、敲声、文理属性构建决策树。（本次作业可以用笔算，鼓励编程实现，但都需要列出主要步骤，其中log2(3)=1.585,log2(5)=2.322,log2(6)=2.585,log2(7)=2.807,log2(9)=3.17,log2(10)=3.322,log2(11)=3.459）

2.	用表4.2中编号为4、5、8、11、12、13的样本做测试集，对上题的训练数据采用预剪枝策略构建决策树，并汇报验证集精度。

3.	用表4.2中编号为4、5、8、11、12、13的样本做测试集，对题1所构建的决策树进行后剪枝，并汇报验证集精度。

# 作业三

1.	试编程实现累积BP算法，在西瓜数据集2.0上(用训练数据)训练一个单隐层网络，用验证集计算出均方误差。要自己实现，不能直接调用现成的库函数。

# 参考资料

[1].《机器学习》.周志华.清华大学出版社

[2].《Machine Learning》.Andrew Ng. Coursera, Standford University
