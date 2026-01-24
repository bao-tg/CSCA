**Date:** 05-01-26

## 14. Inverse Function

> [!Note] Inverse Function — Definition  
> Let $f: A \to B$ be a function.
> 
> The function $f$ is said to be **invertible** if for every $y\in B$ there exists **exactly one** $x\in A$ such that
> $$
> f(x)=y.
> $$
> 
> The inverse function of $f$ is denoted by $f^{-1}$ and satisfies
> $$
> f^{-1}(y)=x \iff f(x)=y.
> $$

---

> [!Note] Domain and Range — Inverse Functions  
> If $f$ is invertible, then:
> 
> - $\mathrm{Dom}(f^{-1})=\mathrm{Ran}(f)$  
> - $\mathrm{Ran}(f^{-1})=\mathrm{Dom}(f)$
> 
> In other words, **domain and range are swapped**.

---

> [!Note] One-to-One Condition (Injective)  
> A function $f$ has an inverse **if and only if** it is **one-to-one**:
> $$
> f(x_1)=f(x_2)\Rightarrow x_1=x_2.
> $$

> [!Note] Graphical Interpretation  
> - A function is invertible if every horizontal line intersects its graph **at most once**.  
> - The graph of $f^{-1}$ is the reflection of the graph of $f$ across the line
> $$
> y=x.
> $$

---

> [!Example] Example 1 — Finding an Inverse Function  
> Find the inverse of
> $$
> f(x)=2x-3.
> $$

**Solution:**

Step 1: Write $y=2x-3$.

Step 2: Swap $x$ and $y$:
$$
x=2y-3.
$$

Step 3: Solve for $y$:
$$
2y=x+3
$$
$$
y=\frac{x+3}{2}.
$$

**Inverse function:**
$$
\boxed{f^{-1}(x)=\frac{x+3}{2}}
$$

---

> [!Example] Example 2 — Inverse of a Quadratic (with Restriction)  
> Consider
> $$
> f(x)=x^2.
> $$

**Solution:**

Step 1: Observe that $f(x)=x^2$ is **not one-to-one** on $\mathbb{R}$.

Step 2: Restrict the domain:
$$
x\ge0.
$$

Step 3: Write $y=x^2$, swap variables:
$$
x=y^2.
$$

Step 4: Solve for $y$:
$$
y=\sqrt{x}.
$$

**Inverse function (with restriction):**
$$
\boxed{f^{-1}(x)=\sqrt{x}},\quad x\ge0.
$$

---

> [!Example] Example 3 — Domain and Range of an Inverse  
> Let
> $$
> f(x)=\ln x.
> $$

**Solution:**

Domain of $f$:
$$
(0,+\infty).
$$

Range of $f$:
$$
\mathbb{R}.
$$

Thus:

- Domain of $f^{-1}$ is $\mathbb{R}$
- Range of $f^{-1}$ is $(0,+\infty)$

Since $f^{-1}(x)=e^x$, this matches the result.

---

> [!Example] Example 4 — Verifying an Inverse  
> Verify that
> $$
> f(x)=\frac{1}{x}, \quad x\neq0
> $$
> is its own inverse.

**Solution:**

Compute composition:
$$
f(f(x))=\frac{1}{\frac{1}{x}}=x.
$$

Thus:
$$
f^{-1}(x)=f(x).
$$

---

> [!Note] Properties — Inverse Functions  
> - $f(f^{-1}(x))=x$ for all $x$ in $\mathrm{Dom}(f^{-1})$  
> - $f^{-1}(f(x))=x$ for all $x$ in $\mathrm{Dom}(f)$  
> - $(f^{-1})^{-1}=f$

---

> [!Note] Problem-Solving Strategy — Inverse Functions  
> 1. Check if the function is one-to-one.  
> 2. Restrict the domain if necessary.  
> 3. Replace $f(x)$ with $y$.  
> 4. Swap $x$ and $y$.  
> 5. Solve for $y$.  
> 6. State domain and range clearly.

---

> [!Note] Common Mistakes — Inverse Functions  
> - Forgetting to restrict the domain  
> - Confusing $f^{-1}(x)$ with $\frac{1}{f(x)}$  
> - Ignoring domain and range conditions

---

> [!Note] Additional Problems — Inverse Functions  
> 1. Find the inverse of $f(x)=3x+7$.  
> 2. Find the inverse of $f(x)=x^3$.  
> 3. Determine whether $f(x)=x^4$ is invertible on $\mathbb{R}$.  
> 4. Find the inverse of $f(x)=\ln(x-2)$.
