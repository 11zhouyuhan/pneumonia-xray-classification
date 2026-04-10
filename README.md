# Pneumonia X-Ray Classification - 肺炎X光图像识别

## 项目简介

本项目使用胸部X光图像数据集，构建卷积神经网络（CNN）对肺炎进行二分类识别。模型能够区分正常肺部与肺炎感染的X光片。

## 数据来源

- **数据集名称**：Chest X-Ray Images (Pneumonia)
- **来源**：Kaggle
- **数据规模**：5856张X光图像（JPEG格式），分为训练集、验证集、测试集

## 项目流程

- 步骤一：数据加载与预处理（图像缩放、归一化、数据增强）
- 步骤二：搭建卷积神经网络（CNN）模型
- 步骤三：模型训练（10个epoch，使用GPU加速）
- 步骤四：模型评估（准确率、精确率、召回率、混淆矩阵）
- 步骤五：结果可视化

## 模型效果

- 测试集准确率：79%
- 肺炎类别精确率：0.76
- 肺炎类别召回率：0.98（漏诊率低，对医疗场景尤为重要）
- 正常类别精确率：0.93
- 正常类别召回率：0.48

### 混淆矩阵

| 实际\预测 | 预测正常 | 预测肺炎 |
|-----------|----------|----------|
| 实际正常 | 113 | 121 |
| 实际肺炎 | 9 | 381 |

## 使用的技术

- Python（PyTorch、Torchvision、NumPy、Matplotlib、Seaborn）
- 卷积神经网络（CNN）
- 数据增强（随机翻转、旋转）
- GPU加速训练

## 如何运行

1. 克隆本仓库到本地
2. 安装依赖：pip install torch torchvision numpy matplotlib seaborn scikit-learn
3. 启动Jupyter Notebook，运行 pneumonia_xray_classification.ipynb

## 项目价值

- 考研/保研复试：证明具备深度学习与计算机视觉实战能力
- 求职简历：展示PyTorch、CNN、医学图像处理项目经验
- 医学AI入门：理解图像分类在医疗诊断中的应用

## 联系方式

- GitHub：11zhouyuhan
- 项目链接：https://github.com/11zhouyuhan/pneumonia-xray-classification
