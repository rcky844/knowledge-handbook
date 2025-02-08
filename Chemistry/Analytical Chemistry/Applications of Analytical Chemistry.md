# Analysis of food and drugs
- Food colouring can be identified using [[Chromatography#Thin-layer chromatography (TLC)|thin-layer chromatography]] (TLC).
- Amount of food colouring can determined using [[colorimetry]].
- Amount of food additives can be determined using [[volumetric analysis]].

## Gas chromatography-mass spectrometry
**Gas chromatography-mass spectrometry** <span class="hi-blue">(GC-MS)</span> can be used to carry out detailed analysis of food and drugs.

*Example*: Content of $\ce{SO2}$ preservative
![[gc_ms.webp|600]]
- **Separation**: gas chromatography
- **Identification**: mass spectrometer

# Environmental protection
## Dioxins
**Dioxins** are emitted by [[combustion]] of <span class="hi-blue">materials containing chlorine</span> (e.g. PVC). They are <span class="hi-green">carcinogenic</span>.

```tikz
\usepackage{chemfig}
\begin{document}
% PCDDs
\chemname
	{\chemfig{*6((-Cl)-=*6(-O-*6(=-(-Cl)=(-Cl)-=?[a])-)-(-O?[a])=-(-Cl)=)}}
	{PCDDs}

\quad\quad

% PCDFs
\chemname
	{\chemfig{[:18]*6((-Cl)-=*5(-*6(=-(-Cl)=(-Cl)-=-=)--O-)-=-(-Cl)=)}}
	{PCDFs}
\end{document}
```

*Analytical methods*:
- Volumetric analysis
- Gas chromatography-mass spectrometry (GC-MS)

> [!tip]
> The dioxins in air are at low levels, [[instrumental methods]] (e.g. GC-MS) will be more accurate.

## Formaldehyde
**Formaldehyde** <span class="hi-blue">(methanal)</span> is a volatile organic compound (VOC) that is <span class="hi-green">irritant</span> and <span class="hi-green">carcinogenic</span>. Its level can be determined by [[colorimetry]].

*Source*:
- Wooden furniture or paint (as they use urea-formaldehyde as an adhesive)
- Added in paint to inhibit bacterial and fungal growth

## Carbon monoxide
*Pre-context: [[Combustion]]*

**Carbon monoxide** is a <span class="hi-green">poisonous</span> gas that mainly comes from <span class="hi-blue">incomplete combustion</span> of fossil fuels in car engines and power stations.

*Detection*:
- Level of carbon monoxide can be detected by <span class="hi-blue">infrared spectroscopy</span>.
- The intensity of the peak at around $\pu{2170 cm-1}$ for $\ce{C\bond{3}O}$ bond is proportional to the <span class="hi-green">concentration of $\ce{CO}$</span>.

# Forensic science
- Illicit <span class="hi-green">poisons and drugs</span> can be identified using [[#Gas chromatography-mass spectrometry|GC-MS]].
- <span class="hi-green">Flammable liquids</span> used in arson can be identified using [[mass spectrometry]] and [[infrared spectroscopy]].
- <span class="hi-green">Inks (mixture of various dyes)</span> on documents can be identified using [[Chromatography#Thin-layer chromatography (TLC)|thin-layer chromatography]].

## Breathalyzer
**Breathalyzer** can be used to detect the <span class="hi-blue">alcohol content</span> of a driver suspected of drunk-driving.

*Example*: HKDSE 2020 Paper 2 Q3(c)(i)
Road checking on ethanol intake of a driver can be done by having the <u>driver exhale a breath</u> into the tube as known below:
![[2020_p2_q3ci.webp|600]]

(1) Suggest the colour change of the silica gel soaked with acidified $\ce{K2Cr2O7(aq)}$ if enough ethanol-contained breath is exhaled into the tube. Write a half equation for the colour change involved.
$$
\underset{\text{orange}}{\ce{Cr2O7^2-(aq)}} \ce{->} \underset{\text{green}}{\ce{Cr^3+(aq)}}
$$


## Iodine sublimation on fingerprints
**Iodine sublimation** can be used to identify <span class="hi-blue">fingerprints</span>.

*Principle*:
- When a finger touches a surface, it leaves an <span class="hi-green">invisible pattern of oil (sebum)</span>.
- The suspected material is placed in a closed container with <span class="hi-orange">iodine crystals</span>, which is heated gently to cause iodine sublimation.
- Iodine vapour <span class="hi-green">dissolves in the grease of fingerprints</span> and make it coloured (usually brown).

> [!tip]
> 1% <span class="hi-blue">starch solution</span> can be sprayed onto the fingerprint to <span class="hi-green">prevent fading</span>.

# Clinical diagnosis
- [[Chromatography#Thin-layer chromatography (TLC)|Thin-layer chromatography]] can be used to give a preliminary test for <span class="hi-orange">urine, blood or tissue samples</span> from a person to <span class="hi-green">identify toxins</span>.
- [[Colorimetry]] can be used to determine the <span class="hi-green">concentrations</span> of certain substances in <span class="hi-orange">body fluids</span>.
- [[Mass spectrometry]] can be used to determine specific <span class="hi-green">proteins</span> present in cancer cells but not in normal cells, which helps development of drugs.
