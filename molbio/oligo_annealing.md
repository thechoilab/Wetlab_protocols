# Protocol for oligo annealing/phosphorylation

#### <u>Purpose</u>:

To anneal/phosphorylate oligos for cloning sgRNAs or shRNAs.

---
#### <u>Materials needed</u>:
| Item | Company | Cat. No. |
| ---- | ------- | -------- |
| T4 DNA ligase reaction buffer | NEB | B0202S |
| T4 PNK enzyme | NEB | M0201L |
| Oligonucleotides (100uM) | n/a | n/a |

---
#### <u>Protocol</u>:

**Important notes:**
- It is important to use **T4 DNA ligase buffer** (and NOT T4 PNK buffer which lacks the necessary ATP) in this reaction.

**Steps:**

1. Set up the reaction in PCR tubes as follows:

	*For annealing many pairs of oligos, it is recommended to first prepare a master mix of everything except the oligos.*

| Ingredient | Amount | Master Mix |
| ---- | ------- | -------- |
| Forward/sense oligo (100 &mu;M) | 1 &mu;L | omit |
| Reverse/antisense oligo (100 &mu;M) | 1 &mu;L | omit |
| 10X T4 DNA ligase reaction buffer | 1 &mu;L |  |
| T4 PNK enzyme | 0.5 &mu;L |  |
| Water | 6.5 &mu;L | |
| TOTAL | 10 &mu;L | (8 &mu;L per reaction) |



2. Place the tubes in a thermocycler and run the following program:

  ie. 'CRISPRAnneal' or 'OligoAnneal' program

  **Step 1**: 37&deg;C x 30 min
  **Step 2**: 14 cycles of 95&deg;C x 1 min, with Autodelta (Starting cycle 2, Delta temp = -5&deg;C, Delta time = 0)
  **Step 3**: 25&deg;C x 1 min
  **Step 4**: 4&deg;C hold  
  
  

3. Prepare a dilution of each reaction 1:200 in water (ie. 2 &mu;L reaction + 398 &mu;L water) and store at -20&deg;C. You can discard the remaining undiluted reaction.

	*The diluted annealed oligos can be freeze-thawed many times without any significant loss in ligation efficiency.*
	
---
**References:**

1. See [Zhang Lab Addgene page](https://www.addgene.org/crispr/zhang/) for original cloning protocol.

