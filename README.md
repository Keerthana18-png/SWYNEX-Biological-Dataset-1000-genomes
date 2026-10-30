# Biological Dataset Selection: 1000 Genomes Project

## 1. Overview
The 1000 Genomes Project (Phase 3) is one of the largest public catalogues of human genetic variation. It maps differences in DNA between people from many parts of the world, and it is widely used as a reference in population genetics and medical genomics.

## 2. Source and Access
| Item | Details |
|---|---|
| Name | 1000 Genomes Project, Phase 3 |
| Provider | International Genome Sample Resource (IGSR) |
| Website | https://www.internationalgenome.org |
| Also available via | NCBI and EBI (FTP: ftp.1000genomes.ebi.ac.uk) |
| Access | Fully open, no registration or approval needed |
| Type of data | Human whole-genome variant calls (SNPs, indels, structural variants) |

## 3. Size and Format
| Item | Details |
|---|---|
| Individuals | 2,504 |
| Populations | 26, grouped into 5 super-populations (African, American, East Asian, European, South Asian) |
| Variants | About 84.7 million |
| File format | VCF (Variant Call Format), one file per chromosome |
| Metadata | Sample ID, population, super-population, sex |
| Total size | (add exact figure after checking the IGSR website) |

## 4. Research Question
**Main question:** How does human genetic variation differ across global populations, and what can it tell us about ancestry and disease susceptibility?

**Sub-questions:**
- Which variants are common in one population but rare in others?
- Do individuals cluster by ancestry when genetic variation is compared?
- Which variants are linked to known disease-related genes, and how does their frequency differ between groups?

## 5. Why I Chose This Dataset
- It is public and needs no lab work.
- It is well documented and widely cited.
- It covers many populations, so comparisons are meaningful.
- It is a standard reference in genomics research.

## 6. Planned Analysis (no lab work required)
1. Download the VCF files for one or two chromosomes and the sample metadata.
2. Filter variants with bcftools or PLINK.
3. Calculate allele frequencies for each population.
4. Run a PCA to see whether samples group by ancestry.
5. Compare frequencies between populations (for example with Fst).
6. Summarize the findings with charts.

## 7. Limitations
- The sample for each population is relatively small.
- Some populations and regions of the world are not represented.
- The data shows variation, not cause and effect for disease.

## 8. Ethics and Licensing
The data is publicly released for research use. Participants consented to open data sharing, and the data contains no personal identifiers.

## 9. Citation
The 1000 Genomes Project Consortium (2015). A global reference for human genetic variation. *Nature*, 526, 68-74.
