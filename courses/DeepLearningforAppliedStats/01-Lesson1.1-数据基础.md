# 1. Numpy（Numerical Python ）
NumPy提供了两种基本的对象：ndarray（N-dimensional array object）和 ufunc（universal function object）。

** ndarray **

神经网络里所有数据 —— 输入图片、权重、输出 —— 本质都是多维数组，PyTorch 里叫 Tensor，NumPy 里叫 ndarray，是同一个东西的前身。

## 1.1 生成NumPy数组
## 1.2 取数据
## 1.3 NumPy的算术运算
## 1.4 数组变形
## 1.5 通用函数
重要概念	
-向量化 Vectorization	不写 for 循环，让函数直接作用于整块数组，这是 NumPy 的核心优势
-通用函数 ufunc	np.sin、np.cos、np.exp 这类能一次性处理数组所有元素的函数
-time.time()	取当前时间戳，用来给代码计时代码
## 1.6 广播机制（Broadcasting）
NumPy 自动把两个数组 "补齐成一样大"，再对应位置相加，不用写循环

神经网络里天天用：比如你有一批 100 张图片的得分矩阵 (100, 10)，要给每一行都加上同一个偏置 [0.1, 0.2, ...]，靠的就是广播自动对齐，一行加法搞定，

# 2. Pandas
## 2.1 Series 
## 2.2 dataframe

# 3. Matplotlib, Seaborn
https://jishuin.proginn.com/p/763bfbd2d68c
## 3.1 散点图
## 3.2 带误差棒的散点图
## 3.3 置信带图
## 3.4 填色等高线图（contourf）
## 3.5 重叠直方图
## 3.6 二维直方图

# 流程
read_csv 读进来 → head/describe 看一眼 → drop_duplicates/fillna 清洗 → pivot_table 汇总
