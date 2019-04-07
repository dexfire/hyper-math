---
title: 极限
sidebar: home_sidebar
permalink: limit.html
toc: true
---

[toc]

# 极限
- 极限是微积分中的基础概念，是分析变量变化趋势的基本工具，也是微积分的重要思想和方法。
- 微积分中许多定义均利用了极限，如：连续、可导、定积分、无穷级数
- 掌握好极限思想非常重要。

## 数列的极限


### 定义

**数列极限的初步定义**：当项数$n$无限增大时，如果数列$\{x_n\}$无限接近于某一个常数$A$，则称$A$为这个数列的极限。
**记法**：$\lim_{n\Rightarrow\infty}x_n=A$
**数列极限的精确定义**：对于数列$\{x_n\}$，如果存在一个常数$A$使得对任意给定的正数$\varepsilon$（可以无穷小），总存在正整数$N$，使得满足$n>N$时，恒有$|x_n-A|<\varepsilon$成立，则称常数$A$为数列$\{x_n\}$的$\bold{\color{red}{\text{极限}}}$。
**数列极限的收敛、发散**：如果$A$为数列$\{x_n\}$的$\bold{\color{red}{\text{极限}}}$，则称数列 $\{x_n\}$ $\bold{\color{red}{\text{收敛}}}$于$A$；如果数列 $\{x_n\}$ 不收敛，则称数列 $\{x_n\}$ $\bold{\color{red}{\text{发散}}}$。
**数列极限的$\varepsilon-N$定义**：$\forall\varepsilon>0$，$\exists$正整数$N$，当$n>N$时，恒有$|x_n-A|<\varepsilon$成立，则称常数$A$为数列$\{x_n\}$的$\bold{\color{red}{\text{极限}}}$。
> **理解**：
1. $\varepsilon$是一个给定的正**常数**，但是它可取到任意正数，这个值越小极限逼近效果越好，直至无穷小。$\varepsilon$表征的是$n>N$条件下，$x_n$于$A$之间的**趋近程度**。也可以理解为**逼近的精确度**。
   - 为什么$\varepsilon$要是正数？ -> 等式左侧为绝对值表达式...
   - $\varepsilon$如何“变化”？ -> 逼近是一个动态过程，$\varepsilon$取很大的值时，条件$|x_n-A|<\varepsilon$很容易满足。但是定义要求对于**任意正数$\varepsilon$**均满足条件要求，所以还应该对$\varepsilon$取极小值时的$|x_n-A|<\varepsilon$表达式进行判别，如果对于任意正数均成立，$A$才为数列$\{x_n\}$的极限。
2. $n>N$表征的是当$n$大到什么程度之后，$|x_n-A|$开始满足$\varepsilon$的精度要求。

**数列极限的等价定义**：设$K>0$为常数，$\forall\varepsilon>0$，$\exists$正整数$N$，当$n>N$时，恒有$|x_n-A|<K\varepsilon$成立，则称常数$A$为数列$\{x_n\}$的$\bold{\color{red}{\text{极限}}}$。

### 性质

**唯一性**：
**有界性**：收敛的数列必有界。
**保序性**：
**保号性**：
**夹逼准则**：
**子数列**：
**四则运算**：

### 极限收敛判别法
> 单调有界准则要求数列单调，Cauchy收敛原理则可以适用于**非单调数列**。


**单调有界准则**：单调有界数列必有极限。
**Cauchy收敛原理**：数列$\{x_n\}$收敛的充分必要条件：$\forall\varepsilon>0$，$\exists$正整数$N$，当$m>N, n>N$时，恒有$|x_m-x_n|<\varepsilon$.

### 题型：证明数列$\{x_n\}$的极限为$A$
**思路**：
    1. 构造**逼近式**$f(n)=|x_n-A|$
    2. **化简**逼近式$f(n)$，期间可以对$f(n)$进行适当**放大**为$g(n)$（$g(n)$一般为$n$的简单表达式），得到$g(n)>f(n)$。
    3. 构造不等式$g(n)<\varepsilon$，得到**逼近条件式**$n>h(\varepsilon)$。
    4. 取正整数值$N=\[h(\varepsilon)\]+1$。
    5. 结论：只需$n>N$，$|x_n-A|<\varepsilon$恒成立。故数列$\{x_n\}$的极限为$A$。
**例题**：


## 函数的极限
- $x\rightarrow x_0$ / 自变量$x$趋于有限值$x_0$的极限
- $x\rightarrow \infty$ / 自变量$x$趋于有限值$x_0$的极限

### 定义

#### **$x\rightarrow x_0$的极限**
**$x\rightarrow x_0$的极限**：
设函数$f(x)$在点$x_0$的某去心邻域内有定义，如果存在常数$A$，使得对于任意给定的正数$\varepsilon$（可以无穷小），总存在正数$\varDelta$


#### **$x\rightarrow \infty$的极限**
**$x\rightarrow \infty$的极限**

## 无穷小和无穷大

## 函数的连续性



