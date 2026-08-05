# Patharapa "Candy" Promprasert

**Bioinformatics Analyst | Cancer Genomics | Multi-Omics | Computational Biology**

Bioinformatics scientist developing reproducible computational workflows for precision oncology across cancer genomics, transcriptomics, single-cell biology, epigenomics, population genomics, and clinical outcomes.

My work focuses on translating high-dimensional cancer datasets into
biologically interpretable and statistically defensible results.

## Research Areas

- Cancer genomics and precision oncology
- Multi-omics integration
- Epigenomics and DNA methylation
- Bulk and single-cell transcriptomics
- Tumor immune microenvironment
- Population genomics and genetic ancestry
- Statistical genomics and survival analysis

## Selected Projects

### Thyroid Cancer Multi-Omics

Integrated somatic DNA, bulk RNA-seq, clinical phenotypes, molecular
drivers, and disease-status information to characterize molecular
heterogeneity in thyroid cancer.

**Methods:** GATK Mutect2, MAF harmonization, somatic-driver
reconciliation, DESeq2, PCA, transcriptional program scoring,
inflammasome analysis, pathway-level interpretation, multivariable
modeling, and DNA–RNA integration.

### CMS4 Single-Cell Immune States & Ancestry

Single-cell analysis of ancestry-associated immune-state heterogeneity
within CMS4 colorectal cancer.

**Methods:** Seurat, compartment-specific QC, Harmony batch integration,
Azimuth reference annotation, patient-level pseudobulk aggregation,
DESeq2, GO Biological Process GSEA, MSigDB Hallmark GSEA.

**Immune programs:** CD8 cytotoxic/exhaustion states, CD4/Treg/Tfh states,
B-cell/plasma differentiation, M2/TAM programs, mast-cell signaling,
and progenitor-like lineage states.

### OED → OSCC Epigenomic Progression

Longitudinal Illumina EPIC methylation analysis investigating
epigenetic alterations associated with progression from oral epithelial
dysplasia to oral squamous cell carcinoma.

**Methods:** EPIC methylation arrays, beta/M-value modeling, limma,
duplicateCorrelation, CpG- and gene-level analysis, baseline-definition
sensitivity analyses, delta-beta effect sizes, BH-FDR, candidate-gene
analysis, and spatial-transcriptomic integration.

### HNSC SLC25A10/SFXN3 Survival Genomics

Evaluated reciprocal metabolic-gene expression states and survival
outcomes in HPV-negative head and neck squamous cell carcinoma.

**Methods:** Kaplan–Meier estimation, log-rank testing, Cox proportional
hazards regression, continuous-expression models, interaction testing,
subsite-specific sensitivity analysis, and nonlinear modeling.

### CRC Immunoepigenomics
Integrated methylation-derived immune composition with LINE-1,
CIMP, ATM methylation, clinical variables and environmental context.

**Methods:** EpiDISH RPC, EPIC methylation, immune deconvolution,
Spearman correlation, nonparametric testing, multivariable models.

### CMS4 Single-Cell CNV Architecture

Evaluated ancestry-stratified chromosomal instability and clonal
heterogeneity in CMS4 colorectal tumors using expression-derived
single-cell copy-number profiles.

**Methods:** scRNA-seq, inferCNV, chromosome- and gene-level CNV
summarization, clonal diversity, ancestry-stratified comparisons,
BH-FDR, and leave-one-sample-out sensitivity analysis.

### CRC Population Genomics & Genetic Ancestry

Developed a population-genomics workflow for genetic ancestry
estimation from RNA-derived germline variation in colorectal cancer.

**Methods:** nf-core/rnavar, GATK HaplotypeCaller, bcftools, PLINK,
1000 Genomes/HGDP reference integration, PCA, supervised and
unsupervised ADMIXTURE, cross-validation, missingness sensitivity
analysis, and Linux/Slurm HPC.

## Additional Projects

**CRC Immunoepigenomics** — EPIC methylation, EpiDISH immune
deconvolution, CD8/TIL analysis, LINE-1, CIMP, ATM methylation,
environmental and neighborhood-level variables.

**CRC Ancestry Transcriptomics & Immunomics** — CMS1–4-stratified
DESeq2, ancestry-associated transcriptional programs, continuous AFR
gradients, xCell and CIBERSORT immune deconvolution.

**CRC Single-Cell Cellular Composition** — patient-level immune/stromal
composition, genetic ancestry, self-reported race, CMS composition,
nonparametric inference and FDR control.

**DNA Damage & Repair Transcriptomics** — DESeq2, ancestry/disease
contrasts, DNA-repair and metabolic programs, ashr shrinkage,
GO/KEGG/Reactome enrichment.

**Cancer Genomics / Exposure Analyses** — somatic variation,
mutational signatures, copy-number analysis, methylation-associated
environmental exposure signatures, and translational cancer genomics.

## Technical Stack

**Languages:** R · Python · Bash · Linux

**Workflow / HPC:** Nextflow · nf-core · Slurm · Singularity · Conda · Git · GitHub Actions

**Cancer Genomics:** GATK · Mutect2 · HaplotypeCaller · Funcotator ·
bcftools · samtools · VEP · ANNOVAR · maftools · GISTIC2

**Bulk Transcriptomics:** Salmon · DESeq2 · limma · ashr ·
clusterProfiler · ReactomePA · MSigDB/GSEA

**Single-Cell:** Seurat · Harmony · Azimuth · SingleR · Monocle3 ·
inferCNV · pseudobulk differential expression

**Epigenomics:** Illumina EPIC · sesame · limma · EpiDISH ·
methylation deconvolution · beta/M-value modeling

**Population Genomics:** PLINK · ADMIXTURE · SNPRelate ·
1000 Genomes · HGDP · PCA

**Tumor Immunology:** xCell · CIBERSORT · EpiDISH · immune-state
scoring · tumor microenvironment profiling

**Statistical Genomics:** GLM · Cox proportional hazards ·
Kaplan–Meier · likelihood-ratio tests · interaction models ·
nonparametric inference · multiple-testing correction
