# Series

# justice the convergence of a series using the characters of the convergence series

* example: $\sum_{n=1}^{\infty}(-1)^{n}$ :
  $$
      n=2m,\lim_{n \rightarrow \infty}u_{2m}=\lim_{n\rightarrow \infty}(-1)=-1\\
      n=2m+1,\lim_{n \rightarrow \infty}u_{2m+1}=\lim_{n\rightarrow \infty}(1)=1\\
      1\neq -1
  $$ 
  according to the characters forth's lemma, the series is divergence.
* example: $\sum_{n=1}^{\infty}\sqrt[n]{n}$:
  $$
      \lim_{n \rightarrow \infty}\sqrt[n]{n}=1\neq 0
  $$  
  according to the characters forth's lemma, the series is divergence.
* example: $\sum_{n=1}^{\infty}(-1)^{n}n ^{2}$:
  $$
      \lim_{n \rightarrow \infty}|(-1)^{n}n^{2}|=+\infty\\
      \Rightarrow \lim_{n \rightarrow \infty}(-1)n^{2}=\infty\\
      \Rightarrow \lim_{n \rightarrow \infty}(-1)^{n}n^{2}\exists     
  $$  
  according to the characters forth, the series is divergence.
* example: $\sum_{n=1}^{\infty}(-1)^{n-1}$:
  $$
      =1-1+1-1+\dots+\dots\\
      \neq (1-1)+(1-1)+\dots
  $$  
  the series is divergence, but we canont add any brackets in a divergence series, or we may get a new convergence series.**this is the converse example of the character second**.

but if $u_n \geq 0$,we call the $\sum_{n=1}^{\infty}u_n$ is a *positive terms series*, if we use the character second on the positive terms series, the anti-proposition is also correct.

# Sepcial series' convergence justicement methods

the most common method of justicing a convergence of a series is the **Cauchy's convergence theorem**
## the methods of justicing a positive terms series




di zeng |* definition : if the $u_n\geq 0,n=1,2,3,\dots$, we call $\sum_{n=1}^{\infty}u_n$ is a **positive terms series**
* the increasing monotonic character of a positive terms series: 
  $$
      S_{n+1}=u_1+u_2+\dots+u_n+u_{n+1}\\
      \geq u_1+u+2+\dots+u_n=S_n
  $$   
  so the $\left\{S_n\right\}$  is a increasing monotonic sequence.
* **the adding condition to the increasing monotonic series making the series convergence**: the $\left\{S_n\right\}$ has a upper boundary:
  $$
      \forall n\in N,S_n\leq M,M\text{ is a constant}
  $$ 
  with this condition, the series is convergence.
* the anti-proposition: if the $\sum_{n =1}^{\infty}u_n$ is convergence, $\Rightarrow \lim_{n \rightarrow \infty}S_n(\exists)=S$
* (proof is a increasing monotonic sequence has a limitation, so the every terms in the sequence is smaller than its limitation value:)
  $$
      S_n=u_1+u_2+\dots+u_n\\
      \leq u_1+u_2+\dots+u_n+u_{n+1}+\dots=\sum_{n=1}^{\infty}u_n=S 
  $$   
according to the analysis above, we get a necessary and sufficient condition of a convergence of a positive terms series;
* **if the $\sum_{n=1}^{\infty} u_n$ is a positive monotic series,the $\sum_{n=1}^{\infty} u_n$'s convergence character's necessary and sufficient condition is $\left\{S_n\right\}$  has a upper boundary.**
*  theorem (comparative methods): if $\sum_{n=1}^{\\infty}u_n,\sum_{n=1}^{\infty} v_n$ are all positive terms' series, and the  $\forall n \in N,u_n\leq v_n$
   1. if $\sum_{n=1}^{\infty}v_n$ is convergence, the $\sum_{n=1}^{\infty}u_n$ is also convergence
   2. if $\sum_{n=1}^{\infty}u_n$ is divergence, the $\sum_{n=1}^{\infty}v_n$ is also divergence, the anti-proposition is incorrect.
* proof: 
  $$
      \sum_{n=1}^{\infty}v_n \text{ is convergence}\Rightarrow \text{we consume the} \sum_{n=1}^{n}v_n=B_n\\
      \text{according to the theorem above: }\exists M>0,\forall n\in N,B_n \leq M\\
      \text{we consume the }\sum_{n=1}^{n}u_n=A_n\\
      A_n=u_1+u_2+\dots+u_n\leq v_1+v_2+\dots+v_n=B_n\leq M 
  $$   
* the anti-proposition's inverse example:
  $$
      \frac{1}{n^{2} }\leq \frac{1}{n},n=1,2,\dots\\
      \sum_{n=1}^{\infty} \frac{1}{n^{2} } \text{ is convergence , but} \sum_{n=1}^{\infty}v_n \text{ is divergence}
  $$ 
*  use the second character of the convergence series: 
   $$
      \exists N , n> N, u_n\leq v_n
   $$ 
   the conclusion is also correct.