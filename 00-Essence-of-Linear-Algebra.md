**Essence of Linear Algebra（线性代数的本质）**
[TOC]
# Chapter1：Vectors ，what even are they？（向量究竟是什么）
- 物理学专业角度：向量是空间中的箭头（Length+Direction）
- 计算机专业角度：向量是有序的数字列表，从原点/向量起点出发到达它的尖端/向量终点。
- 
eg：**向量加法**（运动）
$$
    \left[\begin{array}{c}
        1 
    \\  2 
    \\  
    \end{array}\right]
    +
    \left[\begin{array}{c}
        3 
    \\  -1 
    \\  
    \end{array}\right]
    =
    \left[\begin{array}{c}
        1+3 
    \\  2+（-1） 
    \\  
    \end{array}\right]
$$
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402053649387.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

eg：**向量数乘**（拉伸、缩放）
$$
    2.
    \left[\begin{array}{c}
        3 
    \\  -1 
    \\  
    \end{array}\right]
    =
    \left[\begin{array}{c}
        6 
    \\  2 
    \\  
    \end{array}\right]
$$

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402054111826.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

# Chapter2：Linear combination.span and bases（向量的线性组合、张成的空间与基） 
 - 坐标系的**基向量**：$\hat{i}$，$\hat{j}$,即单位向量
 - $\overrightarrow{v}$与$\overrightarrow{w}$的**线性组合**： $a\overrightarrow{v} + b\overrightarrow{w}$
  **线性组合**：固定一个标量，另外一个量自由变化
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402061701322.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

- $\overrightarrow{v}$与$\overrightarrow{w}$全部线性组合构成的向量集合称为“**张成空间**”，a、b在实数范围内变化。
# Chapter3：Matrices as linear transformations（线性变换与矩阵）
1、什么是**线性**：（1） 直线在变换后仍然保持为直线，不能有所弯曲.（2）原点必须保持固定。
2、 **线性的严格定义**为：1、可加性 2、成比例
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423045209875.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423045306669.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423045500839.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
第二个成比例：将一个向量v与某个数相乘，进行应用变换后，得到结果和变换后的v与这个数相乘一致。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423045736351.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423045744260.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

3、什么是**线性变换**：保持网格平行且等距分布的变换。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200407015552754.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
eg：向量就是-1与i帽之积和2与j帽之积的和。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200407020421396.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200407015931644.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
# Chapter4：Matrix multiplication as composition（线性变换复合与矩阵乘法）


# Chapter5：The determinant（行列式）
**求行列式**：求不同维度中向量构成的体积（每列代表一个向量的位置）。
**线性变换**：通过旋转、剪切方式变换i、j向量。

# Chapter6：Inverse matrices，column space and null space（逆矩阵、列空间与零空间、秩）
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422231030562.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**逆矩阵**$A^{-1}.A$:等于什么都不做，即恒等变换。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422234540599.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422234640417.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
1、$det（A）≠ 0$
线性方程组的逆变换存在时，可以用逆变换求解方程组。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422234933912.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
2、$det（A）= 0$ 即所有区域被压缩成零体积。
没有逆变换，因为不能运用函数将直线或者一个平面解压缩出体积。但解可能存在。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422231921860.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/2020042223214264.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**秩（Rank）**：代表变换后空间的维数。等同于零行列式。精确定义为：列空间的维数。注：$2×2$矩阵，秩最大为2.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422232756865.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422232806286.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
**列空间**：所有可能的输出向量$A\overrightarrow{v}$构成的集合。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422232836667.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422233513245.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422233523263.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422233541585.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**满秩**：当秩达到最大值时，意味着秩与列数相等。

 **零空间或核**：变换后向量落在零向量上，零空间是这些向量所构成的空间。
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422234226896.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200422234235429.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

# Chapter7：Dot products and duality（点积与对偶性）
**点积**：正、负、0
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423000011756.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

** 第一种**：$\overrightarrow{v}.\overrightarrow{w} = 0$
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423001646404.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**  第二种**：$\overrightarrow{v}.\overrightarrow{w} > 0$
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423001506471.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

 **第三种**：$\overrightarrow{v}.\overrightarrow{w} < 0$
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423001748351.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423001515426.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
**对偶性**：对应关系。

解答：
1、**点积与顺序无关**：由于对偶性。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423002229279.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

2、**单位向量的点乘**：将向量投影到单位向量所在的直线上所得的投影长度。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423002741679.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020042300284930.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**非单位向量**：向定向量上投影，将投影的值与定向量长度相乘。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423003146450.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
# Chapter8：Cross products via transformations（以线性变换的眼光看叉积）

**叉乘理解**：
$\overrightarrow{v} × \overrightarrow{w}$=平行四边形的面积
1、$\overrightarrow{v}$ 在$\overrightarrow{w}$左边，值为正。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423004827752.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
2、$\overrightarrow{v}$ 在$\overrightarrow{w}$右边，值为负。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423004837884.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**计算叉乘值**：
1、**二维**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423005103621.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
2、**三维**：$i、j、k$当作常数，原理看视频12.08
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423005652910.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423010037837.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**确定正负**：
**右手法则**：右手食指指向v的方向，中指w方向，大拇指竖起方向为叉积方向
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423005523551.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**性质**：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423005220500.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

# Chapter9：Change of basis（基变换）需再看
**基变换**：将用自己坐标系表示的向量，现在用另外一个坐标系进行表示。

# Chapter10：Eigenvectors and eigenvalue（特征向量与特征值）
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423040246285.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423040342579.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
**特征向量**：向量在变换中发生旋转，从来离开它张成的直线，这些特殊的向量，叫做特征向量。
**特征值**：每个特征向量都有一个所属的值，被称为特征值，即衡量特征向量在变换中拉伸或者压缩比例的因子。可以为负。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423035717263.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423035704710.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423035459354.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
**计算思想**：
求解矩阵A的特征向量及特征值，实际是求解使得整个等式成立的向量和数$λ$。
1、右边写成某个矩阵向量乘积，矩阵的作用为任一向量乘以$λ$，矩阵的列代表变换后的基向量。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423041102211.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

2、每个基向量仅仅与$λ$相乘，所以矩阵的对角元均为$λ$，其余位置为0。矩阵写成I，I为单位矩阵，两侧都为矩阵乘积的形式，移到左侧。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423041119980.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423041213339.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423041445211.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

3、寻找使得等式为0的值，当且仅当矩阵代表的变换将空间压缩到最低的维度时，才会存在一个非零向量，使得矩阵和它的乘积为零向量，而压缩空间对应的是矩阵的行列式为零。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423041716810.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423042016935.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
**注意**：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423042341858.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)

**基变换**：
用特征向量作为基，将坐标作为一个矩阵的列，这个矩阵就是基变换矩阵，左侧写基变换矩阵的逆，右侧写基变换矩阵。所得的矩阵代表的是同一个变换，不过是从新基向量所构成的坐标系的角度来看。用特征向量来做基向量，得到的新矩阵必然是对角的，并且对角元为对应的特征值，原因是它所处的坐标系的基向量在变换中只进行了缩放，一组基向量（同样是特征向量）构成的集合被称为一组“特征基”，注意，并不是所有的矩阵都能对角化，比如剪切变换，它的特征向量不够多，并不能张成全空间。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423042844539.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423043005253.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423043130491.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200423043346793.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2d1MzA1NTI0MDcz,size_16,color_FFFFFF,t_70)
# Chapter11：Abstract vector spaces（抽象向量看空间）
# Chapter12：克莱姆法则