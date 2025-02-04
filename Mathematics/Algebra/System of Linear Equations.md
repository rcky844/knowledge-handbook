$$
\left\{ \begin{aligned} 
  a_1x + b_1y + c_1z = d_1 \\
  a_2x + b_2y + c_2z = d_2 \\
  a_3x + b_3y + c_3z = d_3
\end{aligned} \right.
$$

*Exclusive conclusions of a linear system*:
- No solution
- Unique solution
- Infinitely many solutions

*Consistency*:
- **Consistent**: At least one solution
- **Inconsistent**: No solution

# Determining unique solution
$$
\Delta =
\begin{vmatrix}
	a_1 & b_1 & c_1 \\
	a_2 & b_2 & c_2 \\
	a_3 & b_3 & c_3
\end{vmatrix}
$$
- For $\Delta \neq 0$, the system has unique solutions.
- For $\Delta = 0$, the system has no unique solution.

# Solving methods
## Matrix Method
> [!warning]
> Only applicable to linear systems with unique solutions.

$$
\begin{align}
& \left\{ \begin{aligned} 
  a_1x + b_1y + c_1z = d_1 \\
  a_2x + b_2y + c_2z = d_2 \\
  a_3x + b_3y + c_3z = d_3
\end{aligned} \right.
\Longrightarrow
\begin{bmatrix}
	a_1 & b_1 & c_1 \\
	a_2 & b_2 & c_2 \\
	a_3 & b_3 & c_3
\end{bmatrix}
\begin{bmatrix} x \\ y \\ z \end{bmatrix} = \begin{bmatrix} d_1 \\ d_2 \\ d_3 \end{bmatrix}
\\\\
& \Longrightarrow
\begin{bmatrix} x \\ y \\ z \end{bmatrix} =
\begin{bmatrix}
	a_1 & b_1 & c_1 \\
	a_2 & b_2 & c_2 \\
	a_3 & b_3 & c_3
\end{bmatrix}^{-1}
\begin{bmatrix} d_1 \\ d_2 \\ d_3 \end{bmatrix}
\end{align}
$$
## Cramer's Rule
> [!warning]
> Only applicable to linear systems with unique solutions.

$$
\begin{align}
& \text{Let}\;\Delta =
\begin{vmatrix}
	a_1 & b_1 & c_1 \\
	a_2 & b_2 & c_2 \\
	a_3 & b_3 & c_3
\end{vmatrix}
,\;\Delta_x =
\begin{vmatrix}
	{\color{red}d_1} & b_1 & c_1 \\
	{\color{red}d_2} & b_2 & c_2 \\
	{\color{red}d_3} & b_3 & c_3
\end{vmatrix}
,\;\Delta_y =
\begin{vmatrix}
	a_1 & {\color{red}d_1} & c_1 \\
	a_2 & {\color{red}d_2} & c_2 \\
	a_3 & {\color{red}d_3} & c_3
\end{vmatrix}
,\;\Delta_z =
\begin{vmatrix}
	a_1 & b_1 & {\color{red}d_1} \\
	a_2 & b_2 & {\color{red}d_2} \\
	a_3 & b_3 & {\color{red}d_3}
\end{vmatrix}
\\\\
& \text{Then}\;
x={\Delta_x\over\Delta},\;y={\Delta_y\over\Delta},\;z={\Delta_z\over\Delta}
\end{align}
$$

## Elimination
$$
\begin{align}
& \left\{ \begin{aligned} 
  a_1x + b_1y + c_1z = d_1 \quad \dots (1) \\
  a_2x + b_2y + c_2z = d_2 \quad \dots (2) \\
  a_3x + b_3y + c_3z = d_3 \quad \dots (3) 
\end{aligned} \right.
\Longrightarrow
\left\{ \begin{aligned} 
  p_1y + q_1z = r_1 \quad \dots (4) \\
  p_2y + q_2z = r_2 \quad \dots (5)
\end{aligned} \right.
\Longrightarrow hz = k
\end{align}
$$

| No solution | Unique solution | $\infty$ solution |
| :--: | :--: | :--: |
| $h=0$ | $h\neq0$ | $h=0$ |
| $k\neq0$ | | $k=0$ |
| $\Delta=0$ | $\Delta\neq0$ | $\Delta=0$ |

Then, let one of the variables to be a real number $t$ and solve the linear system.

*Homogeneous system*:
In a homogeneous system, there are at least one solution $(0,0,0)$. In $hz=k$, $k=0$.
- **Unique solution**: Only trivial solution $(0,0,0)$.
- **Infinitely many solutions**: Has non-trivial solution.
