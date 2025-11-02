# Data Directory Documentation

This directory contains quantitative data tables supporting the paper "Before the Command Was Spoken."

## Files

### table1_enforcement_mechanisms.csv
Comparative enforcement mechanisms across primate species.

**Columns**:
- Species: Scientific name (e.g., Pan troglodytes)
- N: Sample size
- TPP: Third-party punishment frequency (%)
- Inequity_Punishment: Outcome-based punishment frequency (%)
- Partner_Choice: Presence of social selection mechanism (Yes/No/Limited)
- Primary_Mechanism: Dominant cooperation enforcement strategy
- Source: Primary citation

**Statistics**: All p-values and effect sizes reported in paper Section 2.1

---

### table2_temporal_evolution_exclusion.csv
Temporal pattern of exclusionary burial practices.

**Columns**:
- Period: Archaeological period (e.g., Upper Paleolithic)
- Years_BP: Thousands of years before present
- N_Burials: Total burials analyzed
- Deviant_N: Number of exclusionary burials
- Deviant_Percent: Percentage of exclusionary burials
- Gini_Coefficient: Wealth inequality estimate
- Cooperation_Mechanism: Inferred enforcement pattern

**Statistics**: χ²(1)=11.89, p<0.001 for Paleolithic vs. Neolithic comparison

---

### table3_primatology_summary.csv
Complete primatology findings across all 5 PROMPTs.

**Columns**:
- Study: Citation (Author Year)
- Species: Scientific name
- N: Sample size
- Paradigm: Experimental design (e.g., Ultimatum Game)
- Key_Finding: Primary result
- P_Value: Statistical significance
- Effect_Size: Cohen's d, β, or χ² as appropriate

**Coverage**: 25+ primary studies, N=52 total individuals (Pan N=46, Cebus N=6)

---

## Data Sources

All data extracted from peer-reviewed publications cited in paper References section. No proprietary or restricted-access data used.

## Replication

To replicate tables:
1. Access primary sources via DOIs provided in paper
2. Extract N, statistics, and effect sizes
3. Verify against values in these CSVs
4. All discrepancies <0.01 due to rounding

## Citation

If using these tables, cite:
Lerer, I. A. (2025). Before the Command Was Spoken: Replication Materials. GitHub. https://github.com/adrianlerer/Before-the-Command-Was-Spoken
