![[isomerism_diagram.webp|650]]

# Structural isomerism
Structural isomers all have the <span class="hi-green">same molecular formula</span>.

## Chain isomerism
**Chain isomers** are isomers that have the <span class="hi-green">same functional group</span> but <span class="hi-green">different carbon skeletons</span>. In general, they have <u>similar chemical properties</u> because they possess the <u>same functional group</u>.

*Examples*:
- Chain isomers of $\ce{C5H12}$
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{[:330]-[:30]-[:330]-[:30]-[:330]}
\qquad
\chemfig{[:330]-[:30](-[:90])-[:330]-[:30]}
\end{document}
```

## Position isomerism
**Position isomers** are isomers that have the <u>same carbon skeleton and functional group</u>. They <span class="hi-green">differ in the position of the functional group</span>. In general, they have similar chemical properties because they possess the same functional group.

*Examples*:
- Position isomers of $\ce{C5H12O}$
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{[:330]-[:30]-[:330]-[:30](-[2]OH)-[:330]}
\qquad
\raisebox{1.5em}{\chemfig{[:30]-[:330]-[:30](-[2]OH)-[:330]-[:30]}}
\end{document}
```

## Functional group isomerism
**Functional group isomers** are isomers that contain <span class="hi-green">different functional group</span>. They have <span class="hi-green">different chemical properties</span> as they have <u>different functional groups</u>.

*Examples*:
- Functional group isomers of $\ce{C4H10O}$
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{[:330]-[:30]-[:330]-[:30]-[:330]OH}
\qquad
\chemfig{[:330]-[:30]-[:330]O-[:30]-[:330]}
\end{document}
```

# Stereoisomerism
**Stereoisomers** are isomers that have the <span class="hi-green">same arrangement of atoms</span>, but have <span class="hi-green"><u>different spatial arrangement</u></span>.

## *Cis-trans* isomerism (geometric isomers)
***Cis-trans* isomers**, also **geometric isomers**, are isomers with different spatial arrangements due to the <u>restricted rotation</u> of $\ce{C=C}$ double bond.

```tikz
\usepackage{chemfig}
\begin{document}
\chemname
	{\chemfig{C(-[5]H)(-[3]{\color{green}Cl})=[,.7]C(-[1]{\color{green}Cl})(-[7]H)}}
	{\textit{\color{green}cis}-1,2-dichloroethene}
\qquad\qquad\qquad
\chemname
	{\chemfig{C(-[5]H)(-[3]{\color{green}Cl})=[,.7]C(-[1]H)(-[7]{\color{green}Cl})}}
	{\textit{\color{green}trans}-1,2-dichloroethene}
\end{document}
```

> [!tip] Chemical properties
> *Cis-trans* isomers show <u>similar (or the same) chemical properties</u> because they possess exactly the <u>same functional group</u>.
> ```tikz
> \usepackage{chemfig}
> \begin{document}
> \chemname
> 	{\chemfig{C(-[5]H)(-[3]HOOC)=[,.7]C(-[1]COOH)(-[7]H)}}
> 	{Polar molecule}
> \qquad\qquad\qquad
> \chemname
> 	{\chemfig{C(-[5]H@{})(-[3]HOOC)=[,.7]C(-[1]H)(-[7]COOH)}}
> 	{Non-polar molecule}
> \chemmove{
>      }
> \end{document}
> ```

> [!tip] Melting point and boiling point
> *Cis* isomers would have a higher boiling point than *trans* isomers.
> - This is because *cis* isomers are polar, while *trans* isomers are non-polar.
> - The van der Waals' force between *cis* molecules is stronger than that in *trans* molecules <u>in liquid state</u>.
> 
> *Trans* isomers would have a higher melting point than *cis* isomers.
> - This is because *trans* isomers have a higher packing efficiency than *cis* isomers.
> - The van der Waals' force between *trans* molecules is stronger than that in *cis* molecules <u>in solid state</u>.

## Enantiomerism
**Enantiomers** are two <u>non-identical molecules</u> with atoms or groups of atoms arranged in different positions.

*Properties*:
- Non-superimposable with mirror image
- Chiral
- No plane of symmetry

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{
  C
  ([::-45]<:OH)
  ([:-90]<H)
  ([::-135]-H_3C)
  ([:90]-CH_2CH_3)
}
\qquad\qquad\qquad
\chemfig{
  C
  ([::-45]-CH_3) 
  ([:-90]<H)
  ([::-135]<:HO)
  ([:90]-CH_2CH_3)
}
\end{document}
```
(* central C atom is the chiral centre)

> [!warning]
> Students are only required to identify enantiomers with one chiral centre. However, carbon compounds with more than one chiral centres may not exhibit enantiomerism.

**Enantiomers** are composed by the same atoms, they have the same molecular size and molecular polarity. Therefore, they have the <u>same physical properties</u>.

However, there are differences in their <u>interactions with polarized light (optical activity)</u>. This can be measured using a <span class="hi-blue">polarimeter</span>.
- **Rotates clockwise**: (+)-isomer
- **Rotates anticlockwise**: (-)-isomer

> [!tip]
> Enantiomers can rotate the plane of plane-polarized light in opposite directions.

They also have the <u>same chemical properties</u> as they have the same chemical bonds. They also have the <u>same standard enthalpy change of formation</u>.

