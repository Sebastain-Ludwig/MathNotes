# Higher derivative

* if $f(x)$ defines on the section $I$,the function's derivative function on $I$ is also derivable which is $[(f(x))^{'}]^{'}\Rightarrow f^{''}(x)$,$(y^{'})^{'}=y^{''}=\frac{d^{2}y}{dx^{2}}$

  * **the symbol explanation:**
    $$
    y^{''}=(y^{'})^{'}=\frac{d}{dx}y^{'}=\frac{\mathrm{d} }{\mathrm{d} x}(\frac{\mathrm{d} y}{\mathrm{d} x})\overset{\Delta}{=}\frac{\mathrm{d} ^{2}}{\mathrm{d} x^{2}}(y)\\
    (\mathrm{d} x^{2})=\mathrm{d} x\mathrm{d} x=(\mathrm{d} x)^{2}\neq \mathrm{d} (x^{2})=2x\mathrm{d} x
    $$
    the symbols above are called $f(x)$'s *second order derivative function*.

  * **lemma**: if function $f(x)$ defined on section $I$ exists a $n$th order derivative function,which is written as 
  $$
    y^{\overset{\text{number n}}{'\dots ''}}=y^{(n)}=f^{n}(x)=\frac{\mathrm{d}^{n}y }{\mathrm{d}  x^{n}}=\frac{\mathrm{d} }{\mathrm{d}x }(\frac{\mathrm{d} ^{n-1}y}{\mathrm{d} x^{n-1}})
    $$

  when the $n>1$,we call the expression as higher derivative,especially
  $$
  y^{0}=y
  $$

## some basic elementary functions' $n$th order derivative

1. $y=a^{x}$ :
   $$
   y^{'}=a^{x}\ln a\\
   y^{''}=a^{x}(\ln a)^{2}\\
   \dots\\
   y^{(n)}=a^{x}(\ln a)^{n}
   $$

   1. $y=e^{x}$
      $$
      y^{(n)}=e^{x}
      $$

   

2. $y=x^{a},(a\neq 0,constant)$
   $$
   y^{'}=ax^{a-1}\\
   y^{''}=a(a-1)x^{a-2}\\
   \dots\\
   y^{(n)}=\left\{\begin{array}{cc}\frac{a!}{n!}x^{a-n}&a> n\\0&a\leq n\end{array}\right.
   $$

   1. $(x^{n})^{(n)}=n!$
   2. $(x^{n})^{(m)}=0,(n,m\in N,M>N)$

3. $y=\ln x$:
   $$
   y^{'}=\frac{1}{x}\\
   y^{''}=-\frac{1}{x^{2}}\\
   y^{'''}=2\frac{1}{x^{3}}\\
   \dots\\
   y^{n}=(-1)^{n}(n-1)!\frac{1}{x^{n}}
   $$

4. $y=\sin x$;
  $$
  y^{'}=\cos x\\
  y^{''}=-\sin x\\
  y^{(3)}=-\cos x\\
  \dots\\
  y^{n}=\left\{
  \begin{array}{c}
  \cos x&n=4k+1\\
  -\sin x& n=4K+2\\
  -\cos x & n=4k+3 \\
  \sin x & n=4k 
  \end{array}
  y= \sin(x+n\frac{\pi}{2})
  \right.
  $$
  
## higher derivative function  Algorithm

* if the $nth$ derivative function of $u(x),v(x)$ all is exists ,so the $(u\pm v)^{(n)}=u^{(n)}+v^{(n)}$

* $(uv)^{(n)}=C^{0}_{n}u^{(n)}v^{(0)}+C_{n}^{1}u^{(n-1)}v^{(1)}+\dots +C_{n}^{n}u^{(0)}v^{(n)},(C_{n}^{k}+C_{n}^{k+1}=C_{n+1}^{k+1})$

  * if one of $u(x),v(x)$ derivate for some times ,and after the calculation the derivative function is zero,the other item has the $n$th order derivative function ,this time we use the formula can simpily the calculation.

  * **example**: $y^{(n)}=(e^{x}x^{2})^{(n)}=C_{n}^{0}e^{x}2x+C_{n}^{2}e^{x}2=e^{x}(x^{2}+2nx+x(n-1)),(n\geq 2,n=1\text{the formula is also established})$



