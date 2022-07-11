# WASP
WASP: A Workflow for Antibody Sequencing Profiling of single cell immune repertoire

| Input files | Tool | Task | Notebook | 
| ---- | ---- | ---- | -------- |
| `filtered_contig_annotations.csv` `filtered_contig.fasta` | [ChangeO](https://academic.oup.com/bioinformatics/article/31/20/3356/195677) | V(D)J annotation and data standardization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yyw-informatics/WASP/blob/main/Immcantation_1_VDJ_Annotation_and_Standardization_with_Change_O_in_Python.ipynb)
| `data_db-pass.tsv` | [TIgGER](https://www.pnas.org/doi/10.1073/pnas.1417683112) | Novel gene discovery and genotyping |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yyw-informatics/WASP/blob/main/Immcantation_2_Novel_V_gene_alleles_with_TIgGER_in_R.ipynb)|
| `data_db-pass-genotyped.tsv`     | [SCOPer](https://academic.oup.com/bioinformatics/article/34/13/i341/5045726) | Clonal lineage clustering |   |
