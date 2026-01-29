# Alpha Asymmetry in Foreign Exchange Markets

**An Investigation of Exploitability**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17918374.svg)](https://doi.org/10.5281/zenodo.17918374)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Abstract

This paper investigates whether distributional asymmetries in foreign exchange alpha signals represent exploitable market inefficiencies. Using EUR/JPY data spanning November 2015–August 2025 (510 weekly observations), we document statistically significant departures from normality across five alpha types, with pronounced right-skewness in tail alpha (5.05) and momentum signals (2.12). However, we find that these asymmetries do not translate to economically significant trading profits.

**Key Finding:** Alpha signal asymmetry, while statistically detectable, does not constitute an exploitable market inefficiency in FX markets.

## Why This Matters

This is a **null result paper**. We document a plausible-sounding trading idea that does not survive rigorous testing. Such findings are underreported in quantitative finance ([Harvey, 2017](https://doi.org/10.1111/jofi.12530)), yet they prevent wasted research effort and capital allocation to spurious patterns.

## Results Summary

| Finding | Result |
|---------|--------|
| Alpha signals deviate from normality? | ✓ Yes |
| Exploitable heavy tails? | ✗ No (GPD ξ ≈ 0) |
| Strategy profitable after costs? | ✗ No |
| Cross-market generalization? | ✗ No |

## Keywords

null result, alpha asymmetry, foreign exchange, skewness, market efficiency, extreme value theory

## JEL Codes

G11, G14, G15, C58

## Repository Structure

```
alpha-asymmetry/
├── paper/
│   ├── alpha-asymmetry.tex    # Main LaTeX source
│   ├── alpha-asymmetry.pdf    # Compiled paper
│   └── references.bib         # Bibliography
├── analysis/                   # Analysis scripts
└── *.png                       # Figures
```

## Citation

```bibtex
@article{farzulla2026alpha,
  author = {Farzulla, Murad},
  title = {Alpha Asymmetry in Foreign Exchange Markets: An Investigation of Exploitability},
  year = {2026},
  journal = {SSRN Working Paper},
  doi = {10.5281/zenodo.17918374}
}
```

## Author

**Murad Farzulla**
King's College London | [Dissensus AI](https://dissensus.ai)
Contact: murad@dissensus.ai

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
