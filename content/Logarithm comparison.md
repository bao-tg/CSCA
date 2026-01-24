**Date:** 05-01-26

## 11. Logarithm Comparison Techniques

> [!Note] Monotonicity of Logarithms  
> Let $a>1$.  
> The logarithmic function
> $$
> f(x)=\log_a x
> $$
> is **strictly increasing** on $(0,+\infty)$.
> 
> Therefore,
> $$
> \log_a x < \log_a y \iff x<y \quad (x,y>0).
> $$

> [!Note] Problem-Solving Insights — Monotonicity  
> - When logarithms have the **same base**, compare their arguments directly.  
> - Always check domain conditions ($x>0$).

> [!Note] Additional Problems — Monotonicity  
> 1. Compare $\log(3x-1)$ and $\log(2x+5)$.  
> 2. Solve $\log_2(x+1)>\log_2(3-x)$.

---

> [!Note] Change of Base Technique  
> For $a,b>0$, $a\neq1$, $b\neq1$,
> $$
> \log_a x=\frac{\log x}{\log a}.
> $$

> [!Note] Key Observation — Change of Base  
> - The sign of $\log x$ matters:
>   - $x>1 \Rightarrow \log x>0$
>   - $0<x<1 \Rightarrow \log x<0$

> [!Note] Problem-Solving Insights — Change of Base  
> - Inequalities may **reverse direction** depending on the sign of $\log x$.  
> - Split into cases when necessary.

> [!Note] Additional Problems — Change of Base  
> 1. Compare $\log_2 x$ and $\log_3 x$.  
> 2. Find all $x$ such that $\log_5 x>\log_2 x$.

Example:

> [!Example] Comparing $\log_2 5$ and $\log_4 9$
> 
> **Step 1: Use change of base**  
> Rewrite $\log_4 9$ in base $2$:
> $$
> \log_4 9=\frac{\log_2 9}{\log_2 4}=\frac{\log_2 9}{2}.
> $$
> 
> **Step 2: Compare using the same base**
> $$
> \log_2 5 \;\; \text{vs.} \;\; \frac{\log_2 9}{2}.
> $$
> Multiply both sides by $2>0$:
> $$
> 2\log_2 5 \;\; \text{vs.} \;\; \log_2 9.
> $$
> 
> **Step 3: Use logarithm properties**
> $$
> 2\log_2 5=\log_2 5^2=\log_2 25.
> $$
> 
> Now compare:
> $$
> \log_2 25 \;\; \text{vs.} \;\; \log_2 9.
> $$
> 
> **Step 4: Apply monotonicity**
> Since $\log_2 x$ is increasing,
> $$
> 25>9 \Rightarrow \log_2 25>\log_2 9.
> $$
> 
> **Conclusion:**
> $$
> \boxed{\log_2 5 > \log_4 9.}
> $$


---

> [!Note] Exponentiation Method  
> If $a>1$ and
> $$
> \log_a f(x) < \log_a g(x),
> $$
> then
> $$
> f(x)<g(x),
> $$
> provided
> $$
> f(x)>0,\quad g(x)>0.
> $$

> [!Note] Problem-Solving Insights — Exponentiation  
> - Valid only for **same-base** logarithms.  
> - Check positivity before exponentiating.

> [!Note] Additional Problems — Exponentiation  
> 1. Solve $\log(x^2+1)<\log(3x+5)$.  
> 2. Compare $\log(2x)$ and $\log(x^2)$.

---

> [!Note] Logarithmic Simplification  
> Use logarithmic identities:
> $$
> \log(ab)=\log a+\log b
> $$
> $$
> \log\left(\frac{a}{b}\right)=\log a-\log b
> $$
> $$
> \log(a^k)=k\log a
> $$

> [!Note] Problem-Solving Insights — Simplification  
> - Simplify before comparing.  
> - Reduce expressions to multiples of $\log x$ when possible.

> [!Note] Additional Problems — Simplification  
> 1. Compare $\log(n^2)$ and $\log(n\log n)$.  
> 2. Determine which grows faster: $\log n$ or $\log\log n$.

---

> [!Note] Asymptotic Log Comparison  
> For large $n$,
> $$
> \log n \ll n^\alpha \ll a^n \quad (\alpha>0,\ a>1).
> $$

> [!Note] Growth Hierarchy  
> $$
> \log\log n \ll \log n \ll n \ll n\log n \ll n^2 \ll 2^n
> $$

> [!Note] Problem-Solving Insights — Asymptotics  
> - Logarithms grow slower than any power of $n$.  
> - Use hierarchy rules instead of exact values.

> [!Note] Additional Problems — Asymptotics  
> 1. Compare $\log n$ and $\sqrt{n}$.  
> 2. Compare $\log(n!)$ and $n\log n$.

---

