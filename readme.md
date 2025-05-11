# Green Bands

> *Green Bands* is a reproducible Python workflow that detects, maps, and analyzes oxygen‑sensitive diagenetic banding in marine sediment cores to illuminate million‑year‑scale changes in bottom‑water oxygen during the Pleistocene.

## Background

Widely observed millimetre‑scale red‑to‑green banding in shallow (< 1 m) marine sediments is tied to redox‑front migration, yet its large‑scale and long‑term controls remain unclear. This project merges **(i)** a global survey of 2,121 IODP core photographs spanning the Atlantic, Indian, and Pacific Oceans with **(ii)** new 1‑million‑year stratigraphic records from Sites U1474 (Indian Ocean) and U1313 (North Atlantic). By coupling computer‑vision detection of green diagenetic bands with environmental datasets (bottom‑water O₂, productivity, sedimentation rate, organic carbon, CaCO₃) and a benthic δ¹³C stack, the workflow tests how orbital‑scale shifts in oxygenation govern band formation and carbon cycling.

All notebooks reproduce the figures, tables, and supplementary datasets in the accompanying manuscript using the Conda environment specified in `green_bands.yml`.

## Repository layout

| Directory    | Contents                                                                                                                                        |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| `Data/`      | **Raw data** required to reproduce every figure and table in the manuscript                                                                     |
| `Documents/` | PDFs for **Supporting Information Datasets 1 & 2** and the complete core‑image sets for the splices of Sites U1474 and U1313 featuring green‑band stratigraphy |
| `Figures/`   | Exported **main manuscript figures 1–9** and **Supporting Information figures S1–S7**                                                           |
| `Notebooks/` | **23 iPython notebook files** used to analyze the data and generate figures |
| `Tables/`    | CSV files for **Supporting Information tables S1–S9**                                                                                       |
