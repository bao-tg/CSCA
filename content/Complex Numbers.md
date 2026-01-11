---
share_link: https://share.note.sx/imh4qod0#YfP7V5v3km9D3xKAI77z0K8UMU1bvWm50WQaJugSFrM
share_updated: 2026-01-07T13:06:59+07:00
---
Date: 07/01/2026

## Complex Numbers (High School Level)

> [!Note] Complex Number  
> A **complex number** is a number of the form
> $$
> z=a+bi,
> $$
> where:
> - $a,b\in\mathbb{R}$  
> - $i$ is the imaginary unit, defined by $i^2=-1$
> 
> - $a$: real part, denoted $\Re(z)$  
> - $b$: imaginary part, denoted $\Im(z)$
> 
> The set of all complex numbers is denoted by $\mathbb{C}$.

VD: $3 + 5i$
+ phần thực 3
+ phần ảo 5
VD: $5i$ ~ số phức
+ phần thực 0
+ phần ảo 5
VD: 5 ~ số thực (vừa là số phức)
+ phần thực 5
+ phần ảo = 0

---

> [!Note] Equality of Complex Numbers  
> Two complex numbers are equal if and only if their real and imaginary parts are equal:
> $$
> a+bi=c+di \iff
> \begin{cases}
> a=c,\\
> b=d.
> \end{cases}
> $$

---

> [!Note] Basic Operations  
> Let $z_1=a+bi$ and $z_2=c+di$.
> 
> - **Addition:**  
>   $$
>   z_1+z_2=(a+c)+(b+d)i
>   $$
> - **Subtraction:**  
>   $$
>   z_1-z_2=(a-c)+(b-d)i
>   $$
> - **Multiplication:**  
>   $$
>   z_1z_2=(ac-bd)+(ad+bc)i
>   $$
> - **Division:**  
>   $$
>   \frac{z_1}{z_2}
>   =\frac{(a+bi)(c-di)}{c^2+d^2},
>   \quad z_2\ne0
>   $$

VD: $(a+bi)(c+di)$ = $(ac + bdi^2 + adi +bci)$
$$= ac - bd + (ad+bc)i$$

VD: $$\frac{a+bi}{c+di} = \frac{(a+bi)(c-di)}{(c+di)(c-di)}$$ $$\frac{a+bi}{c+di} = \frac{(ac + bd + (bc-ad)i)}{c^2+d^2} = \frac{ac+bd}{c^2+d^2} + \frac{bc-ad}{c^2+d^2}i$$
Fact
> Số thực chính là số phức, với phần ảo = 0.


> [!Note] Complex Conjugate  
> The **complex conjugate** of $z=a+bi$ is
> $$
> \overline{z}=a-bi.
> $$

Số phức liên hợp

VD: $z = 3 + 5i$ -> $\overline{z} = 3  - 5i$ 

$$z . \overline{z} = a^2 + b^2$$

> [!Note] Properties — Conjugate  
> - $z\overline{z}=a^2+b^2$  
> - $\overline{z_1+z_2}=\overline{z_1}+\overline{z_2}$  
> - $\overline{z_1z_2}=\overline{z_1}\,\overline{z_2}$

---

> [!Note] Modulus of a Complex Number  
> The **modulus** (absolute value) of $z=a+bi$ is defined by
> $$
> |z|=\sqrt{a^2+b^2}.
> $$

$$z = 3 + 4i$$ -> $|z| =5$

> [!Note] Properties — Modulus  
> - $|z|\ge0$  
> - $|z|=0 \iff z=0$  
> - $|z_1z_2|=|z_1||z_2|$  
> - $\left|\frac{z_1}{z_2}\right|=\frac{|z_1|}{|z_2|}$, $z_2\ne0$

---

> [!Note] Geometric Representation  
> A complex number $z=a+bi$ corresponds to the point
> $$
> (a,b)
> $$
> in the Cartesian plane, called the **complex plane**.

Có nghĩa là, mỗi một số phức -> có thể biểu diễn được bẳng 1 điểm trong hệ tọa độ Oxy

mỗi điểm -> 1 số phức.

VD: $z = 1 + 1i$ -> (1, 1) trên hệ tọa độ.

Nâng cao: **complex plane**
+ trục Ox -> trục số thực
+ trục Oy -> trục số ảo!!!

---

> [!Note] Argument of a Complex Number  
> The **argument** of a nonzero complex number $z$ is the angle $\theta$ between the positive real axis and the vector representing $z$.
> 
> It is denoted by $\arg z$.


---

> [!Note] Polar Form  
> Any nonzero complex number can be written as
> $$
> z=r(\cos\theta+i\sin\theta),
> $$
> where:
> - $r=|z|$  
> - $\theta=\arg z$

---

> [!Note] De Moivre’s Formula  
> For $n\in\mathbb{Z}$,
> $$
> (\cos\theta+i\sin\theta)^n
> =\cos(n\theta)+i\sin(n\theta).
> $$

---

> [!Note] Problem-Solving Insights — Complex Numbers  
> - Use conjugates to simplify division.  
> - Switch to polar form for powers and roots.  
> - Interpret complex numbers geometrically when possible.

---

> [!Note] Additional Problems — Complex Numbers  
> 1. Compute $(2+3i)(1-4i)$.  
> 2. Find the modulus of $z=-3+4i$.  
> 3. Solve $z^2=1-i$.  
> 4. Express $z=1+\sqrt{3}i$ in polar form.  
> 5. Show that $|z+\overline{z}|=2|\Re(z)|$.
