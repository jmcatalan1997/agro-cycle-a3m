# Agro-Cycle A3M

Supporting data and reproducibility materials for:

**Agro-Cycle A3M for Diagnosing Sustained Integration of Agricultural Automation Technologies**

IEEE CaribCon 2026.

## Repository contents

```text
agro-cycle-a3m/
├── README.md
├── CITATION.cff
├── LICENSE_PENDING.md
├── corpus/
├── codebooks/
└── coded_excels/
```

### `corpus/`
Contains the final screening and corpus-construction files used to document the two complementary searches reported in the paper.

Recommended files:
- `S1_cribado_texto_completo_v1.6_FINAL_2026-08-18.xlsx`
- `S2_Scopus_union_final_audit_1698.xlsx`
- `S2_cribado_texto_completo_v1.6_FINAL_2026-08-18.xlsx`

### `codebooks/`
Contains the frozen operational coding rules used for the final A3M evidence-traceability assessment.

Recommended file:
- `A3M_Codebook_v1.3_FINAL_FROZEN.xlsx`

### `coded_excels/`
Contains the primary coding, the independent blinded reapplication, the adjudication of disagreements, and the final post-adjudication 48-study matrix.

Recommended files:
- `A3M_v1.3_PRIMARY_PRE_ADJUDICATION_48studies.xlsx`
- `A3M_v1.3_INDEPENDENT_BLINDED_CODING_48studies.xlsx`
- `A3M_v1.3_FINAL_ADJUDICATION_37_disagreements.xlsx`
- `A3M_v1.3_FINAL_POST_ADJUDICATION_48studies.xlsx`

## Key reproducibility results

The frozen v1.3 codebook was independently reapplied to the complete 48-publication corpus.

Pre-adjudication comparison:
- 48 publications
- 4 interfaces per publication
- 192 coding decisions
- 155 exact agreements
- 37 disagreements
- Overall agreement: **80.73%**
- Cohen's kappa: **0.705**

Per-interface pre-adjudication agreement:
- I12: 45/48 = 93.75%
- I23: 38/48 = 79.17%
- I3M: 34/48 = 70.83%
- IM1: 38/48 = 79.17%

The 37 disagreements were reviewed only after the reliability statistics had been fixed. Source-level adjudications were subsequently reviewed and ratified by the first author. Cohen's kappa was **not** recomputed after adjudication.

## Final post-adjudication evidence map

Each triplet is reported as `D / P / ND`.

| Interface | S1 (n=29) | S2 (n=19) | Total (n=48) |
|---|---:|---:|---:|
| I12 | 29 / 0 / 0 | 19 / 0 / 0 | **48 / 0 / 0** |
| I23 | 7 / 5 / 17 | 14 / 2 / 3 | **21 / 7 / 20** |
| I3M | 8 / 20 / 1 | 6 / 11 / 2 | **14 / 31 / 3** |
| IM1 | 1 / 4 / 24 | 1 / 6 / 12 | **2 / 10 / 36** |

Across all 192 final codes:
- D = 85
- P = 48
- ND = 59

## Interpretation

`D/P/ND` describe **documentary evidence traceability/completeness** in the selected publications. They do not measure mechanism prevalence and do not correspond to the deployment-diagnostic states `SAT/GAP/UNC/NA`.

The corpus was used for conceptual development and evidence mapping. It should not be interpreted as demonstrating formal conceptual saturation, because no prospective saturation stopping rule was applied.

## Third-party publications

Full-text PDFs of the 48 source publications are not redistributed in this repository. Bibliographic information and DOI-based traceability are retained in the accompanying spreadsheets.

## Archived release

Version v1.0.0 is permanently archived in Zenodo:

**DOI:** https://doi.org/10.5281/zenodo.22883822

## Citation

See `CITATION.cff`.

## License

Repository-authored data, coding matrices, codebooks, and documentation are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0), except where otherwise noted.

See `LICENSE.md`.
