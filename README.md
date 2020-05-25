# CV_interviews_Q-A

> 不试着去找找实习，不试着被面试官毒打下，都意识不到自己基础的薄弱，很多东西被问到只知道个大概，再深挖一下为什么就支支吾吾答不上来了。深感CV算法岗竞争之激烈，从来都是狭路相逢勇者胜，借找工作的机会好好整理下所学的知识，希望现在好好准备还来时不晚，一起努力向offers发起冲击吧！

本仓库汇总CV算法岗重要的一些知识点和面试问答，主要分为**计算机视觉、机器学习、图像处理和、C++基础** 四大块，每一块都有几十个问题，每个问题都会努力给出详细完整的解答，帮助你理清这些知识点细节。

## 食用方法
github上直接看的话很多公式和图片看不了，**请 clone 到本地然后下载安装Typora查看**，Typora 是一款支持实时预览的 Markdown 文本编辑器。它有 OS X、Windows、Linux 三个平台的版本，完全免费，体验非常好，推荐你使用。

知识不是看几遍就会的，好记性不如烂笔头，最好看了我们的总结后，你也自己敲出一个适合你的版本，或删减或添加或修改为适合你的表达方式，这样会大大提升学习的效果。

另外知识点琐碎繁杂，及时复习也很重要，这里再推荐个APP，叫**Anki**，需要的请自行了解！

**需要声明的一点是**：本文是作为个人学习总结的，我们不生产知识，只是知识的搬运工，主要做的工作是知识整合与逻辑梳理，参考了很多大神的博客及文章资料(文章中会注明参考的资料，感谢这些作者的贡献)，当然也会有自己的思考，不喜勿喷，如有错误，恳请指正！

**最后如果该项目对你有帮助，请不吝给个Star，给个鼓励，也让更多人看到！**

## 合作

如果你有意一起把这个项目完成好，也可以向我们 **Pull requests** （表格中有记录是否完成，你可以随便挑其中未完成的一个来总结，当然表格中没有的问题，但你觉得很重要，也可以自己想问题然后给出答案），欢迎你加入！！！

## 知识点问题清单

这里列出各大块的问题清单，按照顺序对应于各文件夹下的md文件。

### 计算机视觉
| 序号 | 是否完成 |                           问题描述                           |
| :--: | :------: | :----------------------------------------------------------: |
|  1   |          | 自己项目有关模型的相关问题如：项目整体流程、网络结构、 论文的实验是怎么做的、<br />你的贡献是什么、创新点在哪里、遇到哪些问题是怎么解决的 |
|  2   |    是    |                过拟合和欠拟合的表现及解决方法                |
|  3   |    是    |                       代码实现卷及操作                       |
|  4   |    是    | BN层的深入理解及代码实现　(补充先加BN还是激活函数的区别、反向传播与求导) <br />另外还要着重分析下GN与BN相比的优势 |
|  5   |    是    |         NMS的工作机制及代码实现(要继续补充soft NMS)          |
|  6   |    是    |                      三种常见的激活函数                      |
|  7   |    是    |              ReLU函数在0处不可导，为什么还能用               |
|  8   |    是    |             Pooling层的作用以及如何进行反向传播              |
|  9   |    是    |               为什么输入网络前要对图像做归一化               |
|  10  |    是    | 理清深度学习优化函数发展脉络(添加随机梯度下降和梯度下降的区别) |
|  11  |    是    |        详解深度学习中的梯度消失、爆炸原因及其解决方法        |
|  12  |          |                    训练不收敛的原因有哪些                    |
|  13  |          | 为什么max pooling 要更常用？什么场景下 average pooling 比 max pooling 更合适 |
|  14  |    是    |                   CNN 在图像上表现好的原因                   |
|  16  |          |                卷积层和全连接层相比有哪些好处                |
|  17  |          |                   网络中常用的损失函数汇总                   |
|  18  |          |                有哪些修改、调试模型的经验分享                |
|  19  |          |                  目标检测评价指标mAP的计算                   |
|  20  |          |                     实例分割中的评价指标                     |
|  21  |          |                      手推反向传播公式BP                      |
|  22  |    是    |               各层 FLOPs 和参数量 paras 的计算               |
|  23  |    是    |                        感受野怎么计算                        |
|  24  |    是    |                CV中的卷积操作是互相关还是卷积                |
|  25  |          |    batch size 和 learning rate 的关系(怎么调整和平衡二者)    |
|  26  |          |                    类别不均衡问题怎么解决                    |
|  27  |          |          迁移学习都有哪些方式，怎么在网络训练中使用          |
|  28  |          |                     权重初始化方法有哪些                     |
|  29  |          |                   计算机视觉中的注意力机制                   |
|  30  |          |                 onehot 编码可能会遇到的问题                  |
|  31  |          |            分类问题有哪些评价指标？每种的适用场景            |
|  32  |          |                     为什么要用 F1 score                      |
|  33  |          |                 L1 正则化与 L2 正则化的区别                  |
|  34  |          |         简述CNN分类网络的演变脉络及各自的贡献与特点          |
|  35  |          |                    解释 ResNet 流行的原因                    |
|  36  |          |                 Inception v1-v4的区别与改进                  |
|  37  |          |          模型加速方法：MobileNet、ShuffleNet知道吗           |
|  38  |          |                  了解全卷积网络FCN 和 UNet                   |
|  39  |          | two stage目标检测网络的发展脉络及各自的贡献与特点（尤其注意损失函数） |
|  40  |          |             解释 ROI Pooling 和 ROI Align 的区别             |
|  41  |          |            CascadeRCNN的原理，本质解决了什么问题             |
|  42  |          |                       介绍下 FPN 网络                        |
|  43  |          | one stage目标检测网络 YOLO 和 SSD 网络结构及优缺点（尤其注意损失函数） |
|  44  |          |                     concat 和 add 的区别                     |
|  45  |          |                 了解模型剪枝和模型压缩的概念                 |
|  46  |          |               简单了解循环神经网络 RCNN & LSTM               |
|  47  |          |                  简单了解生成式对抗网络 GAN                  |
|  48  |    是    |                       各种卷积方式串讲                       |

### 机器学习
| 序号 | 是否完成 |                           问题描述                           |
| :--: | :------: | :----------------------------------------------------------: |
|  1   |    是    |                        LR与SVM的比较                         |
|  2   | 合并至57 |             损失函数、交叉熵、权值更新公式的推导             |
|  3   | 合并至57 |                    交叉熵相对于MSE的优点                     |
|  4   |          |                 标签是 -1/1 时损失函数的推导                 |
|  5   |          |                          SVM的原理                           |
|  6   |          |       SVM一般形式、SVM对偶形式的推导（软间隔、硬间隔）       |
|  7   |          |            SVM为什么使用间隔最大化，软间隔的作用             |
|  8   |          |                    为什么要转换成对偶问题                    |
|  9   |          |                         SMO算法思想                          |
|  10  |          |                      引入核函数的的作用                      |
|  11  |    是    |                         boosting思想                         |
|  12  |          |               Adaboost、GBDT、XGBoost算法原理                |
|  13  |          |                    AdaBoost和GBDT算法联系                    |
|  14  |          |                     GBDT和XGBoost的比较                      |
|  15  |          | XGBoost构建树的时候使用哪些优化方式，怎幺处理缺失值的，并行化是如何实现的 |
|  16  |          | XGBOOST采样时有放回的还是无放回的，XGBOOST的调参步骤是怎样的 |
|  17  |          | bagging算法思想，并说说bagging算法与DNN中的dropout技术思想的一致性 |
|  18  |          |                 为什么bagging能降低模型方差                  |
|  19  |          |      如何从偏差和方差的角度解释bagging和boosting的原理       |
|  20  |          | 随机森林算法思想，怎么增加随机性，如何评估特征重要性，为什么不容易过拟合 |
|  21  |          |                随机森立和GBDT的相同点和不同点                |
|  22  |          |                    stacking算法思想和流程                    |
|  23  |          |                       权重更新公式推导                       |
|  24  |          |               多角度解释L1，L2对特征选择的作用               |
|  25  |          |            包含重复特征情况下，线性回归存在的问题            |
|  26  |          |                    k-means算法原理和流程                     |
|  27  |          |                       代码实现k-means                        |
|  28  |          |   选择聚类中心的方式及改进方式，聚类簇数 k 选择的改进方式    |
|  29  |          |                   k-means和GMM的区别与联系                   |
|  30  |          |                 还有哪些常见的聚类方法，简述                 |
|  31  |          |            KNN算法原理，影响KNN算法的因素，优缺点            |
|  32  |          |                     k值选择对模型的影响                      |
|  33  |          |                 决策树的原理、决策树如何生成                 |
|  34  |          |                ID3、C4.5、CART算法总结和对比                 |
|  35  |          |               两种剪枝处理的原理及优缺点、对比               |
|  36  |          |                 决策树如何处理缺失值和连续值                 |
|  37  |          |                   先验概率和后验概率的联系                   |
|  38  |          | 朴素贝叶斯的思想，给出概率图模型表示，独立性假设是指什么的独立性 |
|  39  |          |                最大似然估计和贝叶斯估计的区别                |
|  40  |          |             最大熵模型的原理，给出概率图模型表示             |
|  41  |          |                          EM算法思想                          |
|  42  |          |              使用EM算法求解GMM模型的思想和步骤               |
|  43  |          |                    GMM高斯混合模型的思想                     |
|  44  |    是    |                      PCA原理、公式推导                       |
|  45  |          |                           LDA原理                            |
|  46  |          |                        PCA与LDA的对比                        |
|  47  |          |                     牛顿法和拟牛顿法思想                     |
|  48  |          |                   梯度下降法和牛顿法的区别                   |
|  49  |    是    |                    生成式模型和判别式模型                    |
|  50  |          |                      如何避免数据不平衡                      |
|  51  |          |               如何评价分类和回归算法模型的效果               |
|  52  |          |                监督算法和无监督算法分别有哪些                |
|  53  |          |                       如何进行特征选择                       |
|  54  |          | L1和L2的区别，为什么能防止过拟合，为什么L1是拉普拉斯先验，而L2是高斯先验 |
|  55  |          |                       K折交叉验证原理                        |
|  56  |          |                      CRF条件随机场原理                       |
|  57  |    是    |                有哪些损失函数，一般应用在哪里                |
|  58  |    是    |              线性回归损失函数为什么要用平方形式              |
|  59  |    是    |                 逻辑回归与线性回归之间的异同                 |

### 图像处理
| 序号 | 是否完成 |                       问题描述                        |
| :--: | :------: | :---------------------------------------------------: |
|  1   |          | HOG、LBP、Haar、SIFT、SUFT、ORB特征提取算法原理和对比 |
|  2   |          |         HOG能否检测边缘，它和canny有什么区别          |
|  3   |          |        sift是如何保持尺度不变性和旋转不变性的         |
|  4   |          |         边缘检测算子有哪些以及它们之间的对比          |
|  5   |          |                   canny算子实现原理                   |
|  6   |          |        图像滤波的方法有哪些以及它们之间的对比         |
|  7   |          |                  常见的几种颜色空间                   |
|  8   |    是    |                  常见的图像插值方法                   |
|  9   |          |                  常用的图像分割算法                   |
|  10  |          |              开操作和闭操作，它们的应用               |
|  11  |    是    |                     霍夫变换原理                      |
|  12  |          |                     什么是积分图                      |
|  13  |          |                     图像拼接介绍                      |

### C++基础
| 序号 | 是否完成 |                           问题描述                           |
| :--: | :------: | :----------------------------------------------------------: |
|  1   |          | 描述下一个 C++ 源文件从文本到可执行文件经历的过程（以 hello world 程序为例） |
|  2   |    是    |     说说 incluede 后面使用双引号 " " 和尖括号 <> 的区别      |
|  3   |          |                    说一下 C++ 和 C 的区别                    |
|  4   |          |                    请问 C++ 有哪些新特性                     |
|  5   |          |            请说一下你理解的 C++ 中的四个智能指针             |
|  6   |          |         智能指针有没有内存泄露的情况，有的话如何解决         |
|  7   |          |                    C++ 中指针和引用的区别                    |
|  8   |          |                    回答下数组和指针的区别                    |
|  9   |          |        结构体 struct 、共同体 union和类 class 的区别         |
|  10  |          | 请详细说说 C++ 中类成员的访问权限（包括友元类和继承等情况）  |
|  11  |    是    |        new / delete与 malloc / free 之间的关系与区别         |
|  12  |    是    |                  delete 和 delete[] 的区别                   |
|  13  |          |           说说 ++i 与 i++的区别及各自是怎么实现的            |
|  14  |    是    | 说一说你所理解的虚函数和多态及虚函数表具体是怎样实现运行时多态的 |
|  15  |    是    |                        纯虚函数的作用                        |
|  16  |    是    | 构造函数为什么一般不定义为虚函数？而析构函数一般写成虚函数的原因 |
|  17  | 合并至16 |              子类析构时，会调用父类的析构函数吗              |
|  18  | 合并至14 |               请你说一下静态函数和虚函数的区别               |
|  19  |          |         请你来写一个能在 main 函数执行前先运行的函数         |
|  20  |          |                   #define 和 const 的区别                    |
|  21  |          | 重载(overload)、重写(override)、重定义(overwrite)这三者的区别 |
|  22  |          |                      说说 const 的作用                       |
|  23  |          |                     关键字 static 的作用                     |
|  24  |    是    |                   sizeof 和 strlen 的区别                    |
|  25  |    是    |              strcpy 、strncpy 和 memcpy 的区别               |
|  26  |          |                       定义和声明的区别                       |
|  27  |          |                       实参和形参的区别                       |
|  28  |          |                说一说 C++ 中的四种 cast 转换                 |
|  29  |    是    |                     hash 冲突和解决方法                      |
|  30  |          |    说说 C 语言函数中参数的压栈顺序（顺便了解下变长参数）     |
|  31  |    是    |           说一下什么是右值引用，跟左值又有什么区别           |
|  32  |    是    |                请说说 C++ 的内存管理是怎样的                 |
|  33  | 合并至32 |       C++ / C 的内存分配，详细说一下栈、堆、静态存储区       |
|  34  | 合并至32 |                         堆和栈的区别                         |
|  35  |          |             什么是内存泄露，有几种情况，怎么判断             |
|  36  |          |                       为什么要内存对齐                       |
|  37  |          |                   全局变量和局部变量的区别                   |
|  38  |          |       C++ 中是怎么定义常量的？常量存放在内存的哪个位置       |
|  39  |          |                     请说一说隐式类型转换                     |
|  40  |          |             什么情况下会调用拷贝构造函数（三种）             |
|  41  |          |                      C++ 如何处理返回值                      |
|  42  |          |                    cout 和 printf 的区别                     |
|  43  |          |           C++ 中的拷贝构造函数的形参能否进行值传递           |
|  44  |          |                      extern "C" 的作用                       |
|  45  |          |                   静态绑定和动态绑定的介绍                   |
|  46  |    是    |                     深拷贝和浅拷贝的区别                     |
|  47  |          |                   typedef 和 define 的区别                   |
|  48  |          |                   栈溢出的原因以及解决方法                   |
|  49  |          |                  C++ 类不能被继承的成员函数                  |
|  50  |    是    |               引用作为函数参数以及返回值的好处               |
|  51  |          |                      C++ 中的模板是什么                      |
|  52  |    是    |                   虚函数可以声明为inline吗                   |
|  53  |          |                         什么是野指针                         |
|  54  |    是    |                   常量指针和指针常量的区别                   |
|  55  |    是    |                   函数指针和指针函数的区别                   |
|  56  |    是    |                   数组指针和指针数组的区别                   |
|  57  |          |                     C 语言的函数调用过程                     |
|  58  |          |              vs 中 debug 和 release 模型的区别               |
|  59  |          |                    进程和线程的联系与区别                    |
|  60  |          |                   进程间、线程间的通信方式                   |
|  61  |          |                     线程安全与线程不安全                     |
|  62  |          |                      gcc 和 g++ 的区别                       |
|  63  |    是    |               代码实现7中排序算法并分析复杂度                |
|  64  |          |           常用的 STL 容器有哪些？有哪些常用算法？            |
|  65  |          | map 和 set 有什么区别，分别又是怎么实现的？（最好也了解下红黑树具体工作机制） |
|  66  |          |               unordered_map 和 map 有什么区别                |
|  67  |          |       清说一说 vector 和 list 的区别与应用，越详细越好       |
|  68  | 合并至72 |             STL 中的 vector 的实现，是怎么扩容的             |
|  69  |          |        说一下 STL 中迭代器的作用，与指针又有什么区别         |
|  70  |          |                  说一说 STL 迭代器删除元素                   |
|  71  |          |                      STL 有哪些基本组成                      |
|  72  |    是    |        vector 的扩容原理以及 resize 和 reserve 的区别        |
|  73  |          |                     map[] 和 find 的区别                     |
|  73  |          |          C++ 函数库 \<algorithm\> 有哪些实用的函数           |
|  74  |    是    |                 sort 函数怎么自定义排序规则                  |
|  75  |    是    |                   快速幂问题解决的代码模板                   |
