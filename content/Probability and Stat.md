## Probability and Statistics

> [!Note] Probability & Statistics  
> **Probability** studies randomness and uncertainty.  
> **Statistics** analyzes data and random phenomena.
> + Expected value, standard deviation
> 
> They are fundamental for science, engineering, economics, and AI.


---
# Basic Probability

+ Sample space: $\Omega$ 
	+ (The set of all the outcomes of a random experiment!!!!!)
+ Event: $A \subset \Omega$ 
+ Probability để $A$ xảy ra: 
$$P(A) = \frac{|A|}{|\Omega|}$$

Roll xúc sắc 6 mặt:
+ Sample space: $\Omega = \set{1, 2, 3, 4, 5, 6}$
+ Event: $A = \set{2, 4, 6}$
+ $P(A) = 3/6$ 

## Random Variables

> [!Note] Random Variable  
> A **random variable** is a function that assigns a real number to each outcome of a random experiment.
> 
> Types:
> - **Discrete random variable** (countable values)

Người ta dùng 1 con số duy nhất để biểu thị characteristics của một Event -> đây là random variable!!!!

**Flip 10 coins, compute the probability that exactly 7 coins that come up a head.**

Solution:
According to basic probability
+ Sample space: $\Omega = \set{\set{H,H,H,....,H},\set{H,H,H,..,T},\dots}$
	+ $|\Omega|=$ $2^{10}$
		+ Step 1: chọn mặt cho đồng 1 -> 2 cahcs
		+ Step 2: chọn mặt cho đồng 2
		+ ...
		+ Step 10: chọn mặt cho đồng 10
	+ (quy tắc đã học)
+ Event: $A = \set{\set{H,H,H,..T},\dots}$
	+ Chọn 3 phần tử bất kì (order matters?) trong 10 phần tử => cho 3 mặt này là head (1, 7 mặt còn lại là tails

> mỗi 1 statement phải chắc!!


> Việc chọn 7 trong 10 <-> Việc chọn 3 trong 10!!!!
> 
> $$C(n, r) = \frac{n!}{r!.(n-r)!}$$
> $$C(n, n-r) = \frac{n!}{(n-r)!(n-(n-r))!} = C(n, r)$$


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

+ **Quy tắc nhân**
	+ Process: **có nhiều step**
		+ Step 1: $a_1$
		+ Step 2: $a_2$
		+ ...
		+ Step 3: $a_n$
	+ Process: $a_1.a_2...a_n$ cách chọn

VD: Có 3 cách đi từ thành phố $A \to B$, 5 cách đi từ $B \to C$
Hỏi có bao nhiêu cách đi từ $A \to C$ ?

+ **Quy tắc cộng**
	+ Process: **nhiều cases** (trường hợp)!!!
		+ Case 1: $a_1$
		+ Case 2: $a_2$
		+ ...
		+ Case $n$: $a_n$
	+ Process: $\sum_{i=1}^{n} a_i$

VD: Có 6 cách đi từ $A \to B$, có 10 cách đi từ $B \to C$.
    Có 7 cách đi từ $A \to D$, có 20 cách đi từ $D \to C$.
    Có 15 cách đi trực tiếp từ $A \to C$?
từ $A \to C$ có tổng cộng bao nhiêu cách?

Phân tích: Đi từ $A \to C$ có 3 trường hợp:
+ TH1: $A \to B \to C$: 6x10
+ TH2: $A \to D \to C$: 7x20
+ TH3: $A \to C$: 15
+ KQ: **215.**

---

> [!Note] Factorial  
> $$
> n!=n(n-1)(n-2)\cdots1,\quad 0!=1
> $$

Số cách sắp xếp $n$ phần tử vào $n$ vị trí:

Ví dụ: Cho 3 học sinh A, B, C. Có bao nhiêu cách xếp 3 thằng này vào 3 vị trí 1, 2, 3 => **3!**

Step:
+ Xếp vào vị trí 1: 3
+ Xếp vào vị trí 2: 2
+ Xếp vào vị trí 3: 1
3x2x1 = 3!

Case:
+ Case 1: {ABC}
+ Case 2: {ACB}
+ Case 3: {BAC}
+ Case 4: {BCA}
+ Case 5: {CBA}
+ Case 6: {CAB}
1 + 1+ 1+ .. +1 = 6
---

Tại vì $A$ treat tất cả các bộ là riêng biệt

$$C(n, r).r! = A(n, r)$$

> [!Note] Permutations  
> Number of ways to arrange $r$ objects from $n$:
> $$
> P(n,r)=\frac{n!}{(n-r)!}
> $$

Chỉnh hợp: $A$

---
**Bài toán:** Cho 15 viên kẹo, có bao nhiêu cách chọn ra 3 viên kẹo bất kì trong 15 viên này?

Phân tích: 
Chia trường hợp (Dài quá)
+ TH1: Chọn viên {1, 2 ,3}
+ TH2: Chọn viên {2, 3, 4}
+ ....

Chia **step**:
+ Step 1: Chọn viên kẹo đầu tiên trong 3 viên kẹo 
	+ Chọn 1 trong 15 viên kẹo để làm viên kẹo đầu tiên trong 3 viên kẹo => **15 cách**
+ Step 2: Chọn viên kẹo thứ 2 trong 3 viên kẹo => **14 cách**
+ Step 3: Chọn viên kẹo cuối cùng trong 3 viên kẹo => **13 cách**

Total: 15x14x13

> Nhận xét: Mình đang bị đếm thừa!!!!
> {a, b, c}: bộ 3 viên bi mà mình lấy ra theo thứ tự 1 - 2 -3 
> VD: {1, 2, 3}, {4, 5, 6}
> 
> {1, 2, 3} <-> {2 , 1, 3} <-> {2, 3, 1} <-> {1, 3, 2}: bốc ra 3 viên bi 1, 2, 3 (Mình đã đếm gấp đôi lên)
> 
> Do đó, mình phải chia bớt cho những trường hợp bị trùng!!!!!!!
> 
> Câu hỏi: Có bao nhiêu bộ bị trùng với {1, 2, 3}? 
> {1, 2, 3} <-> {2 , 1, 3} <-> {2, 3, 1} <-> {1, 3, 2} <-> {3, 1, 2} <-> {3, 2, 1}: 6 bộ trùng với {1, 2, 3}.
> 
> Cách đếm nhanh: **3!**
> 
> Mình chỉ nên đếm 1 bộ trong mỗi 6 bộ bị trùng!!!!
> 
> Đáp án: 15x14x13/6

**Bài toán tổng quát:** Cho $n$ viên kẹo, có bao nhiêu cách chọn ra $r$ viên kẹo bất kì trong $n$ viên kẹo này?

Chia step:
+ Step 1: Chọn 1 trong $n$ viên kẹo vào viên kẹo đầu tiên trong $r$ viên kẹo cần được lấy ra => $n -1 + 1$
+ Step 2: $(n-1) = (n- 2 + 1)$
+ ....
+ Step $r$: $(n-r+1)$

> Analogical reasoning: step 2 có (n-1) cách -> step 3 có (n-2) cách... step r có (n-r+1) cách!!!!

Total: $n.(n-1)(n-2)...(n-r+1)$

$$n! = n.(n-1)(n-2)..(n-r+1).(n-r)(n-r-1)....1 $$
$$n! = n.(n-1)...(n-r+1).(n-r)!$$
$$n.(n-1)...(n-r+1) = \frac{n!}{(n-r)!}$$
Lập luận tương tự trường hợp trên!!!!
+ Bộ $r$ số có bao nhiêu bộ bị trùng: $r!$
+ Do đó đáp án cuối phải là:
$$\frac{n!}{r!.(n-r)!}$$
> Chú ý: Là mình treat tất cả các hoán vị là 1 -> nên mình phải chia $r!$

> [!Note] Combinations  
> Number of ways to choose $r$ objects from $n$:
> $$
> C(n,r)=\binom{n}{r}=\frac{n!}{r!(n-r)!}
> $$

Tổ hợp: $C$

---

> [!Note] Insight — Permutation vs Combination  
> - **Permutation:** order matters  
> 	- (A,B,C) - (B,C,A): 2 bộ
> - **Combination:** order does not matter
> 	- (A,B,C) - (B,C,A): 1 bộ

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
