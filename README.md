# CNN-BiLSTM-SE-model
基于CNN-BiLSTM-SE模型的文本情感检测系统
系统的图片可以通过上方的images文件夹查看截图
系统演示：
【基于CNN-BiLSTM-SE模型的文本情感检测系统-哔哩哔哩】 https://b23.tv/vs2zIqS


本系统设计并且实现一个基于CNN-BiLSTM-SE的文本情感检测模型
主框架是由Facebook公司开发PyTorch框架

使用的是卷积神经网络（CNN）和双向长短期记忆网络(BiLSTM)相结合的一个主要架构，
还添加了挤压和激励网络（SENet-----Squeeze-and-Excitation Networks）来提高卷积神经网络的性能。
首先对数据集进行预处理，然后对模型进行初始化，紧接着对模型进行了训练和验证，最后保存模型参数
实现用户通过输入文本内容，经过文本情感识别模型的预测，判断用户所输入的文本情感的功能。
