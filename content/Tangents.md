**Date:** 05-01-26

## 13. Tangent Problems in Analytic Geometry

> [!Note] Tangent Line — Definition  
> A **tangent line** to a curve at a point $A(x_0,y_0)$ is a line that:
> - Passes through $A$, and  
> - Has the same **slope** as the curve at $A$.
> 
> If the curve is $y=f(x)$ and $f'(x_0)$ exists, then the tangent line at $x=x_0$ has slope
> $$
> m=f'(x_0).
> $$

---

> [!Note] Equation of a Tangent Line  
> The equation of the tangent line to $y=f(x)$ at $x=x_0$ is:
> $$
> y-y_0=f'(x_0)(x-x_0),
> $$
> where
> $$
> y_0=f(x_0).
> $$

---

> [!Example] Example 1 — Tangent to a Curve at a Given Point  
> Find the equation of the tangent line to
> $$
> y=x^2
> $$
> at the point where $x=1$.

**Solution:**

Step 1: Compute the derivative:
$$
f'(x)=2x.
$$

Step 2: Evaluate at $x=1$:
$$
m=f'(1)=2.
$$

Step 3: Find the point of tangency:
$$
y_0=1^2=1.
$$

Step 4: Write the tangent equation:
$$
y-1=2(x-1).
$$

**Final answer:**
$$
\boxed{y=2x-1}
$$

---

> [!Example] Example 2 — Tangent Line Parallel to a Given Line  
> Find the equation of the tangent to
> $$
> y=x^3-3x
> $$
> that is parallel to the line
> $$
> y=6x-4.
> $$

**Solution:**

Step 1: Parallel lines have equal slopes:
$$
m=6.
$$

Step 2: Compute derivative:
$$
f'(x)=3x^2-3.
$$

Step 3: Set derivative equal to the slope:
$$
3x^2-3=6
$$
$$
3x^2=9 \Rightarrow x^2=3 \Rightarrow x=\pm\sqrt{3}.
$$

Step 4: Find corresponding points:
$$
y(\sqrt{3})=(\sqrt{3})^3-3\sqrt{3}=0,
$$
$$
y(-\sqrt{3})=(-\sqrt{3})^3+3\sqrt{3}=0.
$$

Step 5: Write tangent equations:

At $x=\sqrt{3}$:
$$
y=6(x-\sqrt{3}).
$$

At $x=-\sqrt{3}$:
$$
y=6(x+\sqrt{3}).
$$

---

> [!Example] Example 3 — Tangent Line Perpendicular to a Given Line  
> Find the tangent to
> $$
> y=x^2
> $$
> that is perpendicular to
> $$
> y=-\frac{1}{4}x+1.
> $$

**Solution:**

Step 1: Perpendicular slope:
$$
m=4.
$$

Step 2: Derivative of the curve:
$$
f'(x)=2x.
$$

Step 3: Solve:
$$
2x=4 \Rightarrow x=2.
$$

Step 4: Point of tangency:
$$
y=2^2=4.
$$

Step 5: Tangent equation:
$$
y-4=4(x-2).
$$

**Final answer:**
$$
\boxed{y=4x-4}
$$

---

> [!Example] Example 4 — Tangent Passing Through a Given Point  
> Find the tangent to
> $$
> y=x^2
> $$
> that passes through point $A(0,-1)$.

**Solution:**

Let the tangent touch the curve at $x=a$.

Step 1: Point of tangency:
$$
(a,a^2).
$$

Step 2: Slope:
$$
m=2a.
$$

Step 3: Tangent equation:
$$
y-a^2=2a(x-a).
$$

Step 4: Substitute point $A(0,-1)$:
$$
-1-a^2=2a(0-a)
$$
$$
-1-a^2=-2a^2
$$
$$
a^2=1 \Rightarrow a=\pm1.
$$

Step 5: Write tangent equations:

For $a=1$:
$$
y-1=2(x-1) \Rightarrow y=2x-1.
$$

For $a=-1$:
$$
y-1=-2(x+1) \Rightarrow y=-2x-1.
$$

---

> [!Note] Tangent to a Circle  
> For a circle
> $$
> (x-a)^2+(y-b)^2=R^2,
> $$
> the tangent at point $M(x_0,y_0)$ on the circle is:
> $$
> (x_0-a)(x-x_0)+(y_0-b)(y-y_0)=0.
> $$

---

> [!Example] Example 5 — Tangent to a Circle  
> Find the tangent to the circle
> $$
> x^2+y^2=25
> $$
> at point $M(3,4)$.

**Solution:**

Apply the formula:
$$
3(x-3)+4(y-4)=0.
$$

Simplify:
$$
3x+4y-25=0.
$$

**Final answer:**
$$
\boxed{3x+4y-25=0}
$$

---

> [!Note] Problem-Solving Strategy — Tangent Problems  
> 1. Identify the curve type.  
> 2. Compute slope (derivative or geometry).  
> 3. Determine the tangency point.  
> 4. Write the line equation.  
> 5. Check conditions (parallel, perpendicular, passing through a point).

> [!Note] Additional Problems — Tangents  
> 6. Find the tangent to $y=x^3$ at $x=-1$.  
> 7. Find tangents to $y=x^2-2x+1$ parallel to $y=4x-3$.  
> 8. Find tangents to $x^2+y^2=13$ passing through $(1,2)$.
