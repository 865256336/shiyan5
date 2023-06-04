# shiyan5
TensorFlow Lite 模型生成
实验内容
了解机器学习基础
• 了解TensorFlow及TensorFlow Lite
• 按照教程完成基于TensorFlow Lite Model Maker的花卉模型生成
• 使用实验三的应用验证生成的模型
• 将上述完成的Jupyter Notebook在Github上进行共享
TensorFlow 石头剪刀布模型生成
实验内容
 进一步掌握TensorFlow模型训练和生成的基本流程
• 下载石头剪刀布图片数据集
• 学习石头剪刀布图片识别模型的生成，参考教程。
• 绘制图像验证模型的性能
实验步骤1
下载数据集（使用wget或者浏览器）
• 训 练 集 ： https://storage.googleapis.com/learningdatasets/rps.zip
• 测 试 集 ： https://storage.googleapis.com/learningdatasets/rps-test-set.zip
• 验证下载的数据集（打印图片）
实验步骤2
• 使用TensorFlow中包含的神经网络库Keras进行
模型训练
• 图片预处理
• 定义模型架构（Sequential）
• 编译模型（compile）：定义相关参数，如损失函数
loss，性能指标（经常为accuracy）
• 用训练数据拟合（fit）
实验步骤3
生成模型的验证
• 以绘制图形的方式验证生成模型的性能
基于TensorFlow Lite Model Maker的花卉模型生成
