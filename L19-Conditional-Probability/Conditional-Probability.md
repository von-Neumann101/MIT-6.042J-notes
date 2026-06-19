# 条件概率
$$
P_r(A\mid B):=给定B的情况下，A的概率
$$
**定义**：如果$P_r(B)\ne 0,P_r(A\mid B)=\frac{P_r(A\land B)}{P_r(B)}$
![[Pasted image 20260618171019.png|375]]
这里就相当于在$B$中找$A$的概率
**一般乘积法则**：（**一步一步**地确定）
$$
P_r(\bigcap_{i=1}^nA_i)=P(A_1)\prod_{k=2}^nP_r(A_k\mid\bigcap_{i=1}^{k-1}A_i)
$$