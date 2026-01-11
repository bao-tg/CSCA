---
share_link: https://share.note.sx/mv3ed8wo#UfVddSMv+P56dvrGLe5QEeZcZD6t3Qp29eAE8sfcHqs
share_updated: 2026-01-09T17:27:40+07:00
---
## Tangents Between Two Given Circles

> [!Note] Problem Setting  
> Given two circles:
> $$
> C_1:\ (x-x_1)^2+(y-y_1)^2=r_1^2
> $$
> $$
> C_2:\ (x-x_2)^2+(y-y_2)^2=r_2^2
> $$
> 
> A **common tangent** is a line that touches **both circles**.

---

> [!Note] Types of Common Tangents  
> There are **two types** of common tangents between two circles:
> 
> 1. **External (Direct) Tangents**  
>    - Do **not** intersect the segment joining the centers  
>    - Exist when the circles are separate or externally tangent
> 
> 2. **Internal (Transverse) Tangents**  
>    - Intersect the segment joining the centers  
>    - Exist only when the circles are sufficiently far apart

---

> [!Note] Number of Common Tangents  

Let $d$ be the distance between centers:
$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}
$$

| Condition | Number of Common Tangents |
|---------|---------------------------|
| $d>r_1+r_2$ | 4 (2 external + 2 internal) |
| $d=r_1+r_2$ | 3 |
| $|r_1-r_2|<d<r_1+r_2$ | 2 |
| $d=|r_1-r_2|$ | 1 |
| $d<|r_1-r_2|$ | 0 |

---

> [!Note] Key Idea — Tangent as a Distance Condition  
> A line
> $$
> ax+by+c=0
> $$
> is tangent to a circle with center $(x_0,y_0)$ and radius $r$ **if and only if**
> $$
> \frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}=r
> $$

This condition is the foundation of all analytic solutions.

---

> [!Note] Method 1 — Equation of Common Tangents (General Method)  
> Let the common tangent be:
> $$
> y=mx+k
> $$
> 
> Distance from center to the line equals radius:
> 
> For $C_1$:
> $$
> \frac{|mx_1-y_1+k|}{\sqrt{m^2+1}}=r_1
> $$
> 
> For $C_2$:
> $$
> \frac{|mx_2-y_2+k|}{\sqrt{m^2+1}}=r_2
> $$

- Same sign → **external tangents**
- Opposite signs → **internal tangents**

Solve the resulting system to find $m$ and $k$.

---

> [!Note] Method 2 — Geometric Reduction (Very Important Insight)  

To find **external tangents**:
- Shrink the larger circle by $r_2-r_1$
- Draw tangents from the center of the smaller circle to the reduced circle

To find **internal tangents**:
- Enlarge one circle by $r_1+r_2$
- Draw tangents from one center to the enlarged circle

This transforms the problem into **tangents from a point to a circle**.

---

> [!Note] Special Case — Equal Radii  
> If $r_1=r_2$:
> - External tangents are **parallel**
> - Internal tangents intersect at the midpoint of the centers
> 
> The external tangents are parallel to the line joining the centers.

---

> [!Note] Worked Example — External Tangents  
> Find the external common tangents of:
> $$
> C_1:\ x^2+y^2=1
> $$
> $$
> C_2:\ (x-4)^2+y^2=1
> $$

Let tangent be $y=mx+k$.

Distance conditions:
$$
\frac{|k|}{\sqrt{m^2+1}}=1,\quad
\frac{|4m+k|}{\sqrt{m^2+1}}=1
$$

Same sign ⇒ subtract:
$$
4m=0 \Rightarrow m=0
$$

Then:
$$
|k|=1
$$

So the external tangents are:
$$
y=1,\quad y=-1
$$

---

> [!Note] Common Mistakes  
> - Forgetting absolute values in distance formulas  
> - Mixing internal and external tangent conditions  
> - Not checking existence conditions using $d$

---

> [!Note] Problem-Solving Insights — Tangents Between Circles  
> - Always check **how many tangents exist** before solving  
> - Decide **external or internal** first  
> - Use geometry to reduce algebra when possible  
> - Sketch the circles to avoid sign errors

---

> [!Note] Additional Problems — Common Tangents  
> 1. Find all common tangents of $x^2+y^2=4$ and $(x-6)^2+y^2=1$.  
> 2. Determine the number of common tangents of $(x+1)^2+y^2=9$ and $(x-3)^2+y^2=1$.  
> 3. Find the equations of internal tangents of $x^2+y^2=1$ and $(x-5)^2+y^2=4$.  
> 4. Prove that external tangents are parallel when $r_1=r_2$.

---
