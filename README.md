**山东大学（威海）数学与统计学院2018级数据科学与人工智能实验班**

暑假科研实训项目

指导教师：郭亮

项目成员：小高、小许、小闫、小叶、小E

## C machine learning algorithm

**目录：**

- **环境配置**
  - 百度AI Studio介绍
  - 百度AI Studio配置
  - 百度AI Studio案例运行
- **公共函数**
  - 读取csv文件数据
  - 数据K折交叉验证
  - 数据标准化
  - 计算算法结果
  - 验证算法结果
- **算法详解**
  - **Simple Linear Regression**
  - **Multivariate Linear Regression**
  - **Logistic Regression**
  - **Perceptron**
  - **Classifification and Regression Trees**
  - **Naive Bayes**
  - **$k$-Nearest Neighbors**
  - **Learning Vector Quantization**
  - **Support Vector Machine**
  - **Backpropagation**
  - **Bootstrap Aggregation**
  - **Random Forest**
  - **Stacked Generalization**
- **简易C语言教程**



百度AI Studio链接：https://aistudio.baidu.com/aistudio/projectdetail/2309566

Github： https://github.com/Gao-Jianxiong-SDUWH/C-machine-learning

知乎专栏：https://www.zhihu.com/column/c_1296572278004940800

B站视频讲解：https://www.bilibili.com/video/BV1st4y1v72S/（未更新）


# 运行说明

## git-bash+gcc

说明：

-l参数 就是用来指定程序要链接的库，-l参数紧接着就是库名，那么库名跟真正的库文件名有什么关系呢？就拿数学库来说，他的库名是m，他的库文件名是libm.so，

```bash
# 编译
gcc main.c read_csv.c k_fold.c evaluate.c rmse.c test_prediction.c -o run -lm
# 运行
./run.exe
```

## vs201* 命令行

1. 打开vs201*的命令行，
2. 到当前路径
3. 命令：cl *.c -o main
4. 运行：./main.exe

## vs201* 
添加相应的头文件

https://ffmpeg.xianwaizhiyin.net/base-compile/intro.html 
