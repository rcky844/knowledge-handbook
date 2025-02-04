# Projection on lines
![[vector_projection_line.webp|300]]

*Calculation*:
$$
\newcommand{\vectorproj}[2][]{\textit{proj}_{#1}#2}
\vectorproj[\vec{v}]{\vec{u}} = \frac{\vec{u}\cdot\vec{v}}{|\vec{v}|^2} \vec{v}
$$

# Projection on planes
![[vector_projection_plane.webp|250]]

> [!tip]
> $\vec{u}$ is usually not known to us! The projection vector $\vec{z_{||}}$ needs is found by first finding the projection onto normal vector $\vec{n}$, then $\vec{z_{||}}$ can be calculated through additions.

*Calculation*:
$$
\newcommand{\vectorproj}[2][]{\textit{proj}_{#1}#2}

\array{
\vectorproj[\hat{n}]{\vec{z}} = \frac{\vec{z} \cdot \hat{n}}{|\hat{n}|^2} \hat{n} \\
\vec{z_{||}} = \vec{z} - \vectorproj[\hat{n}]{\vec{z}} \\
}
$$
