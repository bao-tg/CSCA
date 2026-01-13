## Calculus

> [!Note] What Is Calculus?  
> **Calculus** studies **change** and **accumulation**.
> 
> It has two main branches:
> - **Differential calculus** → rates of change (derivatives)  
> - **Integral calculus** → accumulation and area (integrals)

---

## Limits

> [!Note] Limit  
> The **limit** of a function $f(x)$ as $x$ approaches $a$ is the value that $f(x)$ gets
> close to.
> 
> Notation:
> $$
> \lim_{x\to a} f(x)
> $$

---

> [!Note] One-Sided Limits  
> - Left-hand limit:
>   $$
>   \lim_{x\to a^-} f(x)
>   $$
> - Right-hand limit:
>   $$
>   \lim_{x\to a^+} f(x)
>   $$

> [!Note] Existence of a Limit  
> $$
> \lim_{x\to a} f(x) \text{ exists }
> \iff
> \lim_{x\to a^-} f(x)=\lim_{x\to a^+} f(x)
> $$

---

> [!Note] Basic Limit Rules  
> If limits exist:
> - $\lim(f+g)=\lim f+\lim g$  
> - $\lim(cf)=c\lim f$  
> - $\lim(fg)=(\lim f)(\lim g)$  
> - $\lim \frac{f}{g}=\frac{\lim f}{\lim g}$ if $\lim g\ne0$

---

> [!Note] Important Example  
> $$
> \lim_{x\to2}(x^2-4)=0
> $$
> even though $x^2-4=0$ only at $x=2$.

---

## Derivatives

> [!Note] Derivative (Definition)  
> The **derivative** of $f(x)$ at $x=a$ is
> $$
> f'(a)=\lim_{h\to0}\frac{f(a+h)-f(a)}{h}
> $$

> [!Note] Meaning of the Derivative  
> - Slope of the tangent line  
> - Instantaneous rate of change  
> - Velocity if $f(x)$ is position

---

> [!Note] Basic Derivative Rules  

| Function | Derivative |
|--------|------------|
| $c$ | $0$ |
| $x^n$ | $nx^{n-1}$ |
| $cf(x)$ | $cf'(x)$ |
| $f(x)+g(x)$ | $f'(x)+g'(x)$ |

---

> [!Note] Common Derivatives  

| Function | Derivative |
|--------|------------|
| $x$ | $1$ |
| $x^2$ | $2x$ |
| $\sqrt{x}$ | $\frac{1}{2\sqrt{x}}$ |
| $\frac{1}{x}$ | $-\frac{1}{x^2}$ |

---

> [!Note] Example  
> Find the derivative of
> $$
> f(x)=3x^2-5x+1
> $$
> $$
> f'(x)=6x-5
> $$

---

> [!Note] Tangent Line  
> Equation of the tangent line to $y=f(x)$ at $x=a$:
> $$
> y-f(a)=f'(a)(x-a)
> $$

---

## Applications of Derivatives

> [!Note] Increasing and Decreasing Functions  
> - $f'(x)>0$ → increasing  
> - $f'(x)<0$ → decreasing  

---

> [!Note] Maxima and Minima  
> A **critical point** satisfies:
> $$
> f'(x)=0 \text{ or undefined}
> $$

> [!Note] Insight  
> Maximum or minimum values often occur at **critical points** or **endpoints**.

---

## Integrals

> [!Note] Indefinite Integral  
> An **indefinite integral** is the reverse of differentiation.
> 
> Notation:
> $$
> \int f(x)\,dx
> $$

---

> [!Note] Basic Integral Rules  

| Function | Integral |
|--------|----------|
| $x^n$ | $\frac{x^{n+1}}{n+1}+C$ ($n\ne-1$) |
| $\frac{1}{x}$ | $\ln|x|+C$ |
| $cf(x)$ | $c\int f(x)\,dx$ |

---

> [!Note] Example  
> $$
> \int (4x^3-2x)\,dx
> $$
> $$
> =x^4-x^2+C
> $$

---

> [!Note] Definite Integral  
> The **definite integral** represents **area**:
> $$
> \int_a^b f(x)\,dx
> $$

---

> [!Note] Fundamental Theorem of Calculus  
> If $F'(x)=f(x)$, then
> $$
> \int_a^b f(x)\,dx=F(b)-F(a)
> $$

---

> [!Note] Example  
> $$
> \int_0^2 x^2\,dx
> $$
> $$
> =\left[\frac{x^3}{3}\right]_0^2=\frac{8}{3}
> $$

---

## Summary Table

| Concept | Meaning |
|------|--------|
| Limit | Behavior near a point |
| Derivative | Rate of change |
| Integral | Accumulated change |
| Tangent | Instantaneous linear approximation |

---

> [!Note] Problem-Solving Insights — Calculus  
> - Simplify before taking limits.  
> - Use derivatives to analyze graphs.  
> - Always add **$+C$** for indefinite integrals.  
> - Draw a graph to understand meaning.

---

> [!Note] Additional Problems — Calculus  
> 1. Evaluate $\lim_{x\to3}(2x-1)$.  
> 2. Find the derivative of $f(x)=x^3-4x$.  
> 3. Find the equation of the tangent line to $y=x^2$ at $x=1$.  
> 4. Determine where $f(x)=x^2-2x$ has a minimum.  
> 5. Compute $\int_1^3 (2x+1)\,dx$.

---
