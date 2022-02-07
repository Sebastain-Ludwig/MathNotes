# The law of solvating derivative function

If a inverse function has a derivative function,here are the conditions we can consume:

* $\varphi^{'}(y)\neq 0$

* $\varphi(y)$ is a strictly monotonic function

## law of derivative inverse functions



if $f(x)$'s inverse function exits,and the inverse function  is $\varphi(y)$ is strictly monotonic function,and $\varphi(y)\neq 0$ ,the  $f^{'}(x)=\frac{1}{\varphi^{'}(y)}$ or $\frac{dy}{dx}=\frac{1}{\frac{dy}{dx}}$

* **proof**:

$$
\varphi^{'}(y)\exists,\text{from the derivetive function's definition}\\
\lim_{\Delta y\rightarrow 0}\frac{\Delta x}{\Delta y}()=\varphi^{'}(y)\\
\Rightarrow \lim_{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x}=\lim_{\Delta x\rightarrow}\frac{1}{\frac{\Delta x}{\Delta y}}\\
\text{(Because the inverse function is stictly monotonic}\\
\text{so the function is also stictly monotonic)}\\

(\Delta x\rightarrow 0,\Delta x\neq 0)\\
(\Rightarrow x-x_{0}\neq 0\Rightarrow x\neq x_0)\\
(\Rightarrow f(x)-f(x_0)\neq 0)\\
(\Rightarrow f(x+\Delta x)-f(x)\neq 0)\\
(\Rightarrow \Delta y\neq 0)\\
\text{from the condition }x=\varphi (y)  \text{is derivable and continuous}\\
\text{the function }f(x)\text{is also derivable and continuous}\lim_{\Delta x\rightarrow 0}\Delta y=0\\
\lim_{\Delta x\rightarrow 0}\frac{\Delta x}{\Delta y}=\lim_{\Delta y\rightarrow 0}=\frac{1}{\frac{\Delta y}{\Delta x}}=\frac{1}{\varphi^{'}(y)}=f^{'}(x)
$$

* **explanation**: the $\Delta x\rightarrow 0,\Delta x\neq 0$,for  a strictly monotonic function ,the function value has the same tendency $\Delta y\rightarrow 0,\Delta y\neq 0$
* **format**: the other format of the law :$\frac{dy}{dx}=\frac{1}{\frac{dx}{dy}}$.
* **conditions** : the inverse function is derivable and strictly monotonic function and the derivative function value can't be zero

## inverse trigonometric function's derivative  function

1. $y=\arcsin x,x\in[1,-1]$: inverse function $x=\sin y,y\in[-\frac{\pi}{2},\frac{\pi}{2}]$, this is a strictly monotonic function,$\sin^{'}y=\cos y\neq 0,x\in[-\frac{\pi}{2},\frac{\pi}{2}]$,so the function $y=\arcsin x$ is derivable function on the section$[-1,1]$,$(\arcsin x)^{'}=\frac{1}{(\sin y)^{'}}=\frac{1}{\cos y}=\frac{1}{\sqrt{1-\sin^{2} y}}=\frac{1}{\sqrt{1-x^{2}}},x\in(-1,1)$,**the section's boundary is underivable**
2. $y=\arccos x,x\in[-1,1]$: $y^{'}=-\frac{1}{\sqrt{1-x^{2}}},x\in(-1,1)$,**the boundary of the section is underivable**
3. $y=\arctan x,x\in (-\infty,\infty)$: the function's inverse function is $x=\tan y,y\in (-\frac{\pi}{2},\frac{\pi}{2})$,the inverse function is strictly monotonic and derivable and it's derivative function is $x^{'}=\sec^2 y\neq0$,so the function $f(x)$ is derivable on the definition section and $y^{'}=\frac{1}{\sec^2 y}=\frac{1}{(1+\tan y)^{2}}=\frac{1}{1+x^2},x\in R$,**this function is derivable on the R**
4. $y=\arccot x,x\in R$: $(\arccot x)^{'}=-\frac{1}{1+x^2},x\in R$

* the every points of basic elementary function in the definition section is continuous, but maybe the boundary of the definition section is underivable .
* How to remember the plus and minus before the derivative function: the co* is minus ,and the * is plus.
* All basic elementary functions' derivative function has shown upon.

## The elementary functions' derivative functions 

### Composite functions' derivative functions

* Analysis: $y=f(u),u=\varphi(x)$can composite a function :$y=f(\varphi(x))$,which conditions we can add in order to make the composite function derivable for the variate $x$, in other words the $\frac{dy}{dx}$ exists.

* Consumption:  

  *  $\frac{dy}{du}$,$\frac{du}{dx}$  exists.
  * $\frac{dy}{dx}=\frac{dy}{du}\frac{du}{dx}$

* **theorem**: (the derivative function of a composite function existence theorem)if $u=\varphi(x)$is derivable for variate x,and $y=f(u)$is derivable for variate $u$,the composite function $y=f(\varphi(x))$ is derivable for the variate x,and 
  $$
  \frac{\mathrm{d}y}{\mathrm{d}x}=\frac{dy}{du}\frac{du}{dx}
  $$
  the theorem is called **chain rule**
  $$
  f([\varphi (x)])^{'}=f^{'}(u)\times \varphi^{'}(x)\\
  =f^{'}(\varphi(x))\times \varphi^{'}(x)
  $$
  

~~~mermaid
graph LR;
x -->u-->y
~~~

* explanation: the $[f(\varphi(x))]^{'}$is the derivative of the composite function,$f^{'}(\varphi(x))$is the derivative of the $f(u)$

* **proof**: 
  $$
  \text{the function }f^{'}(x) \text{ exists},\lim_{\Delta u\rightarrow 0 }\frac{\Delta y}{\Delta u}=f^{'}(u)\\
  \text{the function } \varphi^{'}(x) \text{ exits},\lim_{\Delta x\rightarrow 0}\frac{\Delta u}{\Delta x}=\varphi^{'}(x)\\
  \lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}=\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta u}\frac{\Delta u}{\Delta x}\\
  (u=\varphi(x) \text{is devirable,so the function is continuous},\lim_{\Delta x\rightarrow 0}\Delta u=0)\\
  =\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta u}\frac{\Delta u}{\Delta x}=\lim_{\Delta u\rightarrow 0}\frac{\Delta y}{\Delta u}\times \lim_{\Delta x\rightarrow 0} \frac{\Delta u}{\Delta x}\\
  =f^{'}(u)\times \varphi^{'}(x)\\
  (\Delta u\neq 0)??
  $$
  *the correct proof*
  $$
  \text{the function }f^{'}(x) \text{ exists},\lim_{\Delta u\rightarrow 0 }\frac{\Delta y}{\Delta u}=f^{'}(u)\\
  \text{the function } \varphi^{'}(x) \text{ exits},\lim_{\Delta x\rightarrow 0}\frac{\Delta u}{\Delta x}=\varphi^{'}(x)\\
  (\text{if function}\lim_{x\rightarrow x_0}f(x)=A\Rightarrow f(x)=A+\alpha,(\lim_{x\rightarrow x_0}\alpha=0))\\
  \Leftrightarrow \frac{\Delta y}{\Delta u}=f^{'}(u)\\
  \lim_{u \rightarrow 0}  f^{'}(u) = f^{'}(u)+\alpha, \lim_{\Delta  u \rightarrow 0}  ,\alpha=0 \Delta  u\neq 0\\
  \Leftrightarrow \Delta y =f^{'}(u)\Delta u + \Delta  u\alpha\\
  \text{so the limition of the derivative function of}f(x): \lim_{\Delta x \rightarrow 0} \frac{\Delta  y}{\Delta  x}= \lim_{\Delta x \rightarrow 0} =\frac{f^{'}(u)\Delta  u+\alpha \Delta u}{\Delta x}\\
  \Rightarrow \lim_{\Delta x \rightarrow 0}[f^{'}(u)\frac{\Delta  u}{\Delta  x}+\alpha \frac{\Delta  u}{\Delta x}](\text{Here is an added condition: When }\Delta u=0,\alpha =0,\text{and the formula is still established})\\
  =f^{'}(u)\varphi^{'}(x)+ \lim_{\Delta x \rightarrow 0}\alpha \lim_{\Delta x \rightarrow 0} \frac{\Delta  u}{\Delta x}(\text{the }\Delta  u\text{ can be zero})\\
  =f^{'}(u)\varphi^{'}(x)+ 0\varphi^{'}(x)=f ^{'}(u)\varphi^{'}(x)=[f(\varphi(x))]^{'}
  $$
  
* the proof's explanation: the $\Delta  u$ 's definition is somehow not necessary, if we can guarantee the second item is zero ,the proof will be strict.

* **lemma**: the following functions are all derivable functions :$y=f(u),u=\varphi(v),v=g(x)$,so the derivative function of the outer function is $\{f[\varphi(g(x))]\}^{'}=f^{'}(u)\varphi^{'}(v)g^{'}(x)$ existing. **If an outer function has limit qualities of inner functions and inner functions' derivative functions all exist,the chain rule will give the outer functions' derivative function**.(mathematical induction)

* examples:

  * $y=e^{\cos^{2}\frac{1}{x}}$,the $y^{'}$?
    $$
    y=e^{u},u=v ^{2}v,v=\cos w,w=\frac{1}{x}\\
    \text{chain rule:} \frac{dy}{dx}=\frac{dy}{du}\frac{du}{dv}\frac{dv}{dw}\frac{dw}{dx}\\
    y^{'}=e^{u}2v(-\sin w)(-\frac{1}{x^{2}})=e^{\cos^{2}\frac{1}{x^{2}}}2\cos \frac{1}{x}(-\sin \frac{1}{x})(-\frac{1}{x^{2}})  
    $$
    *the second method,repeat the two composite functions' chain rule*
    $$
    y^{'}=e^{\cos ^{2}\frac{1}{x^{2}}}2\cos^{2}\frac{1}{x^{2}}(-\sin \frac{1}{x})(-\frac{1}{x^{2}})
    $$

  

  * $y=\ln |x|$,the $y^{'}$?
    $$
    \text{when }x>0,(\ln |x|)^{'}=(\ln x)^{'}=\frac{1}{x}\\
    \text{when }x<0,(\ln |x|)^{'}=(\ln -x)^{'}=\frac{1}{-x}(-1)=\frac{1}{x}\\
    (\ln |x|)^{'}=\frac{1}{x}
    $$

  * $y=\ln|3x+1|$,$y^{'}$?
    $$
    y=\frac{3}{3x+1}
    $$
    **We cannot use  the regard part as a elementary function in chain rule!**
  
  * $y=\ln (x+\sqrt{x^2+a^2}),(a>0)$,$y^{'}$?
    $$
    y^{'}=\frac{1}{x+\sqrt{x^2+a^{2}}}[1+\frac{2x}{2\sqrt{x^{2}+a^{2}}}]=\frac{1}{x+\sqrt{x^2+a^{2}}}[1+\frac{x}{\sqrt{x^{2}+a^{2}}}]=\\
    \frac{1}{\sqrt{x^{2}+a^{2}}}
    $$
    **when we want to know whose indefinite integral is the function ,we should use this conduction.** 
  
  * $y=\ln|x+\sqrt{x^{2}-a^{2}}|,(a>0)$,$y^{'}$?
    $$
    y^{'}=\frac{1}{x+\sqrt{x^{2}+a^{2}}}(1+\frac{1}{2\sqrt{x^{2}-a^{2}}}2x)=\\
    \frac{1}{\sqrt{x^{2}-a^{2}}}
    $$
    **when we want to know whose indefinite integral is the function ,we should use this conduction.** 
  
  * $y=x^{\sin  x}$,$y^{'}$?
    $$
    \text{Firstly we should transfer the function to an elementary conposite function}\\
    y=e^{\sin x\ln x}\\
    y^{'}=e^{\sin x\ln x}(\sin x \frac{1}{x}+\cos x \ln x)
    $$
    **Here the basic elementary function is not a exponential function, so we only can use the chain rule on composition of the basic elementary functions** 
  
  * $y^{'}=e^{|x^{3}|}$,$y^{'}$
    $$
    y=\left\{ \begin{array}{cc}e^{-x^{3}}&x\leq 0\\ e^{x^{3}} & x>0\end{array}\right.\\
    y^{'}=\left\{ \begin{array}{cc}e^{-x^{3}}(-3x^{2})&x< 0\\ e^{x^{3}}(3x^{2}) & x>0\end{array}\right.\\
    \text{The boundary point is special,the point only has a right derivative: } \lim_{x \rightarrow 0^+}  \frac{f(x)-f(0)}{x-0}= \lim_{x \rightarrow 0^+}\frac{e^{x^{3}}-1}{x}=\lim_{x \rightarrow 0^+}  \frac{-x^{3}}{x}=0\\
    y^{'}=\left\{ \begin{array}{cc}e^{-x^{3}}(-3x^{2})&x\leq 0\\ e^{x^{3}}(3x^{2}) & x>0\end{array}\right.
    $$
    
  
  * $f(x)=\left\{\begin{array}{cc}\frac{\sin x}{x}&x\neq 0\\1&x=0\end{array}\right.$,$y^{'}$?
    $$
    \text{This is a special function, we should garuntee the both sides of boundary points exist}
    $$
    

