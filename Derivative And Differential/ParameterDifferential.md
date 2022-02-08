# 参数方程确定$y=y(x)$的导数

* 若$\left\{\begin{array}{l}x=\varphi(t)\\y=\psi(t)\end{array}\right.$,确定$y=y(x)$,求$\frac{\mathrm{d}y}{\mathrm{d}x}$?(利用微分形式的导数和微分形式的不变形求得参数方程确定函数的导数)
  $$
    \frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\frac{\mathrm{d}y}{\mathrm{d}t}}{\frac{\mathrm{d}x}{\mathrm{d}t}}=\frac{\varphi^{'}(t) }{\psi^{'}(t) }    
  $$ 
  若两个关于变量$t$的导数存在且$\psi^{'}(t) \neq 0$,则$\frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\psi^{'}(t) }{\varphi^{'}(t) }$,或者
  $$
      \frac{\mathrm{d}y}{\mathrm{d}x}=(\frac{\mathrm{d}\varphi(t)}{\mathrm{d}\psi(t)}=\frac{\varphi^{'}(t)\mathrm{d}t }{\psi^{'}(t)\mathrm{d}t })=\frac{\varphi^{'}(t) }{\psi^{'}(t) }
  $$ 

* 例: $\left\{\begin{array}{l}x=f^{'}(t)\\y=f(t)-tf^{'} (t) \end{array}\right.$,$f^{''}(t) $存在,$f^{''} (t)\neq 0$,求$\frac{\mathrm{d}^{3}y}{\mathrm{d}x^{3} }$
  $$
      \frac{\mathrm{d}y}{\mathrm{d}x}=\frac{f^{'}(t)-f^{'}(t)-tf^{''}(t)   }{f^{''}(t) }=-t\\
      y^{''}=-t\\
      \frac{\mathrm{d}^{2}y }{\mathrm{d}x^{2}} =\frac{\mathrm{d}y^{'} }{\mathrm{d}x}=\frac{\frac{\mathrm{d}y^{'} }{\mathrm{d}t}}{\frac{\mathrm{d}x}{\mathrm{d}t}}=\frac{-1}{f^{''}(t) } \\
      \frac{\mathrm{d}^{3}y }{\mathrm{d}x^{3} }=\frac{\mathrm{d}y^{''} }{\mathrm{d}x}=\frac{f^{'''}(t) }{[f^{''}(t) ]^{3} }
  $$ 

* 例: $\left\{\begin{array}{l}x=\ln(1+t^{2} )\\y=t-\arctan t\end{array}\right.$,$\frac{\mathrm{d}^{2} y}{\mathrm{d}x^{2} }$?
  $$
      \frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\mathrm{d}(\ln(1+t^{2} ))}{\mathrm{d}(t-\arctan t)}=\frac{1-\frac{1}{1+t^{2} }}{\frac{2t}{1+t^{2} }\mathrm{d}t}=\frac{t}{2}\\
      \frac{\mathrm{d}^{2} y}{\mathrm{d}x^{2} }=\frac{\frac{1}{2}}{\frac{2t}{1+t^{2} }}=\frac{1+t^{2} }{4t}
  $$ 