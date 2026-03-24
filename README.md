# FourTaStiC (R package)

<!-- badges: start -->
<!-- badges: end -->

**4TaStiC**: Time and trend traveling time series clustering by Preedasawakul and Wiroonsri (2026).

The package is designed for clustering and visualization of time series, especially when similar trajectories may occur with delays or slight trend changes.


The **4TaStiC** dissimilarity addresses this by combining:

- a **correlation-based dissimilarity** for measuring similarity in shape, and
- a **weighted Euclidean distance** for measuring magnitude differences,

while allowing candidate alignments through time shifts and trend tilts.

## Main features

The package includes functions for:

- computing pairwise **4TaStiC dissimilarities**
- storing the **best pairwise alignment**
- preparing **reference-aligned series** for visualization
- plotting aligned time series within clusters
- performing clustering using the 4TaStiC dissimilarity
- artificial dataset for illustrating the use of the 4TaStiC framework.
- 
## Installation

You can install the development version from GitHub using:

```r
# install.packages("remotes")
remotes::install_github("O-PREEDASAWAKUL/FourTaStiC")
```

## References
Preedasawakul, O., and Wiroonsri, N., 4TaStiC: Time and trend traveling time series clustering for classifying long-term type 2 diabetes patients, <i>ACM Transactions on Computing for Healthcare</i>, 2026.

## License

The FourTaStiC package as a whole is distributed under [GPL(>=3)](https://www.gnu.org/licenses/gpl-3.0.en.html).
