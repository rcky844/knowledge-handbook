# Substitution of $\ce{-OH}$
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-OH}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[$\chemfig{SOCl_2 / PCl_3 / PCl_5}$]}[0,2]\schemestop}\quad
\chemfig{R-C(=[2]O)-Cl}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[$\chemfig{NH_3}$]}[0,2]\schemestop}\quad
\chemfig{R-C(=[2]O)-NH_2}
\quad + \quad
\chemfig{HCl}
\end{document}
```

> [!callout | noicon] alkanoic acid → amide
> <table class="infobox-tables"><tr><th>Reagent:</th><td>thionyl chloride (<span class="math display">\ce{SOCl2}</span>) / <span class="math display">\ce{PCl3}</span> / <span class="math display">\ce{PCl5}</span><br>ammonia, <span class="math display">\ce{NH3 (aq)}</span></td></tr></table>

# Direct substitution
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[2]O)-OH}
\quad\raisebox{0.1cm}{\schemestart\arrow{->[$\chemfig{NH_3}$][$\Delta$]}\schemestop}\quad
\chemfig{R-C(=[2]O)-NH_2}
\end{document}
```

> [!callout | noicon] alkanoic acid → amide
> <table class="infobox-tables"><tr><th>Reagent:</th><td>ammonia, <span class="math display">\ce{NH3 (aq)}</span></td></tr><tr><th>Condition:</th><td>Heating</td></tr></table>
