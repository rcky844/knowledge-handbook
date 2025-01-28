![[redox_alcohol.webp|450]]

# Oxidation
![[alcohol_oxidation_reflux.webp|350]]

> [!callout | noicon] alcohol → aldehyde → alkanoic acid<br>alcohol → ketone
> <table class="infobox-tables"><tr><th>Reagent:</th><td><span class="math display">\ce{Na2Cr2O7 / H+}</span></td></tr><tr><th>Condition:</th><td>Heat / Under reflux</td></tr><tr><th>Observations:</th><td>Orange (<span class="math display">\ce{Cr2O7^2-}</span>) → Green (<span class="math display">\ce{Cr^3+}</span>)</td></tr></table>

*For 1° alcohol*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(-[2]H)(-[6]H)-OH}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[[O]]}\schemestop}\quad
\chemname
	{\chemfig{R-C(=[2]O)-H}}
	{\color{green}aldehyde}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[[O]]}\schemestop}\quad
\chemname
	{\chemfig{R-C(=[2]O)-OH}}
	{\color{green}carboxylic acid}
\end{document}
```
↪️ **Application**: breathalyser

*For 2° alcohol*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(-[2]R')(-[6]H)-OH}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[[O]]}\schemestop}\quad
\chemname
	{\chemfig{R-C(=[2]O)-R'}}
	{\color{green}ketone}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[[O]]}\schemestop}\quad
\color[RGB]{0,183,235}No reaction!
\end{document}
```

*For 3° alcohol*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(-[2]R')(-[6]R'')-OH}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[[O]]}\schemestop}\quad
\color[RGB]{0,183,235}No reaction!
\end{document}
```

# Reduction (aldehydes & ketones)
![[reduction_alc.webp]]

> [!callout | noicon] aldehyde → alcohol<br>ketone → alcohol
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Lithium aluminium hydride (<span class="math display">\ce{LiAlH4}</span>) / dry ether; or<br>Sodium borohydride <span class="math display">\ce{NaBH4}</span>) / <span class="math display">\ce{H2O}</span></td></tr><tr><th>Condition:</th><td>Treated with dilute acid (<span class="math display">\ce{H+}</span>) after addition of the reagent</td></tr></table>

*Reason for addition of dry ether*:
$\ce{LiAlH4}$ reacts vigorously with water.

# Reduction (carboxylic acid)
![[reduction_acid.webp|400]]

> [!callout | noicon] alkanoic acid → alcohol
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Lithium aluminium hydride (<span class="math display">\ce{LiAlH4}</span>) / dry ether</td></tr><tr><th>Condition:</th><td>Treated with dilute acid (<span class="math display">\ce{H+}</span>) after addition of the reagent</td></tr></table>

> [!tip]
> $\ce{NaBH4}$ is a weaker R.A. than $\ce{LiAlH4}$, it is not able to reduce carboxylic acids.
