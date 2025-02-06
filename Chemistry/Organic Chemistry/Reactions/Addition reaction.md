**Addition reaction** is a reaction in which two or more molecules are <span class="hi-green">joined together</span> to form a single product <span class="hi-green">without the elimination of small molecules</span>.

# Halogenation (Reaction with halogens)
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-[5,.8])(-[3,.8])=[,.7]C(-[1,.8])(-[7,.8])}
\quad + \quad
\chemfig{X_2}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{-C(-[2,.8])(-[6,.8]X)-C(-[2,.8])(-[6,.8]X)-}
\end{document}
```

> [!callout | noicon] alkene → haloalkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{F2 / Cl2 / Br2 / I2}</span> dissolved in organic solvent</td></tr><tr><th>Observations:</th><td>Colour changes <span class="hi-green">slowly</span> (compared to addition reaction)</td></tr><tr><th>Application:</th><td><a href="Testing for alkanes and alkenes" class="internal-link">Testing for alkanes and alkenes</a></td></tr></table>

# Addition of -OH
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-[5,.8])(-[3,.8])=[,.7]C(-[1,.8])(-[7,.8])}
\quad + \quad [O]
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{-C(-[2,.8])(-[6,.8,,1]OH)-C(-[2,.8,,1])(-[6,.8]OH)-}
\end{document}
```

> [!callout | noicon] alkene → diol
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{KMnO4 / H+}</span></td></tr><tr><th>Observations:</th><td>Colour changes from purple to very pale pink <span class="hi-green">rapidly</span>.</td></tr><tr><th>Application:</th><td><a href="Testing for alkanes and alkenes" class="internal-link">Testing for alkanes and alkenes</a></td></tr></table>

# Hydrogenation (Reaction with $\ce{H2}$)
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-[5,.8])(-[3,.8])=[,.7]C(-[1,.8])(-[7,.8])}
\quad + \quad
\chemfig{H_2}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[Pt / Pd / Ni][$\Delta$]}[0,2]\schemestop}\quad
\chemfig{H-C(-[2,.8]H)(-[6,.8]{\color{green}H})-C(-[2,.8,]H)(-[6,.8]{\color{green}H})-H}
\end{document}
```

> [!callout | noicon] alkene → alkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{H2(g)}</span></td></tr><tr><th>Conditions:</th><td>Finely divided <span class="math display">\ce{Pt / Pd / Ni}</span> + heating (150 ~ 200 °C)</td></tr></table>

# Halohydrogenation
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-[5,.8])(-[3,.8])=[,.7]C(-[1,.8])(-[7,.8])}
\quad + \quad
\chemfig{HX}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2,.8]H)(-[6,.8]{\color{green}H})-C(-[2,.8,]H)(-[6,.8]{\color{green}X})-H}
\end{document}
```

> [!callout | noicon] alkene → haloalkane
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{HX}</span> (X: <span class="math display">\ce{F / Cl / Br / I}</span>)</td></tr></table>

*Markovnikov's rule*:
When a molecule of $\ce{HX}$ is added to an alkene, the hydrogen atom is added to the carbon atom of the carbon-carbon double bond that <u>already carries the larger number of hydrogen atoms</u>.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)=C(-[2]H)-H}
\quad + \quad
\chemfig{HBr}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemname
	{\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]{\color{green}Br})-C(-[2]H)(-[6]{\color{green}H})-H}}
	{major product}
\quad + \quad
\chemname
	{\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]{\color{green}H})-C(-[2]H)(-[6]{\color{green}Br})-H}}
	{minor product}
\end{document}
```
