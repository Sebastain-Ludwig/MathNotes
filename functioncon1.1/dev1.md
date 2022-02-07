# 导数和微分

## 导数的基本概念

## 导数概念的引入

切线:(求切线的斜率)

* 切线的定义:设曲线$y=f(x)$,在曲线上的点$(x_{0},y_{0})$处和曲线相交的割线$P_0Q$(两个方向的割线都可以),当$Q$沿着曲线$y=f(x)$趋于$P_0$时,割线$P_0Q$的极限位置存在且为$P_0T$,称为是曲线$y=f(x)$在$P_0$位置的切线
  * 设曲线$y=f(x)$在曲线上$P_0(x_{0},y_0)$处存在切线$P_0T$,且$P_0T$和$y$轴不平行,求$P_0T$的斜率$k_{P_0T}$(求切线方程)
      过$P_0(x_0,y_0)$作曲线$y=f(x)$割线$P_0Q$,$Q(x_0+\Delta x,f(x+\Delta x))$
$$
\begin{array}{c}
Q\rightarrow P_0\Leftrightarrow \Delta x\rightarrow 0,f(x_0+\Delta x)\rightarrow f(x_0)\\
\Rightarrow f(x+\Delta x_0)-f(x_0) \rightarrow 0\Rightarrow \lim_{\Delta x\rightarrow 0}\Delta y=0\\
\Leftrightarrow f(x)\text{在}x_0\text{连续}\\
\end{array}
$$
割线$P_0Q$的斜率为$k_{P_0Q}=\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}=\frac{\Delta y}{\Delta x}$,称为$(x_0,x_0+\Delta x)$构成的区间上函数的平均率
$$
k_{P_0T}=\lim_{\Delta x_0\rightarrow 0}k_{P_0Q}=\lim_{\Delta x\rightarrow 0}\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}=\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}
$$

**首先要求极限存在**

* 质点作变速直线运动求时刻$t_0$时的瞬时速度$v(t_0)$,设质点作变速直线运动,在$t_0$时刻的位移$s=s(t)$,求在$t_0$时刻的瞬时速度$v(t_0)$
$$
v=\lim_{t_0}\frac{\rightarrow 0}S(t_0+\Delta t)-S(t_0)}{\Delta t}=\lim_{\Delta t\rightarrow 0}\frac{\Delta S}{\Delta t}
$$
无论从哪一侧趋近,速度的表达是都是相同的

* 求末一时刻的人口增长率,总数$N=N(t)$
$$
v=\frac{N(t_0+\Delta t)-N(t_0)}{\Delta t}
$$
$$
v=\lim_{\Delta t\rightarrow 0}\frac{\Delta N}{\Delta t}
$$

## 导数的定义

设$f(x)$在$(x_0-\delta,x_0+\delta)$内有定义($\delta>0$),$x_0+\Delta x\in(x_0-\delta,x_0+\delta)$,若
$$
\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}=\lim_{\Delta x\rightarrow 0}\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}=\lim_{x\rightarrow x_0}\frac{f(x)-f(x_0)}{x-x_0}
$$
存在该极限称为$y=f(x)$在$x=x_0$处的导数,记作$f^{'}(x_0),y^{'}(x_0),\frac{dy}{dx}|_{x=x_0},\frac{d}{dx}f(x)|_{x=x_0}$,最后一个的$\frac{d}{dx}$称为导数算子

有$\lim_{\Delta x\rightarrow 0}\frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}=f^{'}(x_0)$,称为
