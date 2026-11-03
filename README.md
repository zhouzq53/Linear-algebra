# 线性代数 · 学习笔记

> 本仓库是学习教材 Lay, Lay & McDonald《Linear Algebra and Its Applications》(6th ed., 2022) 时整理的个人学习笔记。
> 
## 目录结构

```text
.
├── chapter01.ipynb   # 第 1 章笔记：线性方程组-矩阵和行化简--向量与线性组合--线性无关--线性变换
├── chapter02.ipynb   # 第 2 章笔记：矩阵运算、可逆性、分块矩阵、LU 分解、图形学、子空间、维数与秩
├── README.md
└── .gitignore
```

## 章节内容

### Chapter 1 线性方程组与线性变换

>用矩阵统一表示线性问题，通过主元和自由变量判断解的存在性与唯一性，再利用线性变换建立实际模型。
>
| 章节 | 主题 | 主要知识点 |
| :--- | :--- | :--- |
| 1.1 | 线性方程组（Systems of Linear Equations） | 线性方程组、增广矩阵、初等行变换、解集、相容与不相容 |
| 1.2 | 行化简与阶梯形（Row Reduction and Echelon Forms） | REF、RREF、主元位置、基本变量与自由变量、存在唯一性定理、Gauss-Jordan 消元法 |
| 1.3 | 向量方程（Vector Equations） | $\mathbb{R}^n$、向量运算、线性组合、张成空间（Span）、向量方程与线性方程组的等价性 |
| 1.4 | 矩阵方程（The Matrix Equation $A\mathbf{x}=\mathbf{b}$） | 矩阵与向量相乘、列向量的线性组合、方程有解的等价条件、列张成 $\mathbb{R}^m$ 与每行有主元 |
| 1.5 | 线性方程组的解集（Solution Sets of Linear Systems） | 齐次与非齐次方程组、平凡解与非平凡解、自由变量、参数向量形式、特解与齐次通解 |
| 1.6 | 线性方程组的应用（Applications of Linear Systems） | 经济成本、化学反应平衡、网络流动、实际问题的线性建模 |
| 1.7 | 线性无关（Linear Independence） | 线性相关与无关、齐次方程零解判定、自由变量、线性相关的充分条件、主元列与极大线性无关组 |
| 1.8 | 线性变换简介（Introduction to Linear Transformations） | 定义域、陪域、值域、矩阵变换、线性变换的可加性与齐次性、线性变换的几何意义 |
| 1.9 | 线性变换的标准矩阵（The Matrix of a Linear Transformation） | 标准矩阵的构造与唯一性、旋转、反射、缩放、剪切、投影、单射与满射、复合线性变换 |
| 1.10 | 线性模型及应用（Linear Models in Business, Science, and Engineering） | 电路方程、基尔霍夫定律、矩阵建模、汽车分布模型、人口迁移、矩阵与向量的迭代 |
| 补充习题 | 综合应用（Supplementary Exercises） | 方阵的单射与满射等价性、Givens Rotation、旋转矩阵及向量分量消零 |

### Chapter 2 矩阵代数

> 从线性变换的复合建立矩阵运算，利用逆矩阵与矩阵分解求解方程组，再通过子空间、基、维数与秩理解矩阵的空间结构。

| 章节 | 主题 | 主要知识点 |
| :--- | :--- | :--- |
| 2.1 | 矩阵运算（Matrix Operations） | 加法与数乘、矩阵乘法与复合变换、运算性质及限制、矩阵幂、转置、图案识别与数据清洗 |
| 2.2 | 矩阵的逆（The Inverse of a Matrix） | 逆矩阵的定义与唯一性、二阶矩阵求逆、逆矩阵求解方程组、乘积与转置的逆、初等矩阵、行化简求逆 |
| 2.3 | 可逆矩阵的特性（Characterizations of Invertible Matrices） | 可逆矩阵定理、主元与线性无关、单射与满射、可逆线性变换、病态矩阵与条件数 |
| 2.4 | 分块矩阵（Partitioned Matrices） | 分块矩阵的加法与乘法、矩阵乘积的列行展开、分块上三角矩阵与分块对角矩阵求逆 |
| 2.5 | 矩阵分解（Matrix Factorizations） | LU 分解、消元与分解算法、前代与回代、多右端项求解的计算效率、电路应用 |
| 2.6 | 列昂惕夫投入产出模型（The Leontief Input–Output Model） | 当前 Notebook 尚未整理 |
| 2.7 | 计算机图形学应用（Applications to Computer Graphics） | 图形的矩阵表示、基本几何变换、齐次坐标与平移、三维复合变换、透视投影 |
| 2.8 | 实数向量空间的子空间（Subspaces of Rⁿ） | 子空间与封闭性、张成空间、列空间、零空间、子空间的基、从原矩阵主元列选取列空间的基 |
| 2.9 | 维数与秩（Dimension and Rank） | 基坐标、维数、秩与零度、秩定理、基定理、可逆性与空间结构、数值秩与容差 |
| 补充习题 | 综合应用（Supplementary Exercises） | Pauli 矩阵与反对易、范德蒙德矩阵与插值唯一性、列随机矩阵的幂与稳定状态、特殊矩阵逆的通式 |

第二章习题包含数学证明与 Python 计算：使用 SymPy 进行精确行化简和符号运算，使用 NumPy 计算矩阵幂与数值结果，并通过穷举验证图案识别条件。

## 学习进度

- [x] 第 1 章 Linear Equations in Linear Algebra 线性方程组（已整理）
- [ ] 第 2 章 Matrix Algebra 矩阵代数（已整理 §2.1–2.5、§2.7–2.9 及补充习题；§2.6 尚未整理）
- [ ] 第 3 章 Determinants 行列式（待完成）
- [ ] 第 4 章 Vector Spaces 向量空间（待完成）
- [ ] 第 5 章 Eigenvalues and Eigenvectors 特征值与特征向量（待完成）

---

## 参考教材

- David C. Lay, Steven R. Lay, Judi J. McDonald. *Linear Algebra and Its Applications*, 6th Edition. Pearson, 2022.