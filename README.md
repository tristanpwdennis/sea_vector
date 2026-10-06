# sea_vector
Genomic Surveillance of Malaria Mosquitoes in SE Asia

See "notebooks" for analysis notebooks used to generate the figures in the manuscript [MS LINK]

Analyses use the Adir1.0 and Amin1.0 data via the [malariagen_data](https://github.com/malariagen/malariagen-data-python) API (see `requirements.txt`).

| Notebook | Figure / table |
|---|---|
| `notebooks/fig1_map_pca.ipynb` | Figure 1: sampling map and PCA; defines the *An. dirus* s.l. cohorts |
| `notebooks/fig2_diversity.ipynb` | Figure 2: runs of homozygosity, π and Tajima's D |
| `notebooks/fig3_gwss.ipynb` | Figure 3: Fst and G123 scans; Tables S2 and S3 |
| `notebooks/plot_inversion_pca.ipynb` | Figure 4: windowed PCA |

Each notebook is self-contained, including its cohort definitions. *An. minimus* population assignments (St Laurent et al. 2022) are in `supplementary_data/amin1_cohorts.csv`.
