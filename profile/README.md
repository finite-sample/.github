## Finite Sample

Practical, well‑documented tooling for applied statistics and econometrics: deployable probability calibration, exact thresholding for stepwise metrics, stable trees, projection‑pursuit dimension reduction, nonparametric smoothing, and time‑series trend estimation. Several libraries are scikit‑learn compatible; others target R directly or expose R’s capabilities to AI assistants via MCP.

### Selected projects

- **RMCP** — Model Context Protocol server that brings R’s statistical stack to AI assistants and web apps (Python/HTTP interfaces).  
  [Docs](https://finite-sample.github.io/rmcp/) • [GitHub](https://github.com/finite-sample/rmcp)

- **Calibre** — Advanced probability calibration: nearly‑isotonic, spline‑based, relaxed/regularized isotonic, locally smoothed; includes plateau diagnostics.  
  [Docs](https://finite-sample.github.io/calibre/) • [GitHub](https://github.com/finite-sample/calibre)

- **Rank‑Preserving Calibration** — Calibrate multiclass probabilities to match known totals **without** breaking within‑class ranking (Dykstra projections; strict or nearly‑isotonic options; ADMM variant).  
  [Docs](https://finite-sample.github.io/rank-preserving-calibration/) • [GitHub](https://github.com/finite-sample/rank-preserving-calibration)

- **Optimal Classification Cutoffs** — Exact \(O(n\log n)\) thresholding for F1/precision/recall/accuracy, cost‑sensitive utilities, multiclass strategies; scikit‑learn API.  
  [Docs](https://finite-sample.github.io/optimal-classification-cutoffs/) • [GitHub](https://github.com/finite-sample/optimal-classification-cutoffs)

- **pyppur** — Projection‑pursuit dimensionality reduction optimizing distance distortion or reconstruction loss; scikit‑learn API.  
  [Docs](https://finite-sample.github.io/pyppur/) • [GitHub](https://github.com/finite-sample/pyppur)

- **stable‑cart** — Decision trees designed to lower cross‑bootstrap prediction variance (less‑greedy, robust, variance‑penalized); fully scikit‑learn compatible.  
  [Docs](https://finite-sample.github.io/stable-cart/) • [GitHub](https://github.com/finite-sample/stable-cart)

- **hessband** — Analytic‑Hessian LOOCV/LSCV bandwidth selection for univariate Nadaraya–Watson regression and KDE.  
  [Docs](https://finite-sample.github.io/hessband/) • [GitHub](https://github.com/finite-sample/hessband)

- **incline** — Trend‑at‑a‑point estimators (Savitzky–Golay, splines) for noisy time series, with first/second‑derivative options.  
  [Docs](https://finite-sample.github.io/incline/) • [GitHub](https://github.com/finite-sample/incline)

- **guess (R/CRAN)** — Adjust pre/post knowledge‑gain estimates for guessing (methods and vignettes).  
  [Docs](https://finite-sample.github.io/guess/) • [CRAN](https://cloud.r-project.org/package=guess) • [GitHub](https://github.com/finite-sample/guess)
