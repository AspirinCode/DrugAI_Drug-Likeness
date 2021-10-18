# DrugAI_Drug-Likeness


## Requirements
```python
Python==3.7
RDKit==2020.09.1
```

Drug-Likeness

### QED
quantitative estimation of drug-likeness

Bickerton, G., Paolini, G., Besnard, J. et al. Quantifying the chemical beauty of drugs. Nature Chem 4, 90–98 (2012). https://doi.org/10.1038/nchem.1243

### Rule of 5 : Lipinski
Molecular mass less than 500 Dalton

High lipophilicity (expressed as LogP less than 5)

Less than 5 hydrogen bond donors

Less than 10 hydrogen bond acceptors

Molar refractivity should be between 40-130

### Rule of 4


### Rule of 3
"Rule of Three (Ro3)" compliant fragments (fragment-likeness)
Jhoti, H., Williams, G., Rees, D. et al. The 'rule of three' for fragment-based drug discovery: where are we now?. Nat Rev Drug Discov 12, 644 (2013). https://doi.org/10.1038/nrd3926-c1

### Ghose Filter

### REOS (Rapid Elimination Of Swill)
Walters, W., Namchuk, M. Designing screens: how to make your hits a hit. Nat Rev Drug Discov 2, 259–266 (2003). https://doi.org/10.1038/nrd1063
