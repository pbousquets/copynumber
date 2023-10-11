Copynumber with species agnostic pcf and aspcf
====================================
This repository is forked from:
https://github.com/Bioconductor-mirror/copynumber

And inherits changes carried out in https://github.com/sb43/copynumber/tree/feature/species_agnostic and https://github.com/Irrationone/copynumber. 

pcf and aspcf function now accepts user supplied cytoband file.

All the chromosomes are now referred by its index values.

Original chromosomes names were reassigned to index before returning the processed results.

Same logic can be applied to other functions wherever required.



