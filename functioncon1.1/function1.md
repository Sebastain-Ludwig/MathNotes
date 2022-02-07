# 函数的连续性

* $f(\varphi(x))$在$x=x_0$处连续,而$\lim_{x \rightarrow x_{0}}f(\varphi(x))=f(\varphi(x))$或者$\lim_{x\rightarrow x_0}f(\varphi(x))=f(\lim_{x\rightarrow x_0}\varphi(x))$
  * 推论:$\lim_{x\rightarrow x_{0}}\varphi(x)=u_{0}$且$y=f(u)$在$u=u_{0}$处连续, 则$\lim_{x\rightarrow x_{0}}f(\varphi(x))=f(\lim _{x\rightarrow x_0}\varphi(x))$
  * 证明:令 
    $$
    h(x)=\left\{\begin{array}{cc}\varphi(x) &x\neq x_{0}\\u_{0}&x=x_{0}\end{array} \right.
    $$

    ,此时$h(x)$在$x=x_{0}$处连续,$y=f(u)$在$u=u_{0}=h(x_{0})$处连续,则$\lim_{\rightarrow x_{0}}f(h(x))=f(\lim_{x\rightarrow x_{0}}h(x))$,由$x\rightarrow x_{0}$,$h(x)=\varphi (x)$,所以$\lim_{x\rightarrow x_{0}}f(\varphi (x))=f(\lim_{x\rightarrow x_0}\varphi(x))$
* $y=x^a=e^{\ln x^a}=e^{a\ln x}$由$y=e^u,u=a\ln x$复合的$u=a\ln x$在$x$上连续,而$y=x^u$在$R$上连续,则复合函数也是连续的,(负数也是成立的),因此该函数在定义域内每一点都是连续的

**因此基本初等函数在定义域都是连续的**

* 初等函数在**区间**上的每一点都是连续的

例:$y=\sqrt{\cos x -1}$由$y=\sqrt{u}$与$u=\cos -1$都是连续,经过一次复合得到,由定义域

$$
\left\{\begin{array}{c}\cos x-1\geq 0\\ \cos x\leq 1\end{array}\right.\Rightarrow \cos x=1, x=2k\pi, k\in Z
$$

,定义域为${x:x=2k\pi ,k\in Z}$,$y=\sqrt{\cos x-1}$在定义域内每一点都是不连续的

例:$\lim _{x\rightarrow x_0}\frac{1+e^{x^2}+ \sqrt{1+x^2}}{\sin x^2+\cos x +1}$的连续性:

初等函数连续性(**$f(x_0)=\lim_{x\rightarrow x_0}f(x)$**),原式=

$$
\begin{array}{c}\frac{1+1+1}{2}\end{array}
$$


例:$\lim_{x\rightarrow 0}=\frac{\tan x-\sin x}{\sin x^3}$(首先注意加减的等家两不能直接替换)

原式=

$$
\lim _{x\rightarrow 0}\frac{\tan x(1-\cos x)}{x^3}=\lim _{x\rightarrow 0}=\frac{x\times \frac{1}{2}x^2}{x^3}=\frac{1}{2}
$$


原式=$\lim_{x\rightarrow 0}=\lim_{x\rightarrow 0}\frac{\sin x(\frac{1}{\cos x-1})}{x^3 \cos x}$

> *注意:等价量的替换必须保证是因式,并且需要一次性替换*

* 如果$f(x)$在开区间$(a,b)$内每一点都连续,(双侧连续),成$f(x)$在开区间$(a,b)$内连续,如果$f(x)$在开区间$(a,b)$内连续,在$x=a$右连续,在$x=b$处左连续,那么即称为在闭区间$[a,b]$上连续,如果$f(x)$在区间$I$上连续,在$I$上的曲线称为连续曲线
* 闭区间连续函数的性质
  * 最大值和最小值定理:若$f(x)\in C[a,b]$(连续),则$f(x)$在区间上一定能取到最大值$M$,最小值$m$,$\exists x_{1},x_{2} \in [a,b],f(x_1)=M,f(x_2)=m,\forall x\in [a,b],m\leq f(x)\leq M$
    * $f(x)$在$[a,b]$上有界
    * 若$f(x)\in C[a,b]$,值域就是$R(f)=[m,M]$(**确界定理**)
    * (零点定理,根的存在性定理)若$f(x)\in [a,b]$且$f(a)f(b)<0$,则至少存在一点$\eta$,使得$f(\eta)=0$
    * (介值定理)若$f(x)\in C[a,b]$且$f(a)\neq f(b)$,对于介于$f(a),f(b)$之间的任何一个$C$则存在一点$\eta\in (a,b),f(\eta)=C$
      * 要证明,只要证明$g(x)=f(x)-C=0$有一个根成立,由$g(x)\in [a,b]$,不妨设$f(a)<C<f(b)$,$g(a)=f(a)-C$,$g(b)=f(b)-C>0$,由于根的存在性定理,存在...
      * **根的存在性定理是等价于介值定理的**

例:证明$x-\varepsilon \sin x=1,(0<\varepsilon <1)$仅有一个实根:

$$
x-\varepsilon \sin x=1 \Rightarrow x-\varepsilon \sin x-1=0
$$

设$f(x)=x-\varepsilon \sin x-1,x \in R$,basic function contines everywhere,firstly,$f(0)=-1$,$f(2)=s-\varepsilon \sin 2-1$,$f(x)\in [0,2]$,so from threorem ,$\exists \eta \in (0,2)\in R$let $f(\eta)=0$

comsume $x_1,x_2\in R$ and $x_1<x_2$,we have $x_1-\varepsilon \sin x_1=1$and $x_2-\varepsilon \sin x_2=1$,use the first munus the second ,we get $|x_2-x_1|=|\varepsilon (\sin x_1-\sin x_2)|=\varepsilon |2\cos \frac{x_1+x_2}{2} \sin \frac{ x_1-x_2}{2}|\leq 2\varepsilon |\sin \frac{x_1-x_2}{2}|<2\varepsilon \frac{x_1-x2}{2}$,so we got the conflict that the $\varepsilon$'s bound is not correct

# Some essential  equivalent infinitesimals and their common states

1. $\lim _{x \rightarrow 0}\frac{\sin x}{x}=1$
2. $\lim_{x\rightarrow 0}{(1+x)^{\frac{1}{x}}}=e$
3. $\lim _{x\rightarrow 0}\frac{\tan x}{x}=1$
4. $\lim_{ x\rightarrow_0}\frac{1-\cos x}{x^2}=\frac{1}{2}$
5. $\lim_{x\rightarrow 0}\frac{\ln(1+x)}{x}$
   1. $\lim _{x\rightarrow x_0}\ln (1+x)^{\frac{1}{x}}=\ln \lim _{x\rightarrow x_0}(1+x)^{\frac{1}{x}}=\ln e=1$
6. $\lim _{x\rightarrow x_0}\frac{e^x-1}{x}\overset{e^x-1=u}{=}\lim _{x\rightarrow 0}=\lim _{u\rightarrow 0}\frac{u}{\ln (1+u)}=1$

如果$x\rightarrow x_0$由$f(x)\rightarrow 0$,$\lim _{x\rightarrow x_0} \frac{e^{f(x)}-1}{f(x)}=1,e^{f(x)}-1 \sim x$
7. $\lim _{x\rightarrow 0} \frac{a^x-1}{x}(a>0,a\neq 1.constant)=\lim _{x\rightarrow 0}\frac{e^{x\ln a}-1}{x}=\lim _{x\rightarrow 0}\ln a=\ln a$
8. $\lim _{x\rightarrow 0}\frac{(1+x)^a-1}{x}(a\neq 0,chanstant)=\lim_{x\rightarrow 0}=\lim_{x\rightarrow 0}\frac{x^{a\ln (1+x)}-1}{x}=\lim_{x\rightarrow 0}=\frac{a\ln(1+x)}{x}=a$,(a=0)结论也成立
9. $\lim _{x\rightarrow x_0}u(x)=a>0(constant),\lim _{x\rightarrow x_0}v(x)=b(constant),\Rightarrow \lim_{x\rightarrow x_0}u(x)^{v(x)}=a^b$(幂指函数)=$$
  =\lim_{x\rightarrow x_0}e^{\ln u(x)^{v(x)}}=\lim_{x\rightarrow x_0}e^{v(x)\ln u(x)}=(\text{如果内函数的极限存在})e^{\lim_{x\rightarrow x_0}v(x)\ln u(x)}=e^{\lim _{x\rightarrow x_0}v(x)\lim_{x\rightarrow x_0}\ln u(x)}=e^{b\ln a} =a^{b}

$$
极限确实存在推得的式子是成立
10. $\lim _{x\rightarrow 0}\frac{\arccos{x}}{x}\overset{\arccos{x}=t}{=}\lim_{x\rightarrow 0}\frac{t}{\sin t}=\lim_{t\rightarrow 0}\frac{t}{t}=1$ 
11. $\lim_{x\rightarrow 0}\frac{\arctan x}{x}=\overset{\arctan x=t}{=}\lim_{t\rightarrow 0}\frac{t}{\tan t}=1$

# 重要极限的一般形式



若$x\rightarrow x_0$时,有$f(x)\rightarrow x_0$,$\lim_{x\rightarrow x_0}\frac{\sin f(x)}{f(x)}=1$,$\lim_{x\rightarrow x_0}\frac{\ln(1+f(x))}{f(x)}=1$,$\lim_{x\rightarrow x_0}\frac{e^{f(x)}-1}{f(x)}=1$,$\lim_{x\rightarrow x_{0}}\frac{(1+f(x))^a-1}{f(x)}=a$,$\lim_{x\rightarrow x_0}[1+f(x)]^{\frac{1}{f(x)}}=e$

#重要的等价无穷小量

$x\rightarrow 0$
1. $ \sin x\sim x $ 
2. $\ln (1+x)\sim  x$
3. $1-\cos x\sim \frac{1}{2}x^2$
4. $\tan x\sim x$
5. $e^x-1\sim x$
6. $a^x-1\sim x\ln a(a\neq 1)$
7. $(1+x)^{a}-1\sim ax(a\neq 0)$
8. $\arcsin x\sim x$
9. $\arctan x \sim x$

若$x\rightarrow x_0$,有$f(x)\rightarrow  0$,则
* $\sin f(x)\sim f(x)$
* $\ln(1+f(x))\sim f(x)$
* $e^{f(x)}-1\sim f(x)$
* $a^{f(x)}-1\sim f(x)\ln a(a\neq 1)$
* $(1=f(x))^a-1\sim af(x)(a\neq 0)$
* $1-\cos f(x)\sim \frac{1}{2}f^2(x)$


* 例:
$$

  \lim_{x\rightarrow 0}\frac{\sin \frac{x^5}{\sqrt{1+x^2+x^5}}\arctan(\sin x^2)}{(e^{x^2}-1)(\sqrt[100]{1+x^5}-1)}

$$
首先不能直接带入,函数在$x=0$点没有定义(不连续)
$$

  =\lim_{x\rightarrow 0}\frac{\frac{x^5}{\sqrt{1+x^2+x^5}}x^2}{x^2 \frac{1}{100}x^5}((1+x)^\frac{1}{100}-1\sim \frac{1}{100}x^5)=100\lim_{x\rightarrow 0}\frac{1}{\sqrt{1+x^2+x^5}}=100

$$
* 例:
$$

\begin{array}{c}
  \lim_{x\rightarrow 0}(\frac{a^x+b^x+c^x}{3})(a>0,b>0,c>0,\text{常数})\overset{1^\infty}{=}\lim _{x\rightarrow 0}[1+(\frac{a^x+b^x+c^x}{3}-1)]^{\frac{1}{(\frac{a^x+b^x+c^x}{3}-1)}*\frac{1}{x}(a^x+b^x+c^x)/3}(\text{在计算中验证指数确实是常数})= \\
  e^{\lim_{x\rightarrow 0}\frac{(\frac{a^x+b^x+c^x}{3}-1)}{x}}=\\
  e^{\lim_{x\rightarrow 0}\frac{1}{3}(\frac{a^x-1}{x}+\frac{b^x-1}{x}+\frac{c^x-1}{x})}=\\
  e^{\frac{1}{3}(\ln a+\ln b+\ln c)}=(abc)^{\frac{1}{3}}=\sqrt[3]{abc}
\end{array}

$$


$$

  \begin{array}{c}
  =\lim_{x\rightarrowtail 0}e^{\frac{1}{x}\ln (\frac{a^x+b^x+c^x}{3})}(\text{假设指数是常数})=\\
  e^{\lim_{x\rightarrow 0}\frac{1}{x}\ln(\frac{a^x+b^x+c^x}{3})}(\text{假设外函数连续,内函数极限存在内外极限可以交换顺序})\overset{\infty\times 0}{=}e^{\lim_{x\rightarrow 0}\frac{1}{x}\ln[1+(\frac{a^x+b^x+c^x}{3}-1)]}
  \end{array}

$$
(1) $\lim [f(x) \pm g(x)]=\lim f(x) \pm \lim g(x)=A \pm B$; .
(2) $\lim [f(x) \cdot g(x)]=\lim f(x) \cdot \lim g(x)=A \cdot B$;
(3) 若又有 $B \neq 0$, 则
$$

\lim \frac{f(x)}{g(x)}=\frac{\lim f(x)}{\lim g(x)}=\frac{A}{B} .

$$


$$
