> [!note]
> Many of these tests may be duplicated in other sections, with this being a summary for all of these tests.

*Pre-context: [[Organic Chemistry]]*

# Tests for unsaturated carbon compounds
**Unsaturated carbon compounds** are compounds with $\ce{C=C}$ or $\ce{C≡C}$, it can be tested by addition / oxidative addition.

*Method 1*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)=C(-[2]H)-C(-[2]H)(-[6]H)-H}
\quad + \quad
\chemname
    {\chemfig{Br_2}}
    {(in \chemfig{CCl_4})}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]Br)-C(-[2]H)(-[6]Br)-C(-[2]H)(-[6]H)-H}
\end{document}
```
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)=C(-[2]H)-C(-[2]H)(-[6]H)-H}
\quad + \quad
\chemname
    {\chemfig{HOBr}}
    {(\chemfig{Br_2} (aq))}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]Br)-C(-[2]H)(-[6]OH)-C(-[2]H)(-[6]H)-H}
\end{document}
```
- Add $\ce{Br2(aq)}$ / $\ce{Br2}$ dissolved in organic solvent into sample.
- The solution turns <span class="hi-green">from brown to colourless</span>.

*Method 2*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)=C(-[2]H)-C(-[2]H)(-[6]H)-H}
\quad + \quad
\chemfig{H_2O}
\quad + \quad
[O]
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]OH)-C(-[2]H)(-[6]OH)-C(-[2]H)(-[6]H)-H}
\end{document}
```
- Add <span class="hi-blue">acidified</span> $\ce{KMnO4(aq)}$ into the sample.
- The solution turns <span class="hi-green">from purple to very pale pink / colourless</span>.

# Tests for hydroxyl group (-OH)
*Method 1*: (oxidation)
- Add <span class="hi-blue">acidified</span> $\ce{KMnO4(aq)}$ (or $\ce{Cr2O7^2-/H+(aq)}$) into the sample.
- The solution turns <span class="hi-green">from purple to very pale pink / colourless</span>.

> [!warning]
> - <span class="hi-blue">Primary alcohol and secondary alcohol</span> can be oxidized by oxidizing agents (e.g. $\ce{Cr2O7^2-/H+(aq)}$).
> - <span class="hi-blue">Tertiary alcohol</span> is <span class="hi-green">oxidation-resistant</span> and cannot react with oxidizing agents.

*Method 2*: ([[esterification]])
- Heat the sample with $\ce{CH3COOH(aq)}$ under the presence of concentrated $\ce{H2SO4(aq)}$ under reflux.
- A <span class="hi-green">fruity smell</span> (of the ester) is detected.

# Tests for carboxyl group (-COOH)
*Method 1*: (reaction with sodium hydrogencarbonate)
$$
\ce{2RCOOH + Na2CO3 -> 2RCOO^-Na^+ + H2O + CO2}
$$
- Add $\ce{NaHCO3(aq)}$ solution into the sample.
- Colourless gas bubble is given out.

*Method 2*: ([[esterification]])
- Heat the sample with $\ce{CH3CH2OH(aq)}$ under the presence of concentrated $\ce{H2SO4(aq)}$ under reflux.
- A <span class="hi-green">fruity smell</span> (of the ester) is detected.

# Tests for carbonyl group
**Carbonyl groups** are present in <span class="hi-green">aldehyde and ketones</span>. They can be tested with the chemical reagent <span class="hi-blue">2,4-dinitrophenylhydrazine</span>.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{[:-150]*6(-([,,,1]-NO_2)=(-N(-[2]H)-N(-[2]N)-H)-=-(-NO_2)=)}
\end{document}
```

*Details*:
- Add <span class="hi-blue">2,4-dinitrophenylhydrazine</span> into the sample.
- <span class="hi-green">Red / yellow / orange precipitate</span> (2,4-dinitrophenylhydrazone) is given out.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-[3]R)(-[5]R'\,or\,H)=O}\ \quad + \quad \raisebox{1cm}{\chemfig{[:-150]*6(-([,,,1]-NO_2)=(-N(-[2]H)-N(-[2]N)-H)-=-(-NO_2)=)}}
\quad\schemestart\arrow\schemestop\quad
\raisebox{1cm}{\chemfig{[:-150]*6(-([,,,1]-NO_2)=(-N(-[2]H)-N=C(-[3]R)(-[5]R'\,or\,H))-=-(-NO_2)=)}} \quad + \quad \chemfig{H_2O}
\end{document}
```

# Test for only aldehyde but not ketone
**Aldehydes** can be tested with <span class="hi-blue">Tollens' reagent</span>, a specific test.

*Production*:
$$
\begin{array} \\
\ce{2Ag+(aq) + 2OH-(aq) -> Ag2O(s) + H2O(ℓ)} \\
\ce{Ag2O(s) + H2O(ℓ) + 4NH3(aq) -> 2[Ag(NH3)2]+(aq) + 2OH-(aq)}
\end{array}
$$
- This is made by <span class="hi-green">dissolving silver nitrate solution into excess ammonia</span>.
- An alkaline solution of diamminesilver(I) ion is formed.

*Testing*:
$$
\ce{RCHO + 2[Ag(NH3)2]+ + 3OH- -> RCOO- + 2Ag + 4NH3 + 2H2O}
$$
- Heat sample (aldehyde) (<span class="hi-green">in a water bath</span>) with Tollens' reagent.
- A <span class="hi-blue">silver mirror</span> is formed.

*Problems*:
- Tollens' reagent is <span class="hi-green">explosive</span> (as it is a nitride).
  It is likely to explode on standing, so the reagent is prepared when needed.
