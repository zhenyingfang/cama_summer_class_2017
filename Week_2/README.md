# 第二周：分类
## 学习内容
### 视频课程
全部视频已传至内部 FTP 服务器，下面提供的链接是 Bilibili 上的观看地址。

- [Machine Learning (2017,Spring)](http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML17.html), 李宏毅，台湾大学
    - [逻辑回归（Logistic Regression）](https://www.bilibili.com/video/av10590361/#page=5)
- [Machine Learning Techniques (機器學習技法)](https://www.youtube.com/playlist?list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2)，林轩田，台湾大学
    - [01_Decision_Tree_Hypothesis](https://www.bilibili.com/video/av12469267/#page=34)
    - [02_Decision_Tree_Algorithm](https://www.bilibili.com/video/av12469267/#page=35)
    - [03_Decision_Tree_Heuristics_in_CRT](https://www.bilibili.com/video/av12469267/#page=36)
    - [04_Decision_Tree_in_Action](https://www.bilibili.com/video/av12469267/#page=37)


### 文字资料
- [图像分类（CS231n Notes）](http://cs231n.github.io/classification/)
- [A Complete Guide to K-Nearest-Neighbors with Applications in Python and R](https://kevinzakka.github.io/2016/07/13/k-nearest-neighbor/)

## 作业
In this assignment you will practice putting together a simple image classification pipeline, based on the k-Nearest Neighbor, logistic regression and decision tree classifier. The goals of this assignment are as follows:

- understand the basic **Image Classification pipeline** and the data-driven approach (train/predict stages)
- understand the train/val/test **splits** and the use of validation data for **hyperparameter tuning**.
- develop proficiency in writing efficient **vectorized** code with NumPy
- implement and apply a k-Nearest Neighbor (**kNN**) classifier
- implement and apply a Multiclass **Logistic Regression** classifier
- understand the differences and tradeoffs between these classifiers
- get a basic understanding of performance improvements from using **higher-level representations** than raw pixels (e.g. color histograms, Histogram of Gradient (HOG) features)

Ref: [CS231n assignment 1](http://cs231n.github.io/assignments2017/assignment1/)

## Kaggle 课内竞赛第一期：井字棋胜负判断

- 比赛入口：[https://inclass.kaggle.com/c/hdu-cama](https://inclass.kaggle.com/c/hdu-cama)
- 简介
    - 你需要使用提供的井字棋棋局数据训练一个 ID3 决策树模型，给定一个棋局，能判定 “X” 下棋人的胜负情况。
    - 不能使用额外的 Package（如 scikit-learn）
- 时间
    - 07.28 - 07.31 11:59pm

## 作业提交

截止日期：7 月 29 日（星期六） 18:30
提交邮箱：gaofei@hdu.edu.cn
邮件以及附件格式： **暑期研讨班作业-姓名-Week_2**

其他说明：

- 需要提交的文件
    - assignment 文件夹下的所有 .ipynb 文件以及他们生成的 .html 文件
- 将这些文件压缩成一个 __.zip__ 文件，并按上面说明的格式命名
- 你提交的作业版本应与 Github 上的最新版本一致


