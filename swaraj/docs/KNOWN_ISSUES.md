# Known issues and scope

The base report is published unchanged as a dated development record. The web page and README use the following qualifications.

1. **Airspeed notation:** the density-ratio relationship `V_EAS = V_TAS * sqrt(rho/rho0)` produces equivalent airspeed. Equation 101 should label its output EAS, not CAS. A corrected notation edition is pending.
2. **Gust assessment wording:** peak absolute altitude errors above the 10 m design criterion remain exceedances even when the aircraft later recovers. Report wording suggesting these can be neglected should not be used as a compliance finding.
3. **Route end:** completion flag and map progress require reconciliation; terminal guidance and automatic mission termination remain future work.
4. **Validation scope:** nonlinear simulation and handbook comparisons do not establish flight certification, structural compliance or flight-test validation.
5. **Reproducibility:** the model, initialization scripts and raw logs are not included in this documentation release.
6. **Editorial cleanup:** some cross-references, appendix references and notation require correction in a future report edition.

An error correction in documentation must not be described as an implemented or experimentally verified controller change.
