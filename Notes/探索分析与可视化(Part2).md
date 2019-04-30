## 2. 探索分析与可视化（Part 2）

探索性数据分析（复合分析）可视化

### 2.5 复合分析
- 交叉分析
- 分组分析
- 相关分析
- 因子分析
- 聚类分析（暂略）
- 回归分析（暂略）

#### 2.5.1 交叉分析
有一张数据表，最简单的方法，我们可以通过一行或者一列的角度分析。但有时并不能得到最真是最客观的结论，我们忽略了数据间、属性间的关联性。

我们可以任意取两列，根据假设检验来判断两者间是否有联系；或者，以一个或几个属性为行，令一个或几个属性为列，做成一张交叉表（也叫透视表）。

Note:
The relative Jyputer Notebooks in Code folder are:
- 2.5.1 Cross Analysis.ipynb

#### 2.5.2 分组分析
有两种含义：
- 将数据分组后，再进行分析比较；
- 根据数据的特征，将数据进行切分。分成不同的组，是的组内成员尽可能的靠拢，组间的成员尽可能远离。

根据第二个含义，如果指定每条数据的分组，来计算未知数据的分组，这个过程为分类。而如果不知道分组，只是想把数据物以类聚，这个过程为聚类。

一般需要结合其他分析方法一起使用，所以分组分析更像是一种辅助的手段，而不是目的性分析。例如在对比分析与交叉分析中，都是用了分组手段。常用的手段是：钻取
- 钻取是改变维度的层次，变化分析粒度的过程。

根据方向不同可分：向上钻取与向下钻取。
- 向下钻取：展开数据，查看数据细节的过程
- 向上钻取：分组汇总数据的过程。

- 连续分组


不纯度（Gini系数）

$$ Gini(D) = 1 - \sum{(\frac{C_k}{D})^2}$$

例如：

<table>
    <tr>
        <td>A<td>
        <td>B<td>
    </tr>
    <tr>
        <td>X1<td>
        <td>Y1<td>
    </tr>
    <tr>
        <td>X1<td>
        <td>Y1<td>
    </tr>
    <tr>
        <td>X2<td>
        <td>Y1<td>
    </tr>
    <tr>
        <td>X1<td>
        <td>Y2<td>
    </tr>
    <tr>
        <td>X1<td>
        <td>Y2<td>
    </tr>
</table>


Note:
The relative Jyputer Notebooks in Code folder are:
- 2.5.1 Cross Analysis.ipynb

#### 2.5.3 相关分析

Note:
The relative Jyputer Notebooks in Code folder are:
- 2.5.1 Cross Analysis.ipynb

#### 2.5.4 因子分析

Note:
The relative Jyputer Notebooks in Code folder are:
- 2.5.1 Cross Analysis.ipynb