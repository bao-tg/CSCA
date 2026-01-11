---
share_link: https://share.note.sx/eaqjx0cu#4ACyqU5xnQytchfaxjM7Wrcmstfc881WyB/FSNHb+UA
share_updated: 2026-01-07T13:07:01+07:00
---
## Plane Analytic Geometry

> [!Note] Plane Analytic Geometry  
> **Plane analytic geometry** studies geometric objects in the plane by using
> **coordinates and equations**.
> 
> Each point is represented by:
> $$
> P(x,y)
> $$

---

> [!Note] Line  
> A **line** is the set of points satisfying a first-degree equation.
> 
> **Common forms:**
> - **Slope–intercept form:**
>   $$
>   y=mx+b
>   $$
> - **Point–slope form:**
>   $$
>   y-y_1=m(x-x_1)
>   $$
> - **General form:**
>   $$
>   ax+by+c=0
>   $$

> [!Note] Properties — Line  
> - Slope: $m=\tan\theta$  
> - Parallel lines have equal slopes  
> - Perpendicular lines satisfy $m_1m_2=-1$

---

> [!Note] Circle  
> A **circle** is the set of all points in the plane at a fixed distance from a fixed point.
> 
> - Center: $(h,k)$  
> - Radius: $r$
> 
> **Standard equation:**
> $$
> (x-h)^2+(y-k)^2=r^2
> $$

> [!Note] General Form — Circle  
> $$
> x^2+y^2+Dx+Ey+F=0
> $$

> [!Note] Insight  
> Complete the square to find the center and radius.

---

> [!Note] Parabola  
> A **parabola** is the set of points equidistant from:
> - a fixed point (**focus**)  
> - a fixed line (**directrix**)

![[Pasted image 20260111084004.png]]

Với mọi điểm trên Parabola -> distance từ điểm đấy đến S (focus) = distance từ điểm ấy đến Directrix.

<=> Tập hợp các điểm, sao cho với mỗi điểm, distance từ điểm đấy đến S (focus) = distance từ điểm ấy đến Directrix, chính là 1 parabola.

---

> [!Note] Parabola — Vertical Axis  
> Vertex $(h,k)$, parameter $p>0$:
> $$
> (x-h)^2=4p(y-k)
> $$
> 
> - Focus: $(h,k+p)$  
> - Directrix: $y=k-p$

VD: $y = x^2$ 
+ $h=0$
+ $p=1/4$
+ $k=0$
+ focus: (0, 1/4)
+ directrix: y = -1/4

U hoặc U ngược

---

> [!Note] Parabola — Horizontal Axis  
> $$
> (y-k)^2=4p(x-h)
> $$
> 
> - Focus: $(h+p,k)$  
> - Directrix: $x=h-p$

+ U hướng về bên trái/phải
$$x = y^2$$
---

Nhắc lại [[Distance]]

> 0x + 1y +2 = 0

> [!Note] Careful Example — Parabola from Directrix  
> **Find the equation of the parabola** with focus $F(0,2)$ and directrix $y=-2$.
> 
> Let $P(x,y)$ be any point on the parabola.
> 
> - Distance to focus:
>   $$
>   PF=\sqrt{(x-0)^2+(y-2)^2}
>   $$
> - Distance to directrix:
>   $$
>   d(P,\text{directrix})=|y+2|
>   $$
> 
> Definition of parabola:
> $$
> PF=d(P,\text{directrix})
> $$
> 
> Squaring both sides:
> $$
> x^2+(y-2)^2=(y+2)^2
> $$
> 
> Simplifying:
> $$
> x^2=8y
> $$
> 
> This parabola opens **upward** with vertex at $(0,0)$.

---

> [!Note] Ellipse  
> An **ellipse** is the set of points such that the **sum of distances** to two fixed points (foci) is constant.
![[Pasted image 20260111084203.png]]

d1 + d2 = const

---

> [!Note] Ellipse — Standard Form  
> Center $(h,k)$:
> - Major axis horizontal:
>   $$
>   \frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1,\quad a>b
>   $$
> - Major axis vertical:
>   $$
>   \frac{(x-h)^2}{b^2}+\frac{(y-k)^2}{a^2}=1
>   $$

VD: $$\frac{x^2}{4} + \frac{y^2}{5} = 1$$
+ h = 0
+ k = 0
+ a = 2 (a, b > 0)
+ b = $\sqrt{5}$


> [!Note] Ellipse — Key Relations  
> $$
> c^2=a^2-b^2 (a > b)
> $$
> 
> - Foci: $(h\pm c,k)$

If (a < b)
$$c^2 = b^2 - a^2$$
Foci: $(h,k\pm c)$


---

> [!Note] Hyperbola  
> A **hyperbola** is the set of points such that the **absolute difference of distances** to two fixed points is constant.
> ![[Pasted image 20260111084226.png]]

---

> [!Note] Hyperbola — Standard Form  
> Center $(h,k)$:
> - Horizontal transverse axis:
>   $$
>   \frac{(x-h)^2}{a^2}-\frac{(y-k)^2}{b^2}=1
>   $$
> - Vertical transverse axis:
>   $$
>   \frac{(y-k)^2}{a^2}-\frac{(x-h)^2}{b^2}=1
>   $$

> [!Note] Hyperbola — Key Relations  
> $$
> c^2=a^2+b^2
> $$
> 
> - Foci: $(h\pm c,k)$ or $(h,k\pm c)$  
> - Asymptotes (tiệm cận):
>   $$
>   y-k=\pm\frac{b}{a}(x-h)
>   $$

---

> [!Note] Comparison of Conics  

| Curve     | Distance Definition | Equation Sign |
|-----------|--------------------|----------------|
| Line      | Linear relation    | Degree 1 |
| Circle   | Fixed distance     | $+$, $+$ |
| Parabola | Equal distance     | One squared term |
| Ellipse  | Sum of distances   | $+$, $+$ |
| Hyperbola| Difference         | $+$, $-$ |

---

> [!Note] Problem-Solving Insights — Analytic Geometry  
> - Identify the curve by the **signs** of squared terms.  
> - Always complete the square when given a general equation.  
> - For parabolas, find **vertex, focus, directrix**.  
> - Sketching helps avoid orientation mistakes.

---

> [!Note] Additional Problems — Plane Analytic Geometry  
> 1. Find the equation of the line through $(2,-1)$ with slope $3$.  
> 2. Write the equation of a circle with center $(1,2)$ and radius $4$.  
> 3. Find the focus and directrix of $x^2=12y$.  
> 4. Determine the foci of $\frac{x^2}{16}+\frac{y^2}{9}=1$.  
> 5. Find the asymptotes of $\frac{x^2}{9}-\frac{y^2}{4}=1$.

---
