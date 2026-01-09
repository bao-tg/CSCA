---
share_link: https://share.note.sx/f1f7odx9#UxM93MLWpjmCOWT+zBjh5koa+m6RzNQfM4gtay0Vq/o
share_updated: 2026-01-09T17:04:57+07:00
---
Date: 09/01/2026
## Series

> [!Note] Sequence  
> A **sequence** is an ordered list of numbers, usually written as
> $$
> a_1, a_2, a_3, \dots, a_n, \dots
> $$
> where $a_n$ is the **$n$-th term**.
> 
> Common notation:
> - $\{a_n\}_{n=1}^\infty$: an infinite sequence  
> - $\{a_n\}_{n=1}^N$: a finite sequence

---

> [!Note] Series  
> A **series** is the sum of the terms of a sequence.
> 
> - **Finite series:**
>   $$
>   a_1+a_2+\cdots+a_n
>   $$
> - **Infinite series:**
>   $$
>   \sum_{n=1}^{\infty} a_n
>   $$

---

> [!Note] Sigma Notation  
> The symbol $\sum$ (sigma) represents summation.
> 
> Example:
> $$
> \sum_{k=1}^{5} k = 1+2+3+4+5
> $$

---

> [!Note] Arithmetic Sequence  
> A sequence is **arithmetic** if the difference between consecutive terms is constant.
> 
> - First term: $a_1$  
> - Common difference: $d$
> 
> General term:
> $$
> a_n = a_1+(n-1)d
> $$

---

> [!Note] Arithmetic Series  
> The sum of the first $n$ terms of an arithmetic sequence is
> $$
> S_n=\frac{n}{2}(a_1+a_n)=\frac{n}{2}[2a_1+(n-1)d]
> $$

> [!Note] Example  
> Find the sum of the first 10 terms of $2,5,8,\dots$
> 
> $$
> a_1=2,\ d=3,\ a_{10}=29
> $$
> $$
> S_{10}=\frac{10}{2}(2+29)=155
> $$

---

> [!Note] Geometric (Isomorphic) Sequence  
> A sequence is **geometric** if the ratio between consecutive terms is constant.
> 
> - First term: $a_1$  
> - Common ratio: $r$
> 
> General term:
> $$
> a_n=a_1r^{\,n-1}
> $$

---

> [!Note] Geometric (Isomorphic) Series  
> The sum of the first $n$ terms of a geometric sequence is
> $$
> S_n=
> \begin{cases}
> \displaystyle a_1\frac{1-r^n}{1-r}, & r\ne1\\[6pt]
> na_1, & r=1
> \end{cases}
> $$

> [!Note] Example  
> Find the sum of the first 6 terms of $3,6,12,\dots$
> 
> $$
> a_1=3,\ r=2
> $$
> $$
> S_6=3\frac{1-2^6}{1-2}=189
> $$

---

> [!Note] Infinite Geometric Series  
> An **infinite geometric series**
> $$
> a_1+a_1r+a_1r^2+\cdots
> $$
> **converges** if and only if
> $$
> |r|<1.
> $$

> [!Note] Sum of an Infinite Geometric Series  
> If $|r|<1$, then
> $$
> S=\frac{a_1}{1-r}
> $$

> [!Note] Example  
> $$
> 1+\frac12+\frac14+\frac18+\cdots
> $$
> Here $a_1=1,\ r=\frac12$, so
> $$
> S=\frac{1}{1-\frac12}=2
> $$

---

> [!Note] Telescoping Series  
> A **telescoping series** is one where many terms cancel out.
> 
> Example:
> $$
> \sum_{k=1}^{n}\left(\frac{1}{k}-\frac{1}{k+1}\right)
> $$
> After cancellation:
> $$
> S_n=1-\frac{1}{n+1}
> $$

---

> [!Note] Comparison of Arithmetic vs Geometric Series  
> - Arithmetic: adds a constant **difference**  
> - Geometric: multiplies by a constant **ratio**  
> - Geometric series can converge (finite sum) even if infinite  
> - Arithmetic series always diverge if infinite

---

> [!Note] Problem-Solving Insights — Series  
> - Always identify whether the sequence is **arithmetic or geometric** first.  
> - Write down $a_1$, $d$, or $r$ before applying formulas.  
> - For infinite series, **check $|r|<1$** immediately.  
> - Use cancellation carefully in telescoping series.

---

> [!Note] Additional Problems — Series  
> 1. Find the 15th term of the arithmetic sequence $4,7,10,\dots$  
> 2. Compute the sum of the first 20 terms of $5+9+13+\cdots$  
> 3. Find the 8th term of the geometric sequence $81,27,9,\dots$  
> 4. Evaluate $\sum_{k=1}^{10} (2k-1)$  
> 5. Determine whether the series $3+1.5+0.75+\cdots$ converges, and find its sum if it does  
> 6. Compute $\sum_{k=1}^{n}\left(\frac{1}{k}-\frac{1}{k+2}\right)$

---
