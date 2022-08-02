# 零代码完成图片分类任务

## PaddleX GUI 简洁教程


骆秀韬

epsilon_luoo@outlook.com

湖北第二师范学院

人工智能特别兴趣小组

---
## 计算机视觉四大任务
- ### 图像分类
- ### 目标检测
- ### 语义分割
- ### 实例分割
 


---
 ![[../src/Pasted image 20220723035824.png]]
---
# 图像分类
---
# 回归与分类
![[../src/Pasted image 20220723040701.png]]

---
## 分类是一种特殊的回归
**依靠概率的阈值决定类别**

---
## 回顾一下 **“回归”**

回归的输出是一个具体的数值

笔记本电脑的价格是：5800元

---
### 如果我们把回归出的 <big>数值</big> 变成 <big>概率</big>
5800 元买到笔记本电脑的概率是：80%

5800 元买到爱情的概率是：~0%

---
# 二分类问题
- Positive 
- Negative

---
**Is it a Dog?**
![[../src/celine-sayuri-tagami-2s6ORaJY6gI-unsplash (小) 1.jpg]]

---
$$
f(x)=
\begin{cases}
positive,&if\,\,x\geq50,\\
negative,&if\,\,x<50
\end{cases}
$$
