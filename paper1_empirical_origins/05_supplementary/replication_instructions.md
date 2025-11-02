# Replication Instructions

## Overview

This document provides step-by-step instructions for replicating the systematic reviews and analyses in "Before the Command Was Spoken."

---

## Systematic Review Replication

### Inclusion Criteria (All PROMPTs)
1. **Peer-reviewed** primary research (journals, not reviews)
2. **Quantitative data** reported (N, p-values, or frequencies)
3. **English** or Spanish language
4. **Dates**: Any publication date through October 2025
5. **Species**: Great apes (Pan troglodytes, Pan paniscus), New World monkeys (Cebus apella)

### Search Strategy
- Databases: Google Scholar, PubMed, Web of Science
- Keywords: See each PROMPT's methodology section
- Citation chaining: Forward/backward citations of seminal papers

### Exclusion Criteria
1. Review articles or meta-analyses (except as source of primary citations)
2. Studies without quantitative data
3. Non-primate species (except in PROMPT 4: archaeology)
4. Duplicate reports of same dataset

---

## Statistical Analysis Replication

### Primatology (Section 2.1)
**Required data**:
- Sample sizes (N) from each study
- Rejection rates (%) from ultimatum games
- χ² statistics from GLMMs (Riedl 2012, Surbeck 2025)
- β coefficients with SE and p-values (Surbeck 2025)

**Software**: Any statistical package supporting:
- Chi-squared tests
- Generalized Linear Mixed Models (GLMMs)
- Wilcoxon signed-rank tests

**Verification**: All reported p-values should match within 0.01

---

### Archaeology (Section 2.2)
**Required data**:
- Burial counts by period (Paleolithic, Neolithic, Chalcolithic)
- Classification of burials (normative vs. deviant)
- Gini coefficients (from Nørtoft 2022)

**Analysis**:
```r
# Chi-squared test for temporal difference
paleo <- c(1, 149)  # deviant, normal
neo <- c(353, 3399)  # deviant, normal
chisq.test(rbind(paleo, neo))
# Expected: χ²(1) = 11.89, p < 0.001
```

**Sources**: 
- Chapman 2000 (Neolithic SE Europe)
- Rebay-Salisbury 2010 (Central Europe)
- Trinkaus & Buzhilova 2022 (Paleolithic compilation)

---

## Testable Predictions Replication

See `testable_predictions.md` for:
1. Operationalized hypotheses
2. Measurement protocols
3. Sample size requirements
4. Expected effect sizes
5. Falsification criteria

Each prediction includes pre-registration recommendations for prospective studies.

---

## Data Availability

All primary data are available from published sources cited in paper. No restricted-access datasets used.

**Archaeological data**: Compiled from published site reports (citations in PROMPT 4)
**Primatological data**: Extracted from Methods and Results sections of cited papers
**Linguistic data**: From WALS (World Atlas of Language Structures) - publicly accessible

---

## Contact

Questions about replication: [your email]

Errors or discrepancies: Open an issue on GitHub repository
