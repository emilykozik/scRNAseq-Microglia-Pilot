# Microglia Pilot Analysis
## Background and Objectives
The samples for this experiment were collected and processed in-house and includes isolation of fresh microglia from human donor (MG22; 73yo, M, PD) from hippocampus (HIPP) and medial frontal gyrus (MFG) and frozen nuclei collected from human donor (17_016; 72yo, M, control) from MFG. 

Main objectives:
1. Determine quality of the fresh microglia in comparison to nuclei.
2. Determine the quantity and quality of microglia that can be identified from frozen nuclei sample.
3. Determine whether we can identify the same subclusters from these microglia. 

## Data
We have 3 RData files with Seurat objects which have been processed first in cellranger and filtered by minimumn cells per gene =3 and minimum features per cell = 200. There is also data from Olah et al. 2020 [[paper]](https://www.nature.com/articles/s41467-020-19737-2) [[github]](https://github.com/vilasmenon/Microglia_Olah_et_al_2020) which was [processed](https://emilykozik.github.io/scRNAseq-Microglia-Pilot/Olah_seurat_object.html) for comparison of QC. 
MG22 HIPP and MFG data were [merged](https://emilykozik.github.io/scRNAseq-Microglia-Pilot/Merge_MG22.html) into one Seurat object.

## [Quality Control](https://emilykozik.github.io/scRNAseq-Microglia-Pilot/QC_2.html)
Compared between Olah, and our MG22 and Nuclei samples then filtered

## [Seurat Pipeline for Clustering and Annotation](https://emilykozik.github.io/scRNAseq-Microglia-Pilot/Seurat_Clustering.html)


## Clustering with Random Forest algorithm
We first ran a pilot for the Random Forest script using MG22 Hippocampus sample. "RandomForest_Trial_7.Rmd" -- needs to be run on the chimera

[Annotation and plots](https://emilykozik.github.io/scRNAseq-Microglia-Pilot/RandomForest_Annotation.html)


