![[Genetic engineering]]

**Polymerase chain reaction** (PCR) is a technique for <span class="hi-green">replicating specific DNA sequences <u>outside cells</u></span>. A small amount of DNA sample can be <span class="hi-blue">amplified</span> to many copies quickly and accurately.

# Components
- **DNA template**: Sample of target DNA sequence to be amplified.

- **Primers**: Short sequences of synthetic single-stranded DNA <span class="hi-green">complementary to one end of the target sequence</span>.
	- Binds to <span class="hi-green">one end of the target sequence</span> to mark the point where the synthesis of a new DNA strand starts.
	- Two different primers are needed, as a DNA template consists of <span class="hi-green">two strands</span>.
	- The target sequence to be amplified is <span class="hi-blue">'bracketed'</span>.

- **Heat-stable DNA polymerase**: An enzyme that synthesizes new DNA strands by <span class="hi-green">joining adjacent nucleotides</span>.
	- The *Taq* DNA polymerase is commonly used as it can withstand high temperature required during PCR.

- **Nucleotides** (dNTP; deoxynucleotide triphosphate): Building blocks of new DNA strands.

# Process
```mermaid
flowchart LR
A[Denaturation];
B[Primer annealing];
C[Extension];
A --> B;
B --> C;
```

1. **Denaturation**
   Heat the reaction mixture (to about 95°C) to cause <span class="hi-green">DNA double helix to unwind and separate into two single strands</span>.

2. **Primer annealing**
   Cool the reaction mixture (to between 50°C and 65°C) to <span class="hi-green">allow primers to anneal to the single-stranded DNA</span> by <span class="hi-blue">complementary base pairing</span> to each end of the DNA strands.
   ```
   5'-GATCTGACTGATGCGTATGCTAGT-3'
               (primer 2) ATCA
   
      GATC (primer 1)
   3'-CTAGACTGACTACGCATACGATCA-5'
   ```

3. **Extension**
   <span class="hi-green">Raise the temperature</span> (to about 70°C) for <span class="hi-blue">DNA polymerase</span> to catalyse the <span class="hi-green">synthesis of new DNA strands</span>.
   ```
   5'-GATCTGACTGATGCGTATGCTAGT-3'
                  ...ATACGATCA
   
      GATCTGACT...
   3'-CTAGACTGACTACGCATACGATCA-5'
   ```

At the end of each cycle of PCR, the number of DNA strands is <span class="hi-green">doubled</span>.

> [!tip] Cycling of PCR
> Cycling of PCR can be performed automatically in a <span class="hi-blue">thermal cycler</span> by setting programmes to alter the number of PCR cycles performed, and the temperature and duration for the different stages of a cycle.
> 
> The amplified DNA fragments have to be <span class="hi-green">purified</span> before they are used for other purposes.

# Applications
- Crime scene investigation
- Prenatal diagnosis of genetic diseases
- Detection of infectious diseases
- Archaeological studies for ancient organic remains
