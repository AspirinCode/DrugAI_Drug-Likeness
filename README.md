# DrugAI_Drug-Likeness


## Requirements
```python
Python==3.7
RDKit==2020.09.1
```

## Drug-Likeness

### QED
**quantitative estimation of drug-likeness**

Bickerton, G., Paolini, G., Besnard, J. et al. Quantifying the chemical beauty of drugs. Nature Chem 4, 90–98 (2012). https://doi.org/10.1038/nchem.1243

### Rule of 5 : Lipinski
Molecular mass less than 500 Dalton

High lipophilicity (expressed as LogP less than 5)

Less than 5 hydrogen bond donors

Less than 10 hydrogen bond acceptors

Molar refractivity should be between 40-130

### Rule of 4
**“rule-of-four” (RO4) to evaluate PPI inhibitors**

MW must be higher than 400;

ALogP must be higher than 4;

HBA must be higher than 4;

The number of rings (RING) must be higher than 4.


### Rule of 3
**"Rule of Three (Ro3)" compliant fragments (fragment-likeness)**
Jhoti, H., Williams, G., Rees, D. et al. The 'rule of three' for fragment-based drug discovery: where are we now?. Nat Rev Drug Discov 12, 644 (2013). https://doi.org/10.1038/nrd3926-c1


### Ghose Filter
**This filter defines drug-likeness constraints as follows:**

calculated log P is between -0.4 and 5.6, 

molecular weight is between 160 and 480, 

molar refractivity  is between 40 and 130, 

total number of atoms is between 20 and 70.


### Veber Filter

The Veber filter is a rule of thumb filter for orally active drugs described in Veber et. al., J Med Chem. 2002; 45(12): 2615-23.


### REOS (Rapid Elimination Of Swill)
Walters, W., Namchuk, M. Designing screens: how to make your hits a hit. Nat Rev Drug Discov 2, 259–266 (2003). https://doi.org/10.1038/nrd1063
