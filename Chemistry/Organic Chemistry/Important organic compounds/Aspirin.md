```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{*6(-=(-O-[0]C(=[6]O)-[0]CH_3)-(-C(=[2]O)-[0]OH)=-=)}
\end{document}
```
**Aspirin** (acetylsalicylic acid) is a common active ingredient found in <span class="hi-green">pain killers</span>. It has a <u>carboxyl group</u> ($\ce{-COOH}$) and <u>ester group</u> ($\ce{-OCOCH3}$).

# Production of Aspirin
![[aspirin_reaction.webp|600]]

# Uses of Aspirin
- Pain killer
- Reduce inflammation
- Lowers body temperature quickly if one has fever
- Prevent heart attack and strokes (as it thins the blood)

## Side effects
- Stomach upset & ulcers
- Increased bleeding

## Alternatives
*Paracetamol*:
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{*6((-HO)-=-(-N(-[2,.35,,,,draw=none]H)-[::-60](=[6]O)-)=-=)}
\end{document}
```

# Solubility of Aspirin
**Aspirin** is <span class="hi-green">non-polar</span> and only <span class="hi-green">slightly soluble</span> in water.

In order to make it work more quickly, it is reacted with $\ce{NaOH}$ to produce sodium salt of aspirin, which it has a giant ionic structure with ionic bond to dissolve inside stomach acid and get into the bloodstream more rapidly.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{*6(-=(-OCOCH_3)-(-COOH)=-=)}
\raisebox{0.4cm}{
\quad + \quad
\chemfig{NaOH}
\quad\raisebox{0.1cm}{\schemestart\arrow\schemestop}\quad
}
\chemfig{*6(-=(-OCOCH_3)-(-COO^{-}Na^{+})=-=)}
\raisebox{0.4cm}{
\quad + \quad
\chemfig{H_2O}
}
\end{document}
```

> [!warning]
> To not lose the chemical function of aspirin, the reaction mixture <u>will not be heated under reflux</u>. This prevents the alkaline hydrolysis of the ester group of aspirin.
