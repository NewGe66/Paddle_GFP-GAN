# GFP-GAN: Towards Real-World Blind Face Restoration with Generative Facial Prior

## 目录

- [1. 简介]()
- [2. 数据集和复现精度]()
- [3. 准备数据与环境]()
    - [3.1 准备环境]()
    - [3.2 准备数据]()
    - [3.3 准备模型]()
- [4. 开始使用]()
    - [4.1 模型训练]()
    - [4.2 模型评估]()
    - [4.3 模型预测]()
- [5. 模型推理部署]()
    - [5.1 基于Inference的推理]()
    - [5.2 基于Serving的服务化部署]()
- [6. 自动化测试脚本]()
- [7. LICENSE]()
- [8. 参考链接与文献]()


**注意：**

(1) 目录可以使用[gh-md-toc](https://github.com/ekalinin/github-markdown-toc)生成；

(2) 示例repo和文档可以参考：[AlexNet_paddle](https://github.com/littletomatodonkey/AlexNet-Prod/blob/tipc/pipeline/Step5/AlexNet_paddle/README.md)。

## 1. 简介

简单的介绍模型，以及模型的主要架构或主要功能，如果能给出效果图，可以在简介的下方直接贴上图片，展示模型效果。然后另起一行，按如下格式给出论文名称及链接、参考代码链接、aistudio体验教程链接。

注意：在给出参考repo的链接之后，建议添加对参考repo的开发者的致谢。

**论文:** [GFP-GAN: Towards Real-World Blind Face Restoration with Generative Facial Prior](https://paperswithcode.com/paper/towards-real-world-blind-face-restoration)

**参考repo:** [https://github.com/TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN)

在此非常感谢`$参考repo的 github id$`等人贡献的[repo name](url)，提高了本repo复现论文的效率。

**aistudio体验教程:** [地址](url)


## 2. 数据集和复现精度

给出本repo中用到的数据集的链接，然后按格式描述数据集大小与数据集格式。

格式如下：

- 数据集大小：关于数据集大小的描述，如类别，数量，图像大小等等
- 数据集下载链接：链接地址
- 数据格式：关于数据集格式的说明

基于上述数据集，给出论文中精度、参考代码的精度、本repo复现的精度、数据集名称、模型下载链接（模型权重和对应的日志文件推荐放在**百度云网盘**中，方便下载）、模型大小，以表格的形式给出。如果超参数有差别，可以在表格中新增一列备注一下。

如果涉及到`轻量化骨干网络验证`，需要新增一列骨干网络的信息。

## 3. 准备数据与环境


### 3.1 准备环境

首先介绍下支持的硬件和框架版本等环境的要求，格式如下：

- 硬件：xxx
- 框架：
  - PaddlePaddle >= 2.2.0

然后介绍下怎样安装PaddlePaddle以及对应的requirements。

建议将代码中用到的非python原生的库，都写在requirements.txt中，在安装完PaddlePaddle之后，直接使用`pip install -r requirements.txt`安装依赖即可。

### 3.2 准备数据

简单介绍下全量数据和少量数据分别怎么使用，给出使用命令。


### 3.3 准备模型


可以在此提示用户怎么下载预训练模型、inference模型（如果有）


## 4. 开始使用


### 4.1 模型训练

简单说明一下训练的命令，建议附一些简短的训练日志。

可以简要介绍下可配置的超参数以及配置方法。

### 4.2 模型评估

简单说明一下评估的命令以及结果，建议附一些简短的评估日志。

### 4.3 模型预测


在这里简单说明一下预测的命令，需要提供原始图像、文本等内容，在文档中体现输出结果。


## 5. 模型推理部署

如果repo中包含该功能，可以按照Inference推理、Serving服务化部署再细分各个章节，给出具体的使用方法和说明文档。


## 6. 自动化测试脚本

介绍下tipc的基本使用以及使用链接


## 7. LICENSE

本项目的发布受[Apache 2.0 license](./LICENSE)许可认证。

## 8. 参考链接与文献
