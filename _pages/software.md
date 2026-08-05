---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## dcameaipe (R package)

An R package to estimate the **Average Interactive Partial Effect (AIPE)** and the **Difference in Conditional Average Marginal Effects (D-CAME)** for interactive treatment effects, using flexible (polynomial / B-spline / GAM) functional forms for the treatment-by-moderator interaction — rather than assuming the interaction is linear.

Companion package to Serrano-Serrat, *"The Pitfalls of Assuming Linear Treatment Effects in Interaction Tests,"* forthcoming in *Sociological Science* (2026).

**Installation:**
```r
# install.packages("remotes")
remotes::install_github("SerranoSerrat/dcameaipe")
```

[View on GitHub](https://github.com/SerranoSerrat/dcameaipe)
