3 model categories: for frequency (freq), severity (sev) and aggregate (total).

2 model types: using Generalized Linear Model (glm) or Generalized Additive Model (gam).
Replaced l or a with x below.

Used log as link function unless otherwise stated or pre-set by package.

(Conditional) mean and zero-inflation (if any) depend on covariates.

**For frequency:**
* freq.gxm1: Poisson
* freq.gxm2: Negative Binomial
* freq.zigxm1: zero-inflated Poisson
* freq.zigxm2: zero-inflated Negative Binomial

*freq.zigam2 is unavailable as algorithm did not converge.*

**For severity:**
* sev.gxm1: Gamma
* sev.gxm2: Lognormal

**For aggregate:**
* total.gxm1: Tweedie, 1<p<2
* total.gxm2: zero-inflated/adjusted Gamma

*total.gam2 is too large, see [Google Drive] instead.*
