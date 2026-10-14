# Processed data for: Interpretable Fuzzy-Logic Multimodal Framework for Parkinson's Disease Screening

Processed data accompanying the manuscript **"An Interpretable Fuzzy-Logic Multimodal Machine-Learning Framework for Parkinson's Disease Screening"** by Imene Belgheir and Souad Khellat-Kihel.

The study classifies Parkinson's disease (PD) from three accessible digital biomarkers (sustained-vowel speech, keystroke dynamics and spiral drawings) and combines the modality-specific scores with a fuzzy-logic late-fusion module. Because the three public datasets do not share participants, fusion was evaluated with 100 class-matched virtual-patient simulations. These data therefore do not represent patient-level multimodal measurements.

## Repository contents

> Edit this list to match your actual files.

- `splits/`: train/test split definitions for each modality
- `features/`: processed feature tables used for model training and evaluation
- `scores/`: predicted scores of the unimodal classifiers on the held-out test sets
- `results/`: result tables (unimodal metrics and fuzzy-fusion results over the 100 simulations)

## Original data sources

**This repository does not contain the original datasets.** Please download them from their original sources and cite them if you use them.

| Modality | Dataset | Source |
|---|---|---|
| Speech | Oxford Parkinson's Disease Detection (MDVP) dataset, "Parkinsons" | UCI Machine Learning Repository: https://doi.org/10.24432/C59C74 |
| Keystroke dynamics | Tappy keystroke dataset | https://physionet.org/content/tappy/1.0.0/ |
| Spiral drawings | Parkinson YOLO dataset | Kaggle: https://www.kaggle.com/datasets/cornelioac/parkinson-yolo-dataset |

Please check each dataset's licence on its original page before reusing it. The processed files here are derived from these datasets and remain subject to their terms.

### References

1. M. Little, Parkinsons, UCI Machine Learning Repository, 2007. https://doi.org/10.24432/C59C74
2. M.A. Little, P.E. McSharry, S.J. Roberts, D.A.E. Costello, I.M. Moroz, Exploiting nonlinear recurrence and fractal scaling properties for voice disorder detection, Biomed. Eng. Online 6 (2007) 23.
3. W.R. Adams, High-accuracy detection of early Parkinson's disease using multiple characteristics of finger movement while typing, PLoS One 12 (2017) e0188226.
4. A.C. Cornelio, Parkinson YOLO dataset, Kaggle, 2023. https://www.kaggle.com/datasets/cornelioac/parkinson-yolo-dataset

## Citation

If you use these processed data, please cite the manuscript (full reference to be added once published) and the original datasets listed above.

## Contact

Imene Belgheir, imene.belgheir@gmail.com
