# Testable Predictions

This document contains operationalized testable predictions from "Before the Command Was Spoken."

## Prediction 1: Deontic Density → Enforcement Complexity

**Hypothesis**: Societies with higher deontic modal density in legal texts show more complex enforcement institutions.

**Operationalization**:
- **IV**: Deontic modal frequency per 1,000 words in constitutions (must, may, should, shall)
- **DV**: Institutional Complexity Index (0-10 scale based on: independent judiciary, administrative agencies, enforcement mechanisms, appellate system, constitutional review)
- **N required**: 50+ constitutions across varied legal traditions
- **Expected correlation**: ρ > 0.50, p < 0.01

**Falsification criterion**: If ρ < 0.20 or p > 0.10, prediction fails

**Data sources**: 
- Comparative Constitutions Project (https://comparativeconstitutionsproject.org/)
- World Bank Governance Indicators

---

## Prediction 2: Ritual Frequency → Norm Persistence

**Hypothesis**: Legal norms embedded in ritual transmission persist longer than purely textual norms.

**Operationalization**:
- **IV**: Ritual embedding (binary: 0=text only, 1=ritualized practice)
- **DV**: Norm persistence (years until functional extinction, measured by citation frequency collapse)
- **N required**: 30+ legal norms with 50+ years history
- **Expected effect**: χ² test, p < 0.05 for ritual vs. non-ritual survival

**Falsification criterion**: If no significant difference (p > 0.10) between ritualized and non-ritualized norms

**Data sources**:
- Constitutional citation databases
- Ethnographic ritual documentation

---

## Prediction 3: Neural Overlap (Ritual/Law Processing)

**Hypothesis**: Brain regions activated during ritual observation overlap with those activated during legal judgment tasks.

**Operationalization**:
- **Method**: fMRI study comparing:
  - Condition A: Watching ritual norm transmission (e.g., oath-taking, judicial robing)
  - Condition B: Reading legal text and making judgment
  - Condition C: Control (non-normative content)
- **ROIs**: Anterior Cingulate Cortex (ACC), Temporoparietal Junction (TPJ), Ventromedial Prefrontal Cortex (vmPFC)
- **Expected overlap**: ≥60% voxel overlap in ACC+TPJ between Conditions A and B
- **N required**: 30+ participants

**Falsification criterion**: If overlap <30% or not significantly different from control condition overlap

**Data sources**: Original fMRI experiment required

---

## Prediction 4: Primate Public Goods Game

**Hypothesis**: No non-human primate species will show >30% punishment frequency in multi-party free-rider scenarios where punisher is not directly harmed.

**Operationalization**:
- **Method**: 3-4 individuals contribute to group task (multi-pull rope for shared food)
- **Manipulation**: Some individuals can defect (take food without pulling)
- **DV**: Frequency of costly punishment by contributors toward defectors
- **Species**: Pan troglodytes, Pan paniscus, Cebus apella
- **Expected**: 0-5% punishment across all species

**Falsification criterion**: If any species shows >30% punishment in third-party context

**Data sources**: Original experimental study required (proposed design based on Riedl et al. 2012 paradigm)

---

## Prediction 5: Developmental Transition (Inequity → Intention-Sensitivity)

**Hypothesis**: Human children transition from outcome-based (capuchin-like) to intention-sensitive (human-specific) punishment between ages 3-7, coinciding with deontic language acquisition.

**Operationalization**:
- **Method**: Children observe:
  - Condition A: Actor steals toy from peer (intentional inequity)
  - Condition B: Actor accidentally receives extra toy (accidental inequity)
- **DV**: Punishment frequency (opportunity to remove actor's toy)
- **Age groups**: 2-3 years, 4-5 years, 6-7 years
- **Expected pattern**:
  - Age 2-3: Equal punishment A=B (outcome-based, p>0.10)
  - Age 6-7: A>B by ≥20 percentage points (intention-sensitive, p<0.05)
- **N required**: 30+ children per age group

**Falsification criterion**: If intention-sensitivity appears before age 3 OR never appears by age 7

**Data sources**: Original developmental experiment required

---

## Pre-Registration

All prospective predictions should be pre-registered at:
- Open Science Framework (OSF): https://osf.io/
- AsPredicted: https://aspredicted.org/

Include:
1. Full hypothesis statement
2. Operationalization details
3. Sample size justification (power analysis)
4. Analysis plan (statistical tests)
5. Explicit falsification criteria

---

## Citation

If using these predictions, cite:
Lerer, I. A. (2025). Before the Command Was Spoken: Replication Materials. GitHub. https://github.com/adrianlerer/Before-the-Command-Was-Spoken
