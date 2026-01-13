## Probability and Statistics

> [!Note] Probability & Statistics  
> **Probability** studies randomness and uncertainty.  
> **Statistics** analyzes data and random phenomena.
> 
> They are fundamental for science, engineering, economics, and AI.

---

## Random Variables

> [!Note] Random Variable  
> A **random variable** is a function that assigns a real number to each outcome
> of a random experiment.
> 
> Types:
> - **Discrete random variable** (countable values)
> - **Continuous random variable** (values in intervals)

---

> [!Note] Examples  
> - Tossing a coin:  
>   $$
>   X=
>   \begin{cases}
>   1 & \text{Head}\\
>   0 & \text{Tail}
>   \end{cases}
>   $$
> - Measuring height (continuous)

---

> [!Note] Probability Distribution  
> - Discrete: **Probability mass function (PMF)**  
>   $$
>   P(X=x)
>   $$
> - Continuous: **Probability density function (PDF)**  
>   $$
>   f(x)\ge0,\quad \int_{-\infty}^{\infty}f(x)\,dx=1
>   $$

---

## Expected Value

> [!Note] Expected Value (Mean)  
> The **expected value** of a random variable $X$ is its long-run average value.
> 
> - Discrete:
>   $$
>   \mathbb{E}[X]=\sum xP(X=x)
>   $$
> - Continuous:
>   $$
>   \mathbb{E}[X]=\int_{-\infty}^{\infty}x f(x)\,dx
>   $$

---

> [!Note] Linearity of Expectation  
> For random variables $X,Y$ and constants $a,b$:
> $$
> \mathbb{E}[aX+bY]=a\mathbb{E}[X]+b\mathbb{E}[Y]
> $$
> 
> This holds **without independence**.

---

## Variance and Standard Deviation

> [!Note] Variance  
> The **variance** measures how spread out a random variable is:
> $$
> \mathrm{Var}(X)=\mathbb{E}[(X-\mu)^2]
> $$
> where $\mu=\mathbb{E}[X]$.

---

> [!Note] Useful Formula  
> $$
> \mathrm{Var}(X)=\mathbb{E}[X^2]-\big(\mathbb{E}[X]\big)^2
> $$

---

> [!Note] Standard Deviation  
> The **standard deviation** is:
> $$
> \sigma=\sqrt{\mathrm{Var}(X)}
> $$

---

> [!Note] Variance — Linearity Properties  
> - $\mathrm{Var}(aX)=a^2\mathrm{Var}(X)$  
> - $\mathrm{Var}(aX+b)=a^2\mathrm{Var}(X)$  
> - If $X,Y$ are independent:
>   $$
>   \mathrm{Var}(X+Y)=\mathrm{Var}(X)+\mathrm{Var}(Y)
>   $$

---

## Normal Distribution

> [!Note] Normal Distribution  
> A random variable $X$ follows a **normal distribution** if its PDF is:
> $$
> f(x)=\frac{1}{\sqrt{2\pi}\sigma}
> e^{-\frac{(x-\mu)^2}{2\sigma^2}}
> $$
> 
> Notation:
> $$
> X\sim\mathcal{N}(\mu,\sigma^2)
> $$

---

> [!Note] Symmetry of the Normal Curve  
> - The curve is **symmetric about $x=\mu$**  
> - Mean = median = mode  
> - Areas on both sides of $\mu$ are equal:
>   $$
>   P(X\le\mu-a)=P(X\ge\mu+a)
>   $$

---

> [!Note] Empirical Rule (68–95–99.7 Rule)  

| Interval | Probability |
|--------|-------------|
| $\mu\pm\sigma$ | $\approx68\%$ |
| $\mu\pm2\sigma$ | $\approx95\%$ |
| $\mu\pm3\sigma$ | $\approx99.7\%$ |

---

> [!Note] Standard Normal Distribution  
> If $Z=\frac{X-\mu}{\sigma}$, then
> $$
> Z\sim\mathcal{N}(0,1)
> $$

---

## Counting Techniques

> [!Note] Fundamental Counting Principle  
> If a process has:
> - $m$ choices for step 1  
> - $n$ choices for step 2  
> 
> then total outcomes:
> $$
> m\times n
> $$

---

> [!Note] Factorial  
> $$
> n!=n(n-1)(n-2)\cdots1,\quad 0!=1
> $$

---

> [!Note] Permutations  
> Number of ways to arrange $r$ objects from $n$:
> $$
> P(n,r)=\frac{n!}{(n-r)!}
> $$

---

> [!Note] Combinations  
> Number of ways to choose $r$ objects from $n$:
> $$
> C(n,r)=\binom{n}{r}=\frac{n!}{r!(n-r)!}
> $$

---

> [!Note] Insight — Permutation vs Combination  
> - **Permutation:** order matters  
> - **Combination:** order does not matter

---

> [!Note] Problem-Solving Insights — Probability & Statistics  
> - Identify whether variables are discrete or continuous.  
> - Use symmetry to simplify normal distribution problems.  
> - Expectation is linear; variance is **not** fully linear.  
> - Decide early whether **order matters** in counting.

---

> [!Note] Additional Problems — Probability & Statistics  
> 1. A fair die is rolled. Define a random variable and find its expected value.  
> 2. If $X\sim\mathcal{N}(50,10^2)$, find $P(40<X<60)$.  
> 3. Find $\mathbb{E}[3X-5]$ if $\mathbb{E}[X]=4$.  
> 4. Compute the variance of $X$ where $P(X=0)=P(X=2)=\frac12$.  
> 5. How many ways can 4 students be chosen from 10?

---
