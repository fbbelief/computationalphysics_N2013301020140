#第四次作业

---
##摘要
自由落体运动（Free falling movement）
运用Euler Method求出1.1题的近似解，并与其精确解对照。

---
##背景介绍
自由落体运动是初速度为零、加速度为重力加速度的匀加速直线运动。
在只考虑重力而忽略其他影响的情况下，由牛顿第二定律可得其运动规律。

---
##正文

-----

Euler Method的近似解
>v(t+dt)=v(t)+gdt

直接求得的解析解
>v=-gt

-----

###程序源码：
>[源码](https://github.com/fbbelief/computationalphysics_N2013301020140/blob/master/homework%204.code)

-----
###结果分析
近似解与解析解满足相同的线性关系

![图片1.1]( https://github.com/fbbelief/computationalphysics_N2013301020140/blob/master/1.1)

-----

##结论
-----
验证了Euler method在自由落体运动中给出的近似解即为正确的答案。

-----

##致谢

-----

该程序借鉴了曹一同学的程序，并在陈平涛同学的指导下修改，同时报告格式借鉴了曹一同学的报告。在此表示感谢。
