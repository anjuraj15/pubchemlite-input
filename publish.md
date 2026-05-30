<!-- Title of the deposition. -->
# PubChemLite for Exposomics

<!-- Description: Level two heading under which follows the
description text. -->
## Description

This is the repository for regular updates of the PubChemLite for Exposomics data collection. PubChemLite for Exposomics is a subset of
[PubChem](https://pubchem.ncbi.nlm.nih.gov/) selected from major
categories of the 
[Table of Contents](https://pubchem.ncbi.nlm.nih.gov/classification/#hid=72)
page at the PubChem Classification Browser, described in 
DOI:[10.1186/s13321-021-00489-0](https://doi.org/10.1186/s13321-021-00489-0). 

PubChemLite for Exposomics is compiled from 10 categories:
AgroChemInfo, BioPathway, DrugMedicInfo, FoodRelated, PharmacoInfo,
SafetyInfo, ToxicityInfo, KnownUse, DisorderDisease, Identification. 

PubChemCIDs have been collapsed by InChIKey first block, reporting the
structure from the most annotated CID, plus related CIDs. Entries that
will be ignored by MetFrag (salts, disconnected substances) or cause
errors (e.g. transition metals) have been removed. The Patent and
PubMed ID counts are extracted from files on the PubChem FTP site. The
`AnnoTypeCount' term counts how many of the categories are represented, the
subsequent column (named per category) counts the number of annotation
categories available in the next sub-category of the TOC entry.

These files can be used `as is' as localCSV for
[MetFrag](https://ipb-halle.github.io/MetFrag/) Command Line.

<!-- Creators: Level three headings containing an author's name. Under
the heading, a key-value list such as: 
### Doe, John

- `affiliation` Independent Scientists Unlimited
- `orcid` 0000-0000-0000-0000


The list item sign `-' should be at the beginning of the line.  -->
## Creators

### Bolton, Evan
- `affiliation` NIH/NLM/NCBI
- `orcid` 0000-0002-5959-6190
	
### Schymanski, Emma
- `affiliation` LCSB, University of Luxembourg
- `orcid` 0000-0001-6868-8145

### Kondic, Todor
- `affiliation` LCSB, University of Luxembourg
- `orcid` 0000-0001-6662-4375

### Thiessen, Paul
- `affiliation` NIH/NLM/NCBI
- `orcid` 0000-0002-1992-2086

### Zhang, Jian (Jeff)
- `affiliation` NIH/NLM/NCBI
- `orcid` 0000-0002-6192-4632


<!-- Contributors: Level three headings containing an contributor's
name. Under the heading, a key-value list such as:
### Doe, John

- `affiliation` Independent Scientists Unlimited
- `orcid` 0000-0000-0000-0000
- `type` Distributor

The `type` item should be one of Zenodo's contributor types.

The list item sign `-' should be at the beginning of the line.  -->
## Contributors

<!-- Similar to `Description' heading. -->
## Notes

These files can be used "as is" for MetFrag (command line) and other 
high throughput workflows.

Please do **NOT** *upload* these files directly to the MetFrag web
interface, they are too large. The latest updates 
will be available in a drop-down menu.

<!-- References as a list.  -->
## References

- Schymanski, E.L., Kondić, T., Neumann, S. et al. Empowering large chemical knowledge bases for exposomics: PubChemLite meets MetFrag. J Cheminform 13, 19 (2021). https://doi.org/10.1186/s13321-021-00489-0

<!-- Related identifiers similar to contributors...  -->
## Related identifiers

### PubChem
- `identifier` https://pubchem.ncbi.nlm.nih.gov/
- `relation` isDerivedFrom

### PubChem TOC
- `identifier` https://pubchem.ncbi.nlm.nih.gov/classification/#hid=72
- `relation` isDerivedFrom

### MetFrag
- `identifier` https://msbi.ipb-halle.de/MetFrag/
- `relation` isSupplementTo

### PCL Paper
- `identifier` https://doi.org/10.1186/s13321-021-00489-0
- `relation` isSupplementTo


<!-- Communities as a list. -->
## Communities
- lcsb-eci


<!-- Keywords as a list. -->
## Keywords

- PubChem
- non-target screening
- non-target identification
- MetFrag
- exposomics
- exposome
- PubChemLite

<!-- Single number  -->
## Major Version
1

<!-- cc0, cc-by, cc-by-sa,... -->
## License
cc-by

<!-- open, restricted, closed -->
## Access Right
open

<!-- Must be present if `Access Right' is `restricted' -->
<!-- ## Access Conditions -->
<!-- Ask me _nicely_. -->
