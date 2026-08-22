# Ω-Lab v1.6 benchmark baseline

This record preserves the observed Ω-Lab v1.6 250-trial batch result before any Ω-v2 estimator changes.

## Observed run configuration

- Scenario: single localized discrepancy
- Amplitude: 2.80%
- Hidden center: approximately 0.742 GeV after reveal
- Feature width σ: 0.020 GeV
- Noise: 1.50%
- Correlation: 0.40
- Bins: 105
- Batch trials: 250
- Frozen scoring tolerance: ±25 MeV

The fixed-seed value was not visible in the captured batch-result screenshot, so it is not asserted here. The application default at v1.6 is 20260821 unless changed by the operator.

## Observed aggregate result

| Method | Trials | Hit rate | Median localization error |
|---|---:|---:|---:|
| Ω blend | 250 | 79.6% | 16.3 MeV |
| Pointwise max | 250 | 99.6% | 3.1 MeV |
| χ² window | 250 | 64.0% | 22.4 MeV |
| Shape TV | 250 | 64.4% | 22.4 MeV |

False alarms reported by the scoreboard: 0.

## Interpretation boundary

This is an observed benchmark result for the stated run configuration. It does not by itself establish general superiority of any method outside this parameter regime. The current Ω estimator in v1.6 must remain unchanged in this preserved baseline; any revised estimator should be versioned separately and tested prospectively.

## Audit note

The full per-trial CSV ledger should be exported directly from the Ω-Lab browser session and archived alongside this record before a DOI release. This file preserves the aggregate result visible in the application and the settings visible in the preceding run screenshots, but it is not a substitute for the full per-trial ledger.

## Version anchor

Preservation target: Ω-Lab App v1.6, frozen benchmark protocol v1.0 (2,925 deterministic-trial battery specification).
