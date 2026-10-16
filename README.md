# 线性代数 · 学习笔记

> 本仓库是学习教材 Lay, Lay & McDonald《Linear Algebra and Its Applications》(6th ed., 2022) 时整理的个人学习笔记。
> 
## 目录结构

```text
.
├── chapter01.ipynb   # 第 1 章笔记：线性方程组-矩阵和行化简--向量与线性组合--线性无关--线性变换
├── chapter02.ipynb   # 第 2 章笔记（待添加）
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

## 学习进度

- [x] 第 1 章 Linear Equations in Linear Algebra 线性方程组（已整理）
- [ ] 第 2 章 Matrix Algebra 矩阵代数（待完成
- [ ] 第 3 章 Determinants 行列式（待完成
- [ ] 第 4 章 Vector Spaces 向量空间（待完成
- [ ] 第 5 章 Eigenvalues and Eigenvectors 特征值与特征向量（待完成

---

## 参考教材

- David C. Lay, Steven R. Lay, Judi J. McDonald. *Linear Algebra and Its Applications*, 6th Edition. Pearson, 2022.