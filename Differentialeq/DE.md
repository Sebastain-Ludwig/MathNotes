# Differential  equation

* introduction: if we know a curve ,a point on the curve's tangent line's slope minus the x-axis is $2$ ,and the curve crosses the point $(0,1)$, what is the equation of the curve?
  * we consume the equation of the curve is : $y=f(x)$ 
  * the any points on the curve is $(x,y)$ 
  * from the conditions: $y^{'}-x^{2} =2$
  * the curve's equation satisfies : $y| _{x=0}=1$   
  * so : $\Rightarrow y^{'} =2+x^{2}$
  * so : $\Rightarrow y=\int (2+x^{2}) \mathrm{d}x$ 
  * the indefinite integral is :  $y=2x+\frac{1}{3}x^{3} +C$
  * $C=1$
* introduction: in experiment, we get the conclusion: on the process of droping a object,the resistance from the air is not zero.Now we consume that the original speed of a droping is zero,what is the speed of $t$?$v(t)$ 
  * we consume we have : $f=kv(t)$ , $k$ is a constant
  * according to Newton's second law: $F=mg-kv(t)=ma=m\frac{\mathrm{d}v(t)}{\mathrm{d}t}$ 
  * $m\frac{\mathrm{d}v}{\mathrm{d}t}+kv=mg,v|_{t=0} =0$
  * this is a *first order linear differential equation*

every  ordinary differential eqautions can be converted to one sepecial kind of equations ,which have a commomn method or a formula to solve the equation, the last step should be a indefinite integral.

In practical usage, we always want to know the inner process using law or theorem to establish a formula with derivative and function , the formula with only one variate we call them oridinary differential equations.

## definition

*  a fomula has derivatives(at least one) and functions with only one variate
*  examples:
   *  $y^{'} =0$
   *  $x^{2}+y^{2}  =R^{2}$ is not 
   *  $y^{''} +y^{'}+1=0$
   *  $x\mathrm{d}y+2y\mathrm{d}x=0$    
   *  $\frac{\mathrm{d}^{2} y}{\mathrm{d}x^{2} }+x=0$
* the commomn form:
  $$
      F(x,y, y^{'} ,y^{''},\dots,y^{(n)}  )=0
  $$  
*  the formula is a expression of $x,y,\mathrm{d}xm\mathrm{d}y$ 
*  the order of an ordinary equation: the highest order of the derivative in the formula 
*  if a function makes the formula established, it is called the solution of the equation.
*  if we get all of the solutions of the equation, we call it *general solution*
*  **if a funtion is the solution of $n$ order equation, in the solutions have $n$  dependent coefficient constant,the function must be the general solution**
*  example:a solution of a third order equation:
  $$
      y=C_1 x+c_2+2C_3
  $$ 
  the funtion only has two dependent constant coefficients,the function is not the general solution of the equation.
* if we get some solutions satisfying some special conditions, this kind of solutions we call *speciall solution*
* the special conditions we call *solution fixing conditions*
* getting a special solution of a $n$ order equation ,we need $n$ fixing conditions

# First order ordinary 
  
* forms: 
  $$
      F(x,y,y^{'} )=0\\
      F(x,y,\frac{\mathrm{d}y}{\mathrm{d}x})=0
  $$ 

## variate depart ordinary equation

* form:
  $$
      g(y)\mathrm{d}y=f(x)\mathrm{d}x
  $$ 
* the general solution : 
  $$
      \int g(y)\mathrm{d}y=\int f(x)\mathrm{d}x(+C)
  $$ 
* proof:
  $$
      \text{may as well consume : } y=y(x)\\
      g(y)\mathrm{d}y=f(x)\mathrm{d}x\\
      \Leftrightarrow g(y(x))\mathrm{d}y(x)=f(x)\mathrm{d}x\\
      \Leftrightarrow g(y(x) ) y^{'}(x) \mathrm{d}x=f(x)\mathrm{d}x\\
      \Leftrightarrow g(y(x))y^{'}(x) =f(x)\\
      \Leftrightarrow \int g(y(x))y^{'}(x) \mathrm{d}x=\int f(x)\mathrm{d}x\\
      \Leftrightarrow \int g(y(x))y^{'}(x) \mathrm{d}x+C_1=\int f(x)\mathrm{d}x+c_2
      \Leftrightarrow \int g(y)\mathrm{d}y=\int f(x)\mathrm{d}x+C_2-C_1\\
      (C=C_2-C_1)
  $$ 
* example: $y^{2} \mathrm{d}y=x^{3} \mathrm{d}x$:
  $$
      \int y^{2}\mathrm{d}y =\int x^{3}\mathrm{d}x+C \\
      \frac{1}{3}y^{3}=\frac{1}{4} x^{4} +C\\
      y=(\frac{3}{4}x^{4} +3C)^{\frac{1}{3}} 
  $$  
  **the $y=y(x)$ has no necessity to observe**:wacky
