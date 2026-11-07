# Result provenance and assessment

Source: [SWARAJ_PDR.pdf](../../assets/swaraj/SWARAJ_PDR.pdf), supplied personal PDR, November 2026. Figures and numerical values are report evidence, not a newly executed validation campaign.

## Configuration boundaries

| Campaign | Interpretation |
|---|---|
| Group sensitivity | Original 37.005 m reference; MLA −10% candidate 35.309 m peak active CTE |
| Final nominal | Revised energy/throttle implementation, 125 s; 34.802 m peak active CTE |
| Command deflections | Independent and combined altitude/speed commands; incomplete reduced-speed tracking remains documented |
| Gust validation | Four prescribed schedules, GRC OFF/ON comparisons; assess separately from nominal bank targets |

The final nominal result should not be attributed solely to the MLA gain adjustment. Controller implementation and analysis-window differences also matter. Active-route CTE and full-run extrema must retain their stated windows. A time cutoff near route completion does not implement terminal mission logic.

## Interpretation

- Nominal tracking, altitude, minimum airspeed and bank meet the stated project criteria.
- Completion is qualified: the flag is asserted at 98.51% map progress.
- GRC improves lateral containment, especially in lateral/combined cases.
- GRC ON vertical/combined peak altitude errors are 10.502/11.333 m; they exceed the 10 m criterion.
- Peak absolute error is not a peak-to-peak altitude range.
- CDR/PDR model and configuration changes preclude an equivalent controlled performance comparison.
- TAS, EAS and CAS must retain distinct definitions; unit conversion alone does not convert TAS to CAS.
