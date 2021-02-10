# Microglia Pilot Analysis
## Background and Objectives
The samples for this experiment were collected and processed in-house and includes isolation of fresh microglia from human donor (MG22; 73yo, M, PD) from hippocampus (HIPP) and medial frontal gyrus (MFG) and frozen nuclei collected from human donor (17_016; 72yo, M, control) from MFG. 

Main objectives:
1. Determine quality of the fresh microglia in comparison to nuclei.
2. Determine the quantity and quality of microglia that can be identified from frozen nuclei sample.
3. Determine whether we can identify the same subclusters from these microglia. 

## Data
We have 3 RData files with Seurat objects which have been processed first in cellranger and filtered by minimumn cells per gene =3 and minimum features per cell = 200. There is also data from Olah et al. 2020 [[paper]](https://www.nature.com/articles/s41467-020-19737-2) [[github]](https://github.com/vilasmenon/Microglia_Olah_et_al_2020) which was [processed]() for comparison of QC. 
MG22 HIPP and MFG data were [merged](Merge_MG22) into one Seurat object.

## Quality Control


## Suerat Pipeline for Processing


## Seurat SCTransform


## Clustering with Random Forest algorithm


## Clustering and Annotation


## Nuclei vs Microglia


## Comparing to Olah et al. 2020


