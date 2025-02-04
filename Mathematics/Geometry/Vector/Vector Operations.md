# Basic operations
*Finding unit vector*:
$$\hat{v} = {\vec{v}\over|\vec{v}|}$$

# Scalar ('Dot') Product
```tikz
\usepackage{tikz}
\begin{document}
	
\begin{tikzpicture}
	% Define two vectors
	\coordinate (A) at (0,0);
	\coordinate (B) at (1.5,3); % vec{v}
	\coordinate (C) at (4,0.5); % vec{w}
	
	% Draw vectors
	\draw[thick, red, ->] (A) -- (B) node[red, below right] at (B) {$\vec{v}$};
	\draw[thick, teal, ->] (A) -- (C) node[teal, below right] at (C) {$\vec{w}$};
	
	% Draw the angle between the vectors
	\node[teal, above=10, right=10] at (A) {$\theta$};
	
	% Add description
	\node[draw, below=20, right=10] at (A) {acute angle, $\vec{v}\cdot\vec{w} > 0$};
\end{tikzpicture}

\qquad\qquad

\begin{tikzpicture}
	% Define two vectors
	\coordinate (A) at (0,0);
	\coordinate (B) at (-0.5,3); % vec{v}
	\coordinate (C) at (4,0.5); % vec{w}
	
	% Draw vectors
	\draw[thick, red, ->] (A) -- (B) node[red, below right] at (B) {$\vec{v}$};
	\draw[thick, teal, ->] (A) -- (C) node[teal, below right] at (C) {$\vec{w}$};
	
	% Draw the angle between the vectors
	\node[teal, above=15, right=5] at (A) {$\theta$};
	
	% Add description
	\node[draw, below=20, right=10] at (A) {right angle, $\vec{v}\cdot\vec{w} = 0$};
\end{tikzpicture}

\qquad

\begin{tikzpicture}
	% Define two vectors
	\coordinate (A) at (0,0);
	\coordinate (B) at (-2,2); % vec{v}
	\coordinate (C) at (4,0.5); % vec{w}
	
	% Draw vectors
	\draw[thick, red, ->] (A) -- (B) node[red, above right] at (B) {$\vec{v}$};
	\draw[thick, teal, ->] (A) -- (C) node[teal, below right] at (C) {$\vec{w}$};
	
	% Draw the angle between the vectors
	\node[teal, above=15, right] at (A) {$\theta$};
	
	% Add description
	\node[draw, below=20, right=10] at (A) {obtuse angle, $\vec{v}\cdot\vec{w} < 0$};
\end{tikzpicture}

\end{document}
```
*Calculation*: $\vec{v}\cdot\vec{w} = |\vec{v}||\vec{w}|\cos{\theta}$ (= real number)

*Properties*:
- $|\vec{v}\cdot\vec{w}| = |\vec{v}| |\vec{w}|$ (for two parallel vectors)

# Vector ('Cross') Product
```tikz
\usepackage{tikz}
\begin{document}
\begin{tikzpicture}
\draw[-,fill=white!95!red](0,0)--(3,0)--(4,1)--(1,1)--cycle;
\node at (2,0.5) {$|\textcolor{blue}{a}\times \textcolor{red}{b}|$};
\draw[ultra thick,-latex,blue](0,0)--(3,0)node[midway,below]{$a$};
\draw[ultra thick,-latex,red](0,0)--(1,1)node[midway,above]{$b$};
\draw[ultra thick,-latex,blue!50!red](0,0)--(0,3)node[pos=0.7,right]{$a\times b$};
\draw (0.6,0) arc [start angle=0,end angle=45,radius=0.6]
node[pos=0.7,right]{$\theta$};
\end{tikzpicture}
\end{document}
```

*Properties*:
- $|\vec{v} \times \vec{w}| = |\vec{v}||\vec{w}|\sin{\theta}$ (= real number)
- $|\vec{v} \times \vec{w}| = |\vec{v}||\vec{w}|$ (for two perpendicular vectors)

> [!tip]
> The vector product is a <span class="hi-blue">normal vector</span> that is <span class="hi-green">perpendicular</span> to the two vectors from which it is calculated.
