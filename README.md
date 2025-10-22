![Image](https://github.com/user-attachments/assets/fd267479-2b72-4e70-a1bb-d03ba321fb5d)
# ALFRED
ALFRED was conceived and developed by Prof. Kenneth K. Kidd and Dr. Judith R. Kidd &amp; Kidd Lab - Department of Genetics at Yale university. It provides allele frequency data on human population samples, for scientific research and educational use. It contains public data from literature and unpublished data from host and collaborators research.



ALFRED (The Allele Frequency Database), developed by Professor Kenneth K. Kidd and Dr. Judith K. Kidd at Yale’s Population Genetics Laboratory, is a pioneering resource funded by the NSF and NIJ. It contains over 54 million allele frequency tables for 664,437 polymorphisms across more than 750 anthropologically defined populations.
While similar databases exist—such as NCBI’s ALFA, dbGaP, the 1000 Genomes Project, and HapMap—ALFRED stands out for its broad population coverage, especially of understudied populations. Its user-friendly interface allows searches by chromosome, gene symbol, or dbSNP ID (rsnumber). Population samples are categorized by geographic region, subregion, and specific population, offering insights into human migration and diversity. ALFRED’s structure and display make it a valuable educational and reference tool, widely accessed for teaching and research. (Citation: PMID: 22039151; PMCID: PMC3245092)

### Data Organization
ALFRED contains both public data from literature and unpublished data from our host research laboratory and its collaborators. Over 95% of the polymorphisms in ALFRED have frequency data from more than 10 different populations. This is without considering the samples from different regions within the same population. An individual polymorphism (or Site) is contained within a locus on the genome. Ethnic populations are organized by their geographic location (Geographic_Region). Multiple samples may be drawn from a particular population. For such highly heterogeneous populations as African American or European American, special care is taken to delineate the specific geographic region of the population. Population samples are typed to determine the frequency of alleles at a site. The Typed_Sample table bridges samples and polymorphisms and also associates the typing method, which is detailed in the Typing_Method table. The allele frequency values for a Typed_Sample are stored in the Frequencies table. Information about the contributor of particular allele frequency data is kept in the Contributors Table. 

<img width="617" height="611" alt="Image" src="https://github.com/user-attachments/assets/25ef25db-571c-4bbe-8200-ef7968066cc7" />

**The ALFRED database schema**

### How can users find the data:

There are several great ways of searching ALFRED, the following are examples:
•	Search by chromosome, locus name, polymorphism name, population name, or geographic region: 

- 	Search for a loci or gene using chromosome number:

Users can download all the loci/genes with allele frequency data under a specific chromosome. Chromosome 1 to 22 and X. ALFRED do not hold allele frequency data for chromosome Y.

- 	Search for a population using geographic region name:

Populations are organized under arbitrary geographic regions.
Users can download all the populations with allele frequency data under a specific geographic region. The geographic regions are Africa, Northern Africa, Western Africa, Central Africa, Southern Africa, Eastern Africa, Europe, Asia, East Asia, S. Pacific/Oceania, Northern America, Southern America, and Siberia. After extracting the population names, users can download polymorphism typed for a specific population sample.

- 	Keyword Search (will provide description):

Entrez Gene Symbol 
dbSNP rs number
Population name

### How will this data be used?

ALFRED, the extensive knowledge base, is accessed globally, facilitating research and discovery while also serving educational purposes. ALFRED’s data is crucial in understanding genetic diversity and human evolution, identifying genetic risk factors in disease research, implementing personalized treatments, DNA profiling, studying gene-environment interactions, and public health interventions. 

1. At Bowdoin College in Maine, ALFRED’s data is utilized in the Evolution teaching lab in various ways. Students can test models related to the Out of Africa migration route, where heterozygosity is expected to decrease along the migration path due to the serial founder effect, and FST values should be small between neighboring populations. Many students are eager to investigate the original inhabitants of islands such as Australia, Corsica, or the Azores. They can test hypotheses by gathering allele frequency data from island populations and nearby mainland populations, then calculating heterozygosity and FST for these groups. Heterozygosity should decrease along the migration route, and FST should be smaller between genetically related populations.
2. Researchers analyze allele frequencies across different human populations to infer historical migration patterns and evolutionary relationships.
Changes in allele frequencies over time can reveal natural selection, genetic drift, and gene flow—key mechanisms of evolution.
3. In genome-wide association studies (GWAS), researchers compare allele frequencies between individuals with a disease and healthy controls to identify genetic variants linked to the disease.

- If a particular allele of a gene is significantly more frequent in people with Type 2 diabetes than in the general population, it may suggest that this allele contributes to disease risk.

- The discovery of the APOE ε4 allele as a risk factor for Alzheimer’s disease was based in part on differences in allele frequencies between affected individuals and controls.



