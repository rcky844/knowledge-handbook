# With conc. $\ce{H2SO4}$
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{-C(-[2,.8]H)(-[6,.8])-C(-[2,.8,,1]OH)(-[6,.8])-}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[Conc. $\chemfig{H_2SO_4}$][180 C]}[0,2]\schemestop}\quad
\chemfig{-C(-[6,.8])=C(-[6,.8])-}
\end{document}
```

> [!callout | noicon] alcohol → alkene
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Conc. <span class="math display">\ce{H2SO4}</span> (ℓ) dissolved in organic solvent</td></tr><tr><th>Condition:</th><td>Under heating (180°C)</td></tr></table>

*Zaitzev’s Rule*:
The $\ce{H}$ atom of the $\ce{C}$ atom that has the least $\ce{H}$ atom attached is reacted.
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{-C(-[2,.8])(-[6,.8])-C(-[2,.8])(-[6,.8]H)-C(-[2,.8])(-[6,.8,,1]OH)-C(-[2,.8])(-[6,.8]{\color{green}H})-}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[Conc. $\chemfig{H_2SO_4}$][180 C]}[0,2]\schemestop}\quad
\chemname
	{\chemfig{-C(-[2])(-[6])-C(-[2])=C(-[2])-C(-[2])(-[6]{\color{green}H})-}}
	{major product}
\quad + \quad
\chemname
	{\chemfig{-C(-[2])(-[6])-C(-[2])(-[6]H)-C(-[2])=C(-[2])-}}
	{minor product}
\end{document}
```

# Catalytic dehydration
![[catalytic_dehydration.webp|400]]
- $\ce{Al2O3}$ acts as a catalyst to speed up the reaction.
