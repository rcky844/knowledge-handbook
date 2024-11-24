**Electrolysis** is a chemical process in which electricity is supplied in order to force the redox reaction to occur, converting <span style="color: lightgreen">electrical energy to chemical energy</span>.
- The cell undergoing electrolysis is called <span style="color: skyblue">electrolytic cells</span>.

> [!warning] Attraction of ions between electrodes
> Since electricity is supplied intentionally, charges are created in the electrolytic cell. In the electrolyte, <span style="color: lightgreen">cations will be attracted towards the negative electrode, while anions will be attracted towards the positive electrode.</span>
> 
> However, this is not the case in chemical cells, as it involves the creation of charges by supply electricity to force reactions to occur.

**Basics of electrolysis**:
- The electrolytic cell must be connected to an <span style="color: skyblue">electricity supply</span> (e.g. chemical cell, battery or D.C. supply), with the positive terminal connected to the positive electrode, and vice versa.

- When the electrolysis process involves <span style="color: aqua">aqueous solutions</span>, consider the <span style="color: skyblue">self-ionization of water</span>: $\ce{H2O(ℓ) <=> H+(aq) + OH-(aq)}$

> [!warning] Types of electrolytes
> Aqueous electrolytes contain water, so the self-ionization of water is considered. However, <span style="color: lightgreen">water will not be present in molten electrolytes</span>. The mobile ions in the molten electrolyte will be in <span style="color: aqua">liquid state</span>.

#### Basic process
Consider the <span style="color: violet">electrolysis of molten lead(II) bromide</span> using <span style="color: skyblue">graphite electrodes</span>:
![[electrolysis_molten_pbbr2.webp|700]]

<span style="color: aqua">Solid</span> lead(II) bromide is heated in the <span style="color: skyblue">crucible</span> until it turns molten.
- **Ions present**: $\ce{Pb^2+(ℓ)}$, $\ce{Br^-(ℓ)}$
- **At cathode**: $\ce{Pb^2+(ℓ) + 2e- -> Pb(ℓ)}$
- **At anode**: $\ce{2Br^-(ℓ) -> Br2(ℓ) + 2e-}$
- **Overall equation**: $\ce{PbBr2(ℓ) -> Pb(ℓ) + Br2(ℓ)}$

#### Selection of electrodes
**Reactive electrodes**: (e.g. $\ce{Cu(s)}$)
- These electrodes <span style="color: lightgreen">may participate in the reaction</span>, so they should be considered when determining the electrolysis process.

**Inert electrodes**: (e.g. platinum, graphite)
- These electrodes <span style="color: lightgreen">do not participate in the reaction</span>.

> [!warning] Usage of platinum
> - <span style="color: lightgreen">Platinum electrodes are readily attacked by halogens and halide ions</span>, they must not be used for such reactions.

#### Factors affecting preferential discharge
##### ECS position of ions
*Pre-context: [[Electrochemical series]]*

**Examples**:
- [[Electrolysis of very dilute sodium chloride solution]]
	- [[Hoffman voltameter]]
- [[Electrolysis of dilute copper(II) sulphate solution]]

##### Concentration of ions
> [!warning]
> - This factor mainly affect the <u>discharge of anions</u>.
> - Specifically, $\ce{Cl-(aq)}$, $\ce{Br-(aq)}$  and $\ce{I-(aq)}$.

```mermaid
flowchart TD
X[ECS Position];
Y[Concentration effect];

A[very dilute] --> X;
B[dilute] --> Y;
C[concentrated] --> Y;
```
- In a <span style="color: lightgreen">very dilute</span> solution, the <span style="color: violet">anions have concentration lower than hydroxide ions</span>, so they are discharged according to the ECS position.
- In a <span style="color: lightgreen">dilute or concentrated</span> solution, the <span style="color: violet">anions have concentration higher than hydroxide ions</span>, so the <span style="color: aqua">anions are preferentially discharged</span>.

**Examples**:
- [[Electrolysis of concentrated sodium chloride solution]]

##### Nature of electrodes
###### Anodes
When <span style="color: violet">copper or metals higher in the ECS</span> (higher than hydroxide ion) are used an <span style="color: aqua">anode</span>, they are preferentially discharged to give metal ions.

> [!warning]
> - When copper is used as a cathode, it will not be discharged as copper cannot be reduced further.
> - <span style="color: lightgreen">Lithium, potassium, calcium and sodium cannot be used as an electrode</span>, as they would react with water readily.

**Examples**:
- [[Carbon-copper electrode electrolysis]]

###### Cathodes
When <span style="color: violet">mercury</span> is used as the <span style="color: aqua">cathode</span> in electrolysis of concentrated sodium chloride solution, it <span style="color: lightgreen">favours the discharge of sodium ion</span>.

**Examples**:
- [[Electrolysis of sodium chloride solution with mercury]]
- [[Chloroalkali industry]]

#### Determination of Preferential Discharges
**Order for determination**:
```mermaid
flowchart LR
X[ECS Position];
Y[Concentration effect];
Z[Nature of electrode];
Z --> Y --> X;
```

**Example**: HKDSE 2021 Paper 1B Q2
![[dse2021_1b_q2.webp|700]]

**Answer**:
![[dse2021_1b_q2_marking.webp|640]]

#### Industrial Applications of Electrolysis
1. [[Extraction of metals#Electrolysis of molten metal ore]]
2. [[Corrosion of aluminium#Anodization of aluminium objects]]
3. [[Protection of metals#Cathodic protection]]
4. [[Electroplating]]
