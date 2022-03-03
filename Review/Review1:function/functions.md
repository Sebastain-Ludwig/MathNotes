# 函数和初等函数

* 变量和常量:
  人们在观察、研究某一运动过程中,会遇到许多不同的量. 其中有的量在研究过程们保持不变, 这种量叫做常量; 也有的量在运动过程中可取不问的值,这种量叫做变量.
* 函数的定义: 
  定义 设 $A 、 B$ 是两个非空实数集, 如果存在一个对应法则 $f$, 使得对 $A$ 中任何一个实数 $x$, 在 $B$ 中都有唯一确定的实数 $y$ 与 $x$ 对应, 则称对应法则 $f$ 是 $A$ 上的函数, 记为 $f: x \mapsto y$ 或 $f: A \rightarrow B$.
  $y$ 称为 $x$ 对应的函数值, 记为
  $$
   y=f(x), \quad x \in A .
  $$
* 邻域和去心邻域:
  对区间我们常引人下面的记号. 开区间 $\left(x_{0}-\delta, x_{0}+\delta\right) \triangleq U\left(x_{0}, \delta\right)(\delta>0)$ 称为以 $x_{0}$ 为 心, 以 $\delta$ 为半径的邻域, 简称为 $x_{0}$ 的 $\delta$ 邻域. 若不需要指明半径 $\delta$ 时, 记作 $U\left(x_{0}\right)$, 称为 $x_{0}$ 的 某邻域. $\left(x_{0}-\delta, x_{0}\right) \cup\left(x_{0}, x_{0}+\delta\right) \triangleq \stackrel{0}{U}\left(x_{0}, \delta\right)$ 称为以 $x_{0}$ 为心, 以 $\delta$ 为半径的空心邻域, 简 称为 $x_{0}$ 的 $\delta$ 空心邻域, 若不需要指明半径 $\delta$ 时, 记作 $U\left(x_{0}\right)$, 称为 $x_{0}$ 的某空心邻域. 
  
  同理, $\left(x_{0}, x_{0}+\delta\right) \triangleq U_{+}\left(x_{0}, \delta\right),\left[x_{0}, x_{0}+\delta\right)=U_{+}\left(x_{0}, \delta\right)$ 统称为 $x_{0}$ 的右邻域, $\left(x_{0}-\delta, x_{0}\right) \triangleq \bigcup^{2} \ldots\left(x_{0}, \delta\right),\left(x_{0}-\delta, x_{0}\right]=U_{-}\left(x_{0}, \delta\right)$ 统称为 $x_{0}$ 的左邻域. 
  
  设 $M>0,(M,+\infty) \triangleq U(+\infty, M)$ 称为 $+\infty$ 的左邻域; $(-\infty,-M) \triangleq U(-\infty, M)$ 称为 $=\infty$ 的右邻域; $(-\infty,-M) \cup(M,+\infty) \triangleq U(\infty, M)$ 称为 $\infty(\pm \infty)$ 的邻域.
* 函数的表示方法:
  1. 表格法
  2. 图像法
  3. 公式法
   
# 特殊函数和特殊函数关系

## 特殊函数

1. 取整函数
2. Dirichlet 函数
3. 分段函数

## 特殊函数关系

1. 复合函数:
   定义 设 $y=f(u), u \in E, u=\varphi(x), x \in I$. 若 $I(f) \cap R(\varphi) \neq \emptyset$, 则 $y$ 通过 $u$ 构 成 $x$ 的函数, 称为由 $y=f(u)$ 与 $u=\varphi(x)$ 复合而成的函数, 简称为复合函数, 记作 $y=$ $f(\varphi(x))$.

   **要判断两个函数 $y=f(u), u=\varphi(x)$ 能不能构成复合函数,只要看 $y=f(\varphi(x))$ 的分 $^{t}$ 义域是否为非空集. 若不为空集, 则能构成复合函数, 否则不能.**
2. 反函数:
   设$y=f(x),x \in D$,若对于$R(f)$中每一个$y$,都有唯一确定的且满足$y=f(x)$的$x \in I)$ 与之对应, 则按此对应法则就能得到一个定义在 $R(f)$ 上的函数, 称这个函数为 $f$ 的反 函数, 记作
    $$
    f^{\prime}: R(f) \rightarrow D \text { 或 } x=f^{-1}(y), y \in R(f) \text {. }
    $$
    $$
    y=f^{1}(x), x \in R(f) .
    $$
    函数 $y=f(x)^{1} \mathrm{y} y=f^{1}(x) \mathrm{~ 㠽}$ $y=x$ 对称.

# 初等函数和基本初等函数

1. 常值函数$y=C,x\in R$
2. 幂函数$y=x^{a}$
3. 指数函数$y=a^{x} ,a>0,a\neq 1$
4. 对数函数$y=\log_{a}x,x\in (0,+\infty)$
5. 三角函数
6. 反三角函数
7. 多项式函数
8. 分段函数
9.  狄利克雷函数

 初等函数是由基本初等函数经过四则运算得到

不是初等函数的函数都是非初等函数

# 三角学

## 基本三角函数

1. 正弦函数$\sin \theta=\frac{y}{r}$
2. 余弦函数$\cos \theta=\frac{x}{r}$
3. 正切函数$\tan \theta=\frac{y}{x}$
4. 余切函数$\cot \theta=\frac{x}{y}$
5. 正割函数$\sec \theta=\frac{r}{x}$
6. 余割函数$\csc \theta=\frac{r}{y}$

## 同角三角函数公式

1. $\sin ^{2} \theta+\cos ^{2} \theta=1$
2. $1+\tan ^{2} \theta=\sec ^{2} \theta$  
3. $1+\cot^{2} \theta=\csc ^{2} \theta$
4. $\tan \theta=\frac{\sin \theta}{\cos \theta}$
5. $\cot \theta=\frac{\cos \theta}{\sin \theta}$
6. $\tan \theta=\cot \theta$
7. $\sin \theta=\frac{1}{\csc \theta}$
8. $\cos \theta=\frac{1}{\sec \theta}$   

## 诱导公式

1. $\sin \theta$:
   1. $\sin (2k\pi +\theta )=\sin \theta$  
   2. $\sin (2k\pi -\theta)=-\sin \theta$ 
   3. $\sin [(2k+1)\pi +\theta]=-\sin \theta$ 
   4. $\sin [(2k+1)\pi-\theta]=\sin \theta$
   $$
       \sin (2\pi +\theta)=\sin \theta\\
       \sin (\pi +\theta)=-\sin \theta\\
       \sin (2\pi -\theta)=-\sin \theta\\
       \sin (\pi -\theta)=\sin\theta
   $$ 
2. $\cos \theta$:
   1. $\cos (2k\pi +\theta)=\cos \theta$   
   2. $\cos (2k\pi -\theta)=\cos \theta$
   3. $\cos [(2k+1)\pi +\theta]=-\cos \theta$
   4. $\cos [(2k+1)\pi -\theta]=-\cos \theta$
   $$
       \cos (2\pi +\theta)=\cos \theta\\
       \cos (2\pi -\theta)=\cos \theta\\
       \cos [(2k+1)\pi +\theta]=-\cos \theta\\
       \cos [(2k+1)\pi-\theta]=-\cos \theta 
   $$    
3. $\tan \theta$:
   1. $\tan (2k\pi +\theta)=\tan \theta$
   2. $\tan (2k\pi -\theta)=-\tan \theta$
   3. $\tan [(2k+1)\pi+\theta]=\tan \theta$
   4. $\tan [(2k+1)\pi-\theta]=-\tan \theta$     
   $$
       \tan (\pi +\theta)=\tan \theta\\
       \tan (\pi -\theta)=-\tan \theta
   $$ 

## 基本三角函数的图像

****

## 和角公式和倍角公式

1. $\sin (\alpha\pm \beta)=\sin \alpha \cos \beta\pm \sin \beta \cos \alpha$
2. $\cos (\alpha \pm \beta)=\cos \alpha \cos \beta\mp \sin \alpha\cos \beta$
3. $\tan (\alpha \pm \beta)=\frac{\tan \alpha \pm \tan \beta}{1\mp \tan \alpha \tan \beta}$   
1. $\sin 2\alpha=2\sin \alpha \cos \alpha$
2. $\cos 2\alpha=\cos ^{2} \alpha-\sin ^{2} \alpha=2\cos ^{2} \alpha-1=1-2\sin ^{2} \alpha$
3. $\tan 2\alpha =\frac{2\tan \alpha}{1-\tan ^{2} \alpha}$   
4. $|\sin \frac{\alpha}{2}|=\sqrt{\frac{1-\cos \alpha}{2}}$ 
5. $|\cos \frac{\alpha}{2}|=\sqrt{\frac{1+\cos \alpha}{2}}$
6. $|\tan \frac{\alpha}{2}|=\sqrt{\frac{1-\cos \alpha}{1+\cos \alpha}}$
7. $\tan \frac{\alpha}{2}=\frac{1-\cos \alpha}{\sin \alpha}=\frac{\sin \alpha}{1+\cos \alpha}$ 

## 和差化积和积化和差

1. $\sin \alpha \cos \beta=\frac{1}{2}[\sin (\alpha+\beta)+\sin (\alpha-\beta)]$ 
2. $\cos \alpha\sin \beta=\frac{1}{2}[\sin (\alpha+\beta)-\sin(\alpha-\beta)]$
3. $\cos\alpha \cos \beta=\frac{1}{2}[\cos(\alpha+\beta)+\cos(\alpha+\beta)]$
4. $\sin \alpha\sin \beta=\frac{1}{2}[\cos (\alpha+\beta)-\cos(\alpha-\beta)]$   
5. $\sin \theta-\sin \varphi=2\cos\frac{\theta+\varphi}{2}\sin \frac{\theta-\varphi}{2}$
6. $\cos \theta+\cos \varphi=2\cos \frac{\theta+\varphi}{2}\cos \frac{\theta-\varphi}{2}$
7. $\cos \theta+\cos\varphi=-2\sin \frac{\theta+\varphi}{2}\sin \frac{\theta-\varphi}{2}$ 

# 反函数的性质

* 反函数的存在性:若函数是一一映射,则函数的俄反函数存在,否则反函数不存在
* 两个互为反函数的函数的定义域和值域相互对换
* 互为反函数的两个函数(习惯记法)在同一个坐标系下关于$y=x$对称
* 互为反函数的两个函数单调性一致
* 两个互为反函数的函数的奇偶性一致
* 互为反函数的函数具有自反性:
  $$
     f^{-1} (f(x))=x,x\in D_{f}\\
     f(f^{-1}(x) )=x,x\in M_{f}
  $$ 

# 函数的性质

## 奇函数和偶函数

* 定义 设 $D$ 是关于原点对称的数集, $f$ 为定义在 $I$ 上的函数,若对每一个 $x \in I$ (这时也 有 $-x \in I)$, 都有:
   $$
      f(-x)=-f(x),(f(-x)=f(x))
   $$ 

## 周期函数

* 设 $f$ 为定义在 $I$ 上的函数, 値仔在某个非零常数 $T$, 使得对一切 $x \in D$, 都有 $f(x+T)=f(x)$,
则称 $f$ 为周期函数. $T$ 称为 $f$ 的一个周期. 显然, 若 $T$ 是 $f(x)$ 的周期,则 $k T$ 也是 $f(x)$ 的周期, $k \in \mathbf{Z}$. 若周期函数 $f$ 的所有正周期中存在有最小正周期, 则称这个最小正周期为 $f$ 的基本周 期. 一般地,函数的周期指的是基本周期.

## 单调函数

* 定义 设 $f$ 为定义在 $D$ 上的函数, 若对于 $D$ 中任意两个数 $x_{1}, x_{2}$ 且 $x_{1}<x_{2}$, 总有
$$
f\left(x_{1}\right) \leqslant f\left(x_{2}\right) \quad\left(f\left(x_{1}\right) \geqslant f\left(x_{2}\right)\right),
$$
则称 $f$ 为 $I$ 上的递增 (递减) 函数. 特别地, 若总成立严格不等式
$$
f\left(x_{1}\right)<f\left(x_{2}\right) \quad\left(f\left(x_{1}\right)>f\left(x_{2}\right)\right),
$$
则称 $f$ 为 $I$ 上的严格递增 (递减) 函数.
递增和递词函数统称为单调函数, 严格递增和严格递㖪函数统称为严格单调函数.
反函数存在性定理 严格增 (减) 的函数必有严格增(减) 的反函数.

## 有界集,确界原理,有界函数,无界函数

* 定义 设 $A \subset \mathbf{R}, A \neq O$,若存在常数 $M(\mathrm{~N})$, 使得对一切 $x \in A$, 都有 $x \leqslant M(x=$ $N)$, 则妳 $\Lambda$ 为有上 $(F)$ 界的数集, 数 $M(N)$ 称为 $A$ 的一个上(F) 界. $A$ 为无界集。
* 上确界定义:定义 设 $A \subset \mathbf{R}, A \neq \Theta$, 若常数 $\alpha$ 满足下列二个条件:
  
   1. $\alpha$ 是 $A$ 的上界, 即对一切 $x \in A$, 都有 $x \in \alpha$;

   2. $\alpha$ 是 $\Lambda$ 的最小上界, 即对任意㤷定的 $\varepsilon>0, \alpha \cdots  \varepsilon$ 都不是 $A$ 的上界. 即任给 $\varepsilon>0,-$
   
   定存在 $x_{0} \in A$, 使 $x_{0}>\alpha-\varepsilon$, (:迬意: 这里的 $x_{0}$ 随 $\varepsilon$ 变化而变化.)
则称数 $\alpha$ 为数集 $A$ 的上确界, 记作 $\alpha=\sup A$ 或 $\alpha=\sup _{x \in A} \left\{ x\right\}$.
* 下确界定义: 
  定义 设 $A \subset \mathbf{R}, A \neq \Theta$, 若常数 $\beta$ 满足下列 二个条件:
  1. $\beta$ 是 $A$ 的下界,即对一切 $x \in A$, 都有 $x \geqslant \beta$;
  2. $\beta$ 是 $A$ 的最大下界, 即任给 $\varepsilon>0$,一定存在 $x_{0} \in A$, 使 $x_{0}<\beta+\varepsilon$,
* **确界原理:非空有上(下) 界的数集, 必有上(下) 确界.(公理)**
