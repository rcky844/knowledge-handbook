**Substitution reaction** is a reaction that involves the replacement of an atom (or a group of atoms) of an organic molecule by another atom (or groups of atoms).

# Alkanes
## Reaction with halogens
> [!callout | noicon] alkane → haloalkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{F2 / Cl2 / Br2 / I2}</span> dissolved in organic solvent</td></tr><tr><th>Condition:</th><td>Under sunlight (<span class="math display">h\nu</span>) / heating</td></tr><tr><th>Observations:</th><td>Colour changes <span class="hi-green">slowly</span> (compared to addition reaction)</td></tr><tr><th>Application:</th><td><a href="Testing for alkanes and alkenes" class="internal-link">Testing for alkanes and alkenes</a></td></tr></table>

![[substitution_alkane_halogen.webp|500]]

*Steps of substitution* (free radical process):
1. **Initiation** (Production of free radicals)
```tikz
\usepackage{chemfig}
\begin{document}
\chemname
	{\chemfig{@{a}Cl-[@{c}]@{b}Cl}}
	{\color{green}(homolytic clevage)}
\hspace*{-1.45cm}
\chemmove{
	\draw(c).. controls +(100:5mm) and +(75:5mm).. (a);
	\draw(c).. controls +(80:5mm) and +(105:5mm).. (b);
}
\hspace*{1.45cm}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[$h\nu$]}\schemestop}\quad
\chemname
	{\chemfig{\lewis{0.,Cl}} \quad + \quad \chemfig{\lewis{4.,Cl}}}
	{{\color{green}(free radicals)}\\{\color{red}(very unstable)}}
\end{document}
```
 
2. **Propagation**
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-@{a}C(-[2]H)(-[6]H)-[@{c}]@{b}H}
\hspace*{-2.45cm}
\chemmove{
	\draw(c).. controls +(100:5mm) and +(75:5mm).. (a);
	\draw(c).. controls +(80:5mm) and +(105:5mm).. (b);
}
\hspace*{2.45cm}
\quad + \quad
\chemfig{\lewis{4.,Cl}}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-\lewis{0.,C}(-[2]H)(-[6]H)}
\quad + \quad
\chemfig{H-Cl}
\end{document}
```
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-\lewis{0.,C}(-[2]H)(-[6]H)}
\quad + \quad
\chemfig{@{a}Cl-[@{c}]@{b}Cl}
\hspace*{-1.45cm}
\chemmove{
	\draw(c).. controls +(100:5mm) and +(75:5mm).. (a);
	\draw(c).. controls +(80:5mm) and +(105:5mm).. (b);
}
\hspace*{1.45cm}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2]H)(-[6]H)-Cl}
\quad + \quad
\chemfig{\lewis{0.,Cl}}
\end{document}
```

3. **Termination**
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-\lewis{0.,C}(-[2]H)(-[6]H)}
\quad + \quad
\chemfig{\lewis{4.,Cl}}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2]H)(-[6]H)-Cl}
\end{document}
```

- To prevent forming molecules with more of its atoms substituted, use <u>large excess amount of hydrocarbons</u>. It should be controlled with the mole ratio between hydrocarbons and $\ce{Cl2}$ molecules.
- The free radical substitution process is a [[Redox Reactions, Chemical Cells and Electrolysis|redox reaction]].

## Substitution with $\ce{OH-}$
![[alcohol_sub_oh.webp|400]]

> [!callout | noicon] haloalkane → alcohol
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Dilute <span class="math display">\ce{NaOH / KOH}</span></td></tr><tr><th>Condition:</th><td>Heating (increase the rate of reaction)</td></tr></table>

*Rate of reaction of the haloalkane*:
$\ce{C-I}$ > $\ce{C-Br}$ > $\ce{C-Cl}$ > $\ce{C-F}$

# Alcohol
## Substitution with $\ce{X-}$
### By $\ce{H-X}$
$\ce{R-OH + HCl -> R-Cl + H2O}$

> [!callout | noicon] alcohol → haloalkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Conc. <span class="math display">\ce{HCl / HBr / HI}</span></td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>

### By $\ce{PX3}$
$\ce{3R-OH + PCl3 -> 3R-Cl + H3PO4}$

> [!callout | noicon] alcohol → haloalkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Conc. <span class="math display">\ce{PCl3 / PBr3 / PI3}</span></td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>
