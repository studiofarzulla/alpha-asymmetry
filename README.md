# Alpha Asymmetry in Foreign Exchange Markets

**An Investigation of Exploitability**

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17918374-blue.svg)](https://doi.org/10.5281/zenodo.17918374)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status](https://img.shields.io/badge/Status-SSRN-blue.svg)](https://ssrn.com/abstract=6147567)

**Working Paper DAI-2605** | [Dissensus AI](https://dissensus.ai)

## Abstract

This paper investigates whether distributional asymmetries in foreign exchange alpha signals represent exploitable market inefficiencies. Using EUR/JPY data spanning November 2015--August 2025 (510 weekly observations), we document statistically significant departures from normality across five alpha types, with pronounced right-skewness in tail alpha (5.05) and momentum signals (2.12). However, we find that these asymmetries do not translate to economically significant trading profits. The GPD shape parameter is not significantly different from zero, indicating asymmetry arises from outlier frequency rather than heavy tails. Strategy returns include zero in confidence intervals after HAC correction; cross-market validation fails for equities and commodities; and transaction costs eliminate the modest gross edge. We conclude that alpha signal asymmetry, while statistically detectable, does not constitute an exploitable market inefficiency in FX markets. These null findings caution against over-interpreting higher-moment statistics as trading signals without rigorous economic validation.

## Why This Matters

This is a **null result paper**. We document a plausible-sounding trading idea that does not survive rigorous testing. Such findings are underreported in quantitative finance ([Harvey, 2017](https://doi.org/10.1111/jofi.12530)), yet they prevent wasted research effort and capital allocation to spurious patterns.

## Key Findings

| Finding | Result |
|---------|--------|
| Alpha signals deviate from normality? | Yes -- all five types reject normality (p < 0.001) |
| Exploitable heavy tails? | No -- GPD shape parameter not significantly different from zero |
| Strategy profitable after costs? | No -- confidence intervals include zero after HAC correction |
| Cross-market generalization? | No -- pattern does not generalize beyond EUR/JPY |

## Keywords

null result, alpha asymmetry, foreign exchange, skewness, market efficiency, extreme value theory

## Repository Structure

```
alpha-asymmetry/
├── paper/
│   ├── alpha-asymmetry.tex    # Main LaTeX source
│   ├── alpha-asymmetry.pdf    # Compiled paper
│   └── references.bib         # Bibliography
├── analysis/                   # Analysis scripts
├── figures/                    # Figures
├── reports/                    # Analysis reports
├── CITATION.cff               # Citation metadata
└── LICENSE
```

## Citation

```bibtex
@article{farzulla2026alpha,
  author  = {Farzulla, Murad},
  title   = {Alpha Asymmetry in Foreign Exchange Markets: An Investigation of Exploitability},
  year    = {2026},
  journal = {SSRN Working Paper},
  doi     = {10.5281/zenodo.17918374}
}
```

## Authors

- **Murad Farzulla** -- [Dissensus AI](https://dissensus.ai) & King's College London
  - ORCID: [0009-0002-7164-8704](https://orcid.org/0009-0002-7164-8704)
  - Email: murad@dissensus.ai

## License

Paper content: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
