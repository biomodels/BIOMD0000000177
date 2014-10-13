

This a model from the article:  
**Increased glycolytic flux as an outcome of whole-genome duplication in yeast.**   
Conant GC, Wolfe KH _Mol. Syst. Biol._ [2007 ; Volume: 3 (Issue: )]: 129
[17667951](http://www.ncbi.nlm.nih.gov/pubmed/17667951) ,  
**Abstract:**   
After whole-genome duplication (WGD), deletions return most loci to single
copy. However, duplicate loci may survive through selection for increased
dosage. Here, we show how the WGD increased copy number of some glycolytic
genes could have conferred an almost immediate selective advantage to an
ancestor of Saccharomyces cerevisiae, providing a rationale for the success of
the WGD. We propose that the loss of other redundant genes throughout the
genome resulted in incremental dosage increases for the surviving duplicated
glycolytic genes. This increase gave post-WGD yeasts a growth advantage
through rapid glucose fermentation; one of this lineage's many adaptations to
glucose-rich environments. Our hypothesis is supported by data from enzyme
kinetics and comparative genomics. Because changes in gene dosage follow
directly from post-WGD deletions, dosage selection can confer an almost
instantaneous benefit after WGD, unlike neofunctionalization or
subfunctionalization, which require specific mutations. We also show
theoretically that increased fermentative capacity is of greatest advantage
when glucose resources are both large and dense, an observation potentially
related to the appearance of angiosperms around the time of WGD.

  
  

This model reproduces fig. 2C from the
[corrigendum](http://dx.doi.org/10.1038/msb.2008.46) to the publication  
The parameter **Vmax_PDH** was corrected by a factor 60 from 6.32 mM/min in
the publication to 379.2 mM/min in accordance with the authors.  
see the [corrigendum](http://dx.doi.org/10.1038/msb.2008.46) at msb or its
[pubmed entry (pmid:18594520)](http://www.ncbi.nlm.nih.gov/pubmed/18594520)

This model comprises the glycolysis model from Pritchard and Kell (2002) with
an extension for the metabolisation of pyruvate in the mitochondria by
pyruvate dehydrogenase and an additional parameter, **WGD_E** , to adjust for
the differing enzyme concentrations before the whole genome duplication (WGD).  
To switch off transport of pyruvate to the mitochondria, set the parameter
**t_m** = 0.  
Figure 2C from the article can be reproduced by manually changing the value of
parameter **WGD_E** in the range between 0.65 and 1.0 and calculating the
ratios of ratio of **PDC/PDH** fluxes in the altered model to the one of the
model with **WGD_E** = 1.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

