---
title: 重整化
date: 2025-10-05
categories: physics
layout: page
mathjax: true
---

物理人常说的重整化其实自动包含了两个不同含义的步骤：正规化，以及真正的重整化（流变）

所谓微生无量缘劫不定求真妙法（人话：微扰量子场论/微扰的无穷自由度的量子理论），自然要因为他无穷多的自由度而有无穷的某些结果。

原则上来说，什么样的场论是个好场论，以玻色多体为例：

从费曼的路径积分推导开始，得到场构型路径积分后，
配分函数

$$
Z = \left(\frac{m}{2 \pi \epsilon}\right)^{\tfrac{N}{2}}
\int \prod_{n=0}^{N-1} dq_n \, e^{-S[q]} \Big|_{q_N = q_0}
$$


$$
S[q] = \sum_{n=0}^{N-1} \epsilon \left[
    \tfrac{1}{2} m \left( \frac{q_{n+1} - q_n}{\epsilon} \right)^2
    + \tfrac{1}{4} \kappa \left( q_{n+1}^2 + q_n^2 \right)
\right]
$$

$$
\frac{1}{\lambda} S[q] = 
\sum_{n=0}^{N-1} \xi q_n^2 
- \sum_{n=0}^{N-1} \tfrac{1}{2}(q_{n+1} q_n + q_n q_{n+1})
$$

$$
\lambda = \frac{m}{\epsilon}, 
\qquad 
\xi = 1 + \epsilon^2 \frac{\kappa}{2m}.
$$
