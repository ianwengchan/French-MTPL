TO MODIFY MODEL DESCRIPTIONS


3 model categories: for frequency (freq), severity (sev) and aggregate.

**For frequency:**
* freq.ZIpoisson: zero-inflated Poisson, with 4 latent classes
* freq.ZIgammacount: zero-inflated Gamma Count, with 4 latent classes
* freq.ZIgammacount5: zero-inflated Gamma Count, with 5 latent classes

**For severity:**
* sev.gammax: Gamma, with x={empty}, 6, 8 corresponding to 4, 6, 8 latent classes
* sev.lnormx: Lognormal, with x={empty}, 6, 8 corresponding to 4, 6, 8 latent classes

**For aggregate:**
* 1_lll: zero-inflated Lognormal, with 3 latent classes
* 1_llll: zero-inflated Lognormal, with 4 latent classes
* 1_lllll: zero-inflated Lognormal, with 5 latent classes
* 1_llllll: zero-inflated Lognormal, with 6 latent classes
* 1_llblll: zero-inflated Lognormal and Burr, with 6 latent classes in total
