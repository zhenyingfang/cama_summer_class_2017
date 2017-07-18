# 第一周
## 工具安装
在这第一个部分，大家要完成两个工具的安装，分别是 Anaconda 和 Jupyter notebook：

- Anaconda 是一个包含数据科学常用包的发行版本。它基于 conda ——一个包和环境管理器——衍生而来。你将使用 conda 创建环境，以便分隔使用不同 Python 版本和/或不同包的项目。你还将使用它在环境中安装、卸载和更新包。通过使用 Anaconda，使我处理数据的过程更加愉快。
    - 下载地址：https://www.continuum.io/downloads （推荐使用 2.7 版本）
    - 安装教程：[Windows](http://www.jianshu.com/p/cd35110f1ed0), [Linux](http://blog.topspeedsnail.com/archives/9607), [Mac](http://yongyuan.name/blog/install-opencv3-and-anaconda-in-mac-os.html)
    - 安装完成后输入 `conda install numpy scipy pandas scikit-learn` 命令安装所需要的包
- Jupyter notebook 是 Web 文档，能让你将文本、图像和代码全部组合到一个文档中。它已经成为数据分析的标准环境。
    - Anaconda 中包含 Jupyter notebook，因此可以直接按教程开始使用，如果不行，可使用 `conda install jupyter notebook` 命令安装
    - [快速入门教程](https://www.sdk.cn/news/4523)
    - [视频教程(中文)](https://pan.baidu.com/s/1pK7YsrD)

之后还需要初步掌握 Python 在机器学习、数据分析中最常用的两个库 Pandas 和 Numpy:

- [（译）十分钟的 pandas 入门教程](https://ericfu.me/10-minutes-to-pandas/)
- [（译）NumPy教程(一)](http://hialex.cn/2014/05/22/(%E8%AF%91)NumPy%E6%95%99%E7%A8%8B(%E4%B8%80)/)
- 注：在命令行中输入 `ipython` 即可进入 Python 环境

## 内容
- Python 编程基础
    - [编程基础：Python — 学习面向对象编程方法](https://cn.udacity.com/course/programming-foundations-with-python--ud036)
    - [数据分析入门 — 使用 NumPy 和 Pandas 进行数据分析](https://cn.udacity.com/course/intro-to-data-analysis--ud170)
- 其他前置学习基础
    - [Windows 命令行基础](https://blog.henix.info/blog/windows-cmdbasic/_.html) 了解 1,2,3 即可
    - [Linux(Mac) 命令行基础](https://cn.udacity.com/course/linux-command-line-basics--ud595)
- 图像表示
    - 图像特征
        - [颜色直方图](http://baike.baidu.com/item/%E9%A2%9C%E8%89%B2%E7%9B%B4%E6%96%B9%E5%9B%BE)
        - [目标检测的图像特征提取之（一）HOG特征](http://blog.csdn.net/zouxy09/article/details/7929348)
        - [目标检测的图像特征提取之（二）LBP特征](http://blog.csdn.net/zouxy09/article/details/7929531)
        - [目标检测的图像特征提取之（三）Haar特征](http://blog.csdn.net/zouxy09/article/details/7929570)
- **VIDEO**, Machine Learning (2017,Spring), 李宏毅，台湾大学
    - [Regression](http://www.bilibili.com/video/av10590361/)
    - [Where does the error come from?](http://www.bilibili.com/video/av10590361/#page=2)
    - [Gradient Descent](http://www.bilibili.com/video/av10590361/#page=3)
    - 视频也可以用 FTP 在 10.65.1.69 服务器上获取，速度更快
- 其他
    - [各种距离](http://blog.csdn.net/shiwei408/article/details/7602324)
    - [机器学习中的Bias(偏差)，Error(误差)，和Variance(方差)有什么区别和联系？](https://www.zhihu.com/question/27068705)
    - [Why Data Scientists Split Data into Train and Test](http://info.salford-systems.com/blog/bid/337783/Why-Data-Scientists-Split-Data-into-Train-and-Test)
    - [K折交叉验证评估模型性能](https://github.com/basicv8vc/Python-Machine-Learning-zh/blob/master/%E7%AC%AC%E5%85%AD%E7%AB%A0/ch6_section2.md)
    - 一个介绍机器学习比较通俗化的系列文章
        - [写给大家看的机器学习书 第一篇](https://zhuanlan.zhihu.com/p/25328686)
        - [写给大家看的机器学习书 第二篇](https://zhuanlan.zhihu.com/p/25439997)
        - [写给大家看的机器学习书 第三篇](https://zhuanlan.zhihu.com/p/25358695)
        - [写给大家看的机器学习书 第四篇](https://zhuanlan.zhihu.com/p/25721582)

## 作业
两个作业均使用 Jupyter Notebook，完成其中的 TO DO 代码和 question（问题）后，需提交以下文件：

- 包含完整实现且可正常运行的代码的 “boston_housing.ipynb” 和 “features.ipynb” 文件，并已执行所有代码块和显示了输出。
- 一个由 Jupyter notebook 导出的 HTML 文件，分别重命名为 boston_report.html 和 features_report.html。这两个文件需同 ipynb 文件一起提交
- 完成作业后请将上述文件压缩为 .zip 文件后作为附件发送至 gaofei@hdu.edu.cn, 邮件名格式为 **暑期研讨班作业-姓名-Week_1**

### 图像特征提取练习
自己编写代码提取图片的 HOG 特征。（**作业文件中 k-NN on features 部分暂时不用完成**）

作业文件：assignment/Image_features_exercise/features.ipynb

（本作业修改自 [CS231n assignment 1](http://cs231n.github.io/assignments2017/assignment1/)）

### 波士顿房价预测项目
在此项目中，我们将对为马萨诸塞州波士顿地区的房屋价格收集的数据应用本周学到的几个机器学习概念，以预测新房屋的销售价格。你首先将探索这些数据以获取数据集的重要特征和描述性统计信息。接下来，你要正确地将数据拆分为测试数据集和训练数据集，并确定适用于此问题的性能指标。然后，你将自己编写一个线性回归的模型，并使用不同的参数和训练集大小分析学习算法的性能图表。最后，你将根据一个新样本测试此模型并将预测的销售价格与你的统计数据进行比较。

作业文件：assignment/boston_housing/boston_housing.ipynb

（本项目作业修改自 [Udacity Machine Learning Nanodegree Project](https://github.com/nd009/boston_housing)）

## 其他
如果大家在课程学习中或者做作业时遇到问题，尽量使用 Twist 进行沟通，暑期班内容的变化动态 Twist 也能自动获取。


