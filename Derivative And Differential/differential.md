# differential

* if $y=f(x)$ is derivable at the point $ x $ ,as the definition of the derivative $ \lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}=f^{'} (x)\Leftrightarrow \frac{\Delta y}{\Delta x}=f^{'}(x)+\alpha \Leftrightarrow \Delta y=f^{'}(x)\Delta x+ \alpha \Delta x   $ 
  $$
      \lim_{\Delta x\rightarrow 0}\frac{\alpha \Delta x}{\Delta x}=\lim_{\Delta x\rightarrow 0}\alpha \lim_{\Delta x \rightarrow 0}\frac{\Delta x}{\Delta x}=0\times 1=0
  $$ 
  **so the $ \alpha \Delta x $ is the higher orider derivative of the $\Delta x$**, giving the symbol:$ \alpha \Delta x=O(\Delta x),(\Delta x\rightarrow 0\Leftrightarrow f^{'}(x)\Delta x+ o(\Delta x) (\Delta x\rightarrow 0)$ 
  this means whnen the $ |\Delta x| $ is little, the $ o(\Delta x)| $ is more little.  

* use the common style : 
  $$
      \Delta y \approx f^{'}(x)\Delta x
  $$ 

* **Definition**: there is a function $ y=f(x) $ ,if $ \Delta y=f(x+\Delta x-x)-f(x) $,it can be symbolized by $ \Delta y=A\Delta x+o(\Delta x) (\Delta x\rightarrow 0)$,in the formula $ A $ is isolated with the variate $ \Delta x $  ,which is called function $ y=f(x) $  is differentiable at point $ x $ , or *the linear main part of the formula :$ A\Delta x $ is the function $ f(x) $*'s **differential** ,the symbol of the form is:
  $$
    \mathrm{d}y=A\mathrm{d}x
  $$ 

* **threorem**: the differential's exition necessary and sufficient condition is the function is derivable at point $ x $ and the coeffienct $A=f^{'}(x) $ 
  * **proof**: the sufficient condition is easy to get,the necessary condition(differentiable $\rightarrow$ derivable):
    $$
      f(x)\text{is differentiable at point }x\text{ form the definition:} \\
      \Delta y=A\Delta x+o(\Delta x),(\Delta x\rightarrow 0)\\
      \text{so the }\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\Delta x}=\lim_{\Delta x\rightarrow 0}[A\Delta+\frac{o(\Delta x)}{\Delta x}]=A+0=f^{'}(x)\\
      \text{so we know the function is derivable, and the derivative function is }f^{'}(x)  
    $$ 

  * **practical method:** if the function is differenrial at point $x$,($x$ is the independent variate),$ \mathrm{d}y=f^{'}(x)\Delta x  $,or $ \mathrm{d} f(x)=f^{'} \Delta x$  ,from the condition that $y=x$ is derivative on the point $x$,$\Leftrightarrow x$ is differentiable on the point $x$:
    $$
      \mathrm{d}x=(x)^{'} \Delta x=\Delta x
    $$
    so the independent variate's differential is itself. so the 
    $$
      \mathrm{d}y=f^{'} (x)\Delta x=f^{'}(x)\mathrm{d}x 
    $$ 
    so the derivative form of divide :
    $$
      \frac{\mathrm{d}y}{\mathrm{dx}}=f^{'}(x) 
    $$ 
    **so the divide of differential of $x$ and $y$ is the derivative function,** whicih is called *decivative divide*

  * example: $y=e^{\sqrt{1+x^{2} }} $,$\mathrm{d}y$?
    $$
      y^{'}=e^{\sqrt{1+x^{2} }}\frac{1}{2}\frac{1}{\sqrt{1+x^{2} }}2x\\
      \mathrm{d}y=y^{'} \mathrm{d}x=e^{\sqrt{1+x^{2} }}\frac{1}{2}\frac{1}{\sqrt{1+x^{2} }}2x\mathrm{d}x  
    $$ 
    the function is differentiable on the definition section.
    $\left.\mathrm{d}y\right|_{x=1}$
    $$
      =e^{\sqrt{2}}\frac{1}{\sqrt{2}}\mathrm{d}x 
    $$ 
    **$\mathrm{d}x$ is a symbol!**
    $\left.\mathrm{d}y\right|_{x=1,\mathrm{\Delta}x=2}$
    $$
      \mathrm{d}y=2e^{\sqrt{2}}\frac{1}{\sqrt{2}} 
    $$ 

## the differential of basic elementary fucntion

1. $\mathrm{d}(x^{a} )=ax^{a-1}\mathrm{d}x  $
2. $ \mathrm{d}a^{x}=a^{x}\ln a \mathrm{d}x   $
3. $\mathrm{d}(e^{x} )=e^{x}\mathrm{d}x $
4. $\dots$

## the law of differential 

function $u(x),v(x)$ both are differentiable
1. $ \mathrm{d}(u \pm v)=du \pm dv $ 
2. $d(Cu)=Cdu$
3. $ d(uv)=udv+vdu $ 
4. $ d(\frac{u}{v})= \frac{vdu-udv}{v^{2} } ,(v\neq 0)$ 

## invariance of first order differential form

* if $y=f(x)$ is differentiable ,and the independent variate is $x$:
  $$
    \mathrm{d}y=f^{'}(x)\mathrm{d}x\\
    \mathrm{d}f(x)=f^{'}(x)\mathrm{d}x  
  $$ 
  if $y=f(x)$,$x=\varphi(t)$ both are differentiable ,$\Rightarrow y=f(\varphi(t))$ is differentiable ($f(x)$ is derivable,$\varphi (t)$ is derivable,so on the difinition section,$f(\varphi(t))$ is derivable and differentiable),$t$ is the independent variate:
  $$
    \mathrm{d}y=[f(\varphi(t))]^{'}\mathrm{d}t\\
    \Rightarrow \mathrm{d}(f(\varphi(t)))=f^{'}(x)\varphi^{'} (t)\mathrm{d}t=f^{'}(x)\mathrm{d}(\varphi(t)    )\\
    \Rightarrow x=\varphi(t)\\
    \mathrm{d}f(x)=f^{'}(x)\mathrm{d}x 
  $$ 
  the form is still established

* **so whatever the $x$ is which function's variate,the form of $\mathrm{d}(f(x))=f^{'}(x) \mathrm{d}x$ is always established**,*this is the inavariance of the first order didderential*
* if $\mathrm{d}y=g(u)\mathrm{d}u=\mathrm{d}f(u)$,so $f^{'}(u)=g(u)$,or $\frac{\mathrm{d}y}{\mathrm{d}u}=g(u)=f^{'}(u) $
* example :$y=e^{\sqrt{1+x^{2} }} $,$\mathrm{d}y?$
  $$
    dy=de^{\sqrt{1+x^{2} }} ,\sqrt{1+x^{2} }=u\\
    =e^{\sqrt{1+x^{2} }}d\sqrt{1+x^{2} } =e^{\sqrt{1+x^{2} }}\frac{1}{2\sqrt{1+x^{2} }} d(1+x^{2} )\\
    =e^{\sqrt{1+x^{2} }}\frac{1}{2\sqrt{1+x^{2} }}[d1+d(x^{2} )]=e^{\sqrt{1+x^{2} }}\frac{1}{2\sqrt{1+x^{2} }}d(x^{2} )\\
    =e^{\sqrt{1+x^{2} }}\frac{x}{\sqrt{1+x^{2} }}dx\\
    y^{'}=\dots    
  $$ 

* if we know the differential,how to get the function:
  $$
    \mathrm{d}y=e^{\sqrt{1+x^{2} }}\frac{x}{\sqrt{1+x^{2} }}dx(=y^{'}dx )\\
    dy=e^{\sqrt{1+x^{2} }}\frac{x}{\sqrt{1+x^{2} }}dx\\
    =e^{\sqrt{1+x^{2} }}\frac{1}{2\sqrt{1+x^{2} }}d(x^{2} )=\\
    e^{\sqrt{1+x^{2} }}\frac{1}{2\sqrt{1+x^{2} }}d(1+x^{2} )=\\
    e^{\sqrt{1+x^{2} }}d(\sqrt{1+x^{2} })(\sqrt{1+x^{2} }=u)=d(e^{\sqrt{1+x^{2} }} +C)     
  $$ 

* example: $y^{'}=\frac{\ln x}{x} $,$y$?
  $$
    dy=\frac{\ln x}{x}dx=\ln xd(\ln x) =[\frac{1}{2} (\ln x)^{2}+C]dx 
  $$ 
  
## A significant conclusion

* if $y=f(x)$ is differentiable on the point $x$:
  $$
    \Delta y=A\Delta x+o(\Delta x),(\Delta x\rightarrow 0)=\\
    f^{'}(x)\Delta x+o(\Delta x)=\\
    f^{'}(x)\mathrm{d}x+o(\Delta x)=\\
    \mathrm{d}y+o(\Delta x)  
  $$ 
  when $|\Delta|$ is small enough:
  $$
    \Delta \approx \mathrm{d}y
  $$ 
  if $f^{'}(x)\neq 0 $,$\lim_{\Delta x\rightarrow 0}\frac{\Delta y}{\mathrm{d}y}=\lim_{\Delta x\rightarrow 0} \frac{f^{'}(x)\Delta x+o(\Delta x) }{f^{'}(x)\Delta x }=\lim_{\Delta \rightarrow 0}[1+\frac{1}{f^{'}(x)}\frac{o(\Delta x)}{\Delta x} ]=1$
  ****
  $$
    \Delta x\rightarrow 0,\Delta y \sim \mathrm{d}y
  $$ 
  ****
  *$dy$si the $\Delta y$'s "Best approximation"*,if we want to get $\Delta y=f(x_0+\Delta x)-f(x_0)\approx f^{'}(x_0)\Delta x,(\Delta x \text{ is small})$:
  $$
    \Rightarrow f(x_0+\Delta x)\approx f(x_0)+f^{'}(x_0) 
  $$ 

* lemma: when $|x|$is small ,$f(x)=f(0+x)\approx f(0)+f^{'}(0)x $
* the above method is for approximation caculation.
* **we can use the to get the equaliant estimal**: 
  $$
    \text{when }|x|\text{ is small}:(1+x)^{a}-1\sim ax\\
    (1+x)^{a}-1\approx ax  
  $$