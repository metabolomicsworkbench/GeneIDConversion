# URLs to test The gene ID conversion tool

# Test on bdcw.org

## For REST API-based access to integrate in user’s existing tools:

URLs to use for json output with CLI (e.g., using [curl -L 'URL']; use /viewType/txt for text output):

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/AIM1/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/IFNB2/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3__IL6__KLF4/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3,IL6,KLF4,PTGS2/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/ENTREZID/GeneListStr/3710,10365,3592,5743/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095,NP_001300981/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/ENSEMBL/GeneListStr/ENSG00000136244/View/json

Please use __ (double underscore) or comma (,) to specify more than one gene, as in the string ITPR3__IL6__KLF4 or 3710,10365,3592,5743 in the example above. For SYMBOL like IDs, the user may specify  SYMBOL_OR_ALIAS for GeneIDType, so that the term will be first searched in SYMBOL and if not found then it will be searched in ALIAS.

By default, the above use R package for respective species. Some times, these R packages may not have the entite list of genes available at NCBI gene_info. Hence, we provide an option to incorporate information from NCBI gene_info as well (please note that this is an experimental feature and is currently being updated frequently). Use the parameter USE_NCBI_GENE_INFO/1/ before the View parameter in the REST URL. Some examples are given below.

### With explicit use of the parameter USE_NCBI_GENE_INFO/1/ before the View parameter in the REST URL:

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/AIM1/USE_NCBI_GENE_INFO/1/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3__IL6__KLF4/USE_NCBI_GENE_INFO/0/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/ENTREZID/GeneListStr/3710,10365,3592,5743/USE_NCBI_GENE_INFO/0/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095/USE_NCBI_GENE_INFO/1/View/json

https://bdcw.org/geneid/rest/species/hsa/GeneIDType/ENSEMBL/GeneListStr/ENSG00000136244/USE_NCBI_GENE_INFO/0/View/json

# Test on sc-cfdewebdev.sdsc.edu (intended for internal use)

## For REST API-based access to integrate in user’s existing tools:

URLs to use for json output with CLI (e.g., using [curl -L 'URL']; use /viewType/txt for text output):

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/AIM1/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/IFNB2/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3__IL6__KLF4/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3,IL6,KLF4,PTGS2/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/ENTREZID/GeneListStr/3710,10365,3592,5743/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095,NP_001300981/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/ENSEMBL/GeneListStr/ENSG00000136244/View/json

### With explicit use of the parameter USE_NCBI_GENE_INFO/1/ before the View parameter in the REST URL:

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/AIM1/USE_NCBI_GENE_INFO/1/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/SYMBOL_OR_ALIAS/GeneListStr/ITPR3__IL6__KLF4/USE_NCBI_GENE_INFO/0/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/ENTREZID/GeneListStr/3710,10365,3592,5743/USE_NCBI_GENE_INFO/0/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/REFSEQ/GeneListStr/NM_001318095/USE_NCBI_GENE_INFO/1/View/json

https://sc-cfdewebdev.sdsc.edu/geneid/rest/species/hsa/GeneIDType/ENSEMBL/GeneListStr/ENSG00000136244/USE_NCBI_GENE_INFO/1/View/json

