# Alpha Asymmetry in Foreign Exchange Markets

**An Investigation of Exploitability**

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17918373-blue.svg)](https://doi.org/10.5281/zenodo.17918373)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status](https://img.shields.io/badge/Status-Preprint-green.svg)](https://doi.org/10.5281/zenodo.17918373)

**Working Paper DAI-2605** | [Dissensus AI](https://dissensus.ai)

## Abstract

This paper investigates whether distributional asymmetries in foreign exchange alpha signals represent exploitable market inefficiencies. Using EUR/JPY data spanning November 2015--August 2025 (504 weekly observations after rolling window warmup), we document statistically significant departures from normality across five alpha types, with pronounced right-skewness in tail alpha (5.05) and momentum signals (2.12). However, we find that these asymmetries do not translate to economically significant trading profits. The GPD shape parameter is not significantly different from zero (xi = -0.23, 95% CI: [-1.79, 0.24]), indicating asymmetry arises from outlier frequency rather than heavy tails. Strategy returns include zero in confidence intervals after HAC correction; cross-market validation fails for equities and commodities; and transaction costs eliminate the modest gross edge. We conclude that alpha signal asymmetry, while statistically detectable, does not constitute an exploitable market inefficiency in FX markets. These null findings caution against over-interpreting higher-moment statistics as trading signals without rigorous economic validation.

## Key Findings

| Finding | Result |
|---------|--------|
| Alpha signals deviate from normality? | Yes -- confirmed across all five types |
| Exploitable heavy tails? | No (GPD xi approx 0) |
| Strategy profitable after costs? | No -- the central null finding |
| Cross-market generalization? | No -- EUR/JPY patterns do not transfer |

## Why This Matters

This is a **null result paper**. We document a plausible-sounding trading idea that does not survive rigorous testing. Such findings are underreported in quantitative finance ([Harvey, 2017](https://doi.org/10.1111/jofi.12530)), yet they prevent wasted research effort and capital allocation to spurious patterns.

## Alpha Types Analyzed

| Alpha Type | Description | Skewness |
|-----------|-------------|----------|
| Tail Alpha | Extreme return signals from tail events | 5.05 |
| Fast Alpha | Short-horizon momentum signals | 2.12 |
| Pricing Alpha | Deviation from fair-value estimates | 1.53 |
| Coverage Alpha | Analyst coverage and attention effects | 0.87 |
| Hedge Alpha | Risk-adjusted hedging signals | 0.45 |

## Keywords

null result, alpha asymmetry, foreign exchange, skewness, market efficiency, extreme value theory

## JEL Codes

G11, G14, G15, C58

## Repository Structure

```
alpha-asymmetry/
├── paper/
│   ├── alpha-asymmetry.tex    # LaTeX source
│   ├── alpha-asymmetry.pdf    # Compiled paper
│   ├── references.bib         # Bibliography
│   └── *.png                  # Figures
├── analysis/
│   ├── phase0_data_verification.py  # Data verification
│   └── recompute_tables.py          # Table recomputation
├── CITATION.cff
└── LICENSE
```

## Zenodo

The paper is archived on Zenodo: [10.5281/zenodo.17918373](https://doi.org/10.5281/zenodo.17918373) (concept DOI)

## Citation

```bibtex
@article{farzulla2026alpha,
  author  = {Farzulla, Murad},
  title   = {Alpha Asymmetry in Foreign Exchange Markets: An Investigation of Exploitability},
  year    = {2026},
  journal = {Dissensus AI Working Paper DAI-2605},
  doi     = {10.5281/zenodo.17918373}
}
```

## Authors

- **Murad Farzulla** -- [Dissensus AI](https://dissensus.ai) & King's College London
  - ORCID: [0009-0002-7164-8704](https://orcid.org/0009-0002-7164-8704)
  - Email: murad@dissensus.ai

## Links

- **Paper (Zenodo):** [10.5281/zenodo.17918373](https://doi.org/10.5281/zenodo.17918373)
- **Paper (SSRN):** [SSRN:6147567](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6147567)
- **Code (GitHub):** [github.com/studiofarzulla/alpha-asymmetry](https://github.com/studiofarzulla/alpha-asymmetry)
- **ASCRI Programme:** [systems.ac/3/DAI-2605](https://systems.ac/3/DAI-2605)
- **Dissensus AI:** [dissensus.ai](https://dissensus.ai)

## License

Paper content: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
