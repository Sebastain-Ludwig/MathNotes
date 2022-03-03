
# A equation function's derivative function

* **definition**: consume the formula $F(x,y)=0$,$D,C$ all is nonempty real number set,$\forall x_0\in D,F(x,y)=0$,if the equation has the only $y_0\in C$,which make the formula established. In other word,$F(x_0,y_{0})=0,y_0\in C$. According to the definition of the function,we get a function defined on $D$,we symbolize the function as $y=y(x)$ *we call this function is determined by the equation $F$*

* **problem:** 

  1. how to get the derivative of the function determined by the $F$?

  2. how to get the explicit function from the implicit function(we call the expression of the $f(x)$ as a explicit function ,and the $F(x,y)=0$ as implicit function)?
     $$
     y^{3}-x^{3}=1\\
     \text{determine the function }y(x)\\
     y(x)=\sqrt[3]{1+x^{3}},x\in R
     $$
     the $y=y(x)$ satisfy the equation :$(\sqrt[3]{1+x^{3}})-x^{3}=1$, *the equation is satisfied everywhere on the defined section. if $F(x,y)=0$ determines the expression $y=y(x)$, but if the expression $y=y(x)$ cannot bet get from the equation,we call the function as the absolutely implicit function of the equation*.
     $$
     y-xe^{x}=1\\
     \text{the function can not be explicited from the equation}
     $$
     the formula always establish for 
     $$
     y(x)-xe^{x} \equiv 1,x\in D
     $$

  ## the law of derivating a implicit function

* Both of sides of the equation derivated for variate $x$:
  $$
  y^{'}(x)-1e^{y(x)}-xe^{y(x)}y^{'}(x)=0\\
  (1-xe^{y(x)})y^{'}(x)=e^{y(x)}
  y^{'}=\frac{e^{y(x)}}{1-xe^{y(x)}}
  $$

* **A practical method:**
  $$
  y^{'}-e^{y}-xe^{y}y^{'}=0
  $$
  the $\left. \frac{\mathrm{d} y}{\mathrm{d}x }\right|_{x=0}$?
  $$
  y-0e^{y}=1\Rightarrow y=1\\
  \text{replace the value of }x,y
  $$

* application: a point on the curve is $(0,1)$,the tangent we get is $y-1=ex$,and the normal is $y-1=-\frac{1}{e}x$,the second order derivative is $\frac{\mathrm{d}^{2} y}{\mathrm{d} x^{2}}=(\frac{\mathrm{d} y}{\mathrm{d}x })^{'}$

* the higher derivative of the equation format : we always use the format of the equation's derivative to get the higher derivative directly 
  $$
  y^{'}-e^{y}-xe^{y}y^{'}=0\\
  \text{the second order derivative is : }y^{''}-e^{y}y^{'}-e^{y'}y^{'}-x(e^{y}y^{'}y^{'}+e^{y}y^{''})=0
  $$
   from the example we can get the format of the higher derivative directly.**this kind of format is convenient for us to get a point's derivative's value.**

* example :
  $$
    y=f(x,y),y^{''}? f\text{ is second order serivable}\\
    \text{the function is about the variate }x,y=y(x)\\
    \text{the both side of the function derivated for the variate y: }y^{'}=f^{'}(x+y)(1+y)^{'}\Rightarrow y^{'}=f^{'}(1+y^{'} )\\
    \text{ the format of } y^{'}=(1+y^{'} )f^{'} \text{will not be misunderstood}\\
    (1-f^{'})y^{'} =f^{'} \\
    y^{'}=\frac{f^{'} }{1-f^{'} } \\
    y^{''}=\frac{f^{''}(1+y^{'})(1-f^{'} ) +f^{'}f^{''}(1+y^{'} )   }{(1-f^{'} )^{2} } \text{ accodrding to the } y^{'}=\frac{f^{'} }{1-f^{'} }\\
    \text{simplify the format getting the answer} 
  $$ 

* **A new mathod**: $ y=x^{\sin x}   $,$ y^{'}  $?
  $$
    \text{this is a new method ,but this is not a new example:}\\
    \ln y=\sin x\ln x\\
    \text{the both sides of the formula derivated for variate }x\text{: }\\
    \frac{1}{y}y^{'}=\cos x\ln x+\frac{\sin x}{x}\\
    y^{'}=y\cos x\ln x+y\frac{\sin x}{x}
  $$ 
  the method is **logarithmic differentiation**
  
  * a example: $y=\frac{(\ln x)^{x} }{x^{\ln x} }$
    $$
      \ln y=\ln (\ln(\ln x)^{x}-\ln x^{\ln x}  )\\
      \ln y=x\ln \ln x-(\ln x)^{2} \\
      \text{both sides derivate for variate }x\text{ : }\\
      \frac{1}{y}y^{'}=\ln \ln x+x \frac{1}{\ln x}\frac{1}{x}-2 \frac{\ln x}{x} \\
      y^{'}=y[\ln\ln y+\frac{1}{\ln x}-\frac{2\ln x}{x}] 
    $$ 

  * $y=\frac{\sqrt[3]{3x+1}x^{2} }{\sqrt{2x+1}\sqrt[3]{1-5x}}$,$y^{'} $?
    $$
      \ln y=\frac{1}{3}\ln(3x+1)+2\ln x-\frac{1}{2}\ln (2x+1)-\frac{1}{3}\ln(1-5x)\\
      \frac{1}{y}y^{'}=\frac{1}{3}\frac{1}{3x+1}+2\frac{1}{x}-\frac{1}{2}\frac{1}{2x+1}-\frac{1}{3}\frac{1}{1-5x}\\
      y^{'}= y(\frac{1}{3}\frac{1}{3x+1}+2\frac{1}{x}-\frac{1}{2}\frac{1}{2x+1}-\frac{1}{3}\frac{1}{1-5x} )\\
      \text{transfer the }y \text{as the function of variate }x \text{ will get the answer}
    $$ 
    this method's sweet point is tranforming the multiply-divide to the culculation of add-substract.**Attention : the definition section of the function**.

  * example: $y=\frac{a}{b}^{x}\frac{x}{b}^{x}\frac{a}{x}^{b} (a>0,b>0,a,b\text{ is constant},x>0)  $,$ y^{'}  $ ?
    $$
      \ln y=x(\ln b -\ln a)+a(\ln x-\ln b)+b(\ln a-\ln x)\\
      \frac{1}{y}y^{'}=(\ln b -\ln a)+a \frac{1}{x}- b\frac{1}{x}\\
      y^{'}=y(\ln b -\ln a)+a\frac{y}{x}-b\frac{y}{x}\\
      \text{tranfer the variate } y \text{ the format of }y(x)\\
      \text{we will get the answer.}  
    $$ 
  * example: $ a^{2}x+b^{2}y^{2}=1    $ ,$y^{'} $?
    $$
      2a^{2} x+2b^{2}yy^{'}=0 \\
      y^{'}=-2a^{2}\frac{x}{2b^{2}y }   
    $$  
