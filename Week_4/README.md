# 第四周：无监督学习
## 内容
### 视频课程
> 下面的视频分别来自两个系列的课程，大家在完成作业之前，最好不要看除了下面提到的以外的内容～

- K-Means - Machine Learning, Andrew Ng, Stanford University
    - [Unsupervised Learning: Introduction](https://www.bilibili.com/video/av9912938/#page=77)
    - [K-Means Algorithm](https://www.bilibili.com/video/av9912938/#page=78)
    - [Optimization Objective](https://www.bilibili.com/video/av9912938/#page=79)
    - [Random Initialization](https://www.bilibili.com/video/av9912938/#page=80)
    - [Choosing the Number of Clusters](https://www.bilibili.com/video/av9912938/#page=81)
- Machine Learning 2016&2017, 李宏毅，台湾大学
    - [PCA](https://www.bilibili.com/video/av10590361/index_22.html#page=13)
    - [Neighbor Embedding](https://www.bilibili.com/video/av10590361/index_22.html#page=13)

### 文字资料
- [独立成分分析(ICA)与主成分分析(PCA)的区别](https://www.zhihu.com/question/28845451)
- [Deciding the Number of Clusterings (中)](http://freemind.pluskid.org/machine-learning/deciding-the-number-of-clusterings/)
- [UFLDL 教程](http://ufldl.stanford.edu/wiki/index.php/UFLDL教程) 【可选】

## 作业 - 创建客户细分
(本周作业内容来自 Udacity ML Nanodegree [Creating Customer Segments](https://github.com/nd009/creating_customer_segments))
### 项目概述
在这个项目中，你将应用无监督学习技能研究产品花销数据。这些数据由葡萄牙里斯本的一家批发经销商收集，用于找出数据背后的客户群体。你会先选择一小部分样本，确定是否有任何产品类别是相互高度关联来进行数据研究。之后，你将通过扩展每个产品类别然后识别（和删除）不需要的异常值来进行数据预处理。有了完好的客户开支数据后，你可以对数据进行 PCA 转换，并利用聚类算法为转换后的客户数据分组。最后，你将对你发现的分组与另外的分类方式进行比较，并思考这些信息如何帮助批发经销商改善日后的服务。
### 项目亮点
此项目可以帮助你获得非监督学习的实际经验，并努力从真实的数据集中得出关于某个潜在客户的结论。如今，许多公司都在大量地收集客户和委托人的数据，并有强烈的愿望了解客户数据库背后有意义的联系。这些信息有助于公司在未来开发产品与服务，从而更好地满足客户需求。

完成此项目后，你将学到：

- 如何应用预处理技术，如特征标度和异常值检测。
- 如何阐释 PCA 处理后缩放、转换或减少的数据点。
- 如何分析 PCA 的维度，并构建一个新的特征空间。
- 如何通过优化数据集来发现数据集中的规律。
- 如何评估集群数据提供的信息，并以有意义的方式利用数据。

### 项目描述
近日，一家批发经销商尝试着针对一些客户改变其发货方式，从原来的每周五次每次早上发货，改为了更为便宜的每周三次每次晚上发货。起初，发货方式的改变并没有带来任何显著的负面结果，于是该批发商将这一更为便宜的变动推广到了所有客户。几乎同一时刻，该批发商开始收到客户对发货服务变动的投诉，也有的客户开始取消提货。该批发商受到的损失比节省下来的钱还要多。现在，该批发经销商雇佣你，希望你确定他们的客户特征和信息，以帮助它们在未来做出更加明智的商业决策。你的任务就是利用非监督学习技术，看看客户之间存在哪些相似之处，以及如何以最佳的方式将客户细分为不同类别。
### 项目文件以及执行说明

本项目包含三个文件（assignment 文件夹中）：

- **customer_segments.ipynb**: 这是最主要的文件，项目中的主要工作都将在这个文件上完成
- **customers.csv**: 项目数据表。您将需要把这个数据加载到 notebook 里
- **visuals.py**: 这个 Python 脚本包含 helper 函数，可以让数据和存活结果可视化

在终端或命令行，定位到包含项目文件的文件夹，输入命令 `jupyter notebook customer_segments.ipynb` 会打开一个浏览器用来编辑 notebook。按照 notebook 里面的指示回答每一个问题来完成项目。我们还以供了一个 **README** 文件，提供了一些项目需要的额外信息和指导。

### 作业提交

截止日期：8 月 12 日（星期六） 18:30
提交邮箱：gaofei@hdu.edu.cn
邮件以及附件格式： **暑期研讨班作业-姓名-Week_4**

其他说明：

- **提交前请按照[评价标准](rubrics.md)完善提升自己的作业答案**
- 需要提交的文件
    - 包含完整实现且可正常运行的代码的 “customer_segments.ipynb” 并已执行所有代码块和显示了输出
    - 一个由 Jupyter notebook 导出的 HTML 文件，并重命名为 report.html
- 将这些文件压缩成一个 __.zip__ 文件，并按上面说明的格式命名
- 你提交的作业版本应与 Github 上的最新版本一致

本周将引入作业互评（时间周日至周一），互评标准见文件 [rubrics.md](rubrics.md)。


