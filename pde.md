>The notes primarily cover initial value problems, boundary value problems, and Laplace transforms in ordinary differential equations; and elliptic equations, parabolic equations, and Sobolev spaces in partial differential equations. The ordinary differential equations section references Boye, DiPrima, and Meade's Elementary Differential Equations and Boundary Value Problems, 11th Edition, John Wiley and Sons, 2017. The partial differential equations section is based on Evans' textbook. The latest update includes the fundamental concepts of ordinary differential equations. The notes also cover the necessary functional analysis foundations for partial differential equations, with references to Appendix D of Evans' textbook. Some of the extended material is derived from Brezis' textbook on functional analysis.


- [Part 1](#part-1)
  - [1. Definition](#1-definition)
  - [2. Classiffcation: ODEs vs PDEs](#2-classiffcation-odes-vs-pdes)
  - [3. Classification: linear vs nonlinear](#3-classification-linear-vs-nonlinear)
  - [4. Definition](#4-definition)
  - [5. Example](#5-example)
  - [6. Example](#6-example)
  - [7. Systems of 1st-order ODEs](#7-systems-of-1st-order-odes)
  - [8. Example](#8-example)
  - [9.. Geometric interpretation](#9-geometric-interpretation)
  - [10. Existence and Uniqueness for Initial Value Problems](#10-existence-and-uniqueness-for-initial-value-problems)
  - [11. Picard-Lindelöf Theorem](#11-picard-lindelöf-theorem)
  - [12.Theorem](#12theorem)
  - [13. Definition](#13-definition)
- [Part 2](#part-2)
  - [1. Motivation](#1-motivation)
  - [2. Principle of superposition](#2-principle-of-superposition)
  - [3. Wronskian](#3-wronskian)
  - [4. Abel's theorem](#4-abels-theorem)
  - [5. Abel's formula](#5-abels-formula)
  - [6. Homogeneous systems with constant coeiffcients](#6-homogeneous-systems-with-constant-coeiffcients)
  - [7. Example](#7-example)
  - [8. Three forms](#8-three-forms)
  - [9. Real \& different eigenvalues](#9-real--different-eigenvalues)
  - [10. Example](#10-example)
  - [11. Complex eigenvalues](#11-complex-eigenvalues)
  - [12. Example](#12-example)
  - [13. Matrix algebra methods](#13-matrix-algebra-methods)
  - [14. Definition](#14-definition)
  - [15. Property](#15-property)
  - [16. Definition](#16-definition)
  - [17. Relation to diagonalisation](#17-relation-to-diagonalisation)
  - [18. Example](#18-example)
- [Part 3](#part-3)
  - [1. Repeated eigenvalue: example](#1-repeated-eigenvalue-example)
  - [2. Connection to matrix methods](#2-connection-to-matrix-methods)
  - [3. General method](#3-general-method)
  - [4. Theorem(Non-homogeneous ODE systems)](#4-theoremnon-homogeneous-ode-systems)
  - [5. Diagonalisation](#5-diagonalisation)
  - [6. Example](#6-example-1)
  - [7. Undetermined coeffcients](#7-undetermined-coeffcients)
  - [8. Same example as 6, but diffierent method](#8-same-example-as-6-but-diffierent-method)
  - [9. Variation of parameters](#9-variation-of-parameters)
  - [10. Example](#10-example-1)
- [Part 4](#part-4)
  - [1. Qualitative theory of ODEs](#1-qualitative-theory-of-odes)
  - [2. Definition](#2-definition)
  - [3. Qualitative description](#3-qualitative-description)
  - [4. Definition](#4-definition-1)
  - [5. Theorem](#5-theorem)
  - [6. Motivating the linear approximation](#6-motivating-the-linear-approximation)
  - [7. Linear approximation](#7-linear-approximation)
  - [8. Local analysis: strategy](#8-local-analysis-strategy)
  - [9. Example: Newton's law for pendulum with friction](#9-example-newtons-law-for-pendulum-with-friction)
  - [10. Classiffication of critical points](#10-classiffication-of-critical-points)
  - [11. Real unequal eigenvalues](#11-real-unequal-eigenvalues)
  - [12. Complex eigenvalues](#12-complex-eigenvalues)
  - [13. Summary](#13-summary)
- [Part 5](#part-5)
  - [1. Definition](#1-definition-1)
  - [2. Stability of linear systems](#2-stability-of-linear-systems)
  - [3. Almost linear systems](#3-almost-linear-systems)
  - [4. Center : linear vs non-linear](#4-center--linear-vs-non-linear)
  - [5. Implicit trajectories](#5-implicit-trajectories)
  - [6. Example: Damped pendulum](#6-example-damped-pendulum)
  - [7. Example of ODE model: prey-predator](#7-example-of-ode-model-prey-predator)
  - [8. Intro to nonlinear methods](#8-intro-to-nonlinear-methods)
  - [9. Gaining some intuition from Newton's law](#9-gaining-some-intuition-from-newtons-law)
  - [10. Interpretation of conservation of energy](#10-interpretation-of-conservation-of-energy)
  - [11. Example: pendulum with no friction](#11-example-pendulum-with-no-friction)
  - [12. Example: pendulum with friction](#12-example-pendulum-with-friction)
  - [13. Definition](#13-definition-1)
  - [14. Lyapunov's theory (First)](#14-lyapunovs-theory-first)
  - [15. Lyapunov's theory (Second)](#15-lyapunovs-theory-second)
  - [16. Example 1 (a linear warm-up)](#16-example-1-a-linear-warm-up)
  - [17. Example 2](#17-example-2)
  - [18. Example 3](#18-example-3)
  - [19. Example 4 (use of the 2nd theorem)](#19-example-4-use-of-the-2nd-theorem)
- [Part 6](#part-6)
  - [1. Motivating the rest of the ODE part of the note](#1-motivating-the-rest-of-the-ode-part-of-the-note)
  - [2. Boundary value problem - an example](#2-boundary-value-problem---an-example)
  - [3. Boundary value problems vs. initial value problems](#3-boundary-value-problems-vs-initial-value-problems)
  - [4. Motivating boundary eigenvalue problems](#4-motivating-boundary-eigenvalue-problems)
  - [5. Boundary eigenvalue problems (another example)](#5-boundary-eigenvalue-problems-another-example)
  - [6. Orthogonality of functions for periodic functions](#6-orthogonality-of-functions-for-periodic-functions)
  - [7. Definition](#7-definition)
  - [8. Euler-Fourier formulas](#8-euler-fourier-formulas)
  - [9. Example](#9-example)
  - [10. Connection to vector algebra](#10-connection-to-vector-algebra)
  - [11. Definition](#11-definition)
  - [12. Fourier convergence theorem](#12-fourier-convergence-theorem)
  - [13. Example](#13-example)
  - [14. Diffierentiation vs convergence](#14-diffierentiation-vs-convergence)
  - [15. Convergence of Fourier Series](#15-convergence-of-fourier-series)
  - [16. Gibbs phenomenon](#16-gibbs-phenomenon)
  - [17. Even \& odd functions: Fourier series](#17-even--odd-functions-fourier-series)
  - [18. Example: sawtooth wave](#18-example-sawtooth-wave)
  - [19. Complex form of Fourier series](#19-complex-form-of-fourier-series)
  - [20. Parseval's theorem for Fourier Series](#20-parsevals-theorem-for-fourier-series)
  - [21. Some basic PDEs](#21-some-basic-pdes)
  - [22. Heat (conduction) equation](#22-heat-conduction-equation)
  - [23. Separation of variables in action](#23-separation-of-variables-in-action)
  - [24. Non-homogeneous boundary conditions](#24-non-homogeneous-boundary-conditions)
  - [25. Diffierent boundary conditions](#25-diffierent-boundary-conditions)
- [Part 7](#part-7)
  - [1. Motivating example: vibrating guitar string](#1-motivating-example-vibrating-guitar-string)
  - [2. Wave equation: separation of variables](#2-wave-equation-separation-of-variables)
  - [3. Wave equation: general solution \& interpretation](#3-wave-equation-general-solution--interpretation)
  - [4. Wave equation: more general initial conditions](#4-wave-equation-more-general-initial-conditions)
  - [5. Laplace equation](#5-laplace-equation)
  - [6. Dirichlet problem for a rectangle](#6-dirichlet-problem-for-a-rectangle)
  - [7. Dirichlet problem for a circle](#7-dirichlet-problem-for-a-circle)
  - [8. Eigenvalue boundary problem revisited](#8-eigenvalue-boundary-problem-revisited)
  - [9. Sturm-Liouville boundary problems](#9-sturm-liouville-boundary-problems)
  - [10. Definition](#10-definition)
  - [11. Sturm-Liouville \& general 2nd-order ODEs](#11-sturm-liouville--general-2nd-order-odes)
  - [12. Theorem](#12-theorem)
  - [13. Theorem](#13-theorem)
  - [14. Sturm-Liouville \& orthonormal eigenfunctions](#14-sturm-liouville--orthonormal-eigenfunctions)
  - [15. Theorem](#15-theorem)
  - [16. Example](#16-example)
- [Part 8](#part-8)
  - [1. Banach Spaces](#1-banach-spaces)
    - [1.1 Basic Definitions](#11-basic-definitions)
    - [1.2 Reflexivity. Separability. Dual of $L^p$](#12-reflexivity-separability-dual-of-lp)
  - [2. Hilbert Spaces](#2-hilbert-spaces)
    - [2.1 Basic Definitions](#21-basic-definitions)
    - [2.2 The Dual Space of a Hilbert Space](#22-the-dual-space-of-a-hilbert-space)
    - [2.3 The Theorems of Stampacchia and Lax–Milgram](#23-the-theorems-of-stampacchia-and-laxmilgram)
    - [2.4 Hilbert Sums. Orthonormal Bases](#24-hilbert-sums-orthonormal-bases)
  - [3. Bounded Linear Operators](#3-bounded-linear-operators)
    - [3.1 The Baire Category Theorem](#31-the-baire-category-theorem)
    - [3.2 The Uniform Boundedness Principle](#32-the-uniform-boundedness-principle)
    - [3.3 The Open Mapping Theorem and the Closed Graph Theorem](#33-the-open-mapping-theorem-and-the-closed-graph-theorem)
    - [3.4 Linear Operators on Banach Spaces](#34-linear-operators-on-banach-spaces)
    - [3.5 Linear Operators on Hilbert Spaces](#35-linear-operators-on-hilbert-spaces)
  - [4. Weak Convergence](#4-weak-convergence)
  - [5. Compact Operators, Fredholm Theory](#5-compact-operators-fredholm-theory)
    - [5.1 Spectral Theory in Finite Dimensional Normed Spaces](#51-spectral-theory-in-finite-dimensional-normed-spaces)
    - [5.2 Basic Concepts](#52-basic-concepts)
    - [5.3  Spectral Properties of Bounded Linear Operators](#53--spectral-properties-of-bounded-linear-operators)
    - [5.4 Compact Linear Operators on Normed Spaces](#54-compact-linear-operators-on-normed-spaces)
    - [5.5 Further Properties of Compact Linear Operators](#55-further-properties-of-compact-linear-operators)
    - [5.6 Spectral Properties of Compact Linear Operators on Normed Spaces](#56-spectral-properties-of-compact-linear-operators-on-normed-spaces)

## Part 1

### 1. Definition

Given some independent real variables $x_1, x_2, \ldots x_n$ and some real-valued functions $y_1\left(x_j\right), y_2\left(x_j\right), \ldots y_p\left(x_j\right)$, a system of differential equations is a system of equations relating them involving the derivatives $\partial_j y_r, \partial_i \partial_j y_s \ldots$ of the functions:
$$
\mathcal{F}_s\left[y_r, \partial_j y_r, \ldots, x_j\right]=0, \quad s=1, \cdots, p
$$

### 2. Classiffcation: ODEs vs PDEs

Given the two sets $\left\{x_1, x_2, \ldots x_n\right\}$ and $y_1\left(x_j\right), y_2\left(x_j\right), \ldots y_p\left(x_j\right)$

(1)If $n=1$ : ordinary differential equation (ODE); by necessity, only total derivatives occur.

(2)If $n>1$ and partial derivatives with respect to different variables occur: partial differential equation (PDE).

If there is more than one equation involving functions and their derivatives: system of ODEs or PDEs
$$
\begin{array}{r}
\mathcal{F}_1\left[y_r, \partial_j y_r, \ldots x_j\right]=0, \\
\mathcal{F}_2\left[y_r, \partial_j y_r, \ldots x_j\right]=0, \\
\ldots \\
\mathcal{F}_s\left[y_r, \partial_j y_r, \ldots x_j\right]=0 .
\end{array}
$$

### 3. Classification: linear vs nonlinear

Consider ODEs with a single function of one variable $y(x)$. By collecting all the $y$-dependent terms, we can write the ODE as a condition on a (possibly $x$-dependent) map $L$ acting on $y$
$$
L[y]=f
$$
for some real function $f$. For example, $y^{\prime \prime}(x)-x y(x)=x^2$ corresponds to $L[y]=f$ with $L \equiv \frac{d^2}{d x^2}-x$ and $f(x)=x^2$.

### 4. Definition

We say an ODE is linear if the associated map $L$ is linear, i.e. if it satisfies the property
$$
L\left[a_1 y_1+a_2 y_2\right]=a_1 L\left[y_1\right]+a_2 L\left[y_2\right] \quad \forall a_1, a_2 \in \mathbb{R}
$$
and for any pair of functions $y_1, y_2$.


### 5. Example

Consider $L[y]=\frac{d^2 y}{d x^2}=0$.
Explicit calculation gives
$$
\begin{aligned}
L\left[a_1 y_1+a_2 y_2\right] & =\frac{d^2}{d x^2}\left[a_1 y_1+a_2 y_2\right]=\frac{d^2}{d x^2}\left[a_1 y_1\right]+\frac{d^2}{d x^2}\left[a_2 y_2\right] \\
& =a_1 \frac{d^2}{d x^2}\left[y_1\right]+a_2 \frac{d^2}{d x^2}\left[y_2\right]=a_1 L\left[y_1\right]+a_2 L\left[y_2\right],
\end{aligned}
$$
where we used standard differentiation properties.
Thus, we conclude $L[y]=\frac{d^2 y}{d x^2}=0$ is a linear ODE.

### 6. Example

Consider $L[y]=\left(\frac{d y}{d x}\right)^2=0$.
Explicit calculation gives
$$
\begin{aligned}
L\left[a_1 y_1+a_2 y_2\right] & =\left(\frac{d}{d x}\left(a_1 y_1+a_2 y_2\right)\right)^2=\left(a_1 y_1^{\prime}+a_2 y_2^{\prime}\right)^2 \\
& =a_1^2\left(y_1^{\prime}\right)^2+a_2^2\left(y_2^{\prime}\right)^2+2 a_1 a_2 y_1^{\prime} y_2^{\prime} \neq a_1 L\left[y_1\right]+a_2 L\left[y_2\right] .
\end{aligned}
$$

Thus, we conclude $L[y]=\left(\frac{d y}{d x}\right)^2=0$ is a nonlinear ODE.

### 7. Systems of 1st-order ODEs

Now, we focus on systems of 1st-order ODEs:
$$ ^{\prime}(t)=F_i\left(x_j(t), t\right) \quad i, j=1, \ldots n $$
because systems of higher-order ODEs can be transformed
into systems of 1st-order ODEs.

How? Method: arbitrary $n$-th order ODE
$$
y^{(n)}=F\left(y, y^{\prime}, \ldots, y^{(n-1)}, t\right) .
$$

(1) Change variables to $x_1, x_2, \cdots x_n$ :
$$
x_1=y, x_2=y^{\prime}, \quad \ldots \quad x_n=y^{(n-1)} .
$$
(2) Take derivatives of the new variables
$$
\begin{aligned}
& x_1^{\prime}=x_2, \quad x_2^{\prime}=x_3 \quad \ldots \quad x_{n-1}^{\prime}=x_n \\
& x_n^{\prime}=y^{(n)}=F\left(y, y^{\prime}, \ldots, y^{(n-1)}, t\right)=F\left(x_1, x_2, \ldots, x_n, t\right) .
\end{aligned}
$$
$n$ 1st-order ODEs for $\left(x_1, \cdots, x_n\right)$.


### 8. Example

Consider the 2nd order ODE with parametric dependence on $m, \gamma \in \mathbb{R}$ :
$$
m u^{\prime \prime}+\gamma u^{\prime}+k u=F(t)
$$

Define the new functions
$$
x_1(t) \equiv u(t), \quad x_2(t)=u^{\prime}(t)
$$

Then $\left(x_1(t), x_2(t)\right)$ satisfy the system of 1st-order ODEs
$$
\begin{aligned}
& x_1^{\prime}=u^{\prime}=x_2 \\
& x_2^{\prime}=u^{\prime \prime}=-\frac{\gamma}{m} u^{\prime}-\frac{k}{m} u+\frac{F(t)}{m}=-\frac{\gamma}{m} x_2-\frac{k}{m} x_1+\frac{F(t)}{m} .
\end{aligned}
$$

### 9.. Geometric interpretation

For fixed $t$ and $x_j, \boldsymbol{F}(\boldsymbol{x}, t)=\left(F_1\left(x_j, t\right), \cdots, F_n\left(x_j, t\right)\right) \in \mathbb{R}^n$ is a vector,

For fixed $t, \boldsymbol{F}(\cdot, t)=\left(F_1(\cdot, t), \cdots, F_n(\cdots, t)\right): \mathbb{R}^n \rightarrow \mathbb{R}^n$ is a vector field.

Solving an autonomous system: find an (integral) curve $\boldsymbol{x}(t)=\left(x_1(t), \cdots, x_n(t)\right)$ everywhere tangent to the vector field $\boldsymbol{F}$.

![](https://files.mdnice.com/user/36229/98dd27cd-db95-4f53-8fc3-40ba880b5767.jpg)

### 10. Existence and Uniqueness for Initial Value Problems

Initial value problem (IVP) for a single function of one variable is
$$
\frac{d x}{d t}=f(t, x), \quad x\left(t_0\right)=x_0  \qquad (1)
$$

Let $I$ be an interval and $t_0 \in I$. We say that a differentiable function $x: I \rightarrow \mathbb{R}$ is a solution of the equation above  in the interval $I$ if $\frac{d x}{d t}(t)=f(t, x(t))$ for all $t \in I$ and $x\left(t_0\right)=x_0$.


An important theorem by Charles Emile Picard (1856-1941) and Ernst Lindelöf (1870-1946) says that, under fairly mild assumption on $f$, initial value problems have unique solutions, at least locally.

A good way of visualising initial value problems and their solutions is via direction fields: at every point in the $(t, x)$ plane we draw a vector with the slope $f(t, x)$. Mathematically, we sketch the vector field
$$
\mathbf{V}(t, x)=\left(\begin{array}{c}
1 \\
f(t, x)
\end{array}\right)
$$



An initial value problem is essentially a precise set of directions for
how to travel through the plane, starting at a given point. How
can it not have a unique solution?

### 11. Picard-Lindelöf Theorem

Consider the intervals $I_T=\left[t_0-T, t_0+T\right]$ and $B_d=\left[x_0-d, x_0+d\right]$ for positive, real numbers $T, d$. Suppose that $f: I_T \times B_d \rightarrow \mathbb{R}$ is continuous and that its partial derivative $\frac{\partial f}{\partial x}: I \times B \rightarrow \mathbb{R}$ is also continuous. Then there is a $\delta>0$ so that the initial value problem  has a unique solution in the interval $I_\delta=\left[t_0-\delta, t_0+\delta\right]$.


(i) If $f$ is not continuous, then the initial value problem (1) may not have a solution. Consider, for example,
$$
f(t, x)=\left\{\begin{array}{ll}
1 & \text { if } \quad t \geq 0 \\
0 & \text { if } \quad t<0
\end{array} \quad \text { and } \quad x(0)=0 .\right.
$$

This would imply that $x(t)=t$ for $t \geq 0$ and $x(t)=0$ for $t<0$, which is not differentiable at $t=0$.

(ii) If $f$ does not have a continuous first order partial derivative, there may be more than one solution:
$$
\frac{d x}{d t}=x^{\frac{1}{3}}, \quad x(0)=0
$$
is solved by
$$
x(t)= \begin{cases}\left(\frac{2}{3}(t-c)\right)^{\frac{3}{2}} & \text { for } t \geq c \\ 0 & \text { for } t<c\end{cases}
$$
for any $c \geq 0$.


(iii) The solution may not exist for all $t \in \mathbb{R}$. The initial value problem
$$
\frac{d x}{d t}=2 t x^2, \quad x(0)=1
$$
has the solution
$$
x(t)=\frac{1}{1-t^2}, \quad t \in(-1,1)
$$


### 12.Theorem

The most general 1st order ODE system in $n$ variables is
$$
x_i^{\prime}(t)=F_i\left(x_j(t), t\right) \quad i, j=1, \ldots n . \qquad (2)
$$

Let $F_i\left(x_j, t\right)$ and $\partial_{x_j} F_i\left(x_j, t\right)$ be continuous in the region $R$ defined by $\alpha \leq t \leq \beta, \alpha_i \leq x_i \leq \beta_i, \quad \forall i$. Then, for each $\left(x_i^0, t_0\right) \in R, \exists$ interval $\left[t_0-\delta, t_0+\delta\right]$ in which there is a unique solution $x_i(t)$ of (2) satisfying the initial condition $x_i\left(t_0\right)=x_i^0, \quad i=1, \ldots n$.

If $\partial_t F_i=0$ for all $i$, i.e., $F_i=F_i\left(x_j\right)$, the systems is autonomous.




### 13. Definition

(1) A 1st order ODE system is linear if it has the form
$$
x_i^{\prime}=\frac{d x_i}{d t}=\sum_{j=1}^n P_{i j}(t) x_j+g_i(t) \quad i=1, \cdots, n .
\qquad (3)$$

Otherwise, it is nonlinear.

(2) If $g_i(t) \equiv 0$, the system is homogeneous.
Otherwise, it is non-homogeneous.

**14.Theorem**

Applying the Existence and Uniqueness theorem to the linear system. Suppose each of the $P_{i j}$ is a continuous function of $t$. Then
$$
F_i\left(x_j, t\right)=\sum_{j=1}^n P_{i j}(t) x_j+g_i(t) \quad 
$$
is continuous
and
$$\partial_{x_j} F_i\left(x_j, t\right)=P_{i j}(t) \quad
$$ 
is continuous.

If $P_{i j}(t), g_i(t)$ are continuous in $[\alpha, \beta] \Rightarrow \forall t_0 \in(\alpha, \beta) \exists$ unique solution $x_i(t)$ in $[\alpha, \beta]$ solving (3) and satisfying the initial condition $x_i\left(t_0\right)=x_i^0$.


## Part 2
### 1. Motivation

Most general homogeneous system:
$$
\frac{d x_i}{d t}=\sum_{j=1}^n P_{i j}(t) x_j \quad i=1, \ldots n
$$
or equivalently,
$$
\begin{aligned}
& \quad \frac{d \boldsymbol{x}}{d t}=P(t) \boldsymbol{x} \text {, where } P(t)=\left(\begin{array}{ccc}
P_{11}(t) & \ldots & P_{1 n}(t) \\
\cdot & \ldots & \cdot \\
P_{n 1}(t) & \ldots & P_{n n}(t)
\end{array}\right) \in M^{n \times n}, \\
& \text { with } \boldsymbol{x}(t)=\left(x_1(t), x_2(t), \ldots x_n(t)\right) .
\end{aligned}
$$

Question: how many solutions are there?


### 2. Principle of superposition

If $\left\{\boldsymbol{x}^{(j)}\right\}, j=1, \cdots, p$ is a set of $p$ solutions,
$$
\frac{d \boldsymbol{x}^{(j)}}{d t}=P(t) \boldsymbol{x}^{(j)} \Rightarrow \sum_{j=1}^p c_j \boldsymbol{x}^{(j)}, c_j \in \mathbb{R}, \text { is a solution }
$$

Indeed,
$$
\begin{aligned}
\frac{d\left(\sum_{j=1}^p c_j \boldsymbol{x}^{(j)}\right)}{d t} & =\sum_{j=1}^p c_j \frac{d \boldsymbol{x}^{(j)}}{d t}=\sum_{j=1}^p c_j P(t) \boldsymbol{x}^{(j)} \\
& =P(t)\left(\sum_{j=1}^p c_j \boldsymbol{x}^{(j)}\right)
\end{aligned}
$$
where we used the linearity satisfied by the product of matrices with vectors.

- The space of solutions to the homogeneous linear system is a vector space,
- The dimension of this vector space is $n$ : there are $n$ linearly independent solutions.

We already showed 1.

Question: when is a set of $n$ solutions linearly independent?
- $n$ vectors are linearly independent if the determinant of the squared matrix formed with each of them as a column is non-zero.

### 3. Wronskian

Given $n$ solutions $\left\{\boldsymbol{x}^{(j)}\right\}$, we define the Wronskian at $t$ as the determinant
$$
W\left[\boldsymbol{x}^{(j)}\right](t)=\left|\begin{array}{ccc}
x_1^{(1)}(t) & \ldots & x_1^{(n)}(t) \\
\dot{x_n} & \ldots & \dot{0} \\
x_n^{(1)}(t) & \ldots & x_n^{(n)}(t)
\end{array}\right|
$$
$W(t) \neq 0$ iff the $\left\{\boldsymbol{x}^{(j)}\right\}$ are linearly independent.

Fundamental set of solutions:

If $W(t) \neq 0$ for $\alpha \leq t \leq \beta$, any solution $\boldsymbol{x}(t)$ is a linear combination of the $\boldsymbol{x}^{(j)}$ :
$$
\boldsymbol{x}(t)=c_1 \boldsymbol{x}^{(1)}(t)+\cdots+c_n \boldsymbol{x}^{(n)}(t) .
$$

The $\left\{\boldsymbol{x}^{(j)}\right\}$ form a fundamental set of solutions.

Proof: $\boldsymbol{x}(t)=c_1 \boldsymbol{x}^{(1)}(t)+\cdots+c_n \boldsymbol{x}^{(n)}(t)$ satisfies the system of ODEs, by the principle of superposition.

It can also satisfy any initial condition $\boldsymbol{x}\left(t_0\right)=\boldsymbol{y}$ for a suitable choice of the $c_j$ since the equations
$$
\begin{gathered}
c_1 x_1^{(1)}\left(t_0\right)+\cdots+c_n x_1^{(n)}\left(t_0\right)=y_1 \\
\ldots \\
c_1 x_n^{(1)}\left(t_0\right)+\cdots+c_n x_n^{(n)}\left(t_0\right)=y_n
\end{gathered}
$$
have a unique solution $\left\{c_j\right\}$ when $W\left(t_0\right) \neq 0.$

Although it seems that we need $W(t) \neq 0$ for all $t \in[\alpha, \beta]$, it is enough to check $W\left(t_0\right) \neq 0$ for some $t_0 \in[\alpha, \beta]$.

### 4. Abel's theorem

If $W\left(t_0\right) \neq 0$ for some $t_0$, then $W(t) \neq 0$ for all $\alpha \leq t \leq \beta$.

Proof: suppose $W\left(t_*\right)=0$ for some $t_* \in[\alpha, \beta]$; then the $\left\{\boldsymbol{x}^{(j)}\left(t_*\right)\right\}$ are linearly dependent, that is, there exist $\left(c_1, \cdots, c_n\right) \neq(0, \cdots, 0)$ such that
$$
c_1 \boldsymbol{x}^{(1)}\left(t_*\right)+\cdots+c_n \boldsymbol{x}^{(n)}\left(t_*\right)=0 .
$$

Consider $\boldsymbol{z}(t)=c_1 \boldsymbol{x}^{(1)}(t)+\cdots+c_n \boldsymbol{x}^{(n)}(t)$.
It satisfies the ODE system and $\boldsymbol{z}\left(t_*\right)=0$.
By uniqueness, $\boldsymbol{z}(t)=0$ for all $t \in[\alpha, \beta]$, hence
$$
c_1 \boldsymbol{x}^{(1)}\left(t_0\right)+\cdots+c_n \boldsymbol{x}^{(n)}\left(t_0\right)=0
$$
and $W\left(t_0\right)=0$, a contradiction.

### 5. Abel's formula

Consider a homogeneous linear second-order ordinary differential equation
$$
x^{\prime \prime}+p(t) x^{\prime}+q(t) x=0
$$
on an interval $I$ of the real line with real- or complex-valued continuous functions $p$ and $q$. Abel's identity states that the Wronskian $W=\left(x_1, x_2\right)$ of two real- or complex-valued solutions $x_1$ and $x_2$ of this differential equation, that is the function defined by the determinant
$$
W\left(x_1, x_2\right)(t)=\left|\begin{array}{cc}
x_1(t) & x_2(t) \\
x_1^{\prime}(t) & x_2^{\prime}(t)
\end{array}\right| \mathrm{I}=x_1(t) x_2^{\prime}(t)-x_1^{\prime}(t) x_2(t), \quad t \in I
$$
satisfies the relation
$$
W\left(x_1, x_2\right)(t)=W\left(x_1, x_2\right)\left(t_0\right) \cdot e^{-\int_{t_0}^t p(s) d s}, \quad t \in I
$$
for each point $t_0 \in I$. 

Proof: Differentiating the Wronskian using the product rule gives (writing $W$ for $W\left(x_1, x_2\right)$ and omitting the argument $t$ for brevity)
$$
\begin{gathered}
W^{\prime}=x_1^{\prime} x_2^{\prime}+x_1 x_2^{\prime \prime}-x_1^{\prime \prime} x_2-x_1^{\prime} x_2^{\prime} \\
=x_1 x_2^{\prime \prime}-x_1^{\prime \prime} x_2 .
\end{gathered}
$$

Solving for $x$ in the original differential equation yields
$$
x^{\prime \prime}=-\left(p x^{\prime}+q x\right) .
$$

Substituting this result into the derivative of the Wronskian function to replace the second derivatives of $x_1$ and $x_2$ gives
$$
\begin{gathered}
W^{\prime}=-x_1\left(p x_2^{\prime}+q x_2\right)+\left(p x_1^{\prime}+q x_1\right) x_2 \\
=-p\left(x_1 x_2^{\prime}-x_1^{\prime} x_2\right) \\
=-p W .
\end{gathered}
$$

This is a first-order linear differential equation, and it remains to show that Abel's identity gives the unique solution, which attains the value $W\left(t_0\right)$ at $t_0$. Since the function $p$ is continuous on $I$, it is bounded on every closed and bounded subinterval of $I$ and therefore integrable, hence
$$
V(t)=W(t) \exp \left(\int_{t_0}^t p(\xi) \mathrm{d} \xi\right), \quad t \in I,
$$
is a well-defined function. Differentiating both sides, using the product rule, the chain rule, the derivative of the exponential function and the fundamental theorem of calculus, one obtains
$$
V^{\prime}(t)=\left(W^{\prime}(t)+W(t) p(t)\right) \exp \left(\int_{t_0}^t p(\xi) \mathrm{d} \xi\right)=0, \quad t \in I,
$$
due to the differential equation for $W$. Therefore, $V$ has to be constant on $I$, because otherwise we would obtain a contradiction to the mean value theorem (applied separately to the real and imaginary part in the complex-valued case). 

Since $V\left(t_0\right)=W\left(t_0\right)$, Abel's identity follows by solving the definition of $V$ for $W(t)$.

### 6. Homogeneous systems with constant coeiffcients

Given
$$
\frac{d x}{d t}=A x \qquad  (1)
$$
where $A \in M^{n \times n}$ is constant.
Strategy: As with 2nd order homogeneous ODEs, seek exponential solutions:
$$
\boldsymbol{x}=e^{r t} \boldsymbol{\xi} \Rightarrow \frac{d \boldsymbol{x}}{d t}=r \boldsymbol{x}
$$

Into (1),
$$
(A-r \mathbb{I}) \boldsymbol{\xi}=0
$$

Eigenvalue problem: a linear algebra problem.

Thus, solutions of
$$
\frac{d x}{d t}=A x
$$
have the form
$$
\boldsymbol{x}=\sum_{j=1}^n c_j e^{r_j t} \boldsymbol{\xi}^{(j)}
$$
where

(1) $\operatorname{det}(A-r \mathbb{I})=0$ : this determines $\left\{r_j\right\}$ as eigenvalues of $A$
(2) $\boldsymbol{\xi}^{(j)}$ is the eigenvector associated to the eigenvalue $r_j$
$$
\left(A-r_j \mathbb{I}\right) \boldsymbol{\xi}^{(j)}=0
$$

Remark: We have assumed all eigenvalues $r_j$ are different. When $r_j$ has multiplicity $\geq 2$, we need new methods.

### 7. Example

Consider the linear ODE system
$$
\frac{d x}{d t}=\left(\begin{array}{ll}
1 & 1 \\
4 & 1
\end{array}\right) x \equiv A x
$$

We look for solutions of the form $x=\xi e^{r t}$ where $\boldsymbol{\xi}=\left(\begin{array}{l}y \\ z\end{array}\right)$. Introducing $\xi e^{r t}$ into the ODEs gives the eigenvalue problem
$$
(A-r \mathbb{I}) \boldsymbol{\xi}=0 .
$$

Non-trivial solutions require $\operatorname{det}(A-r \mathbb{I})=0$,
$$
\left|\begin{array}{cc}
1-r & 1 \\
4 & 1-r
\end{array}\right|=(1-r)^2-4=r^2-2 r-3=(r-3)(r+1)=0 .
$$

Thus, $r_1=3$ and $r_2=-1$, giving rise to a solution of the form
$$
\boldsymbol{x}=c_1 e^{3 t} \boldsymbol{\xi}^{(1)}+c_2 e^{-t} \boldsymbol{\xi}^{(2)} .
$$

We are left to determine the two eigenvectors.

When $r=r_1=3$, the original system is equivalent to
$$
\begin{aligned}
\left(1-r_1\right) y+z=0 & \Rightarrow \quad-2 y+z=0 \\
4 y+\left(1-r_1\right) z=0 & \Rightarrow \quad 4 y-2 z=0 .
\end{aligned}
$$

Only one equation is linearly independent Thus, $z=2 y$.

The eigenvector equals
$$
\xi^{(1)}=\left(\begin{array}{l}
y \\
z
\end{array}\right)=y\left(\begin{array}{l}
1 \\
2
\end{array}\right),
$$
where $y$ is any real number. The latter can be absorbed into $c_1$.

When $r=r_2=-1$, the original system is equivalent to
$$
\begin{aligned}
\left(1-r_2\right) y+z=0 & \Rightarrow \quad 2 y+z=0 \\
4 y+\left(1-r_2\right) z=0 & \Rightarrow \quad 4 y+2 z=0 .
\end{aligned}
$$

Only one equation is linearly independent Thus, $z=-2 y$

The eigenvector equals
$$
\xi^{(1)}=\left(\begin{array}{l}
y \\
z
\end{array}\right)=y\left(\begin{array}{c}
1 \\
-2
\end{array}\right),
$$
where $y$ is any real number. The latter can be absorbed into $c_2$.

Solutions:
$$
\boldsymbol{x}^{(1)}=e^{3 t}\left(\begin{array}{l}
1 \\
2
\end{array}\right), \quad \boldsymbol{x}^{(2)}=e^{-t}\left(\begin{array}{c}
1 \\
-2
\end{array}\right)
$$

They are linearly independent. Indeed
$$
\left|\begin{array}{cc}
e^{3 t} & e^{-t} \\
2 e^{3 t} & -2 e^{-t}
\end{array}\right|=-4 e^{2 t} \neq 0
$$

Thus, the general solution is
$$
\boldsymbol{x}=c_1 e^{3 t}\left(\begin{array}{l}
1 \\
2
\end{array}\right)+c_2 e^{-t}\left(\begin{array}{c}
1 \\
-2
\end{array}\right).
$$

### 8. Three forms

The follwing parts are about the general solution to equations of the form
$$
\frac{d x}{d t}=A x,
$$
where $\boldsymbol{x}: \mathbb{R} \rightarrow \mathbb{R}^n$ is a vector-valued function and $A$ a constant $n \times n$ matrix. Solutions are sought in the form $\boldsymbol{x}(t)=\boldsymbol{\xi} e^{r t}$ with $r$ eigenvalue of $A$ and $\boldsymbol{\xi}$ eigenvector.

There are several cases:

(1)real and different eigenvalues,

(2)complex and different eigenvalues,

(3) repeated eigenvalues.

### 9. Real & different eigenvalues

By assumption,
$$
r_i \neq r_j \quad \forall i, j=1, \ldots n \Rightarrow \text { for each } r_i, \exists \xi^{(i)}
$$
so fundamental solutions take the form
$$
\boldsymbol{x}^{(i)}=\boldsymbol{\xi}^{(i)} e^{r_i t}
$$

This set of $n$ solutions is linearly independent if
$$
\begin{aligned}
& \operatorname{det} X(t) \neq 0 \text { with } X(t)=\left(\begin{array}{ccc}
\xi_1^{(1)} e^{r_1 t} & \ldots & \xi_1^{(n)} e^{r_n t} \\
\cdot & \ldots & \cdot \\
\xi_n^{(1)} e^{r_1 t} & \ldots & \xi_n^{(n)} e^{r_n t}
\end{array}\right) \\
& \operatorname{det} X(t)=e^{\left(\sum_{j=1}^n r_j\right) t} W\left[\xi^{(1)}, \ldots \xi^{(n)}\right] \neq 0
\end{aligned}
$$
since the $n$ eigenvectors $\xi^{(j)}$ are linearly independent.
The general solution reads
$$
\boldsymbol{x}(t)=\sum_{j=1}^n c_j e^{r_j t} \boldsymbol{\xi}^{(j)}.
$$

### 10. Example

Consider the linear ODE system for $n=3$
$$
\frac{d x}{d t}=\left(\begin{array}{lll}
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{array}\right) x \equiv A x
$$

We look for solutions of the form $x=\xi e^{r t}$ where $\boldsymbol{\xi}=\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$. Introducing $\boldsymbol{\xi} e^{r t}$ in the ODE, we obtain
$$
(A-r \mathbb{I}) \xi=0 .
$$

This is the homogeneous linear system:
$$
\begin{array}{r}
-r x+y+z=0 \\
x-r y+z=0 \\
x+y-r z=0 .
\end{array}
$$

Eigenvalues:
$$
\begin{aligned}
\operatorname{det}(A-r \mathbb{I}) & =0 \\
& =-r^3+3 r+2=(r-2)(r+1)^2=0
\end{aligned}
$$

Thus, $r_1=2$ has multiplicity one and $r_2=-1$ has algebraic multiplicity 2 , giving rise to a solution of the form
$$
\boldsymbol{x}=c_1 e^{2 t} \boldsymbol{\xi}^{(1)}+c_2 e^{-t} \boldsymbol{\xi}^{(2)}+c_2 e^{-t} \boldsymbol{\xi}^{(3)},
$$

When $r=r_1=2$, the original system is equivalent to
$$
\begin{aligned}
-r x+y+z=0 & \Rightarrow \quad-2 x+y+z=0 \\
x-r y+z=0 & \Rightarrow \quad x-2 y+z=0 \\
x+y-r z=0 & \Rightarrow \quad x+y-2 z=0
\end{aligned}
$$

The 3rd equation is equivalent to the sum of the first two. Subtracting the 1 st and $2 \mathrm{nd} \Rightarrow x=y$ introducing into the 1 st $\Rightarrow x=y=z$

The eigenvector equals
$$
\xi^{(1)}=\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=x\left(\begin{array}{l}
1 \\
1 \\
1
\end{array}\right)
$$
where $x$ is any real number.

When $r=r_2=-1$, the original system is equivalent to
$$
\begin{array}{rll}
-r x+y+z=0 & \Rightarrow & x+y+z=0 \\
x-r y+z=0 & \Rightarrow & x+y+z=0 \\
x+y-r z=0 & \Rightarrow & x+y+z=0 .
\end{array}
$$

Clearly, there is a unique linearly independent equation Its solution is $z=-y-x$. The eigenvector(s) satisfy
$$
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=x\left(\begin{array}{c}
1 \\
0 \\
-1
\end{array}\right)+y\left(\begin{array}{c}
0 \\
1 \\
-1
\end{array}\right)
$$
where $x, y$ are any real numbers.
Thus, there are two linearly independent eigenvectors.
$$
\boldsymbol{\xi}^{(2)}=x\left(\begin{array}{c}
1 \\
0 \\
-1
\end{array}\right), \quad \boldsymbol{\xi}^{(3)}=y\left(\begin{array}{c}
0 \\
1 \\
-1
\end{array}\right)
$$

The linear ODE system
$$
\frac{d x}{d t}=\left(\begin{array}{lll}
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{array}\right) x \equiv A x
$$
has general solution
$$
\boldsymbol{x}(t)=c_1 e^{2 t}\left(\begin{array}{l}
1 \\
1 \\
1
\end{array}\right)+c_2 e^{-t}\left(\begin{array}{c}
1 \\
0 \\
-1
\end{array}\right)+c_3 e^{-t}\left(\begin{array}{c}
0 \\
1 \\
-1
\end{array}\right) .
$$

Lesson: if a given eigenvalue $r$ has multiplicity $s \geq 2$, the method still works if its geometric multiplicity (number of linearly independent eigenvectors $\boldsymbol{\xi}_r$ ) equals $s$.

### 11. Complex eigenvalues

Consider a linear ODE system
$$
\frac{d x}{d t}=A x
$$
with matrix $A$ real. Then if $r_1=\lambda+i \mu$ is one of its eigenvalues eigenvalue, i.e.
$$
\left(A-r_1 \mathbb{I}\right) \xi_1=0
$$
taking the complex conjugate,
$$
\left(A-r_1^{\star} \mathbb{I}\right) \xi_1^{\star}=0 .
$$

Thus, $r_1^{\star}=\lambda-i \mu$ is also an eigenvalue with eigenvector $\xi_1^{\star}$.

Summary: We find two solutions
$$
\boldsymbol{x}_1(t)=e^{r_1 t} \boldsymbol{\xi}_1, \quad \boldsymbol{x}_2(t)=e^{r_1^{\star} t} \boldsymbol{\xi}_1^{\star}
$$

If we are interested in real solutions, we can proceed as follows. Write $\boldsymbol{\xi}_1=\boldsymbol{a}+i \boldsymbol{b}$ and compute $\boldsymbol{x}_1(t)$
$$
\begin{aligned}
\boldsymbol{x}_1(t) & =(\boldsymbol{a}+i \boldsymbol{b}) e^{\lambda t}(\cos \mu t+i \sin \mu t) \\
& =e^{\lambda t}(\boldsymbol{a} \cos \mu t-\boldsymbol{b} \sin \mu t)+i e^{\lambda t}(\boldsymbol{a} \sin \mu t+\boldsymbol{b} \cos \mu t) \\
& \equiv \boldsymbol{u}(t)+i \boldsymbol{v}(t)
\end{aligned}
$$

The 2 real solutions are
$$
\begin{aligned}
& \boldsymbol{u}(t)=e^{\lambda t}(\boldsymbol{a} \cos \mu t-\boldsymbol{b} \sin \mu t) \\
& \boldsymbol{v}(t)=e^{\lambda t}(\boldsymbol{a} \sin \mu t+\boldsymbol{b} \cos \mu t) .
\end{aligned}
$$

General solution: $\boldsymbol{x}(t)=c_1 \boldsymbol{u}(t)+c_2 \boldsymbol{v}(t)+\ldots$

### 12. Example

Consider the linear ODE system
$$
\frac{d x}{d t}=\left(\begin{array}{cc}
-\frac{1}{2} & 1 \\
-1 & -\frac{1}{2}
\end{array}\right) \boldsymbol{x} \equiv A \boldsymbol{x} .
$$

We look for solutions of the form $x=\xi e^{r t}$ where $\xi=\left(\begin{array}{l}x \\ y\end{array}\right)$ because the system involves a $2 \times 2$ matrix. When we introduce $\boldsymbol{\xi} e^{r t}$ in the ODE, we get the equation
$$
(A-r \mathbb{I}) \boldsymbol{\xi}=0 \text {. }
$$

This is an homogeneous linear algebra system of equations:
$$
\begin{gathered}
\left(-\frac{1}{2}-r\right) x+y=0 \\
x+\left(\frac{1}{2}+r\right) y=0 .
\end{gathered}
$$

For the solution not to be $y=x=0$, we require the determinant of the matrix of coefficients to vanish
$$
\begin{aligned}
\operatorname{det}(A-r \mathbb{I}) & =0 \\
& =\left(\frac{1}{2}+r\right)^2+1=r^2+r+\frac{5}{4}=0 \Rightarrow r_{ \pm}=-\frac{1}{2} \pm i
\end{aligned}
$$

Eigenvectors:
$$
\begin{aligned}
& -r=r_{+} \Rightarrow y=i x \Rightarrow \xi_{+} \propto\left(\begin{array}{c}
1 \\
i
\end{array}\right) \\
& >r=r_{-} \Rightarrow y=-i x \Rightarrow \xi_{-} \propto\left(\begin{array}{c}
1 \\
-i
\end{array}\right)
\end{aligned}
$$

General solution: one complex solution is
$$
\begin{aligned}
\boldsymbol{x}_{+} & =e^{-t / 2}(\cos t+i \sin t)\left(\begin{array}{c}
1 \\
i
\end{array}\right) \\
& =e^{-t / 2}\left(\begin{array}{c}
\cos t \\
-\sin t
\end{array}\right)+i e^{-t / 2}\left(\begin{array}{c}
\sin t \\
\cos t
\end{array}\right)
\end{aligned}
$$

Thus, we can identify
$$
\boldsymbol{u}(t)=e^{-t / 2}\left(\begin{array}{c}
\cos t \\
-\sin t
\end{array}\right), \quad \boldsymbol{v}(t)=e^{-t / 2}\left(\begin{array}{c}
\sin t \\
\cos t
\end{array}\right)
$$

General real solution: $\boldsymbol{x}(t)=c_1 \boldsymbol{u}(t)+c_2 \boldsymbol{v}(t)$.

Remark: $\boldsymbol{u}$ and $\boldsymbol{v}$ are linearly independent !!
$$
W[\boldsymbol{u}, \boldsymbol{v}]=e^{-t} \neq 0
$$

### 13. Matrix algebra methods

What if:
One of the $r_i$ has algebraic multiplicity $s \geq 2$ and geometric multiplicity <s?

We do not have $\mathrm{n}$ linearly independent solutions: missing solutions.

Strategy: Use matrix algebra methods.

### 14. Definition

Given a linear system of 1st order ODEs
$$
\frac{d x}{d t}=P(t) \boldsymbol{x},
$$
with $n$ fundamental solutions $\boldsymbol{x}^{(i)} i=1,2, \ldots, n$.

A fundamental matrix $\Psi(t)$ is an $n \times n$ matrix with fundamental solutions $\boldsymbol{x}^{(i)}$ as columns:
$$
\Psi(t)=\left(\begin{array}{cccc}
x_1^{(1)} & x_1^{(2)} & \ldots & x_1^{(n)} \\
x_2^{(1)} & x_2^{(2)} & \ldots & x_2^{(n)} \\
\cdot & \cdot & \ldots & \cdot \\
x_{n-1}^{(1)} & x_{n-1}^{(2)} & \ldots & x_{n-1}^{(n)} \\
x_n^{(1)} & x_n^{(2)} & \ldots & x_n^{(n)}
\end{array}\right)
$$

(1) $\operatorname{det} \Psi(t)=W(t) \neq 0$ because $\boldsymbol{x}^{(i)}$ form a $n$ fundamental set.

(2)The general solution can be written as the matrix product
$$
\boldsymbol{x}(t)=\sum_{j=1}^n c_j \boldsymbol{x}^{(j)}=\Psi(t) \boldsymbol{c}, \quad \text { where } \quad \boldsymbol{c}=\left(\begin{array}{c}
c_1 \\
c_2 \\
\cdot \\
\cdot \\
c_n
\end{array}\right)
$$

(3)If the system satisfies the initial condition: $\boldsymbol{x}\left(t_0\right)=\boldsymbol{x}_0$, then the general solution equals
$$
\begin{aligned}
\boldsymbol{x}\left(t_0\right) & =\Psi\left(t_0\right) \boldsymbol{c}=\boldsymbol{x}_0 \Rightarrow \boldsymbol{c}=\Psi^{-1}\left(t_0\right) \boldsymbol{x}_0 \\
\boldsymbol{x}(t) & =\Psi(t) \boldsymbol{c}=\Psi(t) \Psi^{-1}\left(t_0\right) \boldsymbol{x}_0 .
\end{aligned}
$$

Find the solution + including initial data requires to invert $\Psi(t)$.

### 15. Property

The fundamental matrix satisfies the matrix equation
$$
\Psi^{\prime}=P \Psi
$$

Here,
$$
\Psi^{\prime}=\frac{d \Psi(t)}{d t}=\left(\begin{array}{cccc}
\frac{d x_1^{(1)}}{d t} & \frac{d x_1^{(2)}}{d t} & \ldots & \frac{d x_1^{(n)}}{d t} \\
\frac{d x_2^{(1)}}{d t} & \frac{d x_2^{(2)}}{d t} & \ldots & \frac{d x_2^{(n)}}{d t} \\
\cdot & \cdot & \ldots & \cdot \\
\frac{d x_n^{(1)}}{d t} & \frac{d x_n^{(2)}}{d t} & \ldots & \frac{d x_n^{(n)}}{d t}
\end{array}\right)
$$

The property is clear:
$$
\left(\boldsymbol{x}^{(i)}\right)^{\prime}=P \boldsymbol{x}^{(i)} \Rightarrow\left(\boldsymbol{x}^{(1)}, \cdots, \boldsymbol{x}^{(n)}\right)^{\prime}=P\left(\boldsymbol{x}^{(1)}, \cdots, \boldsymbol{x}^{(n)}\right) .
$$

### 16. Definition

Consider now $P(t)=A$, a constant $n \times n$ matrix. Linear ODE systems generalise
$$
\frac{d x}{d t}=a x \Rightarrow x(t)=e^{a t} x(0) .
$$

We can generalise the exponential function to matrices:


Define the exponential of a matrix $A$ as
$$
e^{A t}=\sum_{n=0}^{\infty} \frac{(A t)^n}{n !}=\mathbb{I}+A t+\frac{1}{2 !} A^2 t^2+\cdots
$$

Alternatively, we could have used $e^{A t}=\lim _{n \rightarrow \infty}\left(\mathbb{I}+\frac{1}{n} A\right)^n$, but this is less useful in this context.

It can be shown that the previous definition converges. Interesting properties:

(1) $e^{A+B}=e^A e^B \quad$ if $A B=B A$.

(2) $\left.e^{A t}\right|_{t=0}=\mathbb{I}$.

(3) $\frac{d e^{A t}}{d t}=A e^{A t}$ since
$$
\begin{aligned}
\frac{d e^{A t}}{d t} & =\sum_{n=1}^{\infty} \frac{A^n t^{n-1}}{(n-1) !}=A \sum_{n=1}^{\infty} \frac{A^{n-1} t^{n-1}}{(n-1) !}= \\
& =A \sum_{m=0}^{\infty} \frac{A^m t^m}{m !}=A\left(\mathbb{I}+\sum_{m=1}^{\infty} \frac{A^m t^m}{m !}\right)=A e^{A t} .
\end{aligned}
$$

Conclusion:

$e^{A t}=\Psi(t)$ for $\Psi(0)=\mathbb{I}$.
$\boldsymbol{x}(t)=e^{A t} \boldsymbol{x}(0) \Leftrightarrow e^{A t}=\Psi(t) \Psi^{-1}(0)$.

In lucky cases, it can evaluate series. For example,
$$
A=\left(\begin{array}{rr}
0 & 1 \\
-1 & 0
\end{array}\right) \Rightarrow A^2=-\mathbb{I}, \quad A^3=-A, \quad A^4=\mathbb{I}
$$
so
$$
\begin{aligned}
e^{A t} & =\sum_{n \text { even }}(-1)^{\frac{n}{2}} \frac{t^n}{n !} \mathbb{I}+\sum_{n \text { odd }}(-1)^{\frac{n-1}{2}} \frac{t^n}{n !} A \\
& =\cos t \mathbb{I}+\sin t A \\
& =\left(\begin{array}{rr}
\cos t & \sin t \\
-\sin t & \cos t
\end{array}\right)
\end{aligned}
$$


### 17. Relation to diagonalisation

Suppose that $A$ has a basis of eigenvectors $\xi^{(1)}, \ldots \xi^{(n)}$ with eigenvalues $r_1, \ldots, r_n$, and consider the matrix $T$ with the eigenvectors $\boldsymbol{\xi}^{(i)}$ as columns
$$
T=\left(\begin{array}{cccc}
\xi_1^{(1)} & \xi_1^{(2)} & \ldots & \xi_1^{(n)} \\
\xi_2^{(1)} & \xi_2^{(2)} & \ldots & \xi_2^{(n)} \\
\cdot & \cdot & \ldots & \cdot \\
\cdot & \cdot & \ldots & \cdot \\
\xi_n^{(1)} & \xi_n^{(2)} & \ldots & \xi_n^{(n)}
\end{array}\right)
$$

Observation: The matrix $A T$ has columns equal to
$$
A \xi^{(i)}=r_i \xi^{(i)} .
$$

Thus, the matrix $A T$ equals
$$
\begin{aligned}
A T & =\left(\begin{array}{cccc}
r_1 \xi_1^{(1)} & r_2 \xi_1^{(2)} & \ldots & r_n \xi_1^{(n)} \\
r_1 \xi_2^{(1)} & r_2 \xi_2^{(2)} & \ldots & r_n \xi_2^{(n)} \\
\cdot & \cdot & \ldots & \cdot \\
\cdot & \cdot & \ldots & \cdot \\
r_1 \xi_n^{(1)} & r_2 \xi_n^{(2)} & \ldots & r_n \xi_n^{(n)}
\end{array}\right)=T\left(\begin{array}{cccc}
r_1 & 0 & \ldots & 0 \\
0 & r_2 & \ldots & 0 \\
\cdot & \cdot & \ldots & \cdot \\
0 & 0 & \ldots & r_n
\end{array}\right) \\
& =T \operatorname{diag}\left(r_1, r_2, \ldots r_n\right) \equiv T D \\
& \Rightarrow D=T^{-1} A T
\end{aligned}
$$

$D=T^{-1} A T \Leftrightarrow$ change of basis.

To see this more explicitly, consider the change of variables
$$
\boldsymbol{x}=T \boldsymbol{y} \Rightarrow T \frac{d \boldsymbol{y}}{d t}=A T \boldsymbol{y} \Rightarrow \frac{d \boldsymbol{y}}{d t}=T^{-1} A T \boldsymbol{y}=D \boldsymbol{y} .
$$

In the new variables, the solution to the linear ODE system is trivial:
$$
\boldsymbol{y}^{(i)}=e^{r_i t} \boldsymbol{e}^{(i)}=e^{r_i t}\left(\begin{array}{l}
0 \\
\cdot \\
1 \\
0 \\
\cdot
\end{array}\right) 1 \text { i-th component }
$$

Thus, its fundamental matrix equals
$$
Q(t)=e^{D t}=\operatorname{diag}\left(e^{r_1 t}, e^{r_2 t}, \ldots, e^{r_n t}\right).
$$

The fundamental matrix in the original variables $\boldsymbol{x}$ is
$$
\Psi(t)=T Q(t)=T \operatorname{diag}\left(e^{r_1 t}, e^{r_2 t}, \ldots, e^{r_n t}\right) .
$$

The exponential matrix is
$$
e^{A t}=\Psi(t) \Psi^{-1}(0)=T Q T^{-1}=T \operatorname{diag}\left(e^{r_1 t}, e^{r_2 t}, \ldots, e^{r_n t}\right) T^{-1} .
$$

Alternative derivation: note that $T^{-1} A^k T=\operatorname{diag}\left(r_1^k, \cdots, r_n^k\right)$,
$$
T^{-1} e^{A t} T=\sum_{k=0}^{\infty} \frac{1}{k !} \operatorname{diag}\left(r_1^k, \cdots, r_n^k\right)=\operatorname{diag}\left(e^{r_1 t}, \cdots, e^{r_n t}\right) .
$$

But, this works when $A$ is diagonalisable.

### 18. Example

$$
\frac{d x}{d t}=\left(\begin{array}{ll}
1 & 1 \\
4 & 1
\end{array}\right) x \equiv A x
$$

Its eigenvalues are:
$$
\operatorname{det}(A-r \mathbb{I})=(r-3)(r+1)=0 .
$$

After solving for the eigenvectors, the general solution is
$$
\boldsymbol{x}=c_1 e^{3 t}\left(\begin{array}{l}
1 \\
2
\end{array}\right)+c_2 e^{-t}\left(\begin{array}{c}
1 \\
-2
\end{array}\right)
$$

Take the two eigenvectors $\boldsymbol{\xi}^{(1)}$ and $\boldsymbol{\xi}^{(2)}$ and construct the change of basis matrix
$$
T=\left(\begin{array}{cc}
1 & 1 \\
2 & -2
\end{array}\right) \Rightarrow T^{-1}=\left(\begin{array}{cc}
\frac{1}{2} & \frac{1}{4} \\
\frac{1}{2} & -\frac{1}{4}
\end{array}\right)
$$

Notice that:
$$
T^{-1} A T=T^{-1}\left(\begin{array}{ll}
1 & 1 \\
4 & 1
\end{array}\right)\left(\begin{array}{cc}
1 & 1 \\
2 & -2
\end{array}\right)=\left(\begin{array}{cc}
\frac{1}{2} & \frac{1}{4} \\
\frac{1}{2} & -\frac{1}{4}
\end{array}\right)\left(\begin{array}{cc}
3 & -1 \\
6 & 2
\end{array}\right)=\left(\begin{array}{cc}
3 & 0 \\
0 & -1
\end{array}\right)
$$

Thus, when we change variable from $\boldsymbol{x}$ to $\boldsymbol{y}, \boldsymbol{x}=T \boldsymbol{y}$, the linear ODE system becomes diagonal,
$$
\frac{d \boldsymbol{y}}{d t}=\left(\begin{array}{cc}
3 & 0 \\
0 & -1
\end{array}\right) \boldsymbol{y} \equiv D \boldsymbol{y}
$$

The fundamental matrix in the original basis equals
$$
\Psi(t)=T Q=\left(\begin{array}{cc}
1 & 1 \\
2 & -2
\end{array}\right)\left(\begin{array}{cc}
e^{3 t} & 0 \\
0 & e^{-t}
\end{array}\right)=\left(\begin{array}{cc}
e^{3 t} & e^{-t} \\
2 e^{3 t} & -2 e^{-t}
\end{array}\right)
$$

From this matrix we can indeed recover the original solution
$$
\boldsymbol{x}^{(1)}=e^{3 t}\left(\begin{array}{l}
1 \\
2
\end{array}\right), \quad \boldsymbol{x}^{(2)}=e^{-t}\left(\begin{array}{c}
1 \\
-2
\end{array}\right).
$$

## Part 3

### 1. Repeated eigenvalue: example

Consider the linear ODE system
$$
x^{\prime}=\left(\begin{array}{cc}
1 & -1 \\
1 & 3
\end{array}\right) x \equiv A x .
$$

Eigenvalues: $r=2$ with multiplicity $s=2$
$$
\left|\begin{array}{cc}
1-r & -1 \\
1 & 3-r
\end{array}\right|=(r-2)^2=0
$$

Eigenvectors:
$$
\begin{aligned}
& \boldsymbol{\xi}=\left(\begin{array}{l}
x \\
y
\end{array}\right) \\
& (1-r) x-y=0 \Rightarrow x+y=0 \\
& x+(3-r) y=0 \Rightarrow x+y=0 \Rightarrow x=-y
\end{aligned}
$$

Thus, $\boldsymbol{\xi} \propto\left(\begin{array}{c}1 \\ -1\end{array}\right):$ geometric multiplicity is $1<2$.

The general solution requires two linearly independent solutions; we are missing one.

Idea:
- Similar situation for $n$-th order linear ODEs with roots of the characteristic equation with multiplicity $s \geq 2$,
- We considered solutions with $e^{r t}$ was to $t e^{r t}$,
- Can the same idea work here?

Let us try
$$
\boldsymbol{x}=t e^{2 t} \boldsymbol{\xi} \Rightarrow \frac{d \boldsymbol{x}}{d t}=\boldsymbol{\xi} e^{2 t}+2 t e^{2 t} \boldsymbol{\xi}
$$

Require this to be $A \boldsymbol{x}$ :
$$
A \boldsymbol{x}=t e^{2 t} A \boldsymbol{\xi}=2 t e^{2 t} \boldsymbol{\xi}
$$

Lesson: It does not work (unless $\boldsymbol{\xi}=0$ )
- Should include an extra unknown vector $\eta$ in our trial solution.

Suppose more generally that a matrix $A$ has eigenvalue $r$ with algebraic multiplicity 2 but geometric multiplicity 1 . Suppose that $\boldsymbol{\xi}$ is an eigenvector and $\boldsymbol{\eta}$ is a generalised eigenvector, i.e.
$$
(A-r \mathbb{I}) \boldsymbol{\eta}=\boldsymbol{\xi}
$$

To solve $\boldsymbol{x}^{\prime}=A \boldsymbol{x}$ we try $\boldsymbol{x}(t)=f(t) \boldsymbol{\xi}+g(t) \boldsymbol{\eta}$ Then
$$
\boldsymbol{x}^{\prime}=f^{\prime} \boldsymbol{\xi}+g^{\prime} \boldsymbol{\eta}, \quad \text { and } \quad A \boldsymbol{x}=r f \boldsymbol{\xi}+r g \boldsymbol{\eta}+g \boldsymbol{\xi}
$$

Comparing coefficients of $\boldsymbol{\xi}$ and $\boldsymbol{\eta}$ in $\boldsymbol{x}^{\prime}=A \boldsymbol{x}$ yields
$$
g^{\prime}=r g, \quad f^{\prime}=r f+g,
$$
which is solved by
$$
g=c_2 e^{r t}, \quad f=c_2 t e^{r t}+c_1 e^{r t},
$$

Thus we obtain the general solution
$$
\boldsymbol{x}(t)=c_1 e^{r t} \boldsymbol{\xi}+c_2\left(t e^{r t} \boldsymbol{\xi}+e^{r t} \boldsymbol{\eta}\right) .
$$

Let $\boldsymbol{\eta}=\left(\begin{array}{l}x \\ y\end{array}\right)$. Then
$$
\begin{aligned}
-x-y & =1 \\
x+y & =-1 \Rightarrow y=-1-x .
\end{aligned}
$$

Thus, the general solution for the vector $\eta$ is
$$
\boldsymbol{\eta}=\left(\begin{array}{c}
0 \\
-1
\end{array}\right)+x\left(\begin{array}{c}
1 \\
-1
\end{array}\right)=\left(\begin{array}{c}
0 \\
-1
\end{array}\right)+x \boldsymbol{\xi}
$$

Thus, our proposal for the second linearly independent solution is:
$$
\boldsymbol{x}^{(2)}=t e^{2 t} \boldsymbol{\xi}+e^{2 t}\left(\begin{array}{c}
0 \\
-1
\end{array}\right)+k e^{2 t} \boldsymbol{\xi}
$$

Notice the last term is proportional to our first solution $e^{2 t} \xi$. It can be ignored (or absorbed into a redefinition of our constants).

Thus,
$$
\boldsymbol{x}^{(2)}=t e^{2 t} \boldsymbol{\xi}+e^{2 t}\left(\begin{array}{c}
0 \\
-1
\end{array}\right)
$$
and the general solution to our linear ODE system is
$$
\begin{aligned}
\boldsymbol{x}(t) & =c_1 \boldsymbol{x}^{(1)}(t)+c_2 \boldsymbol{x}^{(2)}(t) \\
& =c_1 e^{2 t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+c_2\left[t e^{2 t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+e^{2 t}\left(\begin{array}{c}
0 \\
-1
\end{array}\right)\right]
\end{aligned}
$$

Are both solutions linearly independent?
$$
W\left[\boldsymbol{x}^{(1)}, \boldsymbol{x}^{(2)}\right]=\left|\begin{array}{cc}
e^{2 t} & t e^{2 t} \\
-e^{2 t} & -e^{2 t}(1+t)
\end{array}\right|=-e^{4 t} \neq 0
$$

### 2. Connection to matrix methods

We found the solution
$$
\begin{aligned}
\boldsymbol{x}(t) & =c_1 \boldsymbol{x}^{(1)}(t)+c_2 \boldsymbol{x}^{(2)}(t) \\
& =c_1 e^{2 t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+c_2\left[t e^{2 t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+e^{2 t}\left(\begin{array}{c}
0 \\
-1
\end{array}\right)\right].
\end{aligned}
$$

The fundamental matrix is then
$$
\Psi(t)=\left(\boldsymbol{x}^{(1)}, \boldsymbol{x}^{(2)}\right)=\left(\begin{array}{cc}
e^{2 t} & t e^{2 t} \\
-e^{2 t} & -e^{2 t}(1+t)
\end{array}\right) .
$$

Check: since
$$
\begin{aligned}
\Psi(0) & =\left(\begin{array}{cc}
1 & 0 \\
-1 & -1
\end{array}\right) \Rightarrow \Psi^{-1}(0)=\left(\begin{array}{cc}
1 & 0 \\
-1 & -1
\end{array}\right) . \\
e^{A t} & =\Psi(t) \Psi^{-1}(0)=e^{2 t}\left(\begin{array}{cc}
1-t & -t \\
t & 1+t
\end{array}\right) .
\end{aligned}
$$

Question: what is the form of the matrix $A$ in the basis $(\boldsymbol{\xi}, \boldsymbol{\eta})$ ?

Build a matrix out of the two vectors $\xi$ and $\eta$ :
$$
T=\left(\begin{array}{cc}
1 & 0 \\
-1 & -1
\end{array}\right) \Rightarrow T^{-1}=\left(\begin{array}{cc}
1 & 0 \\
-1 & -1
\end{array}\right)
$$

Notice:
$$
T^{-1} A T=T^{-1}\left(\begin{array}{cc}
2 & 1 \\
-2 & -3
\end{array}\right)=\left(\begin{array}{ll}
2 & 1 \\
0 & 2
\end{array}\right)=J_2
$$
$J_2$ is an upper triangular matrix of the form
$$
J_\lambda=\left(\begin{array}{ll}
\lambda & 1 \\
0 & \lambda
\end{array}\right) \quad \text { Jordan form }
$$

To check the consistency of our approach, consider the change of variables $x=T y$, then
$$
\frac{d \boldsymbol{y}}{d t}=T^{-1} A T \boldsymbol{y} \equiv J_2 \boldsymbol{y}
$$

Using $\boldsymbol{y}=\left(\begin{array}{l}y_1 \\ y_2\end{array}\right)$, the new linear ODE system is equivalent to:
$$
\begin{aligned}
& y_2^{\prime}=2 y_2 \Rightarrow y_2(t)=c_2 e^{2 t} \\
& y_1^{\prime}=2 y_1+y_2 \Rightarrow y_1(t)=c_1 e^{2 t}+c_2 t e^{2 t} .
\end{aligned}
$$

Thus, its general solution can be written as
$$
\boldsymbol{y}(t)=c_1 e^{2 t}\left(\begin{array}{l}
1 \\
0
\end{array}\right)+c_2 e^{2 t}\left(\begin{array}{l}
t \\
1
\end{array}\right)
$$

The fundamental matrix of the new ODE system is:
$$
Q(t)=\left(\begin{array}{cc}
e^{2 t} & t e^{2 t} \\
0 & e^{2 t}
\end{array}\right) \Rightarrow \Psi(t)=T Q(t)=\left(\begin{array}{cc}
e^{2 t} & t e^{2 t} \\
-e^{2 t} & -e^{2 t}(1+t)
\end{array}\right)
$$

Lesson: The matrix $A$ is non-diagonalisable
- The best we can do is to bring it to an upper triangular form $\equiv$ Jordan form
$$
J_\lambda=\left(\begin{array}{cc}
\lambda & 1 \\
0 & \lambda
\end{array}\right) .
$$
- Linear algebra result: all matrices can be reduced to blocks that are either diagonal or have Jordan form.

A system in Jordan form is easy to integrate:
$$
\frac{d \boldsymbol{y}}{d t}=J_\lambda \boldsymbol{y}=\left(\begin{array}{cc}
\lambda & 1 \\
0 & \lambda
\end{array}\right) \boldsymbol{y} .
$$

Integrate from the bottom up:
$$
\begin{aligned}
y_2^{\prime} & =\lambda y_2 \\
y_1^{\prime} & =\lambda y_1+y_2
\end{aligned}
$$

Compute the fundamental matrix in the original variables $\boldsymbol{x}$ : $\Psi(t)=T Q(t)$ where $Q(t)$ is the fundamental matrix in the $\boldsymbol{y}$ variables and $T$ the change of basis matrix.

The exponential of Jordan blocks has also a memorable form
$$
e^{J_\lambda t}=\left(\begin{array}{cc}
e^{\lambda t} & t e^{\lambda t} \\
0 & e^{\lambda t}
\end{array}\right).
$$


### 3. General method

Given a general $2 \times 2$ linear ODE system
$$
x^{\prime}=A x
$$
with $\operatorname{det}(A-r \mathbb{I})=(r-\lambda)^2=0$ \& having a single eigenvector $\boldsymbol{\xi}_\lambda$
- One solution is $\boldsymbol{x}^{(1)}=e^{\lambda t} \boldsymbol{\xi}_\lambda$
- Second solution is of the form
$$
\boldsymbol{x}^{(2)}=t e^{\lambda t} \boldsymbol{\xi}_\lambda+e^{\lambda t} \boldsymbol{\eta}
$$
where $(A-\lambda I) \eta=\xi_\lambda$.
- $\boldsymbol{\eta}$ is a generalised eigenvector.

The methods explained extend to $n \times n$ linear ODE systems.

For example, consider a $3 \times 3$ system with eigenvalue $\lambda$ having algebraic multiplicity 3 and geometric multiplicity 1 (single eigenvector $\boldsymbol{\xi}_\lambda$ ).
- One solution is $\boldsymbol{x}^{(1)}=e^{\lambda t} \boldsymbol{\xi}_\lambda$.
- Second solution is of the form
$$
\begin{aligned}
\boldsymbol{x}^{(2)} & =t e^{\lambda t} \boldsymbol{\xi}_\lambda+e^{\lambda t} \eta \\
\boldsymbol{\xi}_\lambda & =(A-\lambda I) \boldsymbol{\eta} .
\end{aligned}
$$
- Third solution is of the form
$$
\begin{aligned}
\boldsymbol{x}^{(3)} & =\frac{t^2}{2} e^{\lambda t} \boldsymbol{\xi}_\lambda+t e^{\lambda t} \boldsymbol{\eta}+e^{\lambda t} \boldsymbol{\zeta} \\
\boldsymbol{\eta} & =(A-\lambda \mathbb{I}) \boldsymbol{\zeta} .
\end{aligned}
$$

The method is algorithmic.

### 4. Theorem(Non-homogeneous ODE systems)

We want to solve linear ODE systems of the form
$$
\boldsymbol{x}^{\prime}=P(t) \boldsymbol{x}+\mathbf{g}(t) \qquad (1)
$$

Theorem:

Suppose $\boldsymbol{x}^{(i)}, i=1, \ldots, n$, is a fundamental set of solutions for the homogeneous ODE system $\boldsymbol{x}^{\prime}=P(t) \boldsymbol{x}$. Then the general solution of (1) is of the form
$$
\boldsymbol{x}(t)=\sum_{i=1}^n c_i \boldsymbol{x}^{(i)}(t)+\boldsymbol{x}_{p a r}(t) \qquad (2)
$$
where and $\boldsymbol{x}_{p a r}$ is any fixed solution of (1).

Note: the solution $\boldsymbol{x}_{\mathrm{par}}(t)$ is often called the particular solution.

In what follows, we focus on systems of the form
$$
x^{\prime}=A x+g(t),
$$
where $A$ is an $n \times n$ constant matrix.

We shall discuss three different methods:
1. Diagonalisation (matrix methods),
2. Undetermined coefficients,
3. Variation of parameters.

### 5. Diagonalisation

Consider a non-homogeneous system
$$
\boldsymbol{x}^{\prime}=A \boldsymbol{x}+\mathbf{g}(t)
$$

Assume the corresponding homogeneous system is solved with eigenvalues $r_i$ and eigenvectors $\xi^{(i)}$

Introduce the change of variables $x=T y$ :
$$
T \boldsymbol{y}^{\prime}=A T \boldsymbol{y}+\mathbf{g}(t) \Rightarrow \frac{d \boldsymbol{y}}{d t}=D \boldsymbol{y}+T^{-1} \boldsymbol{g} \equiv D \boldsymbol{y}+\boldsymbol{h}
$$

System of $n$ decoupled equations $\Rightarrow$ direct integration,
$$
y_i^{\prime}=r_i y_i+h_i \Rightarrow y_i(t)=c_i e^{r_i t}+e^{r_i t} \int_{t_0}^t e^{-r_i s} h_i(s) d s .
$$

Check:
$$
y_i^{\prime}=r_i y_i+e^{r_i t} e^{-r_i t} h_i(t) .
$$

General solution in the original variables equals
$$
\boldsymbol{x}(t)=T \boldsymbol{y}(t) .
$$

Remarks:
- The particular solution is encoded in the $h_i(t)$ part.
- We assumed that $A$ is diagonalisable (later, we will discuss the Jordan form case)
- The power of matrix methods is more apparent when dealing with non-homogeneous ODE systems.

### 6. Example

Consider
$$
\boldsymbol{x}^{\prime}=A \boldsymbol{x}+\boldsymbol{g}=\left(\begin{array}{cc}
-2 & 1 \\
1 & -2
\end{array}\right) \boldsymbol{x}+\left(\begin{array}{c}
2 e^{-t} \\
3 t
\end{array}\right)
$$

Since the system is linear and non-homogeneous, the general solution must be of the form
$$
\boldsymbol{x}(t)=c_1 \boldsymbol{x}^{(1)}+c_2 \boldsymbol{x}^{(2)}+\boldsymbol{x}_{\mathrm{par}}(t) .
$$

Homogeneous solution: eigenvalues \& eigenvectors $x_{\text {hom }}=e^{r t} \boldsymbol{\xi}$
$$
\left|\begin{array}{cc}
-2-r & 1 \\
1 & -2-r
\end{array}\right|=r^2+4 r+3=(r+3)(r+1)=0
$$

When $r=-3$ : if $\xi_{-3}=\left(\begin{array}{l}x \\ y\end{array}\right) \Rightarrow y=-x$. I will choose
$$
\xi_{-3}=\frac{1}{\sqrt{2}}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)
$$
(notice that $\boldsymbol{\xi}_{-3} \cdot \boldsymbol{\xi}_{-3}=1$ )
When $r=-1$ : if $\boldsymbol{\xi}_{-1}=\left(\begin{array}{l}x \\ y\end{array}\right) \Rightarrow y=x$. I| will choose
$$
\xi_{-1}=\frac{1}{\sqrt{2}}\left(\begin{array}{l}
1 \\
1
\end{array}\right)
$$

Thus, general homogeneous solution is
$$
\boldsymbol{x}_{\mathrm{hom}}=c_1 e^{-3 t} \boldsymbol{\xi}_{-3}+c_2 e^{-t} \boldsymbol{\xi}_{-1} .
$$

To find the particular solution, we change variables $x=T y$ with
$$
T=\frac{1}{\sqrt{2}}\left(\begin{array}{cc}
1 & 1 \\
-1 & 1
\end{array}\right) \Rightarrow T^{-1}=\frac{1}{\sqrt{2}}\left(\begin{array}{cc}
1 & -1 \\
1 & 1
\end{array}\right) .
$$

The new variables satisfy the linear ODE:
$$
\begin{aligned}
\frac{d \boldsymbol{y}}{d t} & =\left(\begin{array}{cc}
-3 & 0 \\
0 & -1
\end{array}\right) \boldsymbol{y}+T^{-1} \boldsymbol{g} \\
& =\left(\begin{array}{cc}
-3 & 0 \\
0 & -1
\end{array}\right) \boldsymbol{y}+\frac{1}{\sqrt{2}}\left(\begin{array}{l}
2 e^{-t}-3 t \\
2 e^{-t}+3 t
\end{array}\right)
\end{aligned}
$$

In terms of $\boldsymbol{y}^T=\left(y_1, y_2\right)$, this is equivalent to
$y_1^{\prime}+3 y_1=\sqrt{2} e^{-t}-\frac{3}{\sqrt{2}} t \quad$ (linear non-homogeneous 1st order)
$y_2^{\prime}+y_2=\sqrt{2} e^{-t}+\frac{3}{\sqrt{2}} t \quad$ (linear non-homogeneous 1st order).

General solution must be of the form (using undetermined coefficients):
$$
\begin{aligned}
& y_1(t)=c_1 e^{-3 t}+a e^{-t}+b t+c \\
& y_2(t)=c_2 e^{-t}+f t e^{-t}+h t+m
\end{aligned}
$$

Algebra (\& patience) determine:
$$
\begin{aligned}
& y_1(t)=c_1 e^{-3 t}+\frac{\sqrt{2}}{2} e^{-t}+-\frac{3}{\sqrt{2}}\left(\frac{t}{3}-\frac{1}{9}\right), \\
& y_2(t)=c_2 e^{-t}+\sqrt{2} t e^{-t}+\frac{3}{\sqrt{2}}(t-1) .
\end{aligned}
$$

We must write the solution in the original variables Thus,
$$
\boldsymbol{x}(t)=T \boldsymbol{y}(t)=\frac{1}{\sqrt{2}}\left(\begin{array}{c}
y_1+y_2 \\
-y_1+y_2
\end{array}\right)(t) .
$$

Expanding and grouping terms having the same $t$ functional dependence, we get
$$
\begin{aligned}
\boldsymbol{x}(t) & =k_1 e^{-3 t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+k_2 e^{-t}\left(\begin{array}{l}
1 \\
1
\end{array}\right) \\
& +\frac{1}{2} e^{-t}\left(\begin{array}{c}
1 \\
-1
\end{array}\right)+t e^{-t}\left(\begin{array}{l}
1 \\
1
\end{array}\right)+t\left(\begin{array}{l}
1 \\
2
\end{array}\right)-\frac{1}{3}\left(\begin{array}{l}
4 \\
5
\end{array}\right) .
\end{aligned}
$$

First line: general homogeneous solution,
Second line: particular solution.

### 7. Undetermined coeffcients

When the non-homogeneous system
$$
\boldsymbol{x}^{\prime}=A \boldsymbol{x}+\mathbf{g}(t),
$$
has a vector $g(t)$ built out of polynomials, real or complex exponentials, you may consider the application of this method.
- It has the same rules as before: we assume a similar $t$ dependence for $x_{p a r}$ as in $g(t)$
- One exception: if $\boldsymbol{g}(t)=\boldsymbol{u} e^{\lambda t}$ and $\lambda$ is an eigenvalue of $A$ with multiplicity 1 , then
$$
\boldsymbol{x}_{\mathrm{par}}=t \mathrm{e}^{\lambda t} \boldsymbol{a}+\mathrm{e}^{\lambda t} \boldsymbol{b}
$$

The term $e^{\lambda t} \boldsymbol{b}$ must be included to find a solution. If the multiplicity is $n$, we must write $\boldsymbol{x}_{\text {par }}=e^{\lambda t} \sum_{i=0}^n t^i \boldsymbol{a}_i$.

### 8. Same example as 6, but diffierent method

Consider, as before,
$$
\boldsymbol{x}^{\prime}=A \boldsymbol{x}+\mathbf{g}=\left(\begin{array}{cc}
-2 & 1 \\
1 & -2
\end{array}\right) \boldsymbol{x}+\left(\begin{array}{c}
2 e^{-t} \\
3 t
\end{array}\right)
$$

Since the eigenvalues of A equal $\lambda=-3,-1$ and the vector $\mathbf{g}(t)$ equals
$$
\boldsymbol{g}(t)=e^{-t}\left(\begin{array}{l}
2 \\
0
\end{array}\right)+t\left(\begin{array}{l}
0 \\
3
\end{array}\right)
$$
we look for a particular solution of the form
$$
\boldsymbol{x}_{\mathrm{par}}(t)=e^{-t}(\boldsymbol{a} t+\boldsymbol{b})+\boldsymbol{c} t+\boldsymbol{d} .
$$

The undetermined coefficients are the components of the vectors $\{\boldsymbol{a}, \boldsymbol{b}, \boldsymbol{c}, \boldsymbol{d}\}$.

To fix these coefficients, we introduce our guess into the non-homogeneous linear ODE. First,
$$
\frac{d \boldsymbol{x}_{\mathrm{par}}(t)}{d t}=e^{-t}(\boldsymbol{a}-\boldsymbol{a} t-\boldsymbol{b})+\boldsymbol{c} .
$$

Substituting into the linear ODE system,
$$
\begin{aligned}
(\boldsymbol{a}-\boldsymbol{b}) e^{-t}-\boldsymbol{a} t e^{-t}+\boldsymbol{c} & =A \boldsymbol{a} t e^{-t}+A \boldsymbol{b} e^{-t}+A \boldsymbol{c} t+A \boldsymbol{d} \\
& +e^{-t}\left(\begin{array}{l}
2 \\
0
\end{array}\right)+t\left(\begin{array}{l}
0 \\
3
\end{array}\right) .
\end{aligned}
$$

Key observation: this set of equations must be satisfied $\forall t$.

Thus, they are equivalent to 4 equations:
$$
\begin{aligned}
& A \boldsymbol{a}=-\boldsymbol{a} \quad\left(t e^{-t}\right) \\
& A \boldsymbol{b}=\boldsymbol{a}-\boldsymbol{b}-\left(\begin{array}{l}
2 \\
0
\end{array}\right) \quad\left(e^{-t}\right) \\
& A \boldsymbol{c}=-\left(\begin{array}{l}
0 \\
3
\end{array}\right) \quad(t) \\
& A \boldsymbol{d}=\boldsymbol{c} \quad\left(t^0\right)
\end{aligned}
$$
1st equation $\Rightarrow \boldsymbol{a}$ is an eigenvector of $A$ with eigenvalue $\lambda=-1$
$$
\Rightarrow \boldsymbol{a}=\left(\begin{array}{l}
\alpha \\
\alpha
\end{array}\right)
$$
(from our previous analysis)

Using this into the second equation: let $\boldsymbol{b}=(x, y)^{\mathrm{T}}$ Then, $A \boldsymbol{b}=\boldsymbol{a}-\boldsymbol{b}-\left(\begin{array}{l}2 \\ 0\end{array}\right)$ is equivalent to
$$
\begin{aligned}
-x+y & =\alpha-2 \\
x-y & =\alpha
\end{aligned}
$$

Consistency requires $\alpha=1 \& y=-1+x$. 

Thus,
$$
\boldsymbol{a}=\left(\begin{array}{l}
1 \\
1
\end{array}\right), \quad \boldsymbol{b}=\left(\begin{array}{c}
0 \\
-1
\end{array}\right)+k\left(\begin{array}{l}
1 \\
1
\end{array}\right)
$$

Third equation $A \boldsymbol{c}=-\left(\begin{array}{l}0 \\ 3\end{array}\right) \Rightarrow \boldsymbol{c}=\left(\begin{array}{l}1 \\ 2\end{array}\right)$.

Fourth equation $A \boldsymbol{d}=\boldsymbol{c} \Rightarrow \boldsymbol{d}=-\left(\begin{array}{c}\frac{4}{3} \\ \frac{5}{3}\end{array}\right)$.

Particular solution is:
$$
\boldsymbol{x}_{\mathrm{par}}(t)=t e^{-t}\left(\begin{array}{l}
1 \\
1
\end{array}\right)-e^{-t}\left(\begin{array}{l}
0 \\
1
\end{array}\right)+k e^{-t}\left(\begin{array}{l}
1 \\
1
\end{array}\right)+t\left(\begin{array}{l}
1 \\
2
\end{array}\right)-\frac{1}{3}\left(\begin{array}{l}
4 \\
5
\end{array}\right) .
$$

This agrees with our previous solution, obtained using diagonalisation, for $k=1 / 2$.

Remember particular solutions are not unique.

### 9. Variation of parameters

We are discussing non-homogeneous ODE systems
$$
\frac{d \boldsymbol{x}}{d t}=P(t) \boldsymbol{x}+\mathbf{g}(t)
$$

When $P(t)=A$ is constant, we have discussed two methods to solve this problem:
- Diagonalisation: matrix algebra methods
- Undetermined coefficients

We now turn to the method of variation of parameters. Its application is analogous to what we saw for higher-order differential equations.

Consider the system
$$
\frac{d \boldsymbol{x}}{d t}=P(t) \boldsymbol{x}+\boldsymbol{g}(t) .
$$

Assume the homogeneous problem
$$
\frac{d \boldsymbol{x}_{\mathrm{hom}}}{d t}=P(t) \boldsymbol{x}_{\mathrm{hom}},
$$
is solved by
$$
\boldsymbol{x}_{\mathrm{hom}}=\Psi(t) \boldsymbol{c},
$$
for some constant $\boldsymbol{c}$.

The method consists in looking for solutions to the non-homogeneous problem of the form
$$
\boldsymbol{x}(t)=\Psi(t) \boldsymbol{u}(t) .
$$

That is, $\boldsymbol{c} \mapsto \boldsymbol{u}(t)$ (variation of parameters).

Question: how do we determine $\boldsymbol{u}(t)$ ?
Introducing $\boldsymbol{x}=\Psi(t) \boldsymbol{u}(t)$ into the ODE system:
$$
\frac{d \boldsymbol{x}}{d t}=\Psi^{\prime}(t) \boldsymbol{u}(t)+\Psi(t) \frac{d \boldsymbol{u}}{d t}=P(t) \Psi(t) \boldsymbol{u}(t)+\mathbf{g}(t)
$$

Remember $\Psi^{\prime}=P(t) \Psi$, thus
$$
\begin{aligned}
\Psi \frac{d \boldsymbol{u}}{d t} & =\boldsymbol{g}(t) \Rightarrow \frac{d \boldsymbol{u}}{d t}=\Psi^{-1} \boldsymbol{g} \\
\Rightarrow \boldsymbol{u}(t) & =\int_{t_0}^t \Psi^{-1}(s) \mathbf{g}(s) d s+\boldsymbol{u}\left(t_0\right)
\end{aligned}
$$

Thus, the general solution is
$$
\boldsymbol{x}(t)=\Psi(t) \Psi^{-1}\left(t_0\right) \boldsymbol{x}_0+\Psi(t) \int_{t_0}^t \Psi^{-1}(s) \mathbf{g}(s) d s
$$


We recover the general solution as general homogeneous + particular.

Our particular solution
$$
x_p(t)=\Psi(t) \int_{t_0}^t \Psi^{-1}(s) \mathbf{g}(s) d s
$$
vanishes at $t=t_0$ (this can always be done).

The method applies even if $P(t)$ is not constant.

### 10. Example

Let us solve
$$
\frac{d \boldsymbol{x}}{d t}=A \boldsymbol{x}+\boldsymbol{g}=\left(\begin{array}{cc}
-2 & 1 \\
1 & -2
\end{array}\right) \boldsymbol{x}+\left(\begin{array}{c}
2 e^{-t} \\
3 t
\end{array}\right) .
$$
again, using variation of parameters.
Our previous analysis gave the fundamental matrix:
$$
\Psi(t)=\left(\begin{array}{cc}
e^{-3 t} & e^{-t} \\
-e^{-3 t} & e^{-t}
\end{array}\right)
$$

With
$$
\Psi(t) \frac{d \boldsymbol{u}}{d t}=\mathbf{g}
$$

With $\boldsymbol{u}=\left(u_1, u_2\right)^{\mathrm{T}}$, the above is equivalent to
$$
\begin{aligned}
& u_1^{\prime}=e^{2 t}-\frac{3}{2} t e^{3 t} \\
& u_2^{\prime}=1+\frac{3}{2} t e^t
\end{aligned}
$$

Both equations are 1st order $\Rightarrow$ direct integration !!
$$
\begin{aligned}
& u_1(t)=\frac{1}{2} e^{2 t}-\frac{1}{2} t e^{3 t}+\frac{1}{6} e^{3 t}+c_1 \\
& u_2(t)=t+\frac{3}{2} t e^t-\frac{3}{2} e^t+c_2
\end{aligned}
$$

Choosing $c_1=c_2=0$, we compute
$$
\boldsymbol{x}_p=\Psi(t) \boldsymbol{u}=t e^{-1}\left(\begin{array}{l}
1 \\
1
\end{array}\right)+\frac{1}{2} e^{-t}\left(\begin{array}{r}
1 \\
-1
\end{array}\right)+t\left(\begin{array}{l}
1 \\
2
\end{array}\right)-\frac{1}{3}\left(\begin{array}{l}
4 \\
5
\end{array}\right).
$$


## Part 4

### 1. Qualitative theory of ODEs

Consider a nonlinear autonomous system

$$
\begin{aligned}
& \frac{d x}{d t}=F(x, y), \\
& \frac{d y}{d t}=G(x, y) .
\end{aligned}
$$

Since $F, G$ can be arbitrary, the problem is generically nonlinear.
Question: Can we interpret the solution geometrically?

- View $(x, y)$ as a point in $\mathbb{R}^2$,

- $(F, G)$ defines a vector field,

- $(x(t), y(t))$ parameterises a curve in $\mathbb{R}^2$,

- Integrating a solution $\Leftrightarrow$ finding a curve whose tangent at $(x, y)$ is given by $\frac{d x}{d t}=\dot{x}=F(x, y)$ and $\frac{d y}{d t}=\dot{y}=G(x, y)$.

### 2. Definition

- The $(x, y)$ plane will be referred to as phase plane.

- Solutions to the ODE system $\boldsymbol{x}(t)=(x(t), y(t))^{\mathrm{T}}$ describe curves in the phase plane, often thought as trajectories of point moving with velocity $\frac{d x}{d t}$ and $\frac{d y}{d t}$.

Further remarks:

- Solutions depend on initial conditions $\Rightarrow$ different initial conditions correspond to different trajectories.

- A given ODE system gives rise to as many trajectories as different initial conditions.
- But, there are as many initial conditions as points in the phase plane.

- Plotting a representative set of trajectories will be referred to as the phase portrait of the given ODE system.

- For autonomous systems meeting the conditions of the existence and uniqueness theorem, trajectories cannot intersect.

### 3. Qualitative description

Local description: consider the dynamics in a patch near some $\boldsymbol{x}_0$,

- not very interesting for most $\boldsymbol{x}_0$,

- focus on critical points $x_0$, where $F\left(x_0\right)=G\left(x_0\right)=0$,

- use linearisation (first-order Taylor expansion) and what we have learned about linear systems for $\boldsymbol{x} \approx \boldsymbol{x}_0$,
  gives a local description of the phase portrait.

Global description: understand behaviour in the entire phase plane.

### 4. Definition

A point $x_0=\left(x_0 y_0\right)$ is a critical point if $F\left(x_0, y_0\right)=G\left(x_0, y_0\right)=0$.

### 5. Theorem

Away from critical points, the local dynamics is simple:

Let $\boldsymbol{x}_*=\left(x_*, y_*\right)$ be such that $\left(F\left(\boldsymbol{x}_*, \boldsymbol{y}_*\right), G\left(\boldsymbol{x}_*, \boldsymbol{y}_*\right)\right) \neq 0$, then, in a neighbourhood of $\boldsymbol{x}_*$ there is a smooth change of variable $(\tilde{x}, \tilde{y})=H(x, y)$ under which the ODE system reduces to

$$
\frac{d \tilde{x}}{d t}=1, \quad \frac{d \tilde{y}}{d t}=0 .
$$

Example: for $F(x, y)=-y, G(x, y)=x$ change to polar coordinates $x=r \cos \theta, y=r \sin \theta$ to find $\dot{r}=0, \dot{\theta}=1$.

Proof:
The original system of equations is:

$$
\begin{aligned}
& \frac{d x}{d t}=F(x, y) \\
& \frac{d y}{d t}=G(x, y) .
\end{aligned}
$$

For the given $F(x, y)=-y$ and $G(x, y)=x$, our system becomes:

$$
\begin{aligned}
& \frac{d x}{d t}=-y, \\
& \frac{d y}{d t}=x .
\end{aligned}
$$

Now, we want to transform this system from Cartesian coordinates $(x, y)$ to polar coordinates ( $r, \theta$ ). In polar coordinates, $x=r \cos \theta$ and $y=r \sin \theta$.

To convert the original system into polar coordinates, we need to compute the rates of change of $r$ and $\theta$ with respect to time. Starting with the polar coordinate definitions:

$$
\begin{aligned}
& x=r \cos \theta, \\
& y=r \sin \theta .
\end{aligned}
$$

Differentiating $x$ and $y$ with respect to time gives:

$$
\begin{aligned}
& \frac{d x}{d t}=\frac{d r}{d t} \cos \theta-r \sin \theta \frac{d \theta}{d t}, \\
& \frac{d y}{d t}=\frac{d r}{d t} \sin \theta+r \cos \theta \frac{d \theta}{d t} .
\end{aligned}
$$

Since we have $\frac{d x}{d t}=-y$ and $\frac{d y}{d t}=x$, we can substitute these into the above expressions:

$$
\begin{aligned}
-r \sin \theta & =\frac{d r}{d t} \cos \theta-r \sin \theta \frac{d \theta}{d t}, \\
r \cos \theta & =\frac{d r}{d t} \sin \theta+r \cos \theta \frac{d \theta}{d t} .
\end{aligned}
$$

Using the polar coordinate definitions, we substitute $x$ and $y$ with $r \cos \theta$ and $r \sin \theta$ :

$$
\begin{aligned}
-r \sin \theta & =\frac{d r}{d t} \cos \theta-r \sin \theta \frac{d \theta}{d t}, \\
r \cos \theta & =\frac{d r}{d t} \sin \theta+r \cos \theta \frac{d \theta}{d t} .
\end{aligned}
$$

Now, we solve this system of equations to find $\frac{d r}{d t}$ and $\frac{d \theta}{d t}$.
By solving these equations, we arrive at $\frac{d r}{d t}=0$ and $\frac{d \theta}{d t}=1$.

### 6. Motivating the linear approximation

Consider a generic $2 \times 2$ non-linear ODE system:

$$
\begin{aligned}
x^{\prime} & =F(x, y), \\
y^{\prime} & =G(x, y) .
\end{aligned}
$$

Given a point $\left(x_0, y_0\right)$ in phase space, we can approximate $F, G$ by their Taylor expansions in some open neighbourhood

$$
\begin{aligned}
F(x, y) & =F\left(x_0, y_0\right)+\partial_x F\left(x_0, y_0\right)\left(x-x_0\right)+\partial_y F\left(x_0, y_0\right)\left(y-y_0\right) \\
& +\eta_1(x, y), \\
G(x, y) & =G\left(x_0, y_0\right)+\partial_x G\left(x_0, y_0\right)\left(x-x_0\right)+\partial_y G\left(x_0, y_0\right)\left(y-y_0\right) \\
& +\eta_2(x, y),
\end{aligned}
$$

where

$$
\frac{\eta_1(x, y)}{\left\|\boldsymbol{x}-\boldsymbol{x}_0\right\|}, \frac{\eta_2(x, y)}{\left\|\boldsymbol{x}-\boldsymbol{x}_0\right\|} \rightarrow 0 \quad \text { as } \quad(x, y) \rightarrow\left(x_0, y_0\right)
$$

### 7. Linear approximation

Assume that $\left(x_0 y_0\right)$ is a critical point, i.e. satisfies

$$
F\left(x_0, y_0\right)=G\left(x_0, y_0\right)=0 \text {. }
$$

To explore the evolution of the system around $\left(x_0 y_0\right)$, it is natural to introduce new variables

$$
u_1 \equiv x-x_0, \quad u_2 \equiv y-y_0
$$

These satisfy:

$$
\left(\begin{array}{l}
\frac{d u_1}{d t} \\
\frac{d u_2}{d t}
\end{array}\right)=\left(\begin{array}{ll}
\partial_x F\left(x_0, y_0\right) & \partial_y F\left(x_0, y_0\right) \\
\partial_x G\left(x_0, y_0\right) & \partial_y G\left(x_0, y_0\right)
\end{array}\right)\left(\begin{array}{l}
u_1 \\
u_2
\end{array}\right)+\left(\begin{array}{l}
\eta_1 \\
\eta_2
\end{array}\right)
$$

The linear approximation consists in dropping $\left(\eta_1, \eta_2\right)$ Thus, we are left with

$$
\frac{d \boldsymbol{u}(t)}{d t}=A \boldsymbol{u}, \quad A \equiv\left(\begin{array}{ll}
\partial_x F\left(x_0, y_0\right) & \partial_y F\left(x_0, y_0\right) \\
\partial_x G\left(x_0, y_0\right) & \partial_y G\left(x_0, y_0\right)
\end{array}\right) .
$$

where $\boldsymbol{u}(t)=\left(u_1, u_2\right)^{\mathrm{T}} . A$ is the Jacobian matrix.

Conclusion: Locally, around any critical point, nonlinear ODEs $\approx$ linear ODEs.

### 8. Local analysis: strategy

Given a nonlinear ODE system, we can

- identify all its critical points,
- solve the linear approximation around each of them,
- use nonlinear methods to connect linear behaviours and produce a global picture of the dynamics.

First we

- classify all possible linear behaviours,
- relate the linear dynamics to the stability of the critical point.

### 9. Example: Newton's law for pendulum with friction

Consider Newton's law for a pendulum with friction:

$$
\begin{aligned}
& m L^2 \frac{d^2 \theta}{d t^2}=-c L \frac{d \theta}{d t}-m g L \sin \theta \Leftrightarrow \frac{d^2 \theta}{d t^2}+\gamma \frac{d \theta}{d t}+\omega^2 \sin \theta=0, \\
& \text { with } \gamma=\frac{c}{m L}, \quad \omega^2=\frac{g}{L} \text {. } \\
& \text { Map the 2nd order ODE to a 1st order ODE system: } x=\theta \\
& \text { and } y=\frac{d \theta}{d t} \\
& \qquad \frac{d x}{d t}=y, \quad \frac{d y}{d t}=-\omega^2 \sin x-\gamma y .
\end{aligned}
$$

Critical points:

$$
\begin{aligned}
& \frac{d x}{d t}=0 \Rightarrow y=0 \\
& \frac{d x}{d t}=0 \Rightarrow x=n \pi, \quad n \in \mathbb{Z}
\end{aligned}
$$

Jacobian matrix:

$$
\begin{aligned}
& F(x, y)=y \Rightarrow \partial_x F=0, \quad \partial_y F=1 \\
& G(x, y)=-\omega^2 \sin x-\gamma y \Rightarrow \partial_x G=-\omega^2 \cos x, \quad \partial_y G=-\gamma .
\end{aligned}
$$

Case 1:

Critical point $\left(x_0, y_0\right)=(2 n \pi, 0)$

$$
\frac{d}{d t}\left(\begin{array}{l}
u \\
v
\end{array}\right)=\left(\begin{array}{cc}
0 & 1 \\
-\omega^2 & -\gamma
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right),
$$

where $u=x-2 n \pi$ and $v=y$.

Case 2:

Critical point $\left(x_0, y_0\right)=((2 n+1) \pi, 0)$

$$
\frac{d}{d t}\left(\begin{array}{l}
u \\
v
\end{array}\right)=\left(\begin{array}{cc}
0 & 1 \\
\omega^2 & -\gamma
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)
$$

where $u=x-(2 n+1) \pi$ and $v=y$.
Notice how the information about the given critical point is encoded in a single sign matrix element.

When performing linear approximation, the aim is to simplify the system's behavior near the critical points. Thus, all nonlinear terms (like $\sin x$ or $\cos x$ ) are evaluated at their values at the critical points when computing the Jacobian matrix. This is why in the Jacobian matrix, $-\omega^2 \cos x$ turns into $-\omega^2$.

Solutions of the linear approximation: $(u, v)=e^{\lambda t} \boldsymbol{\xi}$ depend on the eigenvalues $\lambda$.

$$
\begin{aligned}
& \left(x_0, y_0\right)=(2 n \pi, 0): \lambda=\left(-\gamma \pm \sqrt{\gamma^2-4 \omega^2}\right) / 2 \\
& \left(x_0, y_0\right)=((2 n+1) \pi, 0): \lambda=\left(-\gamma \pm \sqrt{\gamma^2+4 \omega^2}\right) / 2
\end{aligned}
$$

Behaviour depends on sign of Re $\lambda$ and differ for the two types of critical points: equilibria at $(2 n \pi, 0)$ are attracting, equilibria at $((2 n+1) \pi, 0)$ are unstable. We will discuss this in detail in the coming parts.

### 10. Classiffication of critical points

In the linear approximation,

$$
\text { critical point } \Leftrightarrow \frac{d \boldsymbol{u}}{d t}=0=A \boldsymbol{u} \text {. }
$$

If $\operatorname{det} A \neq 0 \Rightarrow \boldsymbol{u}=0$ is the unique critical point.

- Classification of critical points $\Leftrightarrow$ Classification of eigenvalues of $A$
- This is because $\boldsymbol{u}(t) \equiv$ trajectory in phase space,
- Different eigenvalues $\Leftrightarrow$ different trajectories,
- Thus, different critical point behaviours $\Leftrightarrow$ different eigenvalues of $A$.

### 11. Real unequal eigenvalues

(i) negative $r_1< r_2<0$.

Solution is

$$
\boldsymbol{x}=c_1 e^{r_1 t} \boldsymbol{\xi}_1+c_2 e^{r_2 t} \boldsymbol{\xi}_2=e^{r_2 t}\left[c_1 e^{\left(r_1-r_2\right) t} \boldsymbol{\xi}_1+c_2 \boldsymbol{\xi}_2\right] .
$$

The solution always approaches the critical point.

- if $c_2 \neq 0, \boldsymbol{x} \rightarrow 0$ along $\boldsymbol{\xi}_2$ direction
- if $c_2=0, \boldsymbol{x} \rightarrow 0$ along $\boldsymbol{\xi}_1$ direction

Node (nodal sink)

![](https://files.mdnice.com/user/36229/9a75c477-1939-4392-a3bf-116f2ddb0971.jpg)

(ii) $r_1>r_2>0$.

Solution is
$$
\boldsymbol{x}=c_1 e^{r_1 t} \boldsymbol{\xi}_1+c_2 e^{r_2 t} \boldsymbol{\xi}_2=e^{r_1 t}\left[c_1 \boldsymbol{\xi}_1+c_2 e^{\left(r_2-r_1\right) t} \boldsymbol{\xi}_2\right]
$$

The solution always gets away from the critical point.
This critical point is called Node (nodal source):
- Similar graph as before, but flipping arrows,
- If $c_1 \neq 0$, trajectories approach the one by $\xi_1$ as $t \rightarrow \infty$,
- Only when $c_1=0$, they do it along $\boldsymbol{\xi}_2$.

(ii) different signs $r_1>0>r_2$.

Solution is
$$
\boldsymbol{x}=c_1 e^{r_1 t} \boldsymbol{\xi}_1+c_2 e^{r_2 t} \boldsymbol{\xi}_2 .
$$

Hence $|\boldsymbol{x}| \rightarrow \infty$ as $t \rightarrow \pm \infty$ for most initial conditions.

If $c_2=0 \Rightarrow|\boldsymbol{x}| \rightarrow \infty$ at $t \rightarrow \infty$ (it gets away along $\boldsymbol{\xi}_1$ ).

If $c_1=0 \Rightarrow|\boldsymbol{x}| \rightarrow 0$ at $t \rightarrow \infty$ (it approaches along $\boldsymbol{\xi}_2$ ).

If $c_1, c_2 \neq 0,|\boldsymbol{x}| \rightarrow \infty$ along $\boldsymbol{\xi}_1$ because $e^{r_1 t}$ dominates.

Saddle point

![](https://files.mdnice.com/user/36229/70cb94eb-9136-4f6c-ba43-ebbd907e9ab4.jpg)


(iii) $r_1=r_2=r<0$ : double eigenvalues (different sign: just flip arrows).

Two cases to consider:
- $\exists$ two independent eigenvectors
- $\exists$ a single independent eigenvector

When two independent eigenvectors exist:
$$
\boldsymbol{x}=c_1 e^{r t} \boldsymbol{\xi}_1+c_2 e^{r t} \boldsymbol{\xi}_2 .
$$

Notice any ratio of $x_2 / x_1$ is $t$ independent $\Rightarrow$ straight line.

Trajectories approach the critical point

Proper node (star point)


![](https://files.mdnice.com/user/36229/304ee8a7-2f54-4c02-a707-d25bbf9476c0.jpg)

(iii) $r_1=r_2=r<0$ with one independent eigenvector $\boldsymbol{\xi}$ :
$$
\boldsymbol{x}=c_1 e^{r t} \boldsymbol{\xi}+c_2 e^{r t}(t \boldsymbol{\xi}+\eta)=e^{r t}\left[c_1 \boldsymbol{\xi}+c_2 \boldsymbol{\eta}+c_2 t \boldsymbol{\xi}\right] .
$$

Since $r<0$, trajectories approach the critical point.
As $t \rightarrow \infty$, the trajectory is dominated by $\xi$ (even if $c_2=0$ ).

Improper (or degenerate) node

![](https://files.mdnice.com/user/36229/da74b53a-2442-4e94-a2bc-4d51f8ec6cb2.jpg)

### 12. Complex eigenvalues

(iv) complex eigenvalues $\lambda \pm i \mu(\mu>0)$.

Eigenvectors are $\boldsymbol{\xi}$ and $\boldsymbol{\xi}^*$ and the transformation $\boldsymbol{x}=T \boldsymbol{y}$ leads to the diagonal matrix
$$
T^{-1} A T=\left(\begin{array}{cc}
\lambda+i \mu & 0 \\
0 & \lambda-i \mu
\end{array}\right) .
$$

Make a further change of coordinates: $\boldsymbol{y}=P \boldsymbol{z}$, where
$$
P=\left(\begin{array}{cc}
1 / 2 & -i / 2 \\
1 / 2 & i / 2
\end{array}\right)
$$
corresponds to using $(\operatorname{Re} \boldsymbol{\xi}, \operatorname{Im} \boldsymbol{\xi})$ as a basis. Then
$$
z^{\prime}=P^{-1} T^{-1} A T P z=\left(\begin{array}{cc}
\lambda & \mu \\
-\mu & \lambda
\end{array}\right) z
$$

For matrices of the form
$$
\begin{aligned}
A & =\left(\begin{array}{cc}
\lambda & \mu \\
-\mu & \lambda
\end{array}\right), \\
\operatorname{det}(A-r \mathbb{I}) & =(r-\lambda)^2+\mu^2=0 \Rightarrow r=\lambda \pm i \mu
\end{aligned}
$$
two linearly independent solutions are given by
$$
e^{\lambda t}\left(\begin{array}{c}
\cos (\mu t) \\
-\sin (\mu t)
\end{array}\right), \quad e^{\lambda t}\left(\begin{array}{c}
\sin (\mu t) \\
\cos (\mu t)
\end{array}\right)
$$

Hence, the general solution is
$$
\left(\begin{array}{l}
x(t) \\
y(t)
\end{array}\right)=e^{\lambda t}\left(\begin{array}{c}
c_1 \cos (\mu t)+c_2 \sin (\mu t) \\
-c_1 \sin (\mu t)+c_2 \cos (\mu t)
\end{array}\right)=C e^{\lambda t}\left(\begin{array}{c}
\cos (\phi-\mu t) \\
\sin (\phi-\mu t)
\end{array}\right),
$$
with $C$ and $\phi$ arbitrary constants.

These solutions satisfy the identity :
$$
x^2+y^2=C^2 e^{2 \lambda t}
$$

spirals towards origin if $\lambda<0$ : stable focus.

diverges from origin if $\lambda>0$ : unstable focus.

In the original coordinates, 'elliptical' spiral.

![](https://files.mdnice.com/user/36229/ef5091fa-275d-4a21-b414-e8044c8b496e.jpg)

An alternative way of reaching this conclusion.
Introduce polar coordinates in phase space
$$
r^2=x^2+y^2, \quad \tan \phi=\frac{y}{x} .
$$
$(x, y)$ satisfy the ODE system
$$
\begin{aligned}
& \dot{x}=\lambda x+\mu y \\
& \dot{y}=\lambda y-\mu x
\end{aligned}
$$

It follows
$$
\begin{aligned}
r \dot{r} & =x \dot{x}+y \dot{y}=x(\lambda x+\mu y)+y(\lambda y-\mu x)=\lambda r^2 \\
\frac{\dot{\phi}}{\cos ^2 \phi} & =\frac{x \dot{y}-y \dot{x}}{x^2} \Rightarrow \dot{\phi}=-\mu
\end{aligned}
$$

$$
\begin{aligned}
& \dot{r}=\lambda r \Rightarrow r=c e^{\lambda t} \\
& \dot{\phi}=-\mu \Rightarrow \phi=-\mu t+\phi_0 .
\end{aligned}
$$
$\lambda>0 \Rightarrow|\boldsymbol{x}| \rightarrow \infty$ for $t \rightarrow \infty$
$\lambda<0 \Rightarrow|\boldsymbol{x}| \rightarrow 0$ for $t \rightarrow \infty$

$\phi$ decreases as $t$ evolves (since $\mu>0) \Rightarrow$ motion is clockwise Conclusions are fully consistent with our spiral picture.

(iv) imaginary eigenvalues $\pm i \mu(\mu>0)$.

In suitable coordinates, the matrix is:
$$
\begin{aligned}
A & =\left(\begin{array}{cc}
0 & \mu \\
-\mu & 0
\end{array}\right), \\
\operatorname{det}(A-r \mathbb{I}) & =\mu^2=0 \Rightarrow r= \pm i \mu
\end{aligned}
$$
and the two linearly independent solutions are
$$
\left(\begin{array}{c}
\cos (\mu t) \\
-\sin (\mu t)
\end{array}\right), \quad\left(\begin{array}{c}
\sin (\mu t) \\
\cos (\mu t)
\end{array}\right)
$$

Hence, the general solution is
$$
\left(\begin{array}{l}
x(t) \\
y(t)
\end{array}\right)=\left(\begin{array}{c}
c_1 \cos (\mu t)+c_2 \sin (\mu t) \\
-c_1 \sin (\mu t)+c_2 \cos (\mu t)
\end{array}\right)=C\left(\begin{array}{c}
\cos (\phi-\mu t) \\
\sin (\phi-\mu t)
\end{array}\right),
$$
with $C$ and $\phi$ arbitrary constants.

These solutions satisfy:
$$
x^2+y^2=C^2,
$$
circles.
They correspond to ellipses in the original coordinates.

Critical point is a centre.

![](https://files.mdnice.com/user/36229/38eb0d21-c686-4fb1-92fa-331e63dc15d9.jpg)







### 13. Summary

Classification critical points
$\Leftrightarrow$
matrix eigenvalues

When eigenvalues are real \& different
- same sign: node
- different sign: saddle

When eigenvalues are real \& equal
- two independent eigenvectors: proper node (star point)
- one independent eigenvector: improper node

When eigenvalues are complex, $\lambda+i \mu$ with $\lambda, \mu \neq 0$,
- $\lambda<0$, stable folcus,
- $\lambda>0$, unstable focus.

Critical points of different types have different behaviours as $t \rightarrow \infty:$

$$
|\boldsymbol{x}| \rightarrow 0 \text { as } t \rightarrow \infty
$$
1. real \& negative eigenvalues: nodal sink
2. complex eigenvalue with negative real part: stable focus 

bounded trajectory as $t \rightarrow \infty$ : purely imaginary eigenvalue $\Rightarrow$ center


$$
|\boldsymbol{x}| \rightarrow \infty \text { as } t \rightarrow \infty
$$
1. at least one eigenvalue is positive: saddle, nodal source
2. complex eigenvalue with positive real part: unstable focus

This behaviour as $t \rightarrow \infty$ is related to the notion of stability.


## Part 5

### 1. Definition


An ODE system
$$
\frac{d x}{d t}=F(x, y), \quad \frac{d y}{d t}=G(x, y),
$$
is referred to as an autonomous systems is $F, G$ have no explicit time dependence.

This describes any physical system whose parameters, forces, etc ... do NOT depend on time.

A critical point $\boldsymbol{x}_0$ is stable if $\forall \epsilon, \exists \delta>0$ such that every solution $\boldsymbol{x}(t)$ with $\left\|\boldsymbol{x}(0)-\boldsymbol{x}_0\right\|<\delta$ satisfies
$$
\left\|\boldsymbol{x}(t)-\boldsymbol{x}_0\right\|<\epsilon, \quad \forall t \geq 0 .
$$

A critical point that is not stable is called unstable.

A critical point $\boldsymbol{x}_0$ is attracting if $\exists \delta>0$ such that every solution $\boldsymbol{x}(t)$ with $\left\|\boldsymbol{x}(0)-\boldsymbol{x}_0\right\|<\delta$ satisfies
$$
\lim _{t \rightarrow \infty} \boldsymbol{x}(t)=\boldsymbol{x}_0.
$$

Definition
A critical point $\boldsymbol{x}_0$ is asymptotically stable if it is stable and $\exists \delta>0$ such that every solution $\boldsymbol{x}(t)$ with $\left\|\boldsymbol{x}(0)-\boldsymbol{x}_0\right\|<\delta$ satisfies
$$
\lim _{t \rightarrow \infty} \boldsymbol{x}(t)=\boldsymbol{x}_0.
$$

In other words, asymptotically stable means both stable and attracting.

### 2. Stability of linear systems

| Eigenvalues                               | Critical Points          | Stability         |
|-------------------------------------------|--------------------------|-------------------|
| $\( r_1 > r_2 > 0 \) $                      | Node (source)            | unstable          |
| $( r_1 < r_2 < 0 )$                       | Node (sink)              | asymp. stable     |
| $( r_2 < 0 < r_1 ) $                      | saddle                   | unstable          |
| $( r_1 = r_2 > 0 ) $                      | Proper/Improper node     | unstable          |
| $( r_1 = r_2 < 0 )  $                     | Proper/Improper node     | asymp. stable     |
| $( r_1, r_2 = \lambda \pm i \mu (\lambda > 0) )$ | focus            | unstable          |
| $( r_1, r_2 = \lambda \pm i \mu (\lambda < 0) )$ | focus            | asymp. stable     |
| $( r_1 = i \mu, r_2 = -i \mu \) $          | center                   | stable            |


### 3. Almost linear systems

Consider the corrections to the linear approximation
$$
\left(\begin{array}{l}
\frac{d u}{d t} \\
\frac{d v}{d t}
\end{array}\right)=\left(\begin{array}{ll}
\partial_x F\left(x_0, y_0\right) & \partial_y F\left(x_0, y_0\right) \\
\partial_x G\left(x_0, y_0\right) & \partial_y G\left(x_0, y_0\right)
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)+\left(\begin{array}{l}
\eta_1 \\
\eta_2
\end{array}\right)
$$
where $u=x-x_0$ and $v=y-y_0$, encoded in the vector $\boldsymbol{\eta}^t=\left(\eta_1, \eta_2\right)$.

Question: Does the type of critical point in the linear approximation change when we include $\boldsymbol{\eta}=\left(\eta_1, \eta_2\right)^{\mathrm{T}}$ ?

Let $r_1$ and $r_2$ be the eigenvalues to the linear approximation corresponding to the almost linear system above, then the critical point $(0,0)$ behaves as in the following table.

![](https://files.mdnice.com/user/36229/90267c0e-07cf-4747-8a0b-326d2225172e.jpg)

N: node 

PN: proper node 

IN: improper node SP: saddle point

SpP: spiral (focus) point

C: center

### 4. Center : linear vs non-linear

Consider ODE systems of the form :
$$
\dot{x}=-y+x\left(x^2+y^2\right)^n, \quad \dot{y}=x+y\left(x^2+y^2\right)^n
$$

Critical points: $\left(x_0, y_0\right)=(0,0)$
Linear system :
$$
\begin{aligned}
& F(x, y)=-y+x\left(x^2+y^2\right)^n \\
& \Rightarrow \partial_x F=\left(x^2+y^2\right)^n+2 n x^2\left(x^2+y^2\right)^{n-1}, \\
& \partial_y F=-1+2 n y x\left(x^2+y^2\right)^{n-1} \\
& G(x, y)=x+y\left(x^2+y^2\right)^n \\
& \Rightarrow \partial_x G=1+2 n x y\left(x^2+y^2\right)^{n-1}, \\
& \partial_y G=\left(x^2+y^2\right)^n+2 n y^2\left(x^2+y^2\right)^{n-1} .
\end{aligned}
$$

At the critical point $(0,0)$, these partial derivatives simplify greatly:
$$
\begin{aligned}
& \partial_x F(0,0)=0, \\
& \partial_y F(0,0)=-1, \\
& \partial_x G(0,0)=1, \\
& \partial_y G(0,0)=0 .
\end{aligned}
$$

So the linearized system near $(0,0)$ is:
$$
\begin{aligned}
& \dot{x} \approx \partial_x F(0,0) \cdot x+\partial_y F(0,0) \cdot y=-y, \\
& \dot{y} \approx \partial_x G(0,0) \cdot x+\partial_y G(0,0) \cdot y=x .
\end{aligned}
$$


Evaluating at the critical point $(0,0)$, we obtain for $u=x, v=y$.
$$
\dot{u}=-v, \dot{v}=u \quad \Leftrightarrow \quad A=\left(\begin{array}{cc}
0 & -1 \\
1 & 0
\end{array}\right)
$$

This corresponds to a center since eigenvalues $\lambda_{ \pm}= \pm i$ are purely imaginary $\Leftrightarrow \exists$ periodic trajectories (at least linearly)

Question: Does this interpretation remain true at the non-linear level?

Strategy: Change to polar coordinates and discuss the exact non-linear ODEs.

$$
\begin{gathered}
r^2=x^2+y^2, \quad \tan \phi=\frac{y}{x} \\
r \dot{r}=x \dot{x}+y \dot{y}=x\left(-y+x r^{2 n}\right)+y\left(x+y r^{2 n}\right)=r^{2(n+1)}, \\
\dot{\phi}=\frac{x \dot{y}-y \dot{x}}{x^2+y^2}=1
\end{gathered}
$$

Integrating, we obtain :
$$
\frac{1}{r^{2 n}}-\frac{1}{r_0^{2 n}}=-2 n t, \quad \phi=t+\phi_0 .
$$

This describes a trajectory starting at $\left(r_0, \phi_0\right)$ :
- rotating anticlockwise
- as $t$ increases, $r$ increases
- in fact as $t \rightarrow \frac{1}{2 n r_0^{2 n}}, r \rightarrow \infty \Rightarrow$ unstable

The linear centre trajectory is gone and it is replaced by a spiral.

### 5. Implicit trajectories

Consider the ODE system:
$$
\frac{d x}{d t}=4-2 y, \quad \frac{d y}{d t}=12-3 x^2 .
$$

Critical points: $\left(x_0, y_0\right)=( \pm 2,2)$

1. For $\frac{d x}{d t}$ :
The partial derivatives are:
$$
\frac{\partial}{\partial x}(4-2 y)=0, \quad \frac{\partial}{\partial y}(4-2 y)=-2 .
$$

So, the linearized form of $\frac{d x}{d t}$ is:
$$
\dot{u}=0 \cdot u-2 \cdot v
$$
2. For $\frac{d y}{d t}$ :
The partial derivatives are:
$$
\frac{\partial}{\partial x}\left(12-3 x^2\right)=-6 x, \quad \frac{\partial}{\partial y}\left(12-3 x^2\right)=0 .
$$

Evaluating at $x=x_0$ (and noting that $y$ doesn't appear in the equation), the linearized form of $\frac{d y}{d t}$ is:
$$
\dot{v}=-6 x_0 \cdot u+0 \cdot v
$$

Therefore, in matrix form, the linearized system around $\left(x_0, y_0\right)$ is:
$$
\left(\begin{array}{c}
\dot{u} \\
\dot{v}
\end{array}\right)=\left(\begin{array}{cc}
0 & -2 \\
-6 x_0 & 0
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)
$$

Linear approximation: $u=x-x_0, v=y-y_0$
$$
\left(\begin{array}{c}
\dot{u} \\
\dot{v}
\end{array}\right)=\left(\begin{array}{cc}
0 & -2 \\
-6 x_0 & 0
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)
$$

Eigenvalues:: $\lambda^2-12 x_0=0$
- if $x_0>0 \Rightarrow \lambda_{ \pm}$real with different sign $\Rightarrow(2,2)$ is a saddle
- if $x_0<0 \Rightarrow \lambda_{ \pm}$purely imaginary $\Rightarrow(-2,2)$ is a center

Question: Can we plot the nonlinear phase portrait for this ODE system?

Remark:
$$
\begin{aligned}
& \left.\begin{array}{l}
\frac{d x}{d t}=4-2 y \\
\frac{d y}{d t}=12-3 x^2
\end{array}\right\} \Rightarrow \frac{d y}{d x}=\frac{12-3 x^2}{4-2 y} \\
& \Rightarrow(4-2 y) d y=\left(12-3 x^2\right) d x \Rightarrow 4 y-y^2=12 x-x^3+c \\
&
\end{aligned}
$$

This is an exact (nonlinear) implicit description of the trajectories solving the ODE system (for any constant $c$ )
- Plotting different values of $c \Leftrightarrow$ plotting different trajectories

The nonlinear ODE system has an exact phase portrait given by
$$
\frac{d x}{d t}=4-2 y, \quad \frac{d y}{d t}=12-3 x^2
$$

![](https://files.mdnice.com/user/36229/a84c7ab5-c1ba-4283-99ce-80fb1a176600.jpg)

Notice how trajectories close to $(-2,2)$ are indeed bounded. $(2,2)$ is indeed a saddle.

One lesson to take home: for those systems that admit implicit curves in the phase plane
$$
\left.\begin{array}{rl}
\frac{d x}{d t} & =F(x, y) \\
\frac{d y}{d t} & =G(x, y)
\end{array}\right\} \Rightarrow \frac{d y}{d x}=\frac{G(x, y)}{F(x, y)} \Rightarrow H(x, y)=c
$$
as solutions to the ODE system, we can draw the exact trajectories
- This rarely happens!

When global trajectories cannot be computed, we build a global picture from local pictures near the critical points:
- example of the dampled pendulum.

### 6. Example: Damped pendulum

Pendulum with friction:
$$
x^{\prime}=y, \quad y^{\prime}=-\omega^2 \sin x-\gamma y .
$$

Critical points:
$$
\begin{aligned}
& x^{\prime}=0 \Rightarrow y=0 \\
& y^{\prime}=0 \Rightarrow x=n \pi, \quad n \in \mathbb{Z}
\end{aligned}
$$

Linear approximation:
$$
\begin{aligned}
& F(x, y)=y \Rightarrow \partial_x F=0, \quad \partial_y F=1 \\
& G(x, y)=-\omega^2 \sin x-\gamma y \Rightarrow \partial_x G=-\omega^2 \cos x, \quad \partial_y G=-\gamma
\end{aligned}
$$

This gives rise to:
$$
\left(\begin{array}{l}
\frac{d u}{d t} \\
\frac{d v}{d t}
\end{array}\right)=\left(\begin{array}{cc}
0 & 1 \\
\epsilon \omega^2 & -\gamma
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)
$$
where $u=x-x_0, v=y$ and $\epsilon= \pm 1$
- $\epsilon=-1$ when $x_0=2 n \pi$
- $\epsilon=1$ when $x_0=(2 n+1) \pi$

Given the linear approximation, we compute its eigenvalues:
$$
\begin{aligned}
\left|\begin{array}{cc}
-\lambda & 1 \\
\epsilon \omega^2 & -\gamma-\lambda
\end{array}\right| & =\lambda^2+\gamma \lambda-\epsilon \omega^2=0 \\
& \Rightarrow \lambda_{ \pm}=\frac{-\gamma \pm \sqrt{\gamma^2+4 \epsilon \omega^2}}{2}
\end{aligned}
$$

Question: how do we draw a phase portrait?

Pick $\epsilon=-1$ and $\gamma^2-4 \omega^2<0$ : small damping $\Rightarrow$ spiral points

Case 1: Stable critical points

Consider the critical point $(0,0)$ :
- to determine the arrow choose $x=0$ (as a particular case) and evaluate the ODE system as that point
$$
\frac{d x}{d t}(x=0)=y, \quad \frac{d y}{d t}(x=0)=-\gamma y .
$$
- if $y>0: x$ increases and $y$ decreases
- if $y<0$ : $x$ decreases and $y$ increases

Thus, motion occurs clockwise
We can repeat the same analysis at the other critical points $(2 n \pi, 0)$.

![](https://files.mdnice.com/user/36229/08a2f319-baa0-4658-9013-92afa2446bd4.jpg)

Case 2: Unstable critical points

Consider $\epsilon=1$ and $x_0=\pi$.
Eigenvalues:
$$
\lambda_{ \pm}=\frac{-\gamma \pm \sqrt{\gamma^2+4 \epsilon \omega^2}}{2} \Rightarrow \lambda_{+}>0, \lambda_{-}<0
$$

This corresponds to a saddle point
Linearly independent solutions:
$$
\left(\begin{array}{l}
u \\
v
\end{array}\right)=c_1 e^{\lambda_{+} t}\left(\begin{array}{c}
1 \\
\lambda_{+}
\end{array}\right)+c_2 e^{\lambda_{-} t}\left(\begin{array}{c}
1 \\
\lambda_{-}
\end{array}\right)
$$

The only direction approaching the critical point at $t \rightarrow \infty$ is $c_1=0$.

Focus on the $c_1=0$ direction
$$
\left(\begin{array}{l}
u \\
v
\end{array}\right)=c_2 e^{\lambda_{-} t}\left(\begin{array}{c}
1 \\
\lambda_{-}
\end{array}\right)
$$

The ratio of the solution components equals
$$
\frac{v}{u}=\lambda_{-}<0
$$

Thus,
- if $c_2>0: u>0, v<0 \Rightarrow$ curve in 4th quadrant
- if $c_2<0: u<0, v>0 \Rightarrow$ curve in 2nd quadrant

Focus on the $c_2=0$ direction
$$
\left(\begin{array}{l}
u \\
v
\end{array}\right)=c_1 e^{\lambda_{+} t}\left(\begin{array}{c}
1 \\
\lambda_{+}
\end{array}\right)
$$

The ratio of the solution components equals
$$
\frac{v}{u}=\lambda_{+}>0
$$

Thus,
- if $c_1>0: u>0, v>0 \Rightarrow$ curve in 1st quadrant
- if $c_1<0: u<0, v<0 \Rightarrow$ curve in 3rd quadrant


![](https://files.mdnice.com/user/36229/36592b57-b117-4793-94d0-97c804a6dc2e.jpg)

When we plot diffierent initial conditions and their associated
trajectories, we obtain phase portraits of the form.

![](https://files.mdnice.com/user/36229/d9d61dd5-7c39-4c00-83f2-ed4f90157a15.jpg)



Critical points keep their nature and stability properties.

No matter how large $|y|$ (velocity) is, the existence of damping (friction) guarantees the solution will eventually stabilise around the stable pendulum point.


Saddle points separate the entire phase space into regions satisfying the property that any trajectory in them asymptotes to a stable spiral point.

The specific trajectory determining a change in such stable spiral point is called separatrix.

The set of all trajectories approaching a given asymptotically stable critical point is called basin of attraction.


### 7. Example of ODE model: prey-predator

System: interaction between two species, prey and predator 

Goal: to model the time evolution of both populations 

Variables: denote by
- $x$ the prey population
- $y$ the predator population

Assumptions:
- If no predator, $\dot{x}=a x(a>0)$, where $a$ is the rate of growth of the prey.
- If no prey, $\dot{y}=-c y(y>0)$, where $c$ is the rate of death of the predator.
- Interactions between both populations are proportional to both populations, i.e. the number of their encounters is proportional to both populations.

Under these assumptions, the proposed nonlinear ODE system describing the evolution of both populations reduces to:
$$
\begin{aligned}
& \dot{x}=a x-\alpha x y, \\
& \dot{y}=-c y+\gamma x y .
\end{aligned}
$$

All parameters are positive, i.e. signs were taken into account in the ODEs explicitly.

These are the Lotka-Volterra equations $(1925,1926)$.

Let us analyse this nonlinear ODE system:
$$
\begin{aligned}
& \dot{x}=a x-\alpha x y, \\
& \dot{y}=-c y+\gamma x y .
\end{aligned}
$$

Critical points:
$$
\begin{aligned}
& \dot{x}=0 \Rightarrow x=0, \quad y=\frac{a}{\alpha} \\
& \dot{y}=0 \Rightarrow y=0, \quad x=\frac{c}{\gamma} .
\end{aligned}
$$

Thus, there is exist two critical points:
- the origin (absence of both populations) $(0,0)$
- non-trivial critical point $(c / \gamma, a / \alpha)$

Linear analysis:
$$
\begin{aligned}
& F(x, y)=a x-\alpha x y \Rightarrow \partial_x F=a-\alpha y, \quad \partial_y F=-\alpha x \\
& -G(x, y)=-c y+\gamma x y \Rightarrow \partial_x G=\gamma y, \quad \partial_y G=-c+\gamma x
\end{aligned}
$$

Linear analysis: origin $(0,0)$
$$
\left(\begin{array}{l}
\dot{x} \\
\dot{y}
\end{array}\right)=\left(\begin{array}{rr}
a & 0 \\
0 & -c
\end{array}\right)\left(\begin{array}{l}
x \\
y
\end{array}\right)
$$

Solution:
$$
\left(\begin{array}{l}
x \\
y
\end{array}\right)=c_1 e^{a t}\left(\begin{array}{l}
1 \\
0
\end{array}\right)+c_2 e^{-c t}\left(\begin{array}{l}
0 \\
1
\end{array}\right)
$$

Thus,
- $(0,0)$ is a saddle point: it is an unstable critical point
- the only direction approaching $(0,0)$ is along the $y$ axis: if we introduce predators in the absence of prey, they will die.

Linear analysis:
- $F(x, y)=a x-\alpha x y \Rightarrow \partial_x F=a-\alpha y, \quad \partial_y F=-\alpha x$
- $G(x, y)=-c y+\gamma x y \Rightarrow \partial_x G=\gamma y, \quad \partial_y G=-c+\gamma x$

Linear analysis: $(c / \gamma, a / \alpha)$

Introduce $u=x-c / \gamma$ and $v=y-a / \alpha$ :
$$
\left(\begin{array}{c}
\dot{u} \\
\dot{v}
\end{array}\right)=\left(\begin{array}{cc}
0 & -c \frac{\alpha}{\gamma} \\
a \frac{\gamma}{\alpha} & 0
\end{array}\right)\left(\begin{array}{l}
u \\
v
\end{array}\right)
$$

Eigenvalues: $\lambda_{ \pm}= \pm i \sqrt{a c} \Rightarrow$ critical point is a center 

Dividing both linear equations:
$$
\frac{d v}{d u}=-\frac{\gamma(a / \alpha)}{c(\alpha / \gamma)} \frac{u}{v} \Rightarrow a \gamma^2 u^2+c \alpha^2 v^2=k^2>0 \text { (ellipses) }
$$

Implicit (exact) trajectory: dividing both exact equations
$$
\begin{aligned}
\frac{d y}{d x} & =\frac{y(-c+\gamma x)}{x(a-\alpha y)} \Rightarrow\left(\frac{a}{y}-\alpha\right) d y=\left(-\frac{c}{x}+\gamma\right) d x \\
& \Rightarrow a \log y-\alpha y=-c \log x+\gamma x+C
\end{aligned}
$$

Plots confirm the existence of periodic stable configurations
- if these models were accurate enough, they would predict the stable co-existence of both species in many areas of phase space

Linear approximation to describe these periodic trajectories:
$$
\begin{aligned}
\dot{u}=-c \frac{\alpha}{\gamma} v, & \dot{v}=a \frac{\gamma}{\alpha} u, \\
\Rightarrow & \ddot{u}+a c u=\ddot{v}+a c v=0 .
\end{aligned}
$$

General real solution:
$$
\begin{aligned}
& u(t)=a_1 \cos \sqrt{a c} t+b_1 \sin \sqrt{a c} t \\
& v(t)=c_1 \cos \sqrt{a c} t+d_1 \sin \sqrt{a c} t
\end{aligned}
$$

For convenience, we can choose:
$$
\begin{array}{ll}
a_1=A \cos \phi_0 & b_1=A \sin \phi_0 \Rightarrow u(t)=A \cos \left(\sqrt{a c} t+\phi_0\right) \\
c_1=B \cos \phi_1 & d_1=B \sin \phi_1 \Rightarrow v(t)=B \sin \left(\sqrt{a c} t+\phi_1\right)
\end{array}
$$

Using the constraint $\dot{u}=-c \frac{\alpha}{\gamma} v$ determines
$$
\phi_0=\phi_1, \quad A=\frac{\alpha}{\gamma} \sqrt{\frac{c}{a}} B .
$$

The amplitude $B$ is related to the constant $k$ determining the ellipses:
$$
a \gamma^2 u^2+c \alpha^2 v^2=k^2 \Rightarrow B=\frac{k}{\alpha \sqrt{c}} .
$$

General solution:
$$
\begin{aligned}
& x(t)=\frac{c}{\gamma}+\frac{k}{\gamma \sqrt{a}} \cos \left(\sqrt{a c} t+\phi_0\right), \\
& y(t)=\frac{a}{\alpha}+\frac{k}{\alpha \sqrt{c}} \sin \left(\sqrt{a c} t+\phi_0\right) .
\end{aligned}
$$

- Period $T=\frac{2 \pi}{\sqrt{a c}}$, independent of initial conditions.
- Both populations are periodic and out of phase by one quarter of a period (prey leads and predator lags)
- Amplitudes of the oscillations are $\frac{k}{\gamma \sqrt{a}}$ and $\frac{k}{\alpha \sqrt{c}}$ : they depend on initial conditions ( $k$ )
- Averages over a cycle coincide with the critical point configuration:
$$
\begin{aligned}
& \langle x\rangle=\frac{1}{T} \int_0^T x(t) d t=\frac{c}{\gamma}, \\
& \langle y\rangle=\frac{1}{T} \int_0^T y(t) d t=\frac{a}{\alpha}
\end{aligned}
$$

![Model](https://files.mdnice.com/user/36229/f495d84e-3b33-4c2b-95f8-c0fddbcfcf47.jpg)



![Data (hare/lynx, Hudson Bay)](https://files.mdnice.com/user/36229/31f3630c-e2bb-43f1-8a5d-19a2fda5f8bf.jpg)


### 8. Intro to nonlinear methods

Given a nonlinear autonomous ODE system:
$$
\dot{x}=F(x, y), \quad \dot{y}=G(x, y)
$$
we would like to know
- existence of critical points
- existence of closed trajectories at the nonlinear level
- intrinsic nonlinear behaviour that can not be seen in the linear approximation

If we can integrate the equations, we can explicitly explore these issues. But this clearly depends on the ODE under considerations.

What we want is to develop methods that allow to answer this type of questions without integrating the system

We will mainly discuss two results:
- Lyapunov's theory: deals with the nonlinear stability of certain critical points
- Poincaré-Bendixson theorem: deals with the existence of closed traiectories



### 9. Gaining some intuition from Newton's law

Systems
$$
\dot{x}=y, \quad \dot{y}=-\frac{d V}{d x}
$$
have invariant (or conserved) energy
$$
E(x, y)=\frac{1}{2} y^2+V(x)=\text { const. }
$$

Critical points: $y=0$ and $d V / d x=0$ : local extrema of $V(x)$.
Easy to see that
- minima of $V$ are stable,
- maxima of $V$ are unstable.


Show this
- locally, using linearisation,
- geometrically.


Let's first identify the critical points of the system. The critical points occur where $\dot{x}=0$ and $\dot{y}=$ 0 , which implies $y=0$ and $\frac{d V}{d x}=0$. The latter condition, $\frac{d V}{d x}=0$, identifies points where $V(x)$ is either a maximum, minimum, or an inflection point.

Now, let's linearise the system near a critical point $\left(x_0, 0\right)$ where $x_0$ is a point where $\frac{d V}{d x}=0$. The Jacobian matrix of the system is
$$
J=\left(\begin{array}{ll}
\frac{\partial \dot{x}}{\partial x} & \frac{\partial \dot{x}}{\partial y} \\
\frac{\partial \dot{y}}{\partial x} & \frac{\partial \dot{y}}{\partial y}
\end{array}\right)=\left(\begin{array}{cc}
0 & 1 \\
-\frac{d^2 V}{d x^2} & 0
\end{array}\right) .
$$

The eigenvalues of $J$ are given by solving $\operatorname{det}(J-\lambda I)=0$, leading to
$$
\lambda^2+\frac{d^2 V}{d x^2}=0
$$

The stability of the critical point depends on the sign of $\frac{d^2 V}{d x^2}$ :
- At a minimum of $V(x), \frac{d^2 V}{d x^2}>0$, leading to purely imaginary eigenvalues. This indicates oscillatory behavior, typical of stable equilibrium points.
- At a maximum of $V(x), \frac{d^2 V}{d x^2}<0$, leading to real eigenvalues of opposite signs. This indicates a saddle point, which is an unstable equilibrium.

Geometrically, the stability can be seen in terms of the potential energy $V(x)$ and kinetic energy $\frac{1}{2} y^2$.
- At a minimum of $V(x)$ : Small displacements from the minimum will result in forces (given by $-\frac{d V}{d x}$ ) that push the system back towards the minimum. This is a characteristic of a stable equilibrium. Moreover, the total energy being constant, a small increase in $V(x)$ due to a displacement implies a decrease in kinetic energy $\left(\frac{1}{2} y^2\right)$, leading to a decrease in velocity and a tendency to return to the minimum.
- At a maximum of $V(x)$ : Small displacements from the maximum will result in forces that push the system away from the maximum, leading to an unstable equilibrium. Here, a small increase in displacement leads to a decrease in $V(x)$ and hence an increase in kinetic energy, accelerating the system away from the maximum.


### 10. Interpretation of conservation of energy

Given the energy evaluated on a solution $E(x(t), y(t))$, its time derivative equals
$$
\begin{aligned}
\frac{d E}{d t} & =\left(\partial_x E\right) \dot{x}+\left(\partial_y E\right) \dot{y} \\
& =\nabla E \cdot \boldsymbol{T}(x, y)=|\nabla E \| \boldsymbol{T}| \cos \phi
\end{aligned}
$$
- $\nabla E=\left(\partial_x E, \partial_y E\right)$ is the gradient vector of $E$.
- $\boldsymbol{T}(x, y)=(\dot{x}, \dot{y})$ is the tangent vector to the trajectory at $(x(t), y(t))$
- $\phi$ is the angle between the gradient and the tangent vectors at the point $(x(t), y(t))$.

Thus, conservation of energy means
$$
\frac{d E}{d t}=\nabla E \cdot \boldsymbol{T}(x, y)=|\nabla E \| \boldsymbol{T}| \cos \phi=0
$$
the gradient and tangent vectors are orthogonal, i.e. $\phi=\frac{\pi}{2}$ This makes sense:
- $E(x(t), y(t))=$ constant for a solution $x(t), y(t)$ of our nonlinear ODE system.
- $E(x, y)=$ constant defines a surface/curve $\Rightarrow \nabla E$ is orthogonal to the surface
- Orthogonality $\Rightarrow \nabla E \perp T \Rightarrow$ conservation of energy

### 11. Example: pendulum with no friction

Consider the energy function $E=\frac{1}{2} y^2+(1-\cos x)$ Gradient of $E$ is $\nabla E=(\sin x, y)$. Since $T=(\dot{x}, \dot{y})=(y,-\sin x)$ we have
$$
\nabla E \cdot \boldsymbol{T}=y \sin x-y \sin x=0 .
$$




$\mathrm{E}=0$ at Linearly Stable Critical Points

At critical points (or equilibrium points) of the system, we have $\dot{x}=0$ and $\dot{y}=0$. This implies that both the kinetic energy (represented by $y^2$ ) and the rate of change of potential energy (represented by $\frac{d V}{d x}$ ) are zero at these points. For the given energy function, critical points are typically the local minima or maxima of $V(x)$.

- At stable critical points of the system (such as $x=2 \pi k$, where $k$ is an integer), the potential energy $V(x)=1-\cos x$ reaches its minimum value of 0 . Since $y=0$ at these points (implying zero kinetic energy), the total energy $E=\frac{1}{2} y^2+(1-\cos x)=0$ at these stable critical points.

$E=2$ at Saddle Points

At saddle points, the behavior of the system is unstable, but $\dot{x}=0$ and $\dot{y}=0$ still hold. These points correspond to local maxima of the potential energy $V(x)$. For the given energy function, a straightforward example is when $x=\pi+2 \pi k$ (where $k$ is an integer), at which point $\cos x=$ -1 .

- At these points, the potential energy $V(x)=1-\cos x=2$, while the kinetic energy $\frac{1}{2} y^2$ remains 0 (because $y=0$ ). Thus, the total energy $E=\frac{1}{2} y^2+(1-\cos x)=2$ at these saddle points.







Since $E=0$ for a linear stable critical point, by continuity, small $E$ curves, must be closed trajectories. Hence critical points are nonlinearly stable, since the existence of a closed trajectory is true nonlinearly.

Since $E=2$ for our saddle points, nearby trajectories are not closed,
- this is consistent: saddle points at the linear level remain saddles at the nonlinear level,
- any change in our conclusions using energy conservation would have violated our current knowledge.

### 12. Example: pendulum with friction

In this case, the non-linear ODE is of the form $(\gamma>0)$ :
$$
\dot{x}=y, \quad \dot{y}=-\sin x-\gamma y .
$$


For a frictionless pendulum, the energy $E$ consists of kinetic and potential energy, given by:
$$
E=\frac{1}{2} y^2+(1-\cos x)
$$

Here, $\frac{1}{2} y^2$ is the kinetic energy, and $1-\cos x$ is the potential energy.
Is Energy Conserved?
To determine whether energy is conserved, we need to calculate the rate of change of energy $E$ with time, $\frac{d E}{d t}$. Applying the chain rule, we get:
$$
\frac{d E}{d t}=\frac{\partial E}{\partial x} \dot{x}+\frac{\partial E}{\partial y} \dot{y}
$$

Substituting the partial derivatives of kinetic and potential energy, we obtain:
$$
\frac{d E}{d t}=(\sin x) \dot{x}+y \dot{y}
$$

Using the system's equations, where $\dot{x}=y$ and $\dot{y}=-\sin x-\gamma y$, we substitute these values to find:
$$
\frac{d E}{d t}=(\sin x) y+y(-\sin x-\gamma y)=-\gamma y^2
$$

The term $-\gamma y^2$ represents the energy loss due to friction. Since $\gamma>0$ and $y^2 \geq 0$, this means $\frac{d E}{d t}$ is always negative or zero.

Question: Is energy conserved?
$$
\frac{d E}{d t}=y \dot{y}+\sin x \dot{x}=-\gamma y^2<0
$$
- $E$ is not conserved but it decreases monotonically
- $\frac{d E}{d t}<0 \Rightarrow \phi \in\left(\frac{\pi}{2}, \frac{3 \pi}{2}\right)$
- For linear stable critical points $\Rightarrow$ tangent vector to the trajectory points towards the interior $\Rightarrow$ nonlinearly asymptotically stable since the trajectory necessarily moves towards the critical point

Without knowing the explicit/implicit trajectory, we can infer this conclusion.

Question: Does this interpretation hold more generally?

### 13. Definition

The main features of our previous discussion are
- $\exists$ a function $E: \mathbb{R}^2 \rightarrow \mathbb{R}$ vanishing at a critical point and is otherwise positive
- The time derivative $\frac{d E}{d t}$ of $E$ evaluated on a solution vanishes at the critical point and is otherwise negative or zero

More mathematically,

Let $E: D \subset \mathbb{R}^2 \rightarrow \mathbb{R}$ be defined on a domain $D$ containing a critical point $\mathbf{x}_0$.
$E$ is positive [negative] definite.

If $E\left(\mathbf{x}_0\right)=0$ and $E(x, y)>0 \forall(x, y) \neq x_0 \in D[E(x, y)<0 \forall(x, y) \in D]$.
$E$ is positive [negative] semi-definite if $E\left(x_0\right)=0$ and $E(x, y) \geq 0 \forall(x, y) \in D[E(x, y) \leq 0 \forall(x, y) \in D]$.

Another feature of our examples which is crucial for the
generalisation to work is that the critical points were isolated:

A critical point $\mathbf{x}_0$ a system of differential equations is isolated if there is a neighbourhood of $\mathbf{x}_0$ containing no other critical points.


### 14. Lyapunov's theory (First)

Consider a two-dimensional autonomous system with an isolated critical point $\mathbf{x}_0$ and a region $D \subset \mathbb{R}^2$ containing $\mathbf{x}_0$. Suppose that there is a positive definite and continuous function $E: D \rightarrow \mathbb{R}$ with continuous first partial derivatives, such that $E\left(\mathbf{x}_0\right)=0$. If $\partial_x E F+\partial_y E G$ is negative semi-definite [negative definite] on $D$ then $\left(x_0\right)$ is a stable critical point [asymptotically stable critical point ].

Whenever $E$ exists, it is called Lyapunov function. This goes beyond our motivational discussion. In particular, $E$ is not interpretable as energy in general.


### 15. Lyapunov's theory (Second)

Lyapunov's second theorem: it tells us when a critical point is
unstable.

Consider a two-dimensional autonomous system with an isolated critical point $\mathbf{x}_0$ and a region $D \subset \mathbb{R}^2$ containing $\mathbf{x}_0$. Suppose that there is a continuous function $E: D \rightarrow \mathbb{R}$ with continuous first partial derivatives, such that $E\left(\mathbf{x}_0\right)=0$ and that in every neighbourhood of $\left(\mathbf{x}_0\right) \exists$ at least one point $\mathbf{x}_1$ where $E\left(\mathbf{x}_1\right)>0$. If $\partial_x E F+\partial_y E G$ is positive definite on $D$ then $\mathbf{x}_0$ is an unstable critical point.

Lyapunov's theory is powerful because it does not require to know the trajectories to the non-linear system

But, no-one tells us what function $E(x, y)$ to use:
- in some cases, it may be the energy, but not always
- usually, we must cook up suitable functions for a given problem
$$
\begin{aligned}
& E(x, y)=a x^{2 n}+b y^{2 m}, \\
& E(x, y)=a(x+y)^{2 n}+b y^{2 m}
\end{aligned}
$$

But there can be infinitely many suitable ones depending on the ODE system.

In the following, we discuss some examples on how to use these methods in linear and non-linear ODE systems.

### 16. Example 1 (a linear warm-up)

Consider the linear ODE system:
$$
\dot{x}=-2 x, \quad \dot{y}=x-y .
$$

Consider, as a candidate Lyapunov function the quadratic
$$
E(x, y)=a x^2+b y^2 .
$$
where $a, b$ are free parameters that we will choose to satisfy the conditions in Lyapunov's theorems.
$$
\begin{aligned}
\frac{d E}{d t} & =\left(\partial_x E\right) \dot{x}+\left(\partial_y E\right) \dot{y}=2 a x(-2 x)+2 b y(x-y) \\
& =-2 b\left(\frac{2 a}{b} x^2-x y+y^2\right)
\end{aligned}
$$

Observation: if we choose $\frac{2 a}{b}=\frac{1}{4}$, then
$$
\dot{E}=-2 b\left(\frac{x^2}{4}-x y+y^2\right)=-2 b\left(\frac{x}{2}-y\right)^2
$$

Whenever $8 a=b>0$, we have $E(x, y)=a\left(x^2+8 y^2\right)$
- $E(x, y)$ is positive definite in a domain containing the critical point $(0,0)$
- $\dot{E}$ is negative semi-definite in the same domain
- $E(x, y)$ is a Lyapunov function

By Lyapunov's theory, $(0,0)$ is stable at the non-linear level (it is an (asymptotically) stable node, according to the linear approximation).

### 17. Example 2

Consider the non-linear system:
$$
\dot{x}=-x y^2, \quad \dot{y}=3 y x^2 .
$$
$\left(x_0, y_0\right)=(0,0)$ is a critical point, but this is not isolated: in fact, all points $(0, y)$ and $(x, 0), x, y \in \mathbb{R}$, on the axes. are critical points. Hence Lyapunov's theory does not apply! (and you can check that $V=3 x+y^2$ would imply stability and $V=x^2+3 y^2$ would imply instability)


### 18. Example 3

Consider the nonlinear ODE system
$$
\frac{d x}{d t}=-2 x+m y^2 x^2, \quad \frac{d y}{d t}=-n y-x^5 y,
$$
where $x, y$ are real variables, and $n, m>0$ and $m$. Prove the origin is asymptotically stable.

Consider the function
$$
E(x, y)=a x^4+b y^2 .
$$

Compute its time derivative:
$$
\begin{aligned}
\dot{E} & =\dot{x} \partial_x E+\dot{y} \partial_y E=4 a x^4\left(-2+m y^2 x\right)+2 b y^2\left(-n-x^5\right) \\
& =-8 a x^4-2 b n y^2+2 x^5 y^2(-b+2 a m)
\end{aligned}
$$
- Choose $b=2 m$ a and $a>0$ (so that $b>0$ ) $\Rightarrow \dot{E}<0$ except at the origin, where it vanishes.
- $E(x, y)$ vanishes at the origin but is otherwise positive.

Thus, $E(x, y)$ is a Lyapunov function $\Rightarrow(0,0)$ is asymptotically stable (nonlinearly).


### 19. Example 4 (use of the 2nd theorem)

Consider
$$
\dot{x}=x+3 y, \quad \dot{y}=2 x
$$

We will study the stability of the origin using the Lyapunov function
$$
E(x, y)=x y+b y^2 .
$$

Notice its time derivative satisfies
$$
\dot{E}=3 y^2+2 x^2+x y(1+4 b)=3 y^2+2 x^2 \quad \text { if } b=-\frac{1}{4}
$$

Thus, $\dot{E}$ is positive definite.
Since we can find points $\left(x_1, y_1\right)$ where $E\left(x_1, y_1\right)>0$ in any neighbourhood of the origin, we satisfy today's Lyapunov's theorem. This guarantees the origin is an unstable critical point.

## Part 6

### 1. Motivating the rest of the ODE part of the note

So far, we have focused on
- ordinary DEs, i.e., a single independent variable,
- initial value problems, specifying $\boldsymbol{x}\left(t_0\right)$,

In this setup, we discussed
- $n$-th order linear ODES $\Leftrightarrow 1$ st order linear systems
- introduction to non-linear methods (autonomous systems)

In the rest of the course, we will discuss
- boundary value problems,
- partial linear DEs, i.e., more than one independent variable,
- Sturm-Liouville: linear algebra in infinite dimension,
- revisit initial value problems, with Laplace transforms.

### 2. Boundary value problem - an example

Solve
$$
y^{\prime \prime}+y=0,
$$
subject to the boundary conditions $y(0)=1$ and $y(\pi)=a$. The general (real) solution to the 2 nd order ODE is:
$$
y(x)=c_1 \cos x+c_2 \sin x .
$$

Boundary conditions:
$$
\begin{aligned}
& y(0)=c_1=1 \Rightarrow c_1=1 \\
& y(\pi)=-c_1=a \Rightarrow c_1=-a .
\end{aligned}
$$

Thus,
- if $a \neq-1$ no solution,
- if $a=-1 \Rightarrow y(x)=\cos x+c_2 \sin x$
$\Rightarrow$ infinitely many solutions.

### 3. Boundary value problems vs. initial value problems

- Recall IVP:
$$
y^{\prime \prime}+p(t) y^{\prime}+q(t) y=g(t), \quad y\left(t_0\right)=\alpha, \quad y^{\prime}\left(t_0\right)=\beta
$$
unique solution on open interval $I$ guaranteed provided that $p$, $q, g$ continuous on $I$.
- BVP:
$$
y^{\prime \prime}+p(x) y^{\prime}+q(x) y=g(x), \quad y\left(x_1\right)=\alpha, \quad y\left(x_2\right)=\beta
$$
could have
- unique solution
- many solutions
- no solution


### 4. Motivating boundary eigenvalue problems

A basis for vectors in $\mathbb{R}^n: n$ linearly independent vectors $\boldsymbol{e}_i$ Any vector $v$ can be expanded as
$$
\boldsymbol{v}=\sum_{i=1}^n v^i \boldsymbol{e}_i
$$

Given a diagonalisable $\mathrm{n} \times \mathrm{n}$ matrix $A$ acting on $\mathbb{R}^n$, one particular such basis is given by the eigenvectors $\boldsymbol{\xi}_\lambda$ :
$$
A \xi_\lambda=\lambda \xi_\lambda
$$
- Any $\mathrm{n} \times \mathrm{n}$ matrix can be identified as a linear map from $\mathbb{R}^n$ to $\mathbb{R}^n$.

Question: what about the space of functions?
Functions $y(x)$ can be thought of as vectors:
$$
a f_1(x)+b f_2(x) \quad a, b \in \mathbb{R} \quad \text { is also a function. }
$$
we can define linear maps using derivatives:
$$
\frac{d}{d x}: y(x) \mapsto \frac{d y}{d x}(x)
$$
is linear. 

So are higher derivatives and their linear combinations, defining linear operators such as
$$
p(x) \frac{d^2}{d x^2}+q(x) \frac{d}{d x} .
$$

Questions: Can we define eigenvalue problems for linear operators? Are the corresponding eigenvectors (= eigenfunctions) useful?

### 5. Boundary eigenvalue problems (another example)

Consider $\lambda \in \mathbb{R}$
$$
y^{\prime \prime}-\lambda y=0 \Leftrightarrow \frac{d^2}{d x^2} y(x)=\lambda y(x), \quad y(0)=y(L)=0 .
$$

Case 1:

If $\lambda=0 \Rightarrow y=c_1 x+c_2$. Using boundary conditions
$$
\begin{aligned}
& y(0)=c_2=0 \\
& y(L)=c_1 L=0 \Rightarrow c_1=0
\end{aligned}
$$

Only the trivial solution remains.

Case 2:

If $\lambda=\mu^2>0 \Rightarrow y=c_1 \cosh \mu x+c_2 \sinh \mu x$. Using boundary conditions
$$
\begin{aligned}
& y(0)=c_1=0 \\
& y(L)=c_2 \sinh \mu L=0 \Rightarrow c_2=0
\end{aligned}
$$

Only the trivial solution remains.

Case 3:

If $\lambda=-\mu^2<0$ then
$$
y(x)=c_1 \cos \mu x+c_2 \sin \mu x .
$$

Using boundary conditions:
$$
\begin{aligned}
& y(0)=0 \Rightarrow c_1=0 \\
& y(L)=0 \Rightarrow c_2 \sin \mu L=0 \Rightarrow \lambda_n=-\left(\frac{n \pi}{L}\right)^2, n=1,2, \ldots
\end{aligned}
$$

Thus, the eigenfunctions are
$$
y_n \propto \sin \frac{n \pi x}{L}
$$
corresponding to the eigenvalues $\lambda_n$.

In the rest of ODE part, we will explore the following questions:

Is there any sense in which an element (function $y(x)$ ) in the subspace of functions satisfying the boundary conditions
$$
y(0)=y(L)=0
$$
can be expanded in the basis of eigenfunctions $y_n(x)$,
$$
y(x)=\sum_{n=1}^{\infty} c_n y_n(x)=\sum_{n=1}^{\infty} c_n \sin \frac{n \pi x}{L} ?
$$

Is it possible to define some notion of orthogonality in the space of functions, using a scalar product such as
$$
(f, g)=\int_a^b f^{\star}(x) g(x) d x ?
$$

What is the equivalent for functions of the symmetry condition $A^{\mathrm{T}}=A$ for matrices?

### 6. Orthogonality of functions for periodic functions

Consider the set of periodic functions $\left\{\sin \frac{n \pi x}{L}, \cos \frac{m \pi x}{L}\right\}$ in the interval $x \in[-L, L]$ with $n, m=1,2, \ldots$

Using the identities
$$
\begin{aligned}
\cos A \cos B & =\frac{1}{2}[\cos (A-B)+\cos (A+B)], \\
\sin A \sin B & =\frac{1}{2}[\cos (A-B)-\cos (A+B)], \\
\sin A \cos B & =\frac{1}{2}[\sin (A+B)+\sin (A-B)],
\end{aligned}
$$
we show that defining the inner product of $u(x)$ and $v(x)$ as
$$
(u(x), v(x)) \equiv \int_{-L}^L u(x) v(x) d x
$$
the set $\left\{\sin \frac{n \pi x}{L}, \cos \frac{m \pi x}{L}\right\}$ is mutually orthogonal, i.e., for every pair of distinct functions $(u(x), v(x))=0$.

Proof:

Consider the pair $S_n(x)=\sin \frac{n \pi x}{L}$ and $S_m(x)=\sin \frac{m \pi x}{L}$ :
$$
\begin{aligned}
\left(S_m, S_n\right) & =\int_{-L}^L \sin \frac{m \pi x}{L} \sin \frac{n \pi x}{L} d x \\
& =\frac{1}{2} \int_{-L}^L\left(\cos \frac{(m-n) \pi x}{L}-\cos \frac{(m+n) \pi x}{L}\right) d x \\
& =\frac{L}{2 \pi}\left[\frac{\sin (m-n) \pi x / L}{m-n}-\frac{\sin (m+n) \pi x / L}{m+n}\right]_{-L}^L \\
& =0 \text { if } m \neq n
\end{aligned}
$$

If $m=n$, then notice that
$$
\left(\sin \frac{n \pi x}{L}\right)^2=\frac{1}{2}\left(1-\cos \frac{2 n \pi x}{L}\right) .
$$

Thus,
$$
\begin{aligned}
\left(S_n, S_n\right) & =\int_{-L}^L\left(\sin \frac{n \pi x}{L}\right)^2 d x \\
& =\frac{1}{2}\left[x-\frac{\sin 2 n \pi x / L}{2 n \pi / L}\right]_{-L}^L \\
& =L
\end{aligned}
$$

If $m=n$, then notice that
$$
\left(\sin \frac{n \pi x}{L}\right)^2=\frac{1}{2}\left(1-\cos \frac{2 n \pi x}{L}\right) .
$$

Thus,
$$
\begin{aligned}
\left(S_n, S_n\right) & =\int_{-L}^L\left(\sin \frac{n \pi x}{L}\right)^2 d x \\
& =\frac{1}{2}\left[x-\frac{\sin 2 n \pi x / L}{2 n \pi / L}\right]_{-L}^L \\
& =L
\end{aligned}
$$

We can write both results as
$$
\left(S_m, S_n\right)=L \delta_{m n} \quad m, n \neq 0
$$

It is clear that if we define $C_n(x)=\cos \frac{n \pi x}{L}$, these satisfy
$$
\left(C_m, C_n\right)=0, \quad m \neq n
$$

When $m=n$ since
$$
\left(\cos \frac{n \pi x}{L}\right)^2=\frac{1}{2}\left(1+\cos \frac{2 n \pi x}{L}\right),
$$
we still get $\left(C_n, C_n\right)=L \Rightarrow\left(C_m, C_n\right)=L \delta_{m n} \quad m, n \neq 0$

Finally,
$$
\begin{aligned}
\left(S_m, C_n\right) & =\int_{-L}^L \sin \frac{m \pi x}{L} \cos \frac{n \pi x}{L} d x \\
& =\frac{1}{2} \int_{-L}^L\left[\sin \frac{(m+n) \pi x}{L}+\sin \frac{(m-n) \pi x}{L}\right] d x \\
& =-\frac{L}{2 \pi}\left[\frac{\cos (m+n) \pi x / L}{(m+n)}+\frac{\cos (m-n) \pi x / L}{(m-n)}\right]_{-L}^L \\
& =0
\end{aligned}
$$
because $\cos x$ is an even function. Notice that this conclusion holds even if $n=m$ :
$$
\left(S_n, C_n\right)=\frac{1}{2} \int_{-L}^L \sin \frac{2 n \pi x}{L} d x=-\frac{L}{2 n \pi}\left[\cos \frac{2 n \pi x}{L}\right]_{-L}^L=0 .
$$

Thus, given the collection of periodic functions $\left\{\sin \frac{n \pi x}{L}, \cos \frac{m \pi x}{L}\right\}$ in the interval $x \in[-L, L]$ with $n, m=1,2, \ldots$, we have indeed shown that it defines a set of mutually orthogonal functions using the inner product
$$
(u(x), v(x)) \equiv \int_{-L}^L u(x) v(x) d x
$$
with $\quad\left(S_n, S_m\right)=\left(C_n, C_m\right)=L \delta_{n m} \quad$ and $\quad\left(S_n, C_m\right)=0$.

### 7. Definition

Given a periodic function $f(x)$ with period $2 L$, it can be expressed as a Fourier series
$$
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}\left(a_n \cos \frac{n \pi x}{L}+b_n \sin \frac{n \pi x}{L}\right)
$$
when $f(x)$ satisfies some conditions to be discussed.
- The coefficients $\left\{a_0, a_n, b_n\right\}$ are constants, called the Fourier coefficients of $f(x)$. They are real if $f(x)$ is real.
- since the series involves an infinite number of terms, there is a natural question concerning the convergence of this series.

### 8. Euler-Fourier formulas

Assume the Fourier series of $f(x)$ converges.

Question: How do we calculate its Fourier coefficients $\left\{a_0, a_n, b_n\right\}$ ?
Use orthogonality: given
$$
f(x)=\frac{a_0}{2}+\sum_{m=1}^{\infty}\left(a_m \cos \frac{m \pi x}{L}+b_m \sin \frac{m \pi x}{L}\right),
$$
compute the inner product of both sides with $\cos \frac{n \pi x}{L}$, i.e., project the function $f(x)$ onto $\cos \frac{n \pi x}{L}$,
$$
\begin{aligned}
\left(f(x), \cos \frac{n \pi x}{L}\right) & =\int_{-L}^L f(x) \cos \frac{n \pi x}{L} d x \\
& =L a_n
\end{aligned}
$$

Thus,
$$
a_n=\frac{1}{L} \int_{-L}^L f(x) \cos \frac{n \pi x}{L} d x \quad n=0,1,2, \ldots
$$
- We used the orthogonality relations
$$
\begin{aligned}
& \left(S_n, S_m\right)=\left(C_n, C_m\right)=L \delta_{m n}, m, n=1,2, \ldots \\
& \left(S_n, C_m\right)=\left(C_m, S_n\right)=0
\end{aligned}
$$
- In fact, these relations can be extended to include $n=0$. Define $C_0=1$ (the constant function equal to one). Notice,
$$
\begin{aligned}
& \left(C_0, C_0\right)=\int_{-L}^L 1 d x=2 L, \\
& \left(C_0, C_m\right)=\int_{-L}^L \cos \frac{m \pi x}{L} d x=0, \\
& \left(C_0, S_m\right)=\int_{-L}^L \sin \frac{m \pi x}{L} d x=0 .
\end{aligned}
$$

Thus, when we project along $C_0$, we obtain
$$
\left(f(x), C_0\right)=\frac{a_0}{2}\left(C_0, C_0\right)=a_0 L \Rightarrow a_0=\frac{1}{L} \int_{-L}^L f(x) d x .
$$
- This justifies/explains why there is a $\frac{1}{2}$ in the original definition, i.e. so that all $a_n$ have the same formula, since $\cos \frac{n \pi x}{L}$ equals one for $n=0$
- the constant term $\frac{a_0}{2}$ is the average value of the function over the period:
$$
\frac{a_0}{2}=\frac{1}{2 L} \int_{-L}^L f(x) d x \equiv\langle f(x)\rangle
$$

Projecting onto $\sin \frac{n \pi x}{L}$, we can compute the remaining coefficients
$$
\begin{aligned}
\left(f(x), \sin \frac{n \pi x}{L}\right) & =\left(\frac{a_0}{2}+\sum_{m=1}^{\infty}\left(a_m \cos \frac{m \pi x}{L}+b_m \sin \frac{m \pi x}{L}\right), \sin \frac{n \pi x}{L}\right) \\
& =L b_n
\end{aligned}
$$

Thus,
$$
b_n=\frac{1}{L} \int_{-L}^L f(x) \sin \frac{n \pi x}{L} d x .
$$

The formulas computing the Fourier coefficients $\left\{a_0, a_n, b_n\right\}$ are referred to as Euler-Fourier formulas.

### 9. Example


![](https://files.mdnice.com/user/36229/8b4770b1-b737-444a-8af6-131e6337e3e4.jpg)

$$
f(x) = 
\begin{cases} 
0 & \text{if } -3 < x < -1 \\
1 & \text{if } -1 < x < 1 \\
0 & \text{if } 1 < x < 3 
\end{cases}
$$


Since the period is $T=6 \Rightarrow 2 L=6 \Rightarrow L=3$.


Thus,
$$
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}\left(a_n \cos \frac{n \pi x}{3}+b_n \sin \frac{n \pi x}{3}\right)
$$

- Using Euler-Fourier formulas:
$$
\begin{aligned}
& a_0=\frac{1}{3} \int_{-3}^3 f(x) d x=\frac{1}{3} \int_{-1}^1 d x=\frac{2}{3} \\
& a_n=\frac{1}{3} \int_{-3}^3 f(x) \cos \frac{n \pi x}{3} d x=\frac{1}{3} \int_{-1}^1 \cos \frac{n \pi x}{3} d x=\frac{2}{n \pi} \sin \frac{n \pi}{3} \\
& b_n=\frac{1}{3} \int_{-3}^3 f(x) \sin \frac{n \pi x}{3} d x=\frac{1}{3} \int_{-1}^1 \sin \frac{n \pi x}{3} d x=0
\end{aligned}
$$

Thus, the Fourier series of the function $f(x)$ is given by the infinite sum
$$
f(x)=\frac{1}{3}+\sum_{n=1}^{\infty} \frac{2}{n \pi} \sin \frac{n \pi}{3} \cos \frac{n \pi x}{3}
$$

### 10. Connection to vector algebra

There is a close analogy between the structure of Fourier series and vector algebra. The correspondence is as follows:
- the space of vectors is replaced by the set of periodic functions,
- the function $f(x)$ corresponds to an arbitrary vector $\boldsymbol{v}$,
- the orthogonal basis $\left\{\boldsymbol{e}_i\right\}$ correspond to $\left\{1, \cos \frac{n \pi x}{L}, \sin \frac{m \pi x}{L}\right\}$
- the vector components $v^i$, i.e., $\boldsymbol{v}=\sum_i v^i \boldsymbol{e}_i$, correspond to the Fourier coefficients $\left\{a_n, b_m\right\}$
- both are computed using the inner product in the same way
$$
v^i=\left(\boldsymbol{v}, \boldsymbol{e}_i\right), \quad \text { vs } \quad a_n=\left(f(x), C_n\right) / L, \quad b_m=\left(f(x), S_m\right) / L
$$

Thus, if the infinite sum converges, we will have discovered the existence of an infinite dimensional vector space, spanned by countably many basis functions (called a Hilbert space).


### 11. Definition

A function $f(x)$ is said to be piecewise continuous on $x \in[a, b]$ if $[a, b]$ can be partitioned into a finite number of points
$a=x_0<x_1<x_2 \ldots x_{n-1}<x_n=b$ such that
- $f(x)$ continuous $x \in\left(x_{i-1}, x_i\right)$
- $f(x)$ has a finite limit as the endpoints of each subinterval $\left(x_{i-1}, x_i\right)$ are approached from within the subinterval For example, let $x_i=c$, then
$$
\begin{aligned}
& f\left(c^{+}\right) \equiv \lim _{x \rightarrow c^{+}} f(x) \text { finite (limit from the right) } \\
& f\left(c^{-}\right) \equiv \lim _{x \rightarrow c^{-}} f(x) \text { finite (limit from the left) }
\end{aligned}
$$

### 12. Fourier convergence theorem

Suppose $f(x)$ and $f^{\prime}(x)$ are piecewise continuous for $x \in[-L, L]$ Suppose $f(x)$ is defined outside this interval so that it is periodic with period $2 L$ .

Then, $f(x)$ has a Fourier series
$$
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}\left(a_n \cos \frac{n \pi x}{L}+b_n \sin \frac{n \pi x}{L}\right),
$$
with coefficients given by the Euler-Fourier formulas. The series converges to $f(x) \forall x$ where $f(x)$ is continuous and to $\frac{f\left(x^{+}\right)+f\left(x^{-}\right)}{2}$ at all points where $f(x)$ is discontinuous.

Remarks:

- $f(x)$ need not be defined at points of discontinuity
- Functions like $\frac{1}{x^2}$ or $\log x$ have no convergent Fourier series because of the infinite divergences of the function at $x=0$
- Functions having an infinite number of discontinuities are not guaranteed to have a convergent Fourier Series

### 13. Example

$$
f(x) = 
\begin{cases} 
0 & \text{if } -L < x < 0 \\
L & \text{if } 0 < x < L 
\end{cases}
$$

with $f(x + 2L) = f(x)$.


![](https://files.mdnice.com/user/36229/06466420-09a5-482c-bceb-b408cd73f3dc.jpg)


In the interval $[-L, L]$ the function has (jump) discontinuities at $x=0$ and $x= \pm L$ with finite limits
$\Rightarrow f(x)$ is piecewise continuous
$\Rightarrow$ Fourier convergence theorem applies.


Using Euler-Fourier formulas:
$$
\begin{aligned}
a_0 & =\frac{1}{L} \int_{-L}^L f(x) d x=\int_0^L d x=L \\
a_n & =\frac{1}{L} \int_{-L}^L f(x) \cos \frac{n \pi x}{L} d x=\int_0^L \cos \frac{n \pi x}{L} d x=0 . \\
b_n & =\frac{1}{L} \int_{-L}^L f(x) \sin \frac{n \pi x}{L} d x=\int_0^L \sin \frac{n \pi x}{L} d x \\
& =\frac{L}{n \pi}(1-\cos n \pi)
\end{aligned}
$$

Since $\cos n \pi=(-1)^n$, we conclude only odd $n$ contribute.

Thus, Fourier series of $f(x)$ is
$$
\frac{L}{2}+\frac{2 L}{\pi} \sum_{m=1}^{\infty} \frac{\sin (2 m-1) \pi x / L}{(2 m-1)}
$$
where we wrote $n=2 m-1$ to sum over odd integers. 

Remarks:
- Let $x_n$ denote the points where the function has discontinuities, i.e., $x=0, \pm n L$
- All $\sin (2 m-1) \pi x / L$ terms in the series vanish at $x_n$
$\Rightarrow$ Fourier series at $x_n=\frac{L}{2}$
- this matches the prediction of the theorem,
- $f\left(x_n\right)$ is not defined, but if we define a new function $\tilde{f}(x)$ equal to $f(x)$ everywhere except at the discontinuities where $\tilde{f}\left(x_n\right)=\frac{L}{2}$ then the Fourier series would converge to $\tilde{f}(x)$ everywhere.

### 14. Diffierentiation vs convergence

Consider the piecewise continuous function given by
$$
f(x) = 
\begin{cases} 
0 & \text{if } -L < x < 0 \\
L & \text{if } 0 < x < L 
\end{cases}
$$
with period $T=2(\Rightarrow L=1)$.
Its convergent Fourier series equals:
$$
f(x)=\frac{4}{\pi} \sum_{n=1}^{\infty} \frac{\sin (2 n-1) \pi x}{2 n-1} .
$$

Question: Does term-by-term differentiation yield a convergent Fourier series?

Formally differentiating term-by-term gives rise to:
$$
f^{\prime}(x) ?=4 \sum_{n=1}^{\infty} \cos (2 n-1) \pi x
$$
- This is divergent! (since $\cos (2 n-1) \pi x \not \rightarrow 0$ as $n \rightarrow \infty)$
- Thus, term-by-term differentiation of a convergent Fourier series does not necessarily yield a convergent series.
- But Fourier series for sufficiently smooth continuous functions can be differentiated term-by-term to yield convergent Fourier series.


### 15. Convergence of Fourier Series

We showed that the function

$$
f(x) = 
\begin{cases} 
0 & \text{if } -L < x < 0 \\
L & \text{if } 0 < x < L 
\end{cases}
$$
          
has the Fourier series
          
$$
f(x)=\frac{L}{2}+\frac{2 L}{\pi} \sum_{m=1}^{\infty} \frac{\sin (2 m-1) \pi x / L}{(2 m-1)} .
$$

To gain some insight into its convergence, it is natural to define a finite truncation
$$
s_n(x)=\frac{L}{2}+\frac{2 L}{\pi}\left(\sin \frac{\pi x}{L}+\cdots+\frac{\sin (2 n-1) \pi x / L}{2 n-1}\right)
$$
and measure its error by computing
$$
\left|e_n(x)\right|=\left|s_n(x)-f(x)\right| .
$$


### 16. Gibbs phenomenon

When we plot $s_n(x)$ ( $n=8$ in the picture)

![](https://files.mdnice.com/user/36229/b3893e0e-3db2-4e43-a9e1-bb3e0fe23320.jpg)

As $n$ increases, the Fourier series approximates $f(x)$ better $\forall x$ where $f(x)$ is continuous.

But the convergence to the mean value at the discontinuity points is not smooth
- $s_n(x)$ overshoots the actual value of the function (see first/last peaks close to any discontinuity point),
- overshooting persists even at large $n$ : Gibbs phenomenon.

### 17. Even & odd functions: Fourier series

- Even functions only have cosine terms in their Fourier series which is called a Fourier cosine series
- This is because $f(x) \sin \frac{m \pi x}{L}$ is odd $\Rightarrow b_m=0$ and
$$
a_m=\frac{2}{L} \int_0^L f(x) \cos \frac{m \pi x}{L} d x .
$$
- Odd functions only have sine terms in their Fourier series which is called a Fourier sine series
- This is because $f(x) \cos \frac{m \pi x}{L}$ is odd $\Rightarrow a_m=0$ and
$$
b_m=\frac{2}{L} \int_0^L f(x) \sin \frac{m \pi x}{L} d x .
$$
- Notice the factor of 2 appears because the range of integration is only over half of the period.

### 18. Example: sawtooth wave

Consider the sawtooth wave function $f(x)=x$ for $x \in(-L, L)$ satisfying
$$
f(-L)=f(L)=0 \quad \text { and } \quad f(x+2 L)=f(x)
$$


![](https://files.mdnice.com/user/36229/ba75448b-eb96-45c4-aa21-7899fe7d8e47.jpg)

Notice $f(x)=x$ is odd since $f(-x)=-x=-f(x)$ Thus, $a_m=0$. The remaining Fourier coefficients are:
$$
\begin{aligned}
b_n & =\frac{2}{L} \int_0^L x \sin \frac{n \pi x}{L} d x \\
& =\frac{2}{L}\left(\frac{L}{n \pi}\right)^2\left[\sin \frac{n \pi x}{L}-\frac{n \pi x}{L} \cos \frac{n \pi x}{L}\right]_0^L \\
& =\frac{2 L}{n \pi}(-1)^{n+1} \quad n=1,2, \ldots
\end{aligned}
$$

Thus, the Fourier sine series equals
$$
f(x)=\frac{2 L}{\pi} \sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{n} \sin \frac{n \pi x}{L} .
$$

Notice $f( \pm n L)=0$, according to the series, which is indeed the mean value of the function, as claimed by the Fourier series convergence theorem.

Since we defined $f(L)=f(-L)=0$ in the first place, this makes the Fourier series convergent everywhere.

### 19. Complex form of Fourier series

Using the identity
$$
e^{i x}=\cos x+i \sin x
$$
we can rewrite the Fourier series using complex exponentials:
$$
\begin{aligned}
f(x) & =\frac{a_0}{2}+\sum_{n=1}^{\infty}\left[\frac{a_n}{2}\left(e^{i n \pi x / L}+e^{-i n \pi x / L}\right)+\frac{b_n}{2 i}\left(e^{i n \pi x / L}-e^{-i n \pi x / L}\right)\right] \\
& =\sum_{n=-\infty}^{\infty} c_n e^{i n \pi x / L}
\end{aligned}
$$
where we defined
$$
c_n=\frac{a_n-i b_n}{2} \quad(n>0), \quad c_{-n}=\frac{a_n+i b_n}{2} \quad(n>0), \quad c_0=\frac{a_0}{2}
$$

Notice the different range in the label $n$, which can take negative integer values.

- We could have used complex exponential basis from the start.
- Using the definition of inner product for complex functions
$$
(f, g)=\int_\alpha^\beta f^{\star}(x) g(x) d x
$$
we find the orthogonality relations
$$
\left(e^{\frac{i m \pi x}{L}}, e^{\frac{i n \pi x}{L}}\right)=\int_{-L}^L e^{\frac{-i m \pi x}{L}} e^{\frac{i n \pi x}{L}} d x=2 L \delta_{m n}
$$
since
$$
\int_{-L}^L e^{\frac{-i m \pi x}{L}} e^{\frac{i n \pi x}{L}} d x=\frac{L\left[e^{i \pi(n-m)}-e^{-i \pi(n-m)}\right]}{i \pi(n-m)}=0, \quad n \neq m
$$
- Using this orthogonality, the Fourier coefficients $c_n$ equal:
$$
c_n=\frac{1}{2 L} \int_{-L}^L e^{-\frac{i n \pi x}{L}} f(x) d x, \quad n \in \mathbb{Z}
$$
- Note: If the function is real, then $c_{-n}=c_n^{\star}$


### 20. Parseval's theorem for Fourier Series

The square norm $(f, f)$ of a periodic function $f(x)$ with a convergent Fourier series
$$
f(x)=\sum_{n=-\infty}^{\infty} c_n e^{i n \pi x / L},
$$
satisfies
$$
\begin{aligned}
(f, f) & =\int_{-L}^L|f(x)|^2 d x=2 L \sum_{n=-\infty}^{\infty}\left|c_n\right|^2 \\
& =L\left[\frac{\left|a_0\right|^2}{2}+\sum_{n=1}^{\infty}\left(\left|a_n\right|^2+\left|b_n\right|^2\right)\right]
\end{aligned}
$$

Proof:

By definition
$$
\begin{aligned}
(f, f) & =\sum_{n, m=-\infty}^{\infty} \int_{-L}^L c_n c_m^{\star} e^{i(n-m) \pi x / L} d x \\
& =\sum_{n, m=-\infty}^{\infty} c_n c_m^{\star} 2 L \delta_{m n} \text { by orthogonality } \\
& =2 L \sum_{n=-\infty}^{\infty}\left|c_n\right|^2
\end{aligned}
$$

To prove the last part, we recall
$$
c_n=\frac{a_n-i b_n}{2} \quad(n>0), \quad c_{-n}=\frac{a+i b_n}{2} \quad(n<0), \quad c_0=\frac{a_0}{2}
$$

Indeed,
$$
\begin{aligned}
2 L \sum_{n=-\infty}^{\infty}\left|c_n\right|^2 & =2 L\left[\left|c_0\right|^2+\sum_{n=1}^{\infty}\left(\left|c_n\right|^2+\left|c_{-n}\right|^2\right)\right] \\
& =2 L\left[\frac{\left|a_0\right|^2}{4}+\sum_{n=1}^{\infty}\left(\frac{\left|a_n\right|^2+\left|b_n\right|^2}{4}+\frac{\left|a_n\right|^2+\left|b_n\right|^2}{4}\right)\right] \\
& =L\left[\frac{\left|a_0\right|^2}{2}+\sum_{n=1}^{\infty}\left(\left|a_n\right|^2+\left|b_n\right|^2\right)\right] .
\end{aligned}
$$


### 21. Some basic PDEs

For now, we consider PDEs:
- linear 2nd order PDEs,
- use separation of variables; i.e., seek solutions of the form:
$$
u\left(x_1, x_2, \ldots x_n\right)=X_1\left(x_1\right) X_2\left(x_2\right) \ldots x_n\left(x_n\right)
$$
- subject to boundary \& initial conditions in simple geometries.

### 22. Heat (conduction) equation 

The linear PDE:
$$
\partial_t u=\alpha^2 \partial_x^2 u
$$
models heat conduction in 1 spatial dimension, for example.
- Notation: $\partial_t u \equiv \frac{\partial u}{\partial t} \equiv u_t, \quad \partial_x^2 u \equiv \frac{\partial^2 u}{\partial x^2} \equiv u_{x x}$
- the function $u(x, t)$ represents the temperature of a thin rod of length $L$, i.e., $0 \leq x \leq L$ at time $t \geq 0$,
- the function $u(x, t)$ satisfies
- initial condition: $u(x, 0)=f(x), 0 \leq x \leq L$,
- boundary conditions: $u(0, t)=u(L, t)=0, t>0$,
- $\alpha^2$ is a real (positive) parameter (called thermal diffusivity).

### 23. Separation of variables in action

Assume solution takes separable form:
$$
u(x, t)=X(x) T(t) .
$$

Introducing into the heat equation, we obtain
$$
\alpha^2 X^{\prime \prime} T=X \dot{T} \quad \Leftrightarrow \quad \frac{X^{\prime \prime}}{X}(x)=\frac{1}{\alpha^2} \frac{\dot{T}}{T}(t)
$$

Question: how can a function of $x$ also be a function of $t$ ?
Answer: It cannot ... unless both functions are constant:
$$
\frac{X^{\prime \prime}}{X}(x)=\frac{1}{\alpha^2} \frac{\dot{T}}{T}(t) \equiv-\lambda
$$
$\lambda$ is an example of a separation constant.

Thus, the PDE
$$
\partial_t u=\alpha^2 \partial_x^2 u
$$
reduces to the pair of ODE problems if $u(x, t)=X(x) T(t)$
$$
X^{\prime \prime}+\lambda X=0, \quad \dot{T}+\alpha^2 \lambda T=0 .
$$

Question: What boundary/initial conditions do $X(x)$ and $T(t)$ satisfy ?
- Since $u(0, t)=u(L, t)=0 \forall t>0 \Rightarrow X(0)=X(L)=0$

Thus, $X(x)$ satisfies the boundary eigenvalue problem
$$
X^{\prime \prime}+\lambda X=0, \quad X(0)=X(L)=0
$$
where the separation constant $=$ eigenvalue.

The boundary eigenvalue problem
$$
X^{\prime \prime}+\lambda X=0, \quad X(0)=X(L)=0
$$
was solved previously:
- there exists an infinite (countable) set of eigenvalues
$$
\lambda_n=\frac{n^2 \pi^2}{L^2} \quad n=1,2, \ldots
$$
- each $\lambda_n$ has a single eigenfunction
$$
X_n(x) \propto \sin \frac{n \pi x}{L}
$$

The second ODE problem is 1st order:
$$
\dot{T}_n+\alpha^2 \lambda_n T_n=0 \Rightarrow T_n \propto e^{-\alpha^2 \lambda_n t}
$$

Thus, for each $\lambda_n$, there exists a different $T_n(t)$
we find a countable infinity of solutions, each of the form
$$
u_n(x, t) \propto X_n(x) T_n(t)
$$
for each eigenvalue $\lambda_n$.
- Since the PDE
$$
\partial_t u=\alpha^2 \partial_x^2 u
$$
is linear, we conclude the most general solution obtained using this method must be the linear combination
$$
u(x, t)=\sum_{n=1}^{\infty} c_n u_n(x, t)=\sum_{n=1}^{\infty} c_n e^{-n^2 \pi^2 \alpha^2 t / L^2} \sin \frac{n \pi x}{L}
$$

The constants $c_n$ are determined by the initial condition
$$
u(x, 0)=f(x)=\sum_{n=1}^{\infty} c_n \sin \frac{n \pi x}{L} .
$$

Thus, given a function $f(x)$, the coefficients $c_n$ are fixed by the Euler-Fourier formulas:
$$
c_n=\frac{2}{L} \int_0^L f(x) \sin \frac{n \pi x}{L} d x,
$$
where we used formulas for a Fourier sine series (hence factor of 2).

Thus, the problem
$$
\partial_t u=\alpha^2 \partial_x^2 u
$$
satisfying
- initial condition: $u(x, 0)=f(x), 0 \leq x \leq L$
- boundary conditions: $u(0, t)=u(L, t)=0, t>0$
is solved by
$$
\begin{aligned}
u(x, t) & =\sum_{n=1}^{\infty} c_n e^{-n^2 \pi^2 \alpha^2 t / L^2} \sin \frac{n \pi x}{L}, \\
\text { with } c_n & =\frac{2}{L} \int_0^L f(x) \sin \frac{n \pi x}{L} d x .
\end{aligned}
$$

### 24. Non-homogeneous boundary conditions

Consider a non-homogeneous set of boundary conditions:
$$
u(0, t)=T_1, \quad u(L, t)=T_2 \quad t>0
$$
i.e, the ends of the rod are fixed at some non-zero temperature.

Trick: we map this problem to one with homogeneous boundary conditions
i.e., with $u(0, t)=0, u(L, t)=0$.

- Define $v(x)$ as the time independent function
$$
v(x)=\lim _{t \rightarrow \infty} u(x, t)
$$
- Since $v(x)$ satisfies $\partial_t v=0$, the heat equation it satisfies reduces to
$$
v^{\prime \prime}=0, \quad v(0)=T_1, \quad v(L)=T_2
$$

Its general solution must be linear in $x$, i.e., $v(x)=a x+b$
$$
v(0)=T_1 \Longrightarrow b=T_1 \quad \text { and } \quad v(L)=T_2 \Longrightarrow a=\frac{T_2-T_1}{L}
$$

Thus
$$
v(x)=\left(T_2-T_1\right) \frac{x}{L}+T_1 .
$$

Finally, we look for a solution to our non-homogeneous boundary value problem of the form
$$
u(x, t)=v(x)+\omega(x, t) .
$$

The new function $\omega(x, t)$ satisfies the same heat equation
$$
\alpha^2 \partial_x^2 \omega=\partial_t \omega,
$$
but with boundary/initial conditions:
$$
\begin{aligned}
& \omega(0, t)=u(0, t)-v(0)=0, \\
& \omega(L, t)=u(L, t)-v(L)=0, \\
& \omega(x, 0)=u(x, 0)-v(x)=f(x)-v(x)
\end{aligned}
$$

Thus, $\omega(x)$ does satisfy an homogeneous set of boundary conditions but with a slightly different initial value function $f(x)-v(x)$.

We conclude the general solution to our non-homogeneous problem is:
$$
\begin{aligned}
u(x, t) & =\left(T_2-T_1\right) \frac{x}{L}+T_1+\sum_{n=1}^{\infty} c_n e^{-n^2 \pi^2 \alpha^2 t / L^2} \sin \frac{n \pi x}{L} \\
\text { with } c_n & =\frac{2}{L} \int_0^L\left[f(x)-\left(T_2-T_1\right) \frac{x}{L}-T_1\right] \sin \frac{n \pi x}{L} d x
\end{aligned}
$$

### 25. Diffierent boundary conditions

Consider again the heat equation:
$$
\partial_t u=\alpha^2 \partial_x^2 u
$$
but with boundary conditions
$$
\partial_x u(0, t)=\partial_x u(L, t)=0 \quad t>0
$$
- the temperature does not vary with the position at the end of both bars $\Leftrightarrow$ both ends are insulated

We shall proceed as before: $u(x, t)=X(x) T(t) \Rightarrow$
$$
\begin{aligned}
X^{\prime \prime}+\lambda X & =0, \quad X^{\prime}(0)=X^{\prime}(L)=0, \\
\dot{T}+\alpha^2 \lambda T & =0 .
\end{aligned}
$$

Same eigenvalue problem (because of same PDE), different boundary value problem (due to different boundary conditions).

- $\lambda=-\mu^2(\lambda<0)$ :
$$
X(x)=a \sinh \mu x+b \cosh \mu x \Rightarrow X^{\prime}(x)=a \mu \cosh \mu x+b \mu \sinh \mu x
$$

Boundary conditions require:
$$
\begin{aligned}
& X^{\prime}(0)=0 \Rightarrow a=0(\mu \neq 0) \\
& X^{\prime}(L)=0 \Rightarrow b=0(\sinh \mu L \neq 0 \text { for } \mu L \neq 0)
\end{aligned}
$$

Thus, only the trivial solution is possible.
- $\lambda=0 \Rightarrow X(x)=a x+b \Rightarrow X^{\prime}(x)=a$
Boundary conditions require $a=0$ but no restriction on $b$; i.e., constant solutions $X(x)=b$ solve this problem.

- $\lambda=\mu^2(\lambda>0):$
$$
X(x)=a \sin \mu x+b \cos \mu x \Rightarrow X^{\prime}(x)=a \mu \cos \mu x-b \mu \sin \mu x
$$

Boundary conditions require:
$$
\begin{aligned}
X^{\prime}(0)=0 & \Rightarrow a=0(\mu \neq 0) \\
X^{\prime}(L)=0 & \Rightarrow \sin \mu L=0 \Rightarrow \mu L=n \pi \\
& \Rightarrow \lambda_n=\frac{n^2 \pi^2}{L^2} \quad n=1,2, \ldots
\end{aligned}
$$

Once all possible compatible $\lambda^{\prime}$ 's are known, we can integrate the linear ODE for $T(t): \dot{T}+\alpha^2 \lambda T=0$
$$
\begin{array}{ll}
T(t)=\text { constant }, & \text { for } \lambda=0 \\
T_n(t) \propto e^{-\alpha^2 \lambda_n t}, & \text { for } \lambda_n>0, \quad(n=1,2,3, \ldots)
\end{array}
$$

For each $\lambda_n(n=1,2, \ldots)$, we find
$$
u_n(x, t)=c_n e^{-\alpha^2 \lambda_n t} \cos \frac{n \pi x}{L}
$$

General solution: since PDE is linear, the general solution is a linear combination of the ones founds above, including the constant solution:
$$
u(x, t)=\frac{c_0}{2}+\sum_{n=1}^{\infty} c_n e^{-n^2 \pi^2 \alpha^2 t / L^2} \cos \frac{n \pi x}{L},
$$
where the coefficients $\left\{c_n\right\}$ are again determined by the initial temperature function $f(x)$ using Fourier analysis
$$
c_n=\frac{2}{L} \int_0^L f(x) \cos \frac{n \pi x}{L} d x \quad n=0,1,2, \ldots
$$

## Part 7
### 1. Motivating example: vibrating guitar string

Consider the vibrations of a string (e.g., on a guitar).

- $u(x, t)=$ string vertical displacement, assumed small,
- $T=$ string tension (constant),
- $\rho=$ string mass per unit length (constant).

Newton's 2nd law for a short string section with small $\theta$ :
$$
\begin{aligned}
\rho \Delta x \partial_t^2 u(x, t) & =T[\sin (\theta(x+\Delta x, t))-\sin (\theta(x, t))] \\
& \approx T[\theta(x+\Delta x, t)-\theta(x, t)] \\
& =T \partial_x \theta(x, t) \Delta x+O\left(\Delta x^2\right) \\
& =T \partial_x^2 u(x, t) \Delta x+O\left(\Delta x^2\right)
\end{aligned}
$$
since $\sin \theta \approx \theta \approx \tan \theta=\partial_x u$.

![](https://files.mdnice.com/user/36229/929788db-e7ae-4931-8f2e-b82af520b146.jpg)

In limit $\Delta x \rightarrow 0$, we obtain wave equation in 1 spatial dimension:
$$
\partial_t^2 u=a^2 \partial_x^2 u
$$
with $a=\sqrt{T / \rho}$ called the wave speed.
For examples:
- electromagnetic waves with a the speed of light
- acoustic waves with a the speed of sound
- water waves in shallow water
- In 2d:
$$
\partial_t^2 u=a^2\left(\partial_x^2 u+\partial_y^2 u\right)
$$
for vibrating membranes (drums).

### 2. Wave equation: separation of variables

Solve
$$
\partial_t^2 u=a^2 \partial_x^2 u, \quad 0 \leq x \leq L, \quad t \geq 0
$$
subject to the following conditions
- $u(0, t)=u(L, t)=0$ : ends of the string are fixed $\forall t \geq 0$
- $\partial_t u(x, 0)=0$ : zero velocity at $t=0$,
- $u(x, 0)=f(x)$ : non-zero displacement at $t=0$
(i.e., $f(x)$ is shape of string profile at $t=0$ ).


Use separation of variables: $u(x, t)=X(x) T(t)$
Introduce into wave equation
$$
a^2 X^{\prime \prime} T=X \ddot{T}
$$

Divide by $u(x, t)$ and rearrange $a^2$
$$
\frac{X^{\prime \prime}}{X}=\frac{\ddot{T}}{a^2 T}=-\lambda
$$
where $\lambda$ is the separation of variables constant.
Thus we are left with ODE problems:
$$
\begin{aligned}
X^{\prime \prime}+\lambda X & =0, \\
\ddot{T}+a^2 \lambda T & =0 .
\end{aligned}
$$

- Since $u(0, t)=0=X(0) T(t), t \geq 0 \Rightarrow X(0)=0$
- Since $u(L, t)=0=X(L) T(t), t \geq 0 \Rightarrow X(L)=0$
- Since $\partial_t u(x, 0)=0=X(x) \dot{T}(0), 0 \leq x \leq L \Rightarrow \dot{T}(0)=0$

Thus, using separation of variables, our problem is mapped to
$$
\begin{array}{rlrl}
X^{\prime \prime}+\lambda X & =0, & X(0)=X(L)=0, \\
\ddot{T}+a^2 \lambda T & =0, & \dot{T}(0) & =0,
\end{array}
$$
with the initial condition
$$
u(x, 0)=f(x), \quad 0 \leq x \leq L
$$
which specifies the initial profile of the wave/string/perturbation.

We already solved the problem
$$
X^{\prime \prime}+\lambda X=0, \quad X(0)=X(L)=0 .
$$

It requires
- $\lambda_n=\frac{n^2 \pi^2}{L^2}$ with $n=1,2,3, \ldots$
- with eigenfunctions
$$
X_n(x) \propto \sin \frac{n \pi x}{L} .
$$

Introducing the allowed values $\lambda_n$ into the $2 \mathrm{nd}$ ODE
$$
\ddot{T}+\left(\frac{n \pi a}{L}\right)^2 T=0,
$$
whose general solution is
$$
T_n(t)=a_n \cos \frac{n \pi a}{L} t+b_n \sin \frac{n \pi a}{L} t .
$$

Using the initial condition $\dot{T}(0)=0$
$$
\begin{aligned}
& \dot{T}_n(t)=\frac{n \pi a}{L}\left(-a_n \sin \frac{n \pi a}{L} t+b_n \cos \frac{n \pi a}{L} t\right) \\
& \dot{T}_n(0)=0 \Rightarrow b_n=0 .
\end{aligned}
$$

Thus, for each $\lambda_n=\frac{n^2 \pi^2}{L^2}$, we find a product solution of the form
$$
u_n(x, t)=X_n(x) T_n(t) \propto \sin \frac{n \pi x}{L} \cos \frac{n \pi a}{L} t .
$$

By linearity, the general solution can be written as a linear combination of the solutions associated with all $\lambda_n=\frac{n^2 \pi^2}{L^2}$ :
$$
u(x, t)=\sum_{n=1}^{\infty} c_n u_n(x, t)
$$

Using the initial condition $u(x, 0)=f(x)$ on the general solution
$$
u(x, t)=\sum_{n=1}^{\infty} c_n \sin \frac{n \pi x}{L} \cos \frac{n \pi a}{L} t
$$
and the orthogonality of the periodic functions
$$
\begin{aligned}
u(x, 0)=f(x) & =\sum_{n=1}^{\infty} c_n \sin \frac{n \pi x}{L} \\
\Longrightarrow \quad c_n & =\frac{2}{L} \int_0^L f(x) \sin \frac{n \pi x}{L} d x
\end{aligned}
$$

Regard general solution as:
- superposition of vibrations at frequencies $f_n=n \pi a /(2 \pi L)$.
- fundamental frequency + harmonics.

Using trigonometry, we express the general solution as
$$
u(x, t)=\sum_{n=1}^{\infty} c_n \sin \frac{n \pi x}{L} \cos \frac{n \pi a}{L} t=\frac{1}{2}[h(x-a t)+h(x+a t)]
$$
where
$$
\begin{aligned}
h(x-a t) & =\sum_{n=1}^{\infty} c_n\left(\sin \frac{n \pi x}{L} \cos \frac{n \pi a}{L} t-\cos \frac{n \pi x}{L} \sin \frac{n \pi a}{L} t\right) \\
& =\sum_{n=1}^{\infty} c_n \sin \frac{n \pi}{L}(x-a t), \\
h(x+a t) & =\sum_{n=1}^{\infty} c_n\left(\sin \frac{n \pi x}{L} \cos \frac{n \pi a}{L} t+\cos \frac{n \pi x}{L} \sin \frac{n \pi a}{L} t\right) \\
& =\sum_{n=1}^{\infty} c_n \sin \frac{n \pi}{L}(x+a t) .
\end{aligned}
$$

Consider the solution
$$
u(x, t)=\frac{1}{2}[h(x-a t)+h(x+a t)]
$$

At $t=0$ it satisfies
$$
u(x, 0)=h(x)
$$

Thus, $h(x)$ controls the shape of the starting perturbation. E.g., suppose $h(x)$ is Gaussian-shaped perturbation for string centred at $x=0$. As time flows,
$$
u(x, t)=\frac{1}{2}[h(x-a t)+h(x+a t)]
$$
the solution looks like the superposition of two such perturbations:
- One centred at $x=a t$ : as $t$ increases, $x$ increases. This perturbation propagates in $x>0$ direction.
- One centred at $x=-$ at: as $t$ increases, $x$ decreases. This perturbation propagates in $x<0$ direction.


E.g., $u(x, t)=\frac{1}{2}\left[e^{-(x-t)^2}+e^{-(x+t)^2}\right]$.

![](https://files.mdnice.com/user/36229/988a41ea-9c15-4055-b289-adde258890dc.jpg)


### 3. Wave equation: general solution & interpretation

Consider the general $1 \mathrm{~d}$ wave equation
$$
\partial_t^2 u=a^2 \partial_x^2 u
$$

Let us change coordinates:
$$
\xi=x-a t, \quad \eta=x+a t
$$

Let us rewrite the PDE in the new coordinates:
$$
u(x, t)=u(x(\xi, \eta), t(\xi, \eta))=u(\xi, \eta)
$$

Question: What about the partial derivatives:
$$
\frac{\partial^2 u}{\partial x^2}, \frac{\partial^2 u}{\partial t^2} ?
$$

We need to use the chain rule
$$
\frac{\partial u(\xi, \eta)}{\partial x}=\partial_{\xi} u \frac{\partial \xi}{\partial x}+\partial_\eta u \frac{\partial \eta}{\partial x}=\partial_{\xi} u+\partial_\eta u
$$

Iterating the process
$$
\begin{aligned}
\frac{\partial^2 u}{\partial x^2} & =\frac{\partial}{\partial x}\left(\partial_{\xi} u+\partial_\eta u\right) \\
& =\partial_{\xi}^2 u \partial_x \xi+\partial_{\eta \xi}^2 u \partial_x \eta+\partial_{\xi \eta}^2 u \partial_x \xi+\partial_\eta^2 u \partial_x \eta \\
& =\partial_{\xi}^2 u+\partial_\eta^2 u+2 \partial_{\xi \eta}^2 u
\end{aligned}
$$

We need to use the chain rule
$$
\frac{\partial u(\xi, \eta)}{\partial t}=\frac{\partial \xi}{\partial t} \partial_{\xi} u+\frac{\partial \eta}{\partial t} \partial_\eta u=-a\left(\partial_{\xi} u-\partial_\eta u\right)
$$

Iterating the process
$$
\frac{\partial^2 u}{\partial t^2}=-a \frac{\partial}{\partial t}\left(\partial_{\xi} u-\partial_\eta u\right)=a^2 \partial_{\xi}^2 u+a^2 \partial_\eta^2 u-2 a^2 \partial_{\xi \eta}^2 u
$$

Altogether:
$$
\begin{aligned}
a^2 \partial_x^2 u & =\partial_t^2 u \\
\Leftrightarrow a^2\left(\partial_{\xi}^2 u+\partial_\eta^2 u+2 \partial_{\xi \eta}^2 u\right) & =a^2\left(\partial_{\xi}^2 u+\partial_\eta^2 u-2 \partial_{\xi \eta}^2 u\right) \\
\Longrightarrow \frac{\partial^2 u}{\partial \xi \partial \eta} & =0=\frac{\partial}{\partial \xi}\left(\frac{\partial u}{\partial \eta}\right)
\end{aligned}
$$

We can integrate $\frac{\partial}{\partial \xi}\left(\frac{\partial u}{\partial \eta}\right)=0$ to yield
$$
\frac{\partial u}{\partial \eta}=p^{\prime}(\eta) \Rightarrow \frac{\partial}{\partial \eta}(u-p(\eta))=0 \Rightarrow u=p(\eta)+q(\xi)
$$
where functions $p$ and $q$ are arbitrary Conclusion (called D'Alembert's solution):
$$
a^2 \partial_x^2 u=\partial_t^2 u \Rightarrow u(x, t)=p(x+a t)+q(x-a t)
$$
- If $q(x)$ represents a perturbation centred at $x=0 \Rightarrow$ $q(x-a t)$ describes a perturbation travelling at speed $a$ to the right (i.e., $x>0$ direction)
- If $p(x)$ represents a perturbation centred at $x=0 \Rightarrow$ $p(x+a t)$ describes a perturbation travelling at speed $a$ to the left (i.e., $x<0$ direction)

### 4. Wave equation: more general initial conditions

Consider
$$
\partial_t^2 u=a^2 \partial_x^2 u
$$
subject to the boundary/initial conditions
$$
\begin{aligned}
& u(0, t)=u(L, t)=0 \\
& u(x, 0)=f(x), \partial_t u(x, 0)=g(x)
\end{aligned}
$$

If we look for solutions of the form $u(x, t)=X(x) T(t)$
- $X(x)$ will satisfy the same eigenvalue boundary problem
- Since $\dot{T}(0) \neq 0$ now, the most general solution will be of the form
$$
u(x, t)=\sum_{n=1}^{\infty} \sin \frac{n \pi x}{L}\left(c_n \sin \frac{n \pi a}{L} t+d_n \cos \frac{n \pi a}{L} t\right)
$$

Fix the two families of constants, using the initial conditions
$$
\begin{aligned}
& \text { - } u(x, 0)=f(x): \\
& \qquad \sum_{n=1}^{\infty} d_n \sin \frac{n \pi x}{L}=f(x) \Rightarrow d_n=\frac{2}{L} \int_0^L f(x) \sin \frac{n \pi x}{L} d x \\
& \text { - } \partial_t u(x, 0)=g(x): \\
& \sum_{n=1}^{\infty} \frac{n \pi a}{L} c_n \sin \frac{n \pi x}{L}=g(x) \Rightarrow \frac{n \pi a}{L} c_n=\frac{2}{L} \int_0^L g(x) \sin \frac{n \pi x}{L} d x
\end{aligned}
$$

Remark: there are many more boundary initial conditions we could consider, but procedure to find solutions would follow same steps:
- Assume separation of variables: $u(x, t)=X(x) T(t)$.
- Introduce a separation of variables constant $\lambda$
- Identify the eigenvalue boundary problem satisfied by $X(x)$ and $\lambda$, which depends upon the boundary conditions
- Solve for $X(x)$ : this step may require some quantisation of $\lambda$ or some constraint on $\lambda$
- Solve the eigenvalue initial problem satisfied by $T(t)$
- Write the most general solution as a linear combination of all solutions to the eigenvalue boundary/initial problems
- Identify any undetermined coefficients using initial conditions


### 5. Laplace equation

The Laplace equation
$$
\nabla^2 u \equiv \partial_x^2 u+\partial_y^2 u=0 \text { in } 2 \mathrm{D}, \quad \nabla^2 u \equiv \partial_x^2 u+\partial_y^2 u+\partial_z^2 u \text { in } 3 \mathrm{D},
$$
arises in numerous areas:
- steady state (i.e., time-independent) solutions of the 2D or 3D heat equation,
- equilibria of membranes, minimal surfaces (soap films),
- fluid dynamics (airfoils, (deep-)water waves,...),
- electromagnetism, gravity...

Given the Laplace equation in 2 dimensions
$$
\partial_x^2 u+\partial_y^2 u=0
$$
there are different types of boundary conditions (b.c.) to consider, e.g.,
- Dirichlet b.c.: function $u(x, y)$ specified at the boundary
- Neumann b.c.: normal derivative of $u(x, y)$ specified at the boundary
- Robin b.c.: mixture of Dirichlet \& Neumann b.c.

We discuss two problems with Dirichlet b.c. of different geometries.


### 6. Dirichlet problem for a rectangle

We solve
$$
\partial_x^2 u+\partial_y^2 u=0, \quad 0 \leq x \leq a, \quad 0 \leq y \leq b
$$
subject to the boundary conditions (Dirichlet):
$$
\begin{aligned}
& u(x, 0)=u(x, b)=0, \\
& u(0, y)=0, \quad u(a, y)=f(y) .
\end{aligned}
$$

Assume separation of variables: $u(x, y)=X(x) Y(y)$ Plugging into Laplace's equation \& dividing by $u(x, y)$
$$
\frac{X^{\prime \prime}}{X}(x)=-\frac{\ddot{Y}}{Y}(y)=\lambda .
$$

Thus, we are left with two eigenvalue boundary problems:
$$
\begin{aligned}
X^{\prime \prime}-\lambda X=0, & X(0)=0 \\
\ddot{Y}+\lambda Y=0, & Y(0)=Y(b)=0 .
\end{aligned}
$$


We already solved the problem:
$$
\ddot{Y}+\lambda Y=0, \quad Y(0)=Y(b)=0
$$

Its general solution is given by
$$
Y_n(y) \propto \sin \frac{n \pi y}{b}, \quad \lambda_n=\frac{n^2 \pi^2}{b^2}, \quad n=1,2, \ldots
$$

The remaining ODE becomes
$$
X_n^{\prime \prime}-\frac{n^2 \pi^2}{b^2} X_n=0 \Rightarrow X_n(x)=d_n \cosh \frac{n \pi x}{b}+c_n \sinh \frac{n \pi x}{b}
$$

Since $X(0)=0 \Rightarrow d_n=0 \Rightarrow X_n \propto \sinh \frac{n \pi x}{b}$

We already solved the problem:
$$
\ddot{Y}+\lambda Y=0, \quad Y(0)=Y(b)=0
$$

Its general solution is given by
$$
Y_n(y) \propto \sin \frac{n \pi y}{b}, \quad \lambda_n=\frac{n^2 \pi^2}{b^2}, \quad n=1,2, \ldots
$$

The remaining ODE becomes
$$
X_n^{\prime \prime}-\frac{n^2 \pi^2}{b^2} X_n=0 \Rightarrow X_n(x)=d_n \cosh \frac{n \pi x}{b}+c_n \sinh \frac{n \pi x}{b}
$$

Since $X(0)=0 \Rightarrow d_n=0 \Rightarrow X_n \propto \sinh \frac{n \pi x}{b}$

Thus, for any $\lambda_n$, the solution is given by
$$
u_n(x, y) \propto \sinh \frac{n \pi x}{b} \sin \frac{n \pi y}{b}
$$

Due to the linearity of the Laplace equation, the general solution is
$$
u(x, y)=\sum_{n=1}^{\infty} c_n \sinh \frac{n \pi x}{b} \sin \frac{n \pi y}{b}
$$

To determine $\left\{c_n\right\}$ we use the final condition
$$
u(a, y)=f(y)=\sum_{n=1}^{\infty} c_n \sinh \frac{n \pi a}{b} \sin \frac{n \pi y}{b}
$$
and the orthogonality of the sine functions
$$
c_n \sinh \frac{n \pi a}{b}=\frac{2}{b} \int_0^b f(y) \sin \frac{n \pi y}{b} d y \Longrightarrow c_n=\frac{\frac{2}{b} \int_0^b f(y) \sin \frac{n \pi y}{b} d y}{\sinh \frac{n \pi a}{b}}
$$

### 7. Dirichlet problem for a circle

Let us consider a similar problem, but with a different geometry. Solve the Laplace equation
$$
\partial_x^2 u+\partial_y^2 u=0
$$
subject to Dirichlet b.c. in polar coords: $u(x, y) \rightarrow u(r, \theta)$
- $u(a, \theta)=f(\theta)$ with $r=a$ and $0 \leq \theta \leq 2 \pi$
- $u(r, \theta)$ bounded for $r \leq a$.
- Boundary conditions refer to a disk $(r \leq a)$ and its boundary circle $(r=a)$
- We change coordinates to polar coordinates
$$
\begin{aligned}
x=r \cos \theta, & y=r \sin \theta \\
r^2=x^2+y^2, & \tan \theta=\frac{y}{x}
\end{aligned}
$$
- When we do this:
$$
u(x, y) \rightarrow u(x(r, \theta), y(r, \theta))=u(r, \theta)
$$

![](https://files.mdnice.com/user/36229/bcf131d0-1730-4f26-b974-1b108e26e6b4.jpg)


Using the chain rule,
$$
\frac{\partial u}{\partial r}=\frac{\partial u}{\partial x} \frac{\partial x}{\partial r}+\frac{\partial u}{\partial y} \frac{\partial y}{\partial r}=\cos \theta \frac{\partial u}{\partial x}+\sin \theta \frac{\partial u}{\partial y} .
$$

Since we are interested in second partial derivatives, need to go one step further
$$
\begin{aligned}
\frac{\partial^2 u}{\partial r^2} & =\cos \theta \frac{\partial}{\partial r} \frac{\partial u}{\partial x}+\sin \theta \frac{\partial}{\partial r} \frac{\partial u}{\partial y} \\
& =\cos \theta\left(\frac{\partial}{\partial x}\left(\frac{\partial u}{\partial x}\right) \frac{\partial x}{\partial r}+\frac{\partial}{\partial y}\left(\frac{\partial u}{\partial x}\right) \frac{\partial y}{\partial r}\right) \\
& +\sin \theta\left(\frac{\partial}{\partial x}\left(\frac{\partial u}{\partial y}\right) \frac{\partial x}{\partial r}+\frac{\partial}{\partial y}\left(\frac{\partial u}{\partial y}\right) \frac{\partial y}{\partial r}\right) \\
& =\cos ^2 \theta \frac{\partial^2 u}{\partial x^2}+2 \cos \theta \sin \theta \frac{\partial^2 u}{\partial x \partial y}+\sin ^2 \theta \frac{\partial^2 u}{\partial y^2}
\end{aligned}
$$

Similarly, $\frac{\partial u}{\partial \theta}=\frac{\partial u}{\partial x} \frac{\partial x}{\partial \theta}+\frac{\partial u}{\partial y} \frac{\partial y}{\partial \theta}=-r \sin \theta \frac{\partial u}{\partial x}+r \cos \theta \frac{\partial u}{\partial y}$. which leads to
$$
\begin{aligned}
\frac{\partial^2 u}{\partial \theta^2} & =-r\left(\cos \theta \frac{\partial u}{\partial x}+\sin \theta \frac{\partial u}{\partial y}\right) \\
& +r^2\left(\sin ^2 \theta \frac{\partial^2 u}{\partial x^2}-2 \cos \theta \sin \theta \frac{\partial^2 u}{\partial x \partial y}+\cos ^2 \theta \frac{\partial^2 u}{\partial y^2}\right)
\end{aligned}
$$
from which we can derive by multiplying by $1 / r^2$
$$
\frac{1}{r^2} \frac{\partial^2 u}{\partial \theta^2}=-\frac{1}{r} \frac{\partial u}{\partial r}+\sin ^2 \theta \frac{\partial^2 u}{\partial x^2}-2 \cos \theta \sin \theta \frac{\partial^2 u}{\partial x \partial y}+\cos ^2 \theta \frac{\partial^2 u}{\partial y^2} .
$$

Putting these pieces together, we conclude
$$
\frac{\partial^2 u}{\partial x^2}+\frac{\partial^2 u}{\partial y^2}=0 \Leftrightarrow \frac{\partial^2 u}{\partial r^2}+\frac{1}{r^2} \frac{\partial^2 u}{\partial \theta^2}+\frac{1}{r} \frac{\partial u}{\partial r}=0 .
$$

Next, we assume separation of variables
$$
u(r, \theta)=R(r) \Theta(\theta) \Rightarrow R^{\prime \prime} \Theta+\frac{1}{r} R^{\prime} \Theta+\frac{1}{r^2} R \ddot{\Theta}=0 .
$$

Multiplying by $r^2$ and dividing by $u(r, \theta)=R(r) \Theta(\theta)$
$$
r^2 \frac{R^{\prime \prime}}{R}+r \frac{R^{\prime}}{R}=-\frac{\ddot{\Theta}}{\Theta}=\lambda
$$
where $\lambda$ is the separation constant.
Our problem becomes
$$
\begin{aligned}
r^2 R^{\prime \prime}+r R^{\prime} & =\lambda R, \\
\ddot{\Theta} & =-\lambda \Theta .
\end{aligned}
$$
subject to periodicity (i.e., $\Theta(\theta)=\Theta(\theta+2 \pi)$ required) and boundedness conditions.

Consider $\ddot{\Theta}+\lambda \Theta=0$
- If $\lambda=-\mu^2(\lambda<0)$, then
$$
\Theta(\theta)=c_1 e^{\mu \theta}+c_2 e^{-\mu \theta} .
$$

Since these solutions are not periodic under $\theta \rightarrow \theta+2 \pi$ (i.e., $\Theta(\theta) \neq \Theta(\theta+2 \pi)) \Rightarrow c_1=c_2=0$
- If $\lambda=0$, then
$$
\Theta(\theta)=c_1 \theta+c_2 .
$$

Again $\Theta(\theta+2 \pi) \neq \Theta(\theta)$ unless $c_1=0$. Thus, only solution allowed is $\Theta(\theta)=c_2$.


- If $\lambda=\mu^2(\lambda>0)$, then
$$
\Theta(\theta)=a_1 \sin \mu \theta+a_2 \cos \mu \theta
$$

Periodicity $\Theta(\theta+2 \pi)=\Theta(\theta)$, i.e.,
$$
a_1 \sin \mu(\theta+2 \pi)+a_2 \cos \mu(\theta+2 \pi)=a_1 \sin \mu \theta+a_2 \cos \mu \theta
$$
only achieved if $\mu=n$ with $\mathrm{n}=1,2,3, \ldots$
Thus, the first eigenvalue problem $\ddot{\Theta}+\lambda \Theta=0$ is solved by
1. $\lambda=0 \Longrightarrow \Theta_0(\theta)=$ constant
2. $\lambda=n^2 \Longrightarrow \Theta_n(\theta)=e_n \cos n \theta+f_n \sin n \theta, \quad n=1,2,3, \ldots$

We are left to solve $r^2 R^{\prime \prime}+r R^{\prime}=\lambda R$ for $\lambda=0$ and $n^2$.
1. If $\lambda=0 \Rightarrow r^2 R^{\prime \prime}+r R^{\prime}=0$
Define $R^{\prime}(r)=Z(r)$, then
$$
\begin{gathered}
r^2 Z^{\prime}+r Z=0 \\
\frac{Z^{\prime}}{Z}=-\frac{1}{r} \Rightarrow \log Z=-\log r+c \Rightarrow Z(r)=\frac{k}{r}
\end{gathered}
$$

So $R^{\prime}=\frac{k}{r} \Rightarrow R(r)=k \log r+\tilde{k}$
Now $\log r \rightarrow-\infty$ as $r \rightarrow 0 \Rightarrow k=0$ (using boundedness). Thus only allowed solution is
$$
R(r)=\tilde{k}
$$
i.e., constant $R(r)$.

2. If $\lambda=n^2 \Rightarrow r^2 R^{\prime \prime}+r R^{\prime}-n^2 R=0$.

A 2nd order ODE with non-constant coefficients - seek solution as:
$$
R(r)=r^\alpha .
$$

Substituting $R^{\prime}=\alpha r^{\alpha-1}, \quad R^{\prime \prime}=\alpha(\alpha-1) r^{\alpha-2}$ into ODE yields
$$
r^\alpha\left[\alpha(\alpha-1)+\alpha-n^2\right]=r^\alpha\left(\alpha^2-n^2\right)=0 \Rightarrow \alpha= \pm n
$$

Thus, for any $\lambda_n=n^2$, general solution to the $2 \mathrm{nd}$ order ODE is
$$
R_n(r)=w_n r^n+q_n r^{-n} \text {. }
$$

Solutions bounded $\Rightarrow q_n=0$ (to avoid divergence lat $r=0$ ).

The solution to
$$
\frac{\partial^2 u}{\partial r^2}+\frac{1}{r^2} \frac{\partial^2 u}{\partial \theta^2}+\frac{1}{r} \frac{\partial u}{\partial r}=0
$$
under the hypothesis $u(r, \theta)=R(r) \Theta(\theta)$ requires:
$$
r^2 R^{\prime \prime}+r R^{\prime}=\lambda R, \quad \ddot{\Theta}=-\lambda \Theta
$$

Periodicity and boundedness deliver:
- $\lambda=0$ allows a constant solution
$$
u_0(r, \theta)=\frac{c_0}{2} .
$$
- $\lambda=n^2$ allows solutions of the form
$$
u_n(r, \theta)=r^n\left(e_n \cos n \theta+f_n \sin n \theta\right) .
$$

Linearity allows us to write the general solution as
$$
u(r, \theta)=\frac{c_0}{2}+\sum_{n=1}^{\infty} r^n\left(e_n \cos n \theta+f_n \sin n \theta\right) .
$$

There is one boundary condition that remains to be satisfied:
$$
u(a, \theta)=f(\theta)=\frac{c_0}{2}+\sum_{n=1}^{\infty} a^n\left(e_n \cos n \theta+f_n \sin n \theta\right) .
$$
- Fourier series: $f(\theta+2 \pi)=f(\theta)$ with period $T=2 L=2 \pi$
- Use Euler-Fourier formulas to determine all coefficients
$$
\begin{aligned}
a^n e_n & =\frac{1}{\pi} \int_{-\pi}^\pi f(\theta) \cos n \theta d \theta \Rightarrow e_n=\frac{1}{a^n \pi} \int_{-\pi}^\pi f(\theta) \cos n \theta d \theta \\
a^n f_n & =\frac{1}{\pi} \int_{-\pi}^\pi f(\theta) \sin n \theta d \theta \Rightarrow f_n=\frac{1}{a^n \pi} \int_{-\pi}^\pi f(\theta) \sin n \theta d \theta \\
c_0 & =\frac{1}{\pi} \int_{-\pi}^\pi f(\theta) d \theta
\end{aligned}
$$

### 8. Eigenvalue boundary problem revisited

Introduce two complex-valued functions $u$ and $v$. Define their inner product for $0 \leq x \leq L$ as
$$
(u, v) \equiv \int_0^L u(x) v^{\star}(x) d x
$$

Compute $(\mathcal{L}[u], v)$ :
$$
\begin{aligned}
-(\mathcal{L}[u], v) & =\int_0^L u^{\prime \prime} v^{\star} d x \\
& =\left.u^{\prime} v^{\star}\right|_0 ^L-\int_0^L u^{\prime} v^{\star \prime} d x \\
& =\left.\left(u^{\prime} v^{\star}-v^{\star \prime} u\right)\right|_0 ^L+\int_0^L u v^{\star \prime \prime} d x \\
& =\left.\left(u^{\prime} v^{\star}-v^{\star \prime} u\right)\right|_0 ^L-(u, \mathcal{L}[v])
\end{aligned}
$$

$$
-(\mathcal{L}[u], v)+(u, \mathcal{L}[v])=\left.\left(u^{\prime} v^{\star}-v^{\star \prime} u\right)\right|_0 ^L
$$
- This identity relates $\mathcal{L}$ to the the boundary conditions.
- Suppose both $u, v$ satisfy homogeneous boundary conditions:
$$
\begin{gathered}
u(0)=u(L)=v(0)=v(L)=0 \\
\text { then } \quad(\mathcal{L}[u], v)-(u, \mathcal{L}[v])=0 .
\end{gathered}
$$
- Consider $u=v=\Phi \equiv M(x)+i N(x)$ where $M, N$ are both real-valued. Assume $\Phi$ solves the eigenvalue boundary problem, i.e., $\mathcal{L}[\Phi]=\lambda \Phi$ for a generally complex-valued $\lambda$
$$
\begin{aligned}
(\mathcal{L}[u], v)=(u, \mathcal{L}[v]) \Longrightarrow(\mathcal{L}[\Phi], \Phi) & =(\Phi, \mathcal{L}[\Phi]) \\
\lambda(\Phi, \Phi) & =\lambda^{\star}(\Phi, \Phi) \\
\left(\lambda-\lambda^{\star}\right)(\Phi, \Phi) & =0
\end{aligned}
$$

$$
\begin{aligned}
\left(\lambda-\lambda^{\star}\right)(\Phi, \Phi) & =0 \\
\left(\lambda-\lambda^{\star}\right) \int_0^L \Phi \Phi^{\star} d x & =0 \\
\left(\lambda-\lambda^{\star}\right) \int_0^L\left(M^2+N^2\right) d x & =0
\end{aligned}
$$

We must conclude $\lambda=\lambda^{\star} \Rightarrow$ eigenvalues must be real valued
- If $u=\Phi_1$ and $v=\Phi_2$ satisfy $\mathcal{L}\left[\Phi_i\right]=\lambda_i \Phi_i$ with $i=1,2 \&$ $\lambda_1 \neq \lambda_2$
$$
\begin{aligned}
\left(\mathcal{L}\left[\Phi_1\right], \Phi_2\right) & =\left(\Phi_1, \mathcal{L}\left[\Phi_2\right]\right) \\
\lambda_1\left(\Phi_1, \Phi_2\right) & =\lambda_2\left(\Phi_1, \Phi_2\right) \quad\left(\text { since } \lambda_2 \in \mathbb{R}\right) \\
\left(\lambda_1-\lambda_2\right)\left(\Phi_1, \Phi_2\right) & =0 \Rightarrow\left(\Phi_1, \Phi_2\right)=0
\end{aligned}
$$

Eigenfunctions of different eigenvalues are orthogonal.

Without explicitly solving the eigenvalue boundary problem
$$
\mathcal{L}[X] \equiv-X^{\prime \prime}(x)=\lambda X(x), \quad X(0)=X(L)=0 \quad \text { with } \quad 0 \leq x \leq L
$$
but using
- the form of $\mathcal{L}$,
- type of boundary conditions
we showed that
- $\lambda \in \mathbb{R}$,
- $\left(\Phi_n, \Phi_m\right)=0$ if $n \neq m$.

What is the general form of $\mathcal{L}+$ b.c. for which this holds?

Finite dimensional equivalent: matrices whose eigenvalues are real and eigenvectors orthogonal, i.e., real symmetric matrices.

### 9. Sturm-Liouville boundary problems

Consider a generalisation of the heat (conduction) equation ( $ 0<x<1 $)


$$
r(x)\partial _tu(x,t)=\partial _x[p(x)\partial _xu(x,t)]-q(x)u(x,t)
$$


with

- $\left\{p(x), p^{\prime}(x), q(x), r(x)\right\}:$ real-valued, continuous on $x \in[0,1]$
- $p(x), r(x)>0 \forall x \in[0,1]$

Separation of variables: $u(x, t)=X(x) T(t)$ yields
$$
r(x) X(x) \dot{T}(t)=\left[p(x) X^{\prime}(x)\right]^{\prime} T(t)-q(x) X(x) T(t)
$$

Dividing by $r(x) X(x) T(t)$ :
$$
\frac{\dot{T}(t)}{T(t)}=\frac{\left[p(x) X^{\prime}(x)\right]^{\prime}}{r(x) X(x)}-\frac{q(x)}{r(x)}=-\lambda
$$

Thus, we are left with 2 ODEs
$$
\begin{aligned}
\dot{T}(t)+\lambda T(t) & =0, \\
{\left[p(x) X^{\prime}(x)\right]^{\prime}-q(x) X(x)+\lambda r(x) X(x) } & =0 .
\end{aligned}
$$

Define $X(x) \equiv y(x)$ and rewrite 2 nd ODE in terms of operator $\mathcal{L}$ :
$$
\begin{aligned}
-\left[p(x) y^{\prime}(x)\right]^{\prime}+q(x) y(x) & =\lambda r(x) y(x) \\
\Leftrightarrow \mathcal{L}[y] & =\lambda r(x) y(x) .
\end{aligned}
$$

Question: When do we have
$$
(\mathcal{L}[u], v)=(u, \mathcal{L}[v])
$$
for arbitrary (generally, complex-valued) $u$ and $v$ ?

By definition
$$
\begin{aligned}
& (\mathcal{L}[u], v)=\int_0^1 \mathcal{L}[u] v^{\star} d x=\int_0^1\left[-\left(p u^{\prime}\right)^{\prime}+q u\right] v^{\star} d x \\
& (u, \mathcal{L}[v])=\int_0^1 u \mathcal{L}[v]^{\star} d x=\int_0^1 u\left[-\left(p v^{\star \prime}\right)^{\prime}+q v^{\star}\right] d x
\end{aligned}
$$

So
$$
\begin{aligned}
(\mathcal{L}[u], v)-(u, \mathcal{L}[v])= & \int_0^1\left[-\left(p u^{\prime}\right)^{\prime} v^{\star}+u\left(p v^{\star \prime}\right)^{\prime}\right] d x \\
= & {\left[-p u^{\prime} v^{\star}\right]_0^1+\int_0^1 p u^{\prime} v^{\star \prime} d x } \\
& +\left[u p v^{\star \prime}\right]_0^1-\int_0^1 u^{\prime} p v^{\star \prime} d x \\
= & -\left[p\left(u^{\prime} v^{\star}-u v^{\star \prime}\right)\right]_0^1
\end{aligned}
$$

Thus we reach the result - called Lagrange's identity:
$$
(\mathcal{L}[u], v)-(u, \mathcal{L}[v])=-\left[p\left(u^{\prime} v^{\star}-u v^{\star \prime}\right)\right]_0^1 .
$$
- If the boundary conditions are such that
$$
-\left[p\left(u^{\prime} v^{\star}-u v^{\star \prime}\right)\right]_0^1=0
$$
then we have
$$
(\mathcal{L}[u], v)=(u, \mathcal{L}[v])
$$
and the conclusions obtained for $\mathcal{L}=-d^2 / d x^2$ (i.e., real-valued eigenvalues and orthogonal eigenvectors) apply.

Question: When does
$$
\left[p\left(u^{\prime} v^{\star}-u v^{\star \prime}\right)\right]_0^1 \quad \text { vanish ? }
$$
- Consider boundary conditions of the type (on the space of real functions)
$$
a_1 y(0)+a_2 y^{\prime}(0)=0, \quad b_1 y(1)+b_2 y^{\prime}(1)=0
$$

Evaluating our expression:
$$
\begin{aligned}
& p(1)\left(u^{\prime}(1) v(1)-u(1) v^{\prime}(1)\right)-p(0)\left(u^{\prime}(0) v(0)-u(0) v^{\prime}(0)\right) \\
& =p(1)\left(-\frac{b_1}{b_2} u(1) v(1)+\frac{b_1}{b_2} u(1) v(1)\right) \\
& -p(0)\left(-\frac{a_1}{a_2} u(0) v(0)+\frac{a_1}{a_2} u(0) v(0)\right)=0
\end{aligned}
$$
- We assumed $b_2, a_2 \neq 0$. But the same conclusion holds when either of them vanishes.

For specific operators $\mathcal{L}$, it is possible to find other boundary conditions for which
$$
(\mathcal{L}[u], v)=(u, \mathcal{L}[v])
$$
- E.g., consider periodic boundary conditions (on the space of real functions) when $p(x)=1$
$$
y(0)=y(1), \quad y^{\prime}(0)=y^{\prime}(1)
$$

Our condition reduces to
$$
\left(u^{\prime}(1) v(1)-u(1) v^{\prime}(1)\right)-\left(u^{\prime}(0) v(0)-u(0) v^{\prime}(0)\right)=0 .
$$

### 10. Definition

The eigenvalue $O D E$ equation
$$
\mathcal{L}[y]=\lambda r(x) y(x) \quad \text { with } \quad \mathcal{L}[y] \equiv-\left(p(x) y^{\prime}\right)^{\prime}+q(x) y(x)
$$
subject to the boundary conditions
$$
a_1 y(0)+a_2 y^{\prime}(0)=0, \quad b_1 y(1)+b_2 y^{\prime}(1)=0
$$
defines a (regular) Sturm-Liouville boundary problem, where the functions $p(x), p^{\prime}(x), q(x), r(x)$ are continuous and $p(x), r(x)>0$ in the entire domain where the problem is defined.

By construction, given any Sturm-Liouville boundary problem, Lagrange's identity yields:
$$
(\mathcal{L}[u], v)=(u, \mathcal{L}[v])
$$
for any pair $u, v$ satisfying the Sturm-Liouville boundary conditions.

### 11. Sturm-Liouville & general 2nd-order ODEs

S-L boundary problems are defined in terms of the ODE
$$
-\left[p(x) y^{\prime}(x)\right]^{\prime}+q(x) y(x)=\lambda r(x) y(x) .
$$

At first sight, it may look like we are constraining ourselves to a particular class of 2 nd-order linear ODEs, but this is not so. Consider the general 2 nd-order linear eigenfunction equation
$$
-p(x) y^{\prime \prime}-\omega(x) y^{\prime}+q(x) y(x)=\lambda r(x) y(x)
$$

Introduce the integrating factor $F(x)$ defined as
$$
\begin{aligned}
& F(x)=\exp \int_0^x \frac{\omega(s)-p^{\prime}(s)}{p(s)} d s \\
& \Longrightarrow F^{\prime}(x)=F(x) \frac{\omega(x)-p^{\prime}(x)}{p(x)} \\
& \Longrightarrow F(x) \omega(x)=[F(x) p(x)]^{\prime}
\end{aligned}
$$

Multiplying the general eigenvalue problem by $F(x)$ delivers
$$
\begin{aligned}
& -F(x) p(x) y^{\prime \prime}-F(x) \omega(x) y^{\prime}+F(x) q(x) y=\lambda F(x) r(x) y(x) \\
& \Longrightarrow-\left[F(x) p(x) y^{\prime}\right]^{\prime}+F(x) q(x) y=\lambda F(x) r(x) y
\end{aligned}
$$
which conforms to the Sturm-Liouville form:
- with a new weight function $F(x) r(x)$
- and $F(x) p(x)>0, F(x) r(x)>0$ since $F(x)$ is an exponential

Thus, a general 2nd-order linear ODE can be written in Sturm-Liouville form, but whether we have a Sturm-Liouville boundary problem or not is determined by the boundary conditions.


### 12. Theorem

Given a Sturm-Liouville boundary problem and using the inner product
$$
(u, v) \equiv \int_0^1 u(x) v^{\star}(x) d x
$$
we can extend results obtained previously for $\mathcal{L}=-d^2 / d x^2$ to the general boundary problem discussed here.

All eigenvalues of the Sturm{Liouville boundary problem are real.

Proof:

Let $\Psi \equiv M(x)+i N(x)$ (real-valued $M, N$ ) be an eigenfunction of the $S-L$ boundary problem with $\lambda \in \mathbb{C}$. Using Lagrange's identity:
$$
\begin{aligned}
(\mathcal{L}[\Psi], \Psi) & =(\Psi, \mathcal{L}[\Psi]) \\
(\lambda r \Psi, \Psi) & =(\Psi, \lambda r \Psi)
\end{aligned}
$$

$$
\begin{aligned}
(\lambda r \Psi, \Psi) & =(\Psi, \lambda r \Psi) \\
\int_0^1 \lambda r(x) \Psi(x) \Psi^{\star}(x) d x & =\int_0^1 \lambda^{\star} r(x) \Psi(x) \Psi^{\star}(x) d x \\
\left(\lambda-\lambda^{\star}\right) \int_0^1 r(x) \Psi(x) \Psi^{\star}(x) d x & =0 \\
\left(\lambda-\lambda^{\star}\right) \int_0^1 r(x)\left[M^2(x)+N^2(x)\right] d x & =0 \Rightarrow \lambda=\lambda^{\star} \Rightarrow \lambda \in \mathbb{R}
\end{aligned}
$$
where in the last step we used $r(x)>0$.

### 13. Theorem

Given $\Psi_1$ and $\Psi_2$ two eigenfunctions of a Sturm-Liouville boundary problem with respective eigenvalues $\lambda_1 \neq \lambda_2$, then
$$
\int_0^1 r(x) \Psi_1(x) \Psi_2(x) d x=0
$$

That is, $\Psi_1$ and $\Psi_2$ are orthogonal with respect to the inner product defined above by the Sturm-Liouville boundary problem.

Proof:

Choose $u=\Psi_1$ and $v=\Psi_2$ solving the Sturm-Liouville boundary problem into Lagrange's identity
$$
\begin{aligned}
\left(\mathcal{L}\left[\Psi_1\right], \Psi_2\right) & =\left(\Psi_1, \mathcal{L}\left[\Psi_2\right]\right) \\
\left(\lambda_1 r \Psi_1, \Psi_2\right) & =\left(\Psi_1, \lambda_2 r \Psi_2\right)
\end{aligned}
$$

$$
\begin{aligned}
\left(\lambda_1 r \Psi_1, \Psi_2\right) & =\left(\Psi_1, \lambda_2 r \Psi_2\right) \\
\left(\lambda_1-\lambda_2\right) \int_0^1 r(x) \Psi_1(x) \Psi_2(x) d x & =0
\end{aligned}
$$

Since $\lambda_1 \neq \lambda_2$, we conclude
$$
\int_0^1 r(x) \Psi_1(x) \Psi_2(x) d x=0 .
$$

Notice we used that $\Psi_1$ and $\Psi_2$ are real.
This suggests that we define the modified inner product
$$
\left\langle\Psi_1, \Psi_2\right\rangle \equiv \int_0^1 r(x) \Psi_1(x) \Psi_2(x) d x,
$$
where the notation $\langle\rangle$ introduced to distinguish from ().


### 14. Sturm-Liouville & orthonormal eigenfunctions

We established the existence of orthogonality amongst different eigenfunctions, i.e.,
$$
\left\langle y_{n_1}, y_{n_2}\right\rangle=0 \quad \text { if } \quad \lambda_{n_1} \neq \lambda_{n_2}
$$

Usually, it is convenient to work with a set of orthonormal functions $\left\{\Phi_n\right\}$ satisfying
$$
\left\langle\Phi_n, \Phi_m\right\rangle=\int_0^1 r(x) \Phi_n(x) \Phi_m(x) d x=\delta_{n m}
$$

Let $\Phi_n(x)$ be related to $y_n(x)$ by a constant: $\Phi_n(x)=k_n y_n(x)$. Then
$$
\begin{aligned}
& \left\langle\Phi_n, \Phi_n\right\rangle=1=\left\langle k_n y_n, k_n y_n\right\rangle=k_n^2\left\langle y_n, y_n\right\rangle \\
& \Longrightarrow k_n=\left\langle y_n, y_n\right\rangle^{-1 / 2}=\left[\int_0^1 r(x) y_n^2(x) d x\right]^{-1 / 2} .
\end{aligned}
$$

Question: Can we expand any function in this set of orthonormal functions $\left\{\Phi_n\right\}$ ?

Formally, we can write:
$$
f(x)=\sum_{n=1}^{\infty} c_n \Phi_n(x) .
$$

Using the inner product, we can compute the coefficients $c_n$ :
$$
\begin{aligned}
\left\langle f(x), \Phi_m\right\rangle & =\left\langle\sum_{n=1}^{\infty} c_n \Phi_n(x), \Phi_m(x)\right\rangle=\sum_{n=1}^{\infty} c_n\left\langle\Phi_n, \Phi_m\right\rangle \\
& =\sum_{n=1}^{\infty} c_n \delta_{n m}=c_m \\
\Rightarrow \quad c_m & =\int_0^1 r(x) f(x) \Phi_m(x) d x
\end{aligned}
$$

What about the convergence of this infinite sum?

### 15. Theorem

Let $\Phi_1(x), \ldots \Phi_n(x), \ldots$ be the orthonormal eigenfunctions of a Sturm-Liouville boundary problem
$$
\begin{aligned}
& -\left[p(x) y^{\prime}\right]^{\prime}+q(x) y=\lambda r(x) y, \\
& a_1 y(0)+a_2 y^{\prime}(0)=0, b_1 y(1)+b_2 y^{\prime}(1)=0
\end{aligned}
$$

Let $f(x)$ and $f^{\prime}(x)$ be piecewise continuous on $0 \leq x \leq 1$. Then the series $f(x)=\sum_{n=1}^{\infty} c_n \Phi_n(x)$ converges to $\left(f\left(x^{-}\right)+f\left(x^{+}\right)\right) / 2$ at each point in the open interval $ 0<x<1 $.

This is an extension of the Fourier convergence theorem.

### 16. Example

Consider the 2 nd order ODE $y^{\prime \prime}+\lambda y=0$ subject to boundary conditions
$$
y(0)=0 \quad \text { and } \quad y(1)+y^{\prime}(1)=0
$$

Notice these define a Sturm-Liouville boundary problem (here $p(x)=1, q(x)=0, r(x)=1, a_1=1, a_2=0, b_1=1$, $\left.b_2=1\right)$
- S-L theory $\Longrightarrow \lambda \in \mathbb{R}$
- $\lambda=0$ : general solution
$$
y(x)=c_1 x+c_2
$$

Using boundary conditions:
$$
\begin{aligned}
y(0) & =c_2=0 \\
y(1)+y^{\prime}(1) & =2 c_1=0
\end{aligned}
$$

Only trivial solution, $c_1=c_2=0$, exists.

- $\lambda=-\mu(\mu>0)$ : general solution
$$
y(x)=c_1 \sinh \sqrt{\mu} x+c_2 \cosh \sqrt{\mu} x
$$

Using boundary conditions:
$$
\begin{aligned}
y(0) & =c_2=0 \\
y(1)+y^{\prime}(1) & =c_1(\sqrt{\mu} \cosh \sqrt{\mu}+\sinh \sqrt{\mu})=0
\end{aligned}
$$

If $c_1 \neq 0$ then $\sqrt{\mu} \cosh \sqrt{\mu}+\sinh \sqrt{\mu}=0$. Does $\sqrt{\mu}=-\tanh \sqrt{\mu}$ have non-trivial solutions?

No! Graphs of $\sqrt{\mu}$ and $-\tanh \sqrt{\mu}$ intersect only at $\mu=0$, which is excluded by hypothesis
$\Longrightarrow$ only trivial solution exists

- $\lambda=\mu(\mu>0)$ : general solution
$$
y(x)=c_1 \sin \sqrt{\mu} x+c_2 \cos \sqrt{\mu} x
$$

Using boundary conditions:
$$
\begin{aligned}
y(0) & =c_2=0 \Rightarrow y(x)=c_1 \sin \sqrt{\mu} x \\
y(1)+y^{\prime}(1) & =c_1(\sqrt{\mu} \cos \sqrt{\mu}+\sin \sqrt{\mu})=0
\end{aligned}
$$

If $c_1 \neq 0$ then $\sqrt{\mu} \cos \sqrt{\mu}+\sin \sqrt{\mu}=0$.
Does $\sqrt{\mu}=-\tan \sqrt{\mu}$ have non-trivial solutions?


Graphs of $\sqrt{\mu}$ and $-\tan \sqrt{\mu}$ intersect an unlimited number of times (due to periodicity of $\tan \sqrt{\mu}$ )
$\Longrightarrow \exists$ infinite countable $\lambda_n$
$$
\begin{aligned}
& \Phi_n(x)=k_n \sin \sqrt{\lambda_n} x \\
& n=1,2, \ldots
\end{aligned}
$$

Our eigenvalue boundary problem is solved by
$$
\Phi_n=k_n \sin \sqrt{\lambda_n} x \text { with } \sin \sqrt{\lambda_n}+\sqrt{\lambda_n} \cos \sqrt{\lambda_n}=0
$$
and $k_n$ fixed by requiring an orthonormal basis:
$$
\begin{aligned}
1 & =\int_0^1\left(\Phi_n(x)\right)^2 d x=k_n^2 \int_0^1\left(\sin \sqrt{\lambda_n} x\right)^2 d x \\
& =k_n^2 \int_0^1\left(\frac{1}{2}-\frac{1}{2} \cos 2 \sqrt{\lambda_n} x\right) d x \\
& =k_n^2\left(\frac{x}{2}-\frac{\sin 2 \sqrt{\lambda_n} x}{4 \sqrt{\lambda_n}}\right)_0^1=k_n^2 \frac{2 \sqrt{\lambda_n}-\sin 2 \sqrt{\lambda_n}}{4 \sqrt{\lambda_n}} \\
& =k_n^2 \frac{\sqrt{\lambda_n}-\sin \sqrt{\lambda_n} \cos \sqrt{\lambda_n}}{2 \sqrt{\lambda_n}}=k_n^2 \frac{1+\cos ^2 \sqrt{\lambda_n}}{2} \\
\text { i.e., } \quad k_n & =\left(\frac{2}{1+\cos ^2 \sqrt{\lambda_n}}\right)^{1 / 2}
\end{aligned}
$$

Expand the function $f(x)=x$ in the interval $0<x<1$ using the previous orthonormal set.
$$
f(x)=x=\sum_{n=1}^{\infty} c_n \Phi_n(x) \quad \text { with } \quad \Phi_n(x)=k_n \sin \sqrt{\lambda_n} x .
$$

Using orthonormality
$$
\begin{aligned}
c_n & =\left\langle f(x), \Phi_n(x)\right\rangle \\
& =\int_0^1 r(x) f(x) \Phi_n(x) d x \\
& =k_n \int_0^1 x \sin \sqrt{\lambda_n} x d x
\end{aligned}
$$
since here $r(x)=1$.

Hence the unknown coefficients are fixed by
$$
\begin{aligned}
c_n & =k_n \int_0^1 x \sin \sqrt{\lambda_n} x d x \\
& =k_n \frac{2 \sin \sqrt{\lambda_n}}{\lambda_n} \text { upon integrating by parts } \\
& =\frac{2 \sqrt{2} \sin \sqrt{\lambda_n}}{\lambda_n\left(1+\cos ^2 \sqrt{\lambda_n}\right)^{1 / 2}}
\end{aligned}
$$

Thus
$$
f(x)=\sum_{n=1}^{\infty} c_n k_n \sin \sqrt{\lambda_n} x=4 \sum_{n=1}^{\infty} \frac{\sin \sqrt{\lambda_n} \sin \sqrt{\lambda_n} x}{\lambda_n\left(1+\cos ^2 \sqrt{\lambda_n}\right)}
$$

## Part 8

### 1. Banach Spaces

#### 1.1 Basic Definitions

Let $X$ denote a real linear space.

>**Definition.** A mapping $\|\quad\|: X \rightarrow[0, \infty)$ is called a norm if (i) $\|u+v\| \leq\|u\|+\|v\|$ for all $u, v \in X$.
(ii) $\|\lambda u\|=|\lambda|\|u\|$ for all $u \in X, \lambda \in \mathbb{R}$.
(iii) $\|u\|=0$ if and only if $u=0$.

Inequality (i) is the triangle inequality.
Hereafter we assume $X$ is a normed linear space.

>**Definition.** We say a sequence $\left\{u_k\right\}_{k=1}^{\infty} \subset X$ converges to $u \in X$, written $$u_k \rightarrow u,$$
if$$
\lim _{k \rightarrow \infty}\left\|u_k-u\right\|=0.$$

>**Definition.**  A sequence $\left\{u_k\right\}_{k=1}^{\infty} \subset X$ is called a Cauchy sequence provided for each $\epsilon>0$ there exists $N>0$ such that$$\left\|u_k-u_l\right\|<\epsilon \quad \text { for all } k, l \geq N$$

>**Definition.** $X$ is complete if each Cauchy sequence in $X$ converges; that is, whenever $\left\{u_k\right\}_{k=1}^{\infty}$ is a Cauchy sequence, there exists $u \in X$ such that $\left\{u_k\right\}_{k=1}^{\infty}$ converges to $u$.

>**Definition.** $A$ Banach space $X$ is a complete, normed linear space.

>**Definition.** We say $X$ is separable if $X$ contains a countable dense subset.

A Example is $L^p$ spaces. Assume $U$ is an open subset of $\mathbb{R}^n$, and $1 \leq p \leq$ $\infty$. If $f: U \rightarrow \mathbb{R}$ is measurable, we define 

$$\|f\|_{L^p(U)}:= \begin{cases}\left(\int_U|f|^p d x\right)^{1 / p} & \text { if } 1 \leq p<\infty \\ \operatorname{esssup}_U|f| & \text { if } p=\infty\end{cases}$$

We define $L^p(U)$ to be the linear space of all measurable functions $f$ : $U \rightarrow \mathbb{R}$ for which $\|f\|_{L^p(U)}<\infty$. Then $L^p(U)$ is a Banach space, provided we identify two functions which agree a.e.

 We denote by $C_c\left(\mathbb{R}^N\right)$ the space of all continuous functions on $\mathbb{R}^N$ with compact support, i.e.,
$$
C_c\left(\mathbb{R}^N\right)=\left\{f \in C\left(\mathbb{R}^N\right) ; f(x)=0 \quad \forall x \in \mathbb{R}^N \backslash K \text {, where } K \text { is compact }\right\} .
$$

>**Theorem  (density)**. The space $C_c\left(\mathbb{R}^N\right)$ is dense in $L^1\left(\mathbb{R}^N\right)$; i.e.,$$\forall f \in L^1\left(\mathbb{R}^N\right) \quad \forall \varepsilon>0 \quad \exists f_1 \in C_c\left(\mathbb{R}^N\right) \text { such that }\left\|f-f_1\right\|_1 \leq \varepsilon \text {. }$$


> **Theorem  (dominated convergence theorem, Lebesgue)**. Let $\left(f_n\right)$ be a sequence of functions in $L^1$ that satisfy
(a) $f_n(x) \rightarrow f(x)$ a.e. on $\Omega$,
(b) there is a function $g \in L^1$ such that for all $n,\left|f_n(x)\right| \leq g(x)$ a.e. on $\Omega$.
Then $f \in L^1$ and $\left\|f_n-f\right\|_1 \rightarrow 0$.

> **Theorem  (Fubini)**.( Assume that $F \in L^1\left(\Omega_1 \times \Omega_2\right)$. Then for a.e. $x \in \Omega_1$, $F(x, y) \in L_y^1\left(\Omega_2\right)$ and $\int_{\Omega_2} F(x, y) d \mu_2 \in L_x^1\left(\Omega_1\right)$. Similarly, for a.e. $y \in \Omega_2$, $F(x, y) \in L_x^1\left(\Omega_1\right)$ and $\int_{\Omega_1} F(x, y) d \mu_1 \in L_y^1\left(\Omega_2\right)$.
Moreover, one has $$
\int_{\Omega_1} d \mu_1 \int_{\Omega_2} F(x, y) d \mu_2=\int_{\Omega_2} d \mu_2 \int_{\Omega_1} F(x, y) d \mu_1=\iint_{\Omega_1 \times \Omega_2} F(x, y) d \mu_1 d \mu_2 . $$

Let $1 \leq p \leq \infty$; we denote by $p^{\prime}$ the conjugate exponent,
$$
\frac{1}{p}+\frac{1}{p^{\prime}}=1
$$

>**Theorem (Hölder's inequality)**. Assume that $f \in L^p$ and $g \in L^{p^{\prime}}$ with $1 \leq p \leq \infty$. Then $f g \in L^1$ and $\int|f g| \leq\|f\|_p\|g\|_{p^{\prime}}$.


#### 1.2 Reflexivity. Separability. Dual of $L^p$

 We denote by $E^{\star}$ the dual space of $E$, that is, the space of all continuous linear functionals on $E$; the (dual) norm on $E^{\star}$ is defined by
$$
\|f\|_{E^{\star}}=\sup _{\substack{\|x\| \leq 1 \\ x \in E}}|f(x)|=\sup _{\substack{\|x\| \leq 1 \\ x \in E}} f(x) .
$$

When there is no confusion we shall also write $\|f\|$ instead of $\|f\|_{E^{\star}}$.
Given $f \in E^{\star}$ and $x \in E$ we shall often write $\langle f, x\rangle$ instead of $f(x)$; 

We say that $\langle$, $\rangle$ is the scalar product for the duality $E^{\star}, E$.

It is well known that $E^{\star}$ is a Banach space, i.e., $E^{\star}$ is complete (even if $E$ is not); this follows from the fact that $\mathbb{R}$ is complete.


>**Definition**. Let $E$ be a Banach space and let $J: E \rightarrow E^{\star \star}$ be the canonical injection from $E$ into $E^{\star \star}$ (see Section 1.3). The space $E$ is said to be reflexive if $J$ is surjective, i.e., $J(E)=E^{\star \star}$.
When $E$ is reflexive, $E^{\star \star}$ is usually identified with $E$.

Remark . Many important spaces in analysis are reflexive. Clearly, finite-dimensional spaces are reflexive (since $\operatorname{dim} E=\operatorname{dim} E^{\star}=\operatorname{dim} E^{\star \star}$ ).  $L^p$ (and $\ell^p$ ) spaces are reflexive for $1 < p < \infty$. We shall see that Hilbert spaces are reflexive. However, equally important spaces in analysis are not reflexive; for example:

- $L^1$ and $L^{\infty}$ (and $\ell^1, \ell^{\infty}$ ) are not reflexive);

- $C(K)$, the space of continuous functions on an infinite compact metric space $K$, is not reflexive.


We shall consider separately the following three cases:

(A) $1 < p < \infty $,

(B) $p=1$,

(C) $p=\infty$.


**A. Study of $L^p(\Omega)$ for $1 < p< \infty$.**

This case is the most "favorable": $L^p$ is reflexive, separable, and the dual of $L^p$ is $L^{p^{\prime}}$, i.e $\left(L^p\right)^{\star}=L^{p^{\prime}}$.

>**Theorem (Riesz representation theorem)**. Let $1<p< \infty $ and let $\phi \in$ $\left(L^p\right)^{\star}$. Then there exists a unique function $u \in L^{p^{\prime}}$ such that $$ \langle\phi, f\rangle=\int u f \quad \forall f \in L^p .$$ Moreover, $\|u\|_{p^{\prime}}=\|\phi\|_{\left(L^p\right)^{\star}}.$

It says that every continuous linear functional on $L^p$ with $1<p< \infty $ can be represented "concretely" as an integral. The mapping $\phi \mapsto u$, which is a linear surjective isometry, allows us to identify the "abstract" space $\left(L^p\right)^{\star}$ with $L^{p^{\prime}}$.

**B. Study of $L^1(\Omega)$.**


>**Theorem(Riesz representation theorem)**. Let $\phi \in\left(L^1\right)^{\star}$. Then there exists a unique function $u \in L^{\infty}$ such that $$\langle\phi, f\rangle=\int u f \quad \forall f \in L^1 .$$ Moreover, $\|u\|_{\infty}=\|\phi\|_{\left(L^1\right)^{\star}}$.


This theorem asserts that every continuous linear functional on $L^1$ can be represented "concretely" as an integral. The mapping $\phi \mapsto u$, which is a linear surjective isometry, allows us to identify the "abstract" space $\left(L^1\right)^{\star}$ with $L^{\infty}$. In what follows, we shall make the identification
$$
\left(L^1\right)^{\star}=L^{\infty}.
$$

The space $L^1(\Omega)$ is never reflexive except in the trivial case where $\Omega$ consists of a finite number of atoms - and then $L^1(\Omega)$ is finite-dimensional. 
 
**C. Study of $L^{\infty}$.**

We already know that $L^{\infty}=\left(L^1\right)^{\star}$.
 
The following table summarizes the main properties of the space $L^p(\Omega)$ when $\Omega$ is a measurable subset of $\mathbb{R}^N$ :

 
|  | Reflexive | Separable | Dual space |
| :---: | :---: | :---: | :---: |
| $L^p$ with $1<p< \infty $ | YES | YES | $L^{p^{\prime}}$ |
| $L^1$ | NO | YES | $L^{\infty}$ |
| $L^{\infty}$ | NO | NO | Strictly bigger than $L^1$ |


### 2. Hilbert Spaces

#### 2.1 Basic Definitions

Let $H$ be a real linear space.

>**Definition**. $A$ mapping $():, H \times H \rightarrow \mathbb{R}$ is called an inner product if
(i) $(u, v)=(v, u)$ for all $u, v \in H$,
(ii) the mapping $u \mapsto(u, v)$ is linear for each $v \in H$,
(iii) $(u, u) \geq 0$ for all $u \in H$,
(iv) $(u, u)=0$ if and only if $u=0$.

If $(,)$ is an inner product, the associated norm is
$$
\|u\|:=(u, u)^{1 / 2} \quad(u \in H) .
$$

The Cauchy-Schwarz inequality states
$$
|(u, v)| \leq\|u\|\|v\| \quad(u, v \in H).
$$


>**Definition**. $A$ Hilbert space $H$ is a Banach space endowed with an inner product which generates the norm.

The space $L^2(U)$ is a Hilbert space, with
$$
(f, g)=\int_U f g d x.
$$

The Sobolev space $H^1(U)$ is a Hilbert space, with
$$
(f, g)=\int_U f g+D f \cdot D g d x.
$$

>**Definition**.  Two elements $u, v \in H$ are orthogonal if $(u, v)=0$.


>**Definition**.A countable basis $\left\{w_k\right\}_{k=1}^{\infty} \subset H$ is called orthonormal if $\left\{\begin{array}{cl}\left(w_k, w_l\right)=0 & (k, l=1, \ldots ; k \neq l) \\ \left\|w_k\right\|=1 & (k=1, \ldots)\end{array}\right.$



If $u \in H$ and $\left\{w_k\right\}_{k=1}^{\infty} \subset H$ is an orthonormal basis, we can write
$$
u=\sum_{k=1}^{\infty}\left(u, w_k\right) w_k
$$
the series converging in $H$. In addition
$$
\|u\|^2=\sum_{k=1}^{\infty}\left(u, w_k\right)^2.
$$

>**Definition**. If $S$ is a subspace of $H, S^{\perp}=\{u \in H \mid(u, v)=0$ for all $v \in S\}$ is the subspace orthogonal to $S$.

In what follows, $H$ will always denote a Hilbert space.

 $L^2(\Omega)$ equipped with the scalar product
$$
(u, v)=\int_{\Omega} u(x) v(x) d \mu
$$
is a Hilbert space. In particular, $\ell^2$ is a Hilbert space. The Sobolev space $H^1$ studied later is another example of a Hilbert space; it is "modeled" on $L^2(\Omega)$.

$H$ is uniformly convex, and thus it is reflexive.



> **Theorem (projection onto a closed convex set)**. Let $K \subset H$ be a nonempty closed convex set. Then for every $f \in H$ there exists a unique element $u \in K$ such that $|f-u|=\min _{v \in K}|f-v|=\operatorname{dist}(f, K)$. Moreover, $u$ is characterized by the property $u \in K$ and $(f-u, v-u) \leq 0 \quad \forall v \in K$.

The above element $u$ is called the projection of $f$ onto $K$ and is denoted by
$$
u=P_K f
$$

The scalar product of the vector $\overrightarrow{u f}$ with any vector $\overrightarrow{u v}(v \in$ $K)$ is $\leq 0$, i.e., the angle $\theta$ determined by these two vectors is $\geq \pi / 2$; see Figure.


![](https://files.mdnice.com/user/36229/ede0ae5a-cb63-450b-89ab-cb12a275db35.jpg)


#### 2.2 The Dual Space of a Hilbert Space

It is easy to prove that Hilbert spaces are reflexive.

>**Theorem (Riesz-Fréchet representation theorem)**. Given any $\varphi \in H^{\star}$ there exists a unique $f \in H$ such that
$ \langle\varphi, u\rangle=(f, u) \quad \forall u \in H .$ Moreover,$|f|=\|\varphi\|_{H^{\star}} .$

#### 2.3 The Theorems of Stampacchia and Lax–Milgram

> **Definition**. A bilinear form $a: H \times H \rightarrow \mathbb{R}$ is said to be
(i) continuous if there is a constant $C$ such that $$|a(u, v)| \leq C|u||v| \quad \forall u, v \in H $$ (ii) coercive if there is a constant $\alpha>0$ such that $$a(v, v) \geq \alpha|v|^2 \quad \forall v \in H. $$

> **Theorem (Stampacchia)**. Assume that a $(u, v)$ is a continuous coercive bilinear form on $H$. Let $K \subset H$ be a nonempty closed and convex subset. Then, given any $\varphi \in H^{\star}$, there exists a unique element $u \in K$ such that $$ a(u, v-u) \geq\langle\varphi, v-u\rangle \quad \forall v \in K. $$ Moreover, if a is symmetric, then $u$ is characterized by the property $u \in K \quad$ and $\quad \frac{1}{2} a(u, u)-\langle\varphi, u\rangle=\min _{v \in K}\left\{\frac{1}{2} a(v, v)-\langle\varphi, v\rangle\right\}$.

The proof of Theorem relies on the following very classical result.

>**Theorem (Banach fixed-point theorem-the contraction mapping principle)**. Let $X$ be a nonempty complete metric space and let $S: X \rightarrow X$ be a strict contraction, i.e., $$
d\left(S v_1, S v_2\right) \leq k d\left(v_1, v_2\right) \quad \forall v_1, v_2 \in X \text { with } k<1 .$$ Then $S$ has a unique fixed point, $u=S u.$

> **Corollary (Lax-Milgram)**. Assume that $a(u, v)$ is a continuous coercive bilinear form on $H$. Then, given any $\varphi \in H^{\star}$, there exists a unique element $u \in H$ such that $$
a(u, v)=\langle\varphi, v\rangle \quad \forall v \in H.$$ Moreover, if a is symmetric, then $u$ is characterized by the property $
u \in H \quad \text { and } \quad \frac{1}{2} a(u, u)-\langle\varphi, u\rangle=\min _{v \in H}\left\{\frac{1}{2} a(v, v)-\langle\varphi, v\rangle\right\} .$


The Lax–Milgram theorem is a very simple and efficient tool for solving
linear elliptic partial differential equations.

 There is a direct and elementary argument proving that $
a(u, v)=\langle\varphi, v\rangle \quad \forall v \in H$ has a unique solution. 

Indeed, this amounts to showing that
$\forall f \in H \quad \exists u \in H \quad$ unique such that $A u=f$,
i.e., $A$ is bijective from $H$ onto $H$. This is a trivial consequence of the following facts:

(a) $A$ is injective (since $A$ is coercive),

(b) $R(A)$ is closed, since $\alpha|v| \leq|A v| \forall v \in H$ (a consequence of the coerciveness),

(c) $R(A)$ is dense; indeed, suppose $v \in H$ satisfies
$$
(A u, v)=0 \quad \forall u \in H,
$$
then $v=0$.

#### 2.4 Hilbert Sums. Orthonormal Bases

> **Definition**. Let $\left(E_n\right)_{n \geq 1}$ be a sequence of closed subspaces of $H$. One says that $H$ is the Hilbert sum of the $E_n$ 's and one writes $H=\oplus_n E_n$ if (a) the spaces $E_n$ are mutually orthogonal, i.e., $$
(u, v)=0 \quad \forall u \in E_n, \quad \forall v \in E_m, m \neq n $$ (b) the linear space spanned by $\bigcup_{n=1}^{\infty} E_n$ is dense in $H .$ The linear space spanned by the $E_n$ 's is understood in the algebraic sense, i.e., finite linear combinations of elements belonging to the spaces $\left(E_n\right)$.


> **Theorem**. Assume that $H$ is the Hilbert sum of the $E_n$ 's. Given $u \in H$, set$ u_n=P_{E_n} u  $  and $
S_n=\sum_{k=1}^n u_k .$ Then we have $\lim _{n \rightarrow \infty} S_n=u$ and $\sum_{k=1}^{\infty}\left|u_k\right|^2=|u|^2 \quad$ (Bessel-Parseval's identity).

> **Definition**. A sequence $\left(e_n\right)_{n \geq 1}$ in $H$ is said to be an orthonormal basis of $H$ (or a Hilbert basis or simply a basis when there is no confusion ) if it satisfies the following properties:
(i) $\left|e_n\right|=1 \forall n$ and $\left(e_m, e_n\right)=0 \forall m \neq n$,
(ii) the linear space spanned by the $e_n$ 's is dense in $H.$


> **Corollary**. Let $\left(e_n\right)$ be an orthonormal basis. Then for every $u \in H$, we have $u=\sum_{k=1}^{\infty}\left(u, e_k\right) e_k, \quad \text { i.e., } u=\lim _{n \rightarrow \infty} \sum_{k=1}^n\left(u, e_k\right) e_k$  and  $|u|^2=\sum_{k=1}^{\infty}\left|\left(u, e_k\right)\right|^2 .$


> **Theorem**. Every separable Hilbert space has an orthonormal basis.

### 3. Bounded Linear Operators

#### 3.1 The Baire Category Theorem

>  **Theorem  (Baire)**. Let $X$ be a complete metric space and let $\left(X_n\right)_{n \geq 1}$ be a sequence of closed subsets in $X$. Assume that $\text { Int } X_n=\emptyset \quad \text { for every } n \geq 1 \text {. }$ Then $
\operatorname{Int}\left(\bigcup_{n=1}^{\infty} X_n\right)=\emptyset. $


The Baire category theorem is often used in the following form. Let $X$ be a nonempty complete metric space. Let $\left(X_n\right)_{n \geq 1}$ be a sequence of closed subsets such that
$$
\bigcup_{n=1}^{\infty} X_n=X .
$$

Then there exists some $n_0$ such that Int $X_{n_0} \neq \emptyset$.

#### 3.2 The Uniform Boundedness Principle

Let $E$ and $F$ be two n.v.s. We denote by $\mathcal{L}(E, F)$ the space of continuous (= bounded) linear operators from $E$ into $F$ equipped with the norm
$$
\|T\|_{\mathscr{L}(E, F)}=\sup _{\substack{x \in E \\\|x\| \leq 1}}\|T x\| .
$$

As usual, one writes $\mathscr{L}(E)$ instead of $\mathscr{L}(E, E)$.


> **Theorem (Banach-Steinhaus, uniform boundedness principle)**. Let $E$ and $F$ be two Banach spaces and let $\left(T_i\right)_{i \in I}$ be a family (not necessarily countable) of continuous linear operators from $E$ into $F$. Assume that $\sup _{i \in I}\left\|T_i x\right\|<\infty \quad \forall x \in E .$ Then $\sup _{i \in I}\left\|T_i\right\|_{\mathscr{L}(E, F)}<\infty .$ In other words, there exists a constant $c$ such that $$
\left\|T_i x\right\| \leq c\|x\| \quad \forall x \in E, \quad \forall i \in I .$$

The conclusion of Theorem is quite remarkable and surprising. From pointwise estimates one derives a global (uniform) estimate.

Here are a few direct consequences of the uniform boundedness principle.

> **Corollary**. Let $E$ and $F$ be two Banach spaces. Let $\left(T_n\right)$ be a sequence of continuous linear operators from $E$ into $F$ such that for every $x \in E, T_n x$ converges (as $n \rightarrow \infty$ ) to a limit denoted by $T x$. Then we have
(a) $\sup _n\left\|T_n\right\|_{\mathscr{L}(E, F)}<\infty$,(b) $T \in \mathcal{L}(E, F)$,(c) $\|T\|_{\mathscr{L}(E, F)} \leq \liminf _{n \rightarrow \infty}\left\|T_n\right\|_{\mathscr{L}(E, F)}$.

> **Corollary**. Let $G$ be a Banach space and let $B$ be a subset of $G$. Assume that
for every $f \in G^{\star}$ the set $f(B)=\{\langle f, x\rangle ; x \in B\}$ is bounded (in $\mathbb{R}$ ). Then $B$ is bounded.

Corollary says that in order to prove that a set $B$ is bounded it suffices to "look" at $B$ through the bounded linear functionals. This is a familiar procedure in finite-dimensional spaces, where the linear functionals are the components with respect to some basis. 


#### 3.3 The Open Mapping Theorem and the Closed Graph Theorem

Here are two basic results due to Banach.

> **Theorem (open mapping theorem)**. Let $E$ and $F$ be two Banach spaces and let $T$ be a continuous linear operator from $E$ into $F$ that is surjective (=onto). Then there exists a constant $c>0$ such that $$T\left(B_E(0,1)\right) \supset B_F(0, c) .$$

> **Corollary**. Let $E$ and $F$ be two Banach spaces and let $T$ be a continuous linear operator from $E$ into $F$ that is bijective, i.e., injective (=one-to-one) and surjective. Then $T^{-1}$ is also continuous (from $F$ into $E$ ).

> **Corollary**. Let $E$ be a vector space provided with two norms, \|\|$_1$ and \|\|$_2$. Assume that $E$ is a Banach space for both norms and that there exists a constant $C \geq 0$ such that $$\|x\|_2 \leq C\|x\|_1 \quad \forall x \in E .$$ Then the two norms are equivalent, i.e., there is a constant $c>0$ such that $$\|x\|_1 \leq c\|x\|_2 \quad \forall x \in E .$$

> **Theorem (closed graph theorem)**. Let $E$ and $F$ be two Banach spaces. Let $T$ be a linear operator from $E$ into $F$. Assume that the graph of $T, G(T)$, is closed in $E \times F$. Then $T$ is continuous.

The converse is obviously true, since the graph of any continuous map (linear or not) is closed.

#### 3.4 Linear Operators on Banach Spaces

Let $X$ and $Y$ be real Banach spaces.

> **Definition**. (i) $A$ mapping $A: X \rightarrow Y$ is a linear operator provided
$A[\lambda u+\mu v]=\lambda A u+\mu A v$
for all $u, v \in X, \lambda, \mu \in \mathbb{R}$.
(ii) The range of $A$ is $R(A):=\{v \in Y \mid v=$ Au for some $u \in X\}$ and the null space of $A$ is $N(A):=\{u \in X \mid A u=0\}$.

> **Definition**. A linear operator $A: X \rightarrow Y$ is bounded if $\|A\|:=\sup \left\{\|A u\|_Y \mid\|u\|_X \leq 1\right\}<\infty .$

It is easy to check that a bounded linear operator $A: X \rightarrow Y$ is continuous.

> **Definition**. A linear operator $A: X \rightarrow Y$ is called closed if whenever $u_k \rightarrow u$ in $X$ and $A u_k \rightarrow v$ in $Y$, then $$A u=v .$$

> **Theorem (Closed Graph Theorem)**. Let $A: X \rightarrow Y$ be a closed, linear operator. Then $A$ is bounded.

> **Definition**. Let $A: X \rightarrow X$ be a bounded linear operator.(i) The resolvent set of $A$ is$$\rho(A)=\{\eta \in \mathbb{R} \mid(A-\eta I) \text { is one-to-one and onto }\} .$$(ii) The spectrum of $A$ is $$\sigma(A)=\mathbb{R}-\rho(A) .$$

If $\eta \in \rho(A)$, the Closed Graph Theorem then implies that the inverse $(A-\eta I)^{-1}: X \rightarrow X$ is a bounded linear operator.

> **Definition**. (i) We say $\eta \in \sigma(A)$ is an eigenvalue of $A$ provided $$N(A-\eta I) \neq\{0\} .$$We write $\sigma_p(A)$ to denote the collection of eigenvalues of $A ; \sigma_p(A)$ is the point spectrum.(ii) If $\eta$ is an eigenvalue and $w \neq 0$ satisfies $$A w=\eta w,$$we say $w$ is an associated eigenvector.


> **Definition**. (i) $A$ bounded linear operator $u^*: X \rightarrow \mathbb{R}$ is called a bounded linear functional on $X$.
(ii) We write $X^*$ to denote the collection of all bounded linear functionals on $X ; X^*$ is the dual space of $X$.

> **Definition**. (i) If $u \in X, u^* \in X^*$ we write$$\left\langle u^*, u\right\rangle $$ to denote the real number $u^*(u)$. The symbol $\langle$,$\rangle denotes the pairing of X^*$ and $X$. (ii) We define $\left\|u^*\right\|:=\sup \left\{\left\langle u^*, u\right\rangle \mid\|u\| \leq 1\right\} .$ (iii) A Banach space is reflexive if $\left(X^*\right)^*=X$. More precisely, this means that for each $u^{* *} \in\left(X^*\right)^*$, there exists $u \in X$ such that $\left\langle u^{* *}, u^*\right\rangle=\left\langle u^*, u\right\rangle \quad \text { for all } u^* \in X^* \text {. }$

#### 3.5 Linear Operators on Hilbert Spaces

Now let $H$ be a real Hilbert space, with inner product $($,$) .$

> **Theorem (Riesz Representation Theorem)**. $H^*$ can be canonically identified with $H$; more precisely, for each $u^* \in H^*$ there exists a unique element $u \in H$ such that $$\left\langle u^*, v\right\rangle=(u, v) \quad \text { for all } v \in H .$$

The mapping $u^* \mapsto u$ is a linear isomorphism of $H^*$ onto $H$.

> **Definition**. (i) If $A: H \rightarrow H$ is a bounded, linear operator, its adjoint $A^*: H \rightarrow H$ satisfies $$(A u, v)=\left(u, A^* v\right)$$ for all $u, v \in H$. (ii) $A$ is symmetric if $A^*=A$.


### 4. Weak Convergence

Let $X$ denote a real Banach space.

> **Definition**. We say a sequence $\left\{u_k\right\}_{k=1}^{\infty} \subset X$ converges weakly to $u \in X$, written$$
u_k \rightharpoonup u $$ if  
$\left\langle u^*, u_k\right\rangle \rightarrow\left\langle u^*, u\right\rangle$ for each bounded linear functional $u^* \in X^*$.

It is easy to check that if $u_k \rightarrow u$, then $u_k \rightharpoonup u$. It is also true that any weakly convergent sequence is bounded. In addition, if $u_k \rightarrow u$, then  $$\|u\| \leq \liminf _{k \rightarrow \infty}\left\|u_k\right\|. $$

> **Theorem (Weak compactness)**. Let $X$ be a reflexive Banach space and suppose the sequence $\left\{u_k\right\}_{k=1}^{\infty} \subset X$ is bounded. Then there exists a subsequence $\left\{u_{k_j}\right\}_{j=1}^{\infty} \subset\left\{u_k\right\}_{k=1}^{\infty}$ and $u \in X$ such that $$u_{k_j} \rightharpoonup u.$$

In other words, bounded sequences in a reflexive Banach space are weakly precompact. In particular, a bounded sequence in a Hilbert space contains a weakly convergent subsequence.

Mazur's Theorem asserts that a convex, closed subset of $X$ is weakly closed.

 We will most often employ weak convergence ideas in the following context. Take $U \subset \mathbb{R}^n$ to be open, and assume $1 \leq p<\infty$. Then
the dual space of $X=L^p(U)$ is $X^*=L^q(U)$
where $\frac{1}{p}+\frac{1}{q}=1,1<q \leq \infty $. 

More precisely, each bounded linear functional on $L^p(U)$ can be represented as $f \mapsto \int_U g f d x$ for some $g \in L^q(U)$. Therefore
$$
f_k \rightarrow f \quad \text { weakly in } L^p(U)
$$
means $\quad \int_U g f_k d x \rightarrow \int_U g f d x \quad$ as $k \rightarrow \infty$, for all $g \in L^q(U)$.

Now the identification of $L^q(U)$ as the dual of $L^p(U)$ shows that
$L^p(U)$ is reflexive if $1<p< \infty $.


### 5. Compact Operators, Fredholm Theory

#### 5.1 Spectral Theory in Finite Dimensional Normed Spaces

For a given (real or complex) $n$-rowed square matrix $A=\left(\alpha_{j k}\right)$ the concepts of eigenvalues and eigenvectors are defined in terms of the equation
$$
A x=\lambda x     \quad (1)
$$
as follows.

> **Definition (Eigenvalues, eigenvectors, eigenspaces, spectrum, resolvent set of a matrix)**. An eigenvalue of a square matrix $A=\left(\alpha_{j k}\right)$ is a number $\lambda$ such that (1) has a solution $x \neq 0$. This $x$ is called an eigenvector of $A$ corresponding to that eigenvalue $\lambda$. The eigenvectors corresponding to that eigenvalue $\lambda$ and the zero vector form a vector subspace of $X$ which is called the eigenspace of $A$ corresponding to that eigenvalue $\lambda$. The set $\sigma(A)$ of all eigenvalues of $A$ is called the spectrum of $A$. Its complement $\rho(A)=\mathbf{C}-\sigma(A)$ in the complex plane is called the resolvent set of $A$.

How did we obtain this result, and what can we say about the existence of eigenvalues of a matrix in general?
To answer this question, let us first note that (1) can be written
$$
(A-\lambda I) x=0  \quad (2)
$$
where $I$ is the $n$-rowed unit matrix. This is a homogeneous system of $n$ linear equations in $n$ unknowns $\xi_1, \cdots, \xi_n$, the components of $x$. The determinant of the coefficients is $\operatorname{det}(A-\lambda I)$ and must be zero in order that (2) have a solution $x \neq 0$. This gives the characteristic equation of $A$ :
$$
 (3)\operatorname{det}(A-\lambda I)=\left|\begin{array}{cccc}
\alpha_{11}-\lambda & \alpha_{12} & \cdots & \alpha_{1 n} \\
\alpha_{21} & \alpha_{22}-\lambda & \cdots & \alpha_{2 n} \\
\cdot & \cdot & \cdots & \cdot \\
\alpha_{n 1} & \alpha_{n 2} & \cdots & \alpha_{n n}-\lambda
\end{array}\right|=0 .
$$
$\operatorname{det}(A-\lambda I)$ is called the characteristic determinant of $A$. By developing it we obtain a polynomial in $\lambda$ of degree $n$, the characteristic polynomial of $A$. Equation (3) is called the characteristic equation of A.

>**Theorem (Eigenvalues of a matrix)**. The eigenvalues of an $n$-rowed square matrix $A=\left(\alpha_{j k}\right)$ are given by the solutions of the characteristic equation (3) of A. Hence $A$ has at least one eigenvalue (and at most $n$ numerically different eigenvalues).

How can we apply our result to a linear operator $T: X \longrightarrow X$ on a normed space $X$ of dimension $n$ ? Let $e=\left\{e_1, \cdots, e_n\right\}$ be any basis for $X$ and $T_e=\left(\alpha_{j k}\right)$ the matrix representing $T$ with respect to that basis (whose elements are kept in the given order). Then the eigenvalues of the matrix $T_e$ are called the eigenvalues of the operator $T$, and similarly for the spectrum and the resolvent set. This is justified by

>**Theorem (Eigenvalues of an operator)**. All matrices representing a given linear operator $T: X \longrightarrow X$ on a finite dimensional normed space $X$ relative to various bases for $X$ have the same eigenvalues.

> **Existence Theorem (Eigenvalues)**. A linear operator on a finite dimensional complex normed space $X \neq\{0\}$ has at least one eigenvalue.

#### 5.2 Basic Concepts

In the preceding section the spaces were finite dimensional. In this section we consider normed spaces of any dimension, and we shall see that in infinite dimensional spaces, spectral theory becomes more complicated.

Let $X \neq\{0\}$ be a complex normed space and $T: \mathscr{D}(T) \longrightarrow X$ a linear operator with domain $\mathscr{D}(T) \subset X$. With $T$ we associate the operator
(1)
$$
T_\lambda=T-\lambda I
$$
where $\lambda$ is a complex number and $I$ is the identity operator on $\mathscr{D}(T)$. If $T_\lambda$ has an inverse, we denote it by $R_\lambda(T)$, that is,
$$
R_\lambda(T)=T_\lambda^{-1}=(T-\lambda I)^{-1}
$$
and call it the resolvent operator of $T$ or, simply, the **resolvent**  of $T$. Instead of $R_\lambda(T)$ we also write simply $R_\lambda$ if it is clear to what operator $T$ we refer in a specific discussion.

The name "resolvent" is appropriate, since $R_\lambda(T)$ helps to solve the equation $T_\lambda x=y$. Thus, $x=T_\lambda^{-1} y=R_\lambda(T) y$ provided $R_\lambda(T)$ exists.

More important, the investigation of properties of $R_\lambda$ will be basic for an understanding of the operator $T$ itself. Naturally, many properties of $T_\lambda$ and $R_\lambda$ depend on $\lambda$. And spectral theory is concerned with those properties. For instance, we shall be interested in the set of all $\lambda$ in the complex plane such that $R_\lambda$ exists. Boundedness of $R_\lambda$ is another property that will be essential. We shall also ask for what $\lambda$ 's the domain of $R_\lambda$ is dense in $X$, to name just a few aspects.

> **Definition (Regular value, resolvent set, spectrum)**. Let $X \neq\{0\}$ be a complex normed space and $T: \mathscr{D}(T) \longrightarrow X$ a linear operator with domain $\mathscr{D}(T) \subset X$. A regular value $\lambda$ of $T$ is a complex number such that (R1) $R_\lambda(T)$ exists,
(R2) $ R_\lambda(T)$ is bounded,
(R3) $R_\lambda(T)$ is defined on a set which is dense in $X$. The resolvent set $\rho(T)$ of $T$ is the set of all regular values $\lambda$ of $T$. Its complement $\sigma(T)=\mathbf{C}-\rho(T)$ in the complex plane $\mathbf{C}$ is called the spectrum of $T$, and a $\lambda \in \sigma(T)$ is called a spectral value of $T$. 

Furthermore, the spectrum $\sigma(T)$ is partitioned into three disjoint sets as follows.

> **Definition**. The point spectrum or discrete spectrum $\sigma_p(T)$ is the set such that $R_\lambda(T)$ does not exist. A $\lambda \in \sigma_p(T)$ is called an eigenvalue of $T$.

> **Definition**. The continuous spectrum $\sigma_c(T)$ is the set such that $R_\lambda(T)$ exists and satisfies (R3) but not (R2), that is, $R_\lambda(T)$ is unbounded.

> **Definition**. The residual spectrum $\sigma_r(T)$ is the set such that $R_\lambda(T)$ exists (and may be bounded or not) but does not satisfy (R3), that is, the domain of $R_\lambda(T)$ is not dense in $X$.

To avoid trivial misunderstandings, let us say that some of the sets in this definition may be empty. This is an existence problem which we shall have to discuss. For instance, $\sigma_c(T)=\sigma_r(T)=\varnothing$ in the finite dimensional case, as we know from Sec. 7.1.

The conditions stated in Def can be summarized in the following table.

![](https://files.mdnice.com/user/36229/73752fb8-748c-4263-a394-1c06f04826ad.jpg)


We first note that the four sets in the table are disjoint and their union is the whole complex plane:
$$
\begin{aligned}
\mathbf{C} & =\rho(T) \cup \sigma(T) \\
& =\rho(T) \cup \sigma_p(T) \cup \sigma_c(T) \cup \sigma_r(T)
\end{aligned}
$$

Hence if $T_\lambda x=(T-\lambda I) x=0$ for some $x \neq 0$, then $\lambda \in \sigma_p(T)$, by definition, that is, $\lambda$ is an eigenvalue of $T$. The vector $x$ is then called an eigenvector of $T$ (or eigenfunction of $T$ if $X$ is a function space) corresponding to the eigenvalue $\lambda$. The subspace of $\mathscr{D}(T)$ consisting of 0 and all eigenvectors of $T$ corresponding to an eigenvalue $\lambda$ of $T$ is called the eigenspace of $T$ corresponding to that eigenvalue $\lambda$.


Example (Operator with a spectral value which is not an eigenvalue). On the Hilbert sequence space $X=l^2$ (cf. 3.1-6) we define a linear operator $T: l^2 \longrightarrow l^2$ by
$$ (1) \quad
\left(\xi_1, \xi_2, \cdots\right) \longmapsto\left(0, \xi_1, \xi_2, \cdots\right)
$$
where $x=\left(\xi_j\right) \in l^2$. The operator $T$ is called the right-shift operator. $T$ is bounded (and $\|T\|=1$ ) because
$$
\|T x\|^2=\sum_{j=1}^{\infty}\left|\xi_j\right|^2=\|x\|^2
$$

The operator $R_0(T)=T^{-1}: T(X) \longrightarrow X$ exists; in fact, it is the leftshift operator given by
$$
\left(\xi_1, \xi_2, \cdots\right) \longmapsto\left(\xi_2, \xi_3, \cdots\right) .
$$

But $R_0(T)$ does not satisfy (R3), because (1) shows that $T(X)$ is not dense in $X$; indeed, $T(X)$ is the subspace $Y$ consisting of all $y=\left(\eta_j\right)$ with $\eta_1=0$. Hence, by definition, $\lambda=0$ is a spectral value of $T$. Furthermore, $\lambda=0$ is not an eigenvalue. We can see this directly from (1) since $T x=0$ implies $x=0$ and the zero vector is not an eigenvector.

#### 5.3  Spectral Properties of Bounded Linear Operators

> **Theorem (Inverse)**. Let $T \in B(X, X)$, where $X$ is a Banach space. If $\|T\|<1$, then $(I-T)^{-1}$ exists as a bounded linear operator on the whole space $X$ and $$
(I-T)^{-1}=\sum_{j=0}^{\infty} T^j=I+T+T^2+\cdots$$[where the series on the right is convergent in the norm on $B(X, X)$ ].

> **Theorem (Spectrum closed)**. The resolvent set $\rho(T)$ of a bounded linear operator $T$ on a complex Banach space $X$ is open; hence the spectrum $\sigma(T)$ is closed.


#### 5.4 Compact Linear Operators on Normed Spaces

> **Definition(Compact linear operator)**. Let $X$ and $Y$ be normed spaces. An operator $T: X \longrightarrow Y$ is called a compact linear operator (or completely continuous linear operator) if $T$ is linear and if for every bounded subset $M$ of $X$, the image $T(M)$ is relatively compact, that is, the closure $\overline{T(M)}$ is compact. 

> **Lemma (Continuity)**. Let $X$ and $Y$ be normed spaces. Then:
(a) Every compact linear operator $T: X \longrightarrow Y$ is bounded, hence continuous.
(b) If $\operatorname{dim} X=\infty$, the identity operator I: $X \longrightarrow X$ (which is continuous) is not compact.

> **Theorem (Compactness criterion)**. Let $X$ and $Y$ be normed spaces and $T: X \longrightarrow Y$ a linear operator. Then $T$ is compact if and only if it maps every bounded sequence $\left(x_n\right)$ in $X$ onto a sequence $\left(T x_n\right)$ in $Y$ which has a convergent subsequence.

> **Theorem (Finite dimensional domain or range)**. Let $X$ and $Y$ be normed spaces and $T: X \longrightarrow Y$ a linear operator. Then:
(a) If $T$ is bounded and $\operatorname{dim} T(X) \dot{<}$, the operator $T$ is compact.
(b) If $\operatorname{dim} X<\infty$, the operator $T$ is compact.

We mention that an operator $T \in B(X, Y)$ with $\operatorname{dim} T(X)<\infty$  is often called an operator of finite rank.

> **Theorem (Sequence of compact linear operators)**. Let $\left(T_n\right)$ be a sequence of compact linear operators from a normed space $X$ into a Banach space $Y$. If $\left(T_n\right)$ is uniformly operator convergent, say, $\left\|T_n-T\right\| \longrightarrow 0$, then the limit operator $T$ is compact.

Example (Space $l^2$ ). Prove compactness of $T: l^2 \longrightarrow l^2$ defined by $y=\left(\eta_j\right)=T x$ where $\eta_j=\xi_j / j$ for $j=1,2, \cdots$.

Solution. $T$ is linear. If $x=\left(\xi_j\right) \in l^2$, then $y=\left(\eta_j\right) \in l^2$. Let $T_n: l^2 \longrightarrow l^2$ be defined by
$$
T_n x=\left(\xi_1, \frac{\xi_2}{2}, \frac{\xi_3}{3}, \cdots, \frac{\xi_n}{n}, 0,0, \cdots\right) .
$$
$T_n$ is linear and bounded, and is compact . Furthermore,
$$
\begin{aligned}
\left\|\left(T-T_n\right) x\right\|^2=\sum_{j=n+1}^{\infty}\left|\eta_j\right|^2 & =\sum_{j=n+1}^{\infty} \frac{1}{j^2}\left|\xi_j\right|^2 \\
& \leqq \frac{1}{(n+1)^2} \sum_{j=n+1}^{\infty}\left|\xi_j\right|^2 \leqq \frac{\|x\|^2}{(n+1)^2} .
\end{aligned}
$$

Taking the supremum over all $x$ of norm 1 , we see that
$$
\left\|T-T_n\right\| \leqq \frac{1}{n+1}
$$

Hence $T_n \longrightarrow T$, and $T$ is compact.

Now let $H$ denote a real Hilbert space, with inner product $($,$) . It is$ easy to see that if a linear operator $K: H \rightarrow H$ is compact and $u_k \rightharpoonup u$, then $K u_k \rightarrow K u$.



#### 5.5 Further Properties of Compact Linear Operators

> **Theorem (Separability of range)**. The range $\mathscr{R}(T)$ of a compact linear operator $T: X \longrightarrow Y$ is separable; here, $X$ and $Y$ are normed spaces.


> **Theorem (Adjoint operator)**. Let $T: X \longrightarrow Y$ be a linear operator. If $T$ is compact, so is its adjoint operator $T^{\times}: Y^{\prime} \longrightarrow X^{\prime}$; here $X$ and $Y$ are normed spaces and $X^{\prime}$ and $Y^{\prime}$ the dual spaces of $X$ and $Y$.



#### 5.6 Spectral Properties of Compact Linear Operators on Normed Spaces

In this section and the next one we consider spectral properties of a compact linear operator $T: X \longrightarrow X$ on a normed space $X$. For this purpose we shall again use the operator

$$(1) \quad
T_\lambda=T-\lambda I \quad(\lambda \in \mathbf{C})
$$
and the basic concepts of spectral theory.

Our first theorem is concerned with eigenvalues. It tells us that the
point spectrum of a compact linear operator is not complicated.

> **Theorem (Eigenvalues)**. The set of eigenvalues of a compact linear operator $T: X \longrightarrow X$ on a normed space $X$ is countable (perhaps finite or even empty), and the only possible point of accumulation is $\lambda=0$.

This theorem shows that if a compact linear operator on a normed space has infinitely many eigenvalues, we can arrange these eigenvalues in a sequence converging to zero.

Composition of a compact linear operator and a bounded linear operator yields compact linear operators. This interesting fact is the content of the following lemma which has many applications and, at present, will be used to prove a basic property of compact linear operators.

> **Lemma (Compactness of product)**. Let $T: X \longrightarrow X$ be a compact linear operator and $S: X \longrightarrow X$ a bounded linear operator on a normed space $X$. Then TS and ST are compact.

For every nonzero eigenvalue which a
compact linear operator may (or may not) have the eigenspace is finite
dimensional. Indeed, this is implied by

> **Theorem (Null space)**. Let $T: X \longrightarrow X$ be a compact linear operator on a normed space $X$. Then for every $\lambda \neq 0$ the null space $\mathcal{N}\left(T_\lambda\right)$ of $T_\lambda=T-\lambda I$ is finite dimensional.

> **Theorem (Range)**. Let $T: X \longrightarrow X$ be a compact linear operator on a normed space $X$. Then for every $\lambda \neq 0$ the range of $T_\lambda=T-\lambda I$ is closed.

