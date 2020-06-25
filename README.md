# image-classification
image classification(图像分类)
### 技巧：

### 一、数据扩充
1.1、数据增强：
+ 水平 / 竖直翻转
+ 90°，180°，270° 旋转
+ 翻转 + 旋转
+ 亮度，饱和度，对比度的随机变化
+ 随机裁剪（Random Crop）
随机缩放（Random Resize）
加模糊（Blurring）
加高斯噪声（Gaussian Noise）
FMix、MixUp
1.2、G-A-N(防和谐)网络生成数据
二、标签平滑
三、细粒度
四、损失函数
focal loss
OHEM
五、数据采样
上采样
下采样
权重采样
六、注意力机制
通道贡献设置权重


资料的汇总：
FMix
https://mp.weixin.qq.com/s/-VcS2zfet42D1A3yoJE14w
https://github.com/ecs-vlc/FMix
如何针对数据不平衡做处理
http://www.spytensor.com/index.php/archives/45/
鲁棒植物病害诊断，校正元学习方法
https://arxiv.org/pdf/2003.07603.pdf
https://mp.weixin.qq.com/s/Ez0t9XtGyNOFjCT2emhXDg
solve the industrial or agricultural label problem
https://github.com/JaryHuang/Label
类别不平衡学习：论文/代码/框架/库
https://github.com/ZhiningLiu1998/awesome-imbalanced-learning
BBN: Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition
http://www.weixiushen.com/publication/cvpr20_BBN.pdf
https://www.zhihu.com/question/379109637/answer/1080076071
https://github.com/Megvii-Nanjing/BBN
Bags of Tricks for Classification：
https://zhuanlan.zhihu.com/p/119305930
小样本数据学习：
http://note.youdao.com/noteshare?id=df8131e48eb091d947b9759da8d259e1&sub=D13586E29D2741FFBF42D44BB39D24B9


数据增强方法：
大盘点 | 基于深度学习的数据增广技术一览
https://mp.weixin.qq.com/s/MpaBtd8HdSogOgq6Sfdk0w
常用数据增广方法汇总
https://mp.weixin.qq.com/s/Qx8m9VwTytsnz0V63PcZ6g
数据读取与数据扩增方法
https://mp.weixin.qq.com/s/I-hE0-QQguVTxAHIIeybXA
https://mp.weixin.qq.com/s/eat4fqvc3P20XzUUG6NddQ
Kaggle知识点：数据扩增方法
https://mp.weixin.qq.com/s/jLd0Uvm5JHggcP8oQLYKAQ
数据增强方法 | 基于随机图像裁剪和修补的方式
https://mp.weixin.qq.com/s/cCqvW72uR87_8w1sIpzDDQ
常用数据增广方法，解决数据单一问题
https://mp.weixin.qq.com/s/kL8sj10Ih2W0ePGU0ZE1-g

验证数据集
比较经典相对比较小的数据集：
MNIST，Fashion-MNIST，CIFAR10，CIFAR100
http://yann.lecun.com/exdb/mnist/
https://github.com/zalandoresearch/fashion-mnist
http://www.cs.toronto.edu/~kriz/cifar.html

图像分类很好的benchmark:
基于开源数据集Fashion-MNIST的应用实践
https://mp.weixin.qq.com/s/MoNWvbv1mjYntcERl50NPg
https://github.com/whut2962575697/image_classification
pytorch 图像分类竞赛框架
https://github.com/spytensor/pytorch_img_classification_for_competition
基于pytorch框架的classification万用模板
https://github.com/OdingdongO/pytorch_classification
图像分类比赛和教程：
整理中ing：
kaggle植物病虫害叶子分类比赛
https://www.kaggle.com/c/plant-pathology-2020-fgvc7
https://www.kaggle.com/c/plant-pathology-2020-fgvc7/discussion
Kaggle竞赛方案分享：如何分辨杂草和植物幼苗
https://zhuanlan.zhihu.com/p/38359300
https://www.kaggle.com/c/plant-seedlings-classification
从实例掌握 pytorch 进行图像分类
http://www.spytensor.com/index.php/archives/21/
pytorch_classification
https://github.com/lxztju/pytorch_classification
SupContrast: Supervised Contrastive Learning
https://github.com/HobbitLong/SupContrast
Collective Loss Function for Positive and Unlabeled Learning
https://www.arxiv-vanity.com/papers/2005.03228/
https://arxiv.org/abs/2005.03228
