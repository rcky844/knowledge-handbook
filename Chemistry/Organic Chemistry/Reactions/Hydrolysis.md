**Hydrolysis** is a chemical reaction in which a compound is broken down by reaction with $\ce{H2O}$.

# Esters
## Acid hydrolysis
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-[@{cc}]O-R'}
\hspace*{-3.6cm}
{\color{green}\chemmove{
\draw[-,dashed,thick] ([yshift=2pt]cc) -- ++(0,1.5);
\draw[-,dashed,thick] ([yshift=-2pt]cc) -- ++(0,-1);
}}
\hspace*{3.6cm}
\quad + \quad
{\color{red}\chemfig{H-OH}}
\quad\raisebox{0.1cm}{\schemestart\arrow{<=>[$\chemfig{H^+}$][$\Delta$]}\schemestop}\quad
\chemfig{R-C(=[2]O)-{\color{red}OH}}
\quad + \quad
\chemfig{{\color{red}H}-O-R'}
\end{document}
```

> [!callout | noicon] ester ⇌ alkanoic acid + alcohol
> (<u>Reversible reaction</u>)
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Dilute acid (<span class="math display">\ce{HCl} / \ce{H2SO4}</span>)</td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>
> 
> *See also: [[Esterification]]*

## Alkaline hydrolysis
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-[@{cc}]O-R'}
\hspace*{-3.6cm}
{\color{green}\chemmove{
\draw[-,dashed,thick] ([yshift=2pt]cc) -- ++(0,1.5);
\draw[-,dashed,thick] ([yshift=-2pt]cc) -- ++(0,-1);
}}
\hspace*{3.6cm}
\quad + \quad
{\color{red}\chemfig{OH^{-}}(aq)}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[][$\Delta$]}\schemestop}\quad
\chemname
	{\chemfig{R-C(=[2]O)-{\color{red}O^{\ominus}}}}
	{{\color{green}(carboxylate ion)}\\{\color{red}soluble in water}}
\quad + \quad
\chemfig{{\color{red}H}-O-R'}
\end{document}
```
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-{\color{red}O^{\ominus}}}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[dil. $\chemfig{H^{+}}$(aq)]}[0,2]\schemestop}\quad
\chemfig{R-C(=[2]O)-{\color{red}O}-H}
\end{document}
```

> [!callout | noicon] ester ⇌ alkanoic acid + alcohol
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Dilute alkali (<span class="math display">\ce{NaOH}</span>)</td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>

# Amides
## Acid hydrolysis
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-[@{cc}]NH_2}
\hspace*{-2.95cm}
{\color{green}\chemmove{
\draw[-,dashed,thick] ([yshift=2pt]cc) -- ++(0,1.5);
\draw[-,dashed,thick] ([yshift=-2pt]cc) -- ++(0,-1);
}}
\hspace*{2.95cm}
\quad + \quad
{\color{red}\chemfig{H-OH}}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[$\chemfig{H^+}$][$\Delta$]}\schemestop}\quad
\chemfig{R-C(=[2]O)-{\color{red}OH}}
\quad + \quad
\chemfig{NH{_4}^{+}}
\end{document}
```

> [!callout | noicon] amide → alkanoic acid + ammonium ion
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Dilute alkali (<span class="math display">\ce{HCl} / \ce{H2SO4}</span>)</td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>

## Alkaline hydrolysis
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-[@{cc}]NH_2}
\hspace*{-2.95cm}
{\color{green}\chemmove{
\draw[-,dashed,thick] ([yshift=2pt]cc) -- ++(0,1.5);
\draw[-,dashed,thick] ([yshift=-2pt]cc) -- ++(0,-1);
}}
\hspace*{2.95cm}
\quad + \quad
{\color{red}\chemfig{OH^{-}}(aq)}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[][$\Delta$]}\schemestop}\quad
\chemfig{R-C(=[2]O)-{\color{red}O^{\ominus}}}
\quad + \quad
\chemfig{NH_3}
\end{document}
```
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-{\color{red}O^{\ominus}}}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[dil. $\chemfig{H^{+}}$(aq)]}[0,2]\schemestop}\quad
\chemfig{R-C(=[2]O)-{\color{red}O}-H}
\end{document}
```

> [!callout | noicon] amide → alkanoic acid + amine (/ ammonia)
> <table class="infobox-tables"><tr><th>Reagent:</th><td>Dilute alkali (<span class="math display">\ce{NaOH}</span>)</td></tr><tr><th>Condition:</th><td>Under reflux</td></tr></table>
