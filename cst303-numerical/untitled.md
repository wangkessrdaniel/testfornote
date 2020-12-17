# TEST

## 第五章：Higher Order Taylor Method

## Local Truncation Error

![](../.gitbook/assets/0.png)

![](../.gitbook/assets/1.png)

### Example

using the Euler's method

![](../.gitbook/assets/2.png)

 每一步的error means in every step

### Extrapolation

![](../.gitbook/assets/3.png)

![](../.gitbook/assets/4.png)

* 如何从EM推理得到LTE
* Derivative（y\(ti\)）== f\(ti,yi\)
* 所以：Derivative——Derivative（y\(ti\)） == Derivative（ f\(ti,yi\) ）

![](../.gitbook/assets/5.png)

### Higher Order Taylor Method

FOR THE ORDER N IN THE TM

![](../.gitbook/assets/6.png)

* 目标 improving the convergence properties of the difference methods

![](../.gitbook/assets/7.png)

n+1 连续性

![](../.gitbook/assets/8.png)

拥有更高维度的TM

### Exapmle

#### n=2

![](../.gitbook/assets/9.png)

![](../.gitbook/assets/10.png)

![](../.gitbook/assets/11.png)

error会不断的积累

TM都会不断的积累误差

![](../.gitbook/assets/12.png)

we need to compute the 4 terms for the following terms

![](../.gitbook/assets/13.png)

![](../.gitbook/assets/14.png)

## Local Truncation Error\(Taylor\)

![](../.gitbook/assets/15.png)

* 对于不同的order LTE 也是不同的减小的 error呈现指数级的减小

![](../.gitbook/assets/16.png)

由于我们的 TM本身是有error的

分析变量和error的关系我们需要将其他的part 减去

Derivative（y\(ti\)）== f\(ti,yi\)

通过对最后一项的分析

![](../.gitbook/assets/17.png)

记住将h除去

![](../.gitbook/assets/18.png)

![](../.gitbook/assets/19.png)

![](../.gitbook/assets/20.png)

![](../.gitbook/assets/21.png)

## Runge-Kutta Methods

### Intro& TM in 2 variable

#### compare with TM

![](../.gitbook/assets/22.png)

* 评估的过程非常的复杂（TM）
* 需要求导

#### 2 Variable of the TM

![](../.gitbook/assets/23.png)

注意有reminder term存在

![](../.gitbook/assets/24.png)

* the constant in the front is the C20 C21 C22

![](../.gitbook/assets/25.png)

### RK M of order 2

首先我们需要知道

![](../.gitbook/assets/26.png)

LTE for the TM of 2

![](../.gitbook/assets/27.png)

RK2 的基本构造

![](../.gitbook/assets/28.png)

保证LTE的情况之下

![](../.gitbook/assets/29.png)

The algorithm of the RKM

### Example

### Higer-order of RKM

\#\#\#\#\#\#

