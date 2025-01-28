```tikz
\usepackage{chemfig}
\begin{document}
\chemname
	{\chemfig{R-C(=[2]O)-OH}}
	{alkanoic acid}
\quad + \quad
\chemname
	{\chemfig{H-O-R'}}
	{alcohol}
\quad\raisebox{0.1cm}{\schemestart\arrow{<=>[Conc. $\chemfig{H_2SO_4}$][$\Delta$]}[0,2]\schemestop}\quad
\chemname
	{\chemfig{R-C(=[2]O)-O-R'}}
	{ester}
\quad + \quad
\chemname
	{\chemfig{H_2O}}
	{water}
\end{document}
```

> [!callout | noicon] alkanoic acid → alcohol
> <table class="infobox-tables"><tr><th>Reaction:</th><td>alkanoic acid + alcohol ⇌ ester (Reversible reaction)</td></tr><tr><th>Reagent:</th><td>Conc. <span class="math display">\ce{H2SO4}</span></td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>

*Functions of the reagent*:
- **As a catalyst**
  Addition of sulphuric acid will <span class="hi-green">speed up the reaction</span> and therefore the equilibrium is achieved more quickly.

- **As a dehydrating agent**
  Sulphuric acid helps in <span class="hi-green">removing the water content</span> of the reaction, and shifts the equilibrium position to the product side.
