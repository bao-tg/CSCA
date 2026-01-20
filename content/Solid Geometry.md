---
share_link: https://share.note.sx/ytiygg9u#z+c6qw6WYPDGdSl+0gvg40JgP3+FT3mTgyNntnL4ZUM
share_updated: 2026-01-09T17:27:27+07:00
---
prongs: cạnh
## Solid Geometry

> [!Note] Solid Geometry  
> **Solid geometry** studies three-dimensional (3D) objects: their **shapes, sizes, positions**, and **relationships in space**.
> 
> In 3D space, a point is represented by:
> $$
> A(x,y,z)
> $$

---

> [!Note] Basic Elements in Space  
> - **Point:** has position only  
> - **Line:** extends infinitely in one direction  
> - **Plane:** extends infinitely in two directions  
> - **Solid:** occupies space and has volume

---

> [!Note] Distance Between Two Points  
> For $A(x_1,y_1,z_1)$ and $B(x_2,y_2,z_2)$:
> $$
> AB=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
> $$

---

> [!Note] Line in Space  
> A line passing through point $A(x_0,y_0,z_0)$ with direction vector $\vec{v}=(a,b,c)$:
> 
> - **Parametric form:**
>   $$
>   \begin{cases}
>   x=x_0+at\\
>   y=y_0+bt\\
>   z=z_0+ct
>   \end{cases}
>   $$

> [!Note] Direction Vector  
> Any nonzero vector parallel to a line is a **direction vector** of that line.

---

> [!Note] Plane in Space  
> A plane with normal vector $\vec{n}=(A,B,C)$ passing through $P(x_0,y_0,z_0)$:
> 
> **Equation of the plane:**
> $$
> A(x-x_0)+B(y-y_0)+C(z-z_0)=0
> $$

> [!Note] General Form of a Plane  
> $$
> Ax+By+Cz+D=0
> $$

---

> [!Note] Angle Relationships  
> - **Line ∥ Plane:** direction vector ⟂ normal vector  
> - **Line ⟂ Plane:** direction vector ∥ normal vector  
> - **Plane ∥ Plane:** normal vectors are parallel  
> - **Plane ⟂ Plane:** normal vectors are perpendicular

---

> [!Note] Polyhedra  
> A **polyhedron** is a solid bounded by flat polygonal faces.
> 
> Examples:
> - Prism  
> - Pyramid  
> - Cube  
> - Rectangular box

---

> [!Note] Prism  
> A **prism** has:
> - Two parallel, congruent bases  
> - Lateral faces are parallelograms
> 
> **Volume:**
> $$
> V=\text{Base area}\times \text{height}
> $$
![[Pasted image 20260111085350.png]]

---

> [!Note] Pyramid  
> A **pyramid** has:
> - One base  
> - Triangular faces meeting at a vertex
> 
> **Volume:**
> $$
> V=\frac{1}{3}\times \text{Base area}\times \text{height}
> $$
> ![[Pasted image 20260111085422.png]]


số triang


---

> [!Note] Cylinder  
> A **cylinder** has:
> - Two parallel circular bases  
> - Curved lateral surface
> 
> **Volume:**
> $$
> V=\pi r^2h
> $$
> ![[Pasted image 20260111085447.png]]



---

> [!Note] Cone  
> A **cone** has:
> - One circular base  
> - One vertex
> 
> **Volume:**
> $$
> V=\frac{1}{3}\pi r^2h
> $$
> ![[Pasted image 20260111085512.png]]



---

> [!Note] Sphere  
> A **sphere** is the set of all points at a fixed distance $r$ from a center.
> 
> **Equation:**
> $$
> (x-h)^2+(y-k)^2+(z-l)^2=r^2
> $$

> [!Note] Volume of a Sphere  
> $$
> V=\frac{4}{3}\pi r^3
> $$

---

> [!Note] Surface Area (Key Formulas)  

| Solid     | Surface Area |
|-----------|--------------|
| Cube      | $6a^2$ |
| Cylinder  | $2\pi r(r+h)$ |
| Cone      | $\pi r(r+l)$ |
| Sphere    | $4\pi r^2$ |

---

> [!Note] Problem-Solving Insights — Solid Geometry  
> - Always draw a **3D diagram**.  
> - Identify heights carefully (they may not be edges).  
> - Use vectors to handle directions and angles in space.  
> - Separate **geometry reasoning** and **calculation**.

---

> [!Note] Additional Problems — Solid Geometry  
> 1. Find the distance between $A(1,2,3)$ and $B(4,-2,1)$.  
> 2. Write the equation of the plane through $(1,0,0)$ with normal vector $(2,-1,1)$.  
> 3. Compute the volume of a pyramid with base area $12$ and height $5$.  
> 4. Find the surface area of a sphere of radius $7$.  
> 5. Determine whether two planes with normals $(1,2,3)$ and $(2,4,6)$ are parallel.

---
## Frustum (Truncated Solid)

> [!Note] Frustum  
> A **frustum** is a solid formed when the **top part of a cone or pyramid is cut off**
> by a plane **parallel to the base**.
> 
> Common frustums:
> - **Frustum of a cone**
> - **Frustum of a pyramid**

---

## Frustum of a Cone

> [!Note] Definition — Conical Frustum  
> A **conical frustum** has:
> - Two parallel circular bases  
> - Different radii  
> - A curved lateral surface

Let:
- Larger radius: $R$  
- Smaller radius: $r$  
- Height: $h$  
- Slant height: $l$

---

> [!Note] Volume — Conical Frustum  
> $$
> V=\frac{1}{3}\pi h\left(R^2+r^2+Rr\right)
> $$

---

> [!Note] Slant Height  
> $$
> l=\sqrt{h^2+(R-r)^2}
> $$

---

> [!Note] Lateral Surface Area  
> $$
> S_{\text{lateral}}=\pi(R+r)l
> $$

---

> [!Note] Total Surface Area  
> $$
> S_{\text{total}}=\pi(R+r)l+\pi R^2+\pi r^2
> $$

---

> [!Note] Insight — Similarity  
> A frustum comes from **similar cones**, which explains why $R^2+r^2+Rr$
> appears in the volume formula.

---

## Frustum of a Pyramid

> [!Note] Definition — Pyramidal Frustum  
> A **pyramidal frustum** is formed by cutting a pyramid with a plane
> parallel to its base.

Let:
- Area of larger base: $B_1$  
- Area of smaller base: $B_2$  
- Height: $h$

---

> [!Note] Volume — Pyramidal Frustum  
> $$
> V=\frac{h}{3}\left(B_1+B_2+\sqrt{B_1B_2}\right)
> $$

---

> [!Note] Special Case — Square Frustum  
> If bases are squares with side lengths $a$ and $b$:
> $$
> V=\frac{h}{3}\left(a^2+b^2+ab\right)
> $$

---

## Comparison

> [!Note] Frustum vs Original Solid  

| Solid | Bases | Lateral Faces |
|------|------|---------------|
| Cone | 1 circular | Curved |
| Cone Frustum | 2 circular | Curved |
| Pyramid | 1 polygon | Flat |
| Pyramid Frustum | 2 polygons | Flat |

---

> [!Note] Problem-Solving Insights — Frustum  
> - Always check the **bases are parallel**.  
> - Use similarity to derive missing dimensions.  
> - Slant height is **not** the same as vertical height.  
> - Draw the full cone/pyramid if needed.

---

> [!Note] Additional Problems — Frustum  
> 1. A conical frustum has $R=5$, $r=3$, $h=4$. Find its volume.  
> 2. Find the lateral surface area of a frustum with $R=6$, $r=2$, $h=8$.  
> 3. A pyramid frustum has square bases of side $10$ and $4$, height $6$. Find its volume.  
> 4. Show how the frustum volume formula follows from subtracting two similar cones.

---
