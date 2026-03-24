# FourTaStiC (R package)

<!-- badges: start -->
<!-- badges: end -->

**4TaStiC**: Time and trend traveling time series clustering by Preedasawakul and Wiroonsri (2026).

The package is designed for clustering time-series data and visualizing the results, especially when similar trajectories occur with delays or slight trend differences.


The **4TaStiC** dissimilarity addresses these complications by combining:

- a **correlation-based dissimilarity** for measuring similarity in patterns, and
- a **weighted Euclidean distance** for measuring magnitude differences,

while finding the best-matched pairwise time shifts and tilting angles.

## Main features

The package includes functions for:

- computing pairwise **4TaStiC dissimilarities**
- storing the **best pairwise alignment parameters**
- preparing **reference-aligned series** for visualization
- plotting aligned time series within clusters
- performing clustering using the 4TaStiC dissimilarity
- artificial dataset for illustrating the use of the 4TaStiC framework.

## Installation

This package can be installed directly through RStudio or other editors by

```r
# install.packages("remotes")
remotes::install_github("O-PREEDASAWAKUL/FourTaStiC")
```

## References
Preedasawakul, O., and Wiroonsri, N., 4TaStiC: Time and trend traveling time series clustering for classifying long-term type 2 diabetes patients, <i>ACM Transactions on Computing for Healthcare</i>, 2026. (https://dl.acm.org/doi/10.1145/3802823)

## License

The FourTaStiC package as a whole is distributed under [GPL(>=3)](https://www.gnu.org/licenses/gpl-3.0.en.html).
