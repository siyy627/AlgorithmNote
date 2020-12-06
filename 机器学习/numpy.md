### 数组
#### np.array
* dytpe: 查看数据类型

#### np.zeros, np.ones
* 零数组

#### np.full()
* 指定参数矩阵

#### np.arange()

#### np.linspace()

#### np.random.randint()
* 如果有三个参数，最后一个参数是dshape
* 随机种子， np.random.seed(xxx) 一次性

#### np.random.rand()
* 浮点数

#### np.random.normal()
* 符合正态分布的浮点数

---

#### ndim
* 查看是几纬数组

#### shape

#### reshape

---

#### 合并与分割
* concatenate([], axis=)
  * axis默认是0，沿着第一个纬度的方向
* vstack() 拼接不同纬度

#### 聚合
* np.percentile() # 相当于可选中位数
* 0, 25, 50, 75, 100, 百分位点

#### 排序相关
* np.random.shuffle()
* np.argsort() 返回在原数组中的索引
* np.partition
* np.argpartition()

#### 计数
* np.count_nonzero()
* np.any()
