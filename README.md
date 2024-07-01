# OPSSAT-AD
Code of the OPS-SAT benchmark for detecting anomalies in satellite telemetry.

This package provides a novel collection of satellite telemetry for anomaly detection. It has been prepared and evaluated with the help of satellite operators and includes data from the ESA OPS-SAT aircraft, the first flying nanosatellite laboratory.

## Configurations Tested

* python 3.9 (the Python configuration we used is detailed in the included `requirements.txt` file).

## How to use and how to cite

- The two data files required for this code can be found in this repository [^1].
- The paper [^2] provides benchmark results of 30 supervised and unsupervised anomaly detection models on this dataset.
- In the other conference paper we presented some preliminary results on this dataset [^3].

## References

[^1] DATA: OPSSAT-AD - anomaly detection dataset for satellite telemetry [Zenodo:12588359](https://doi.org/10.5281/zenodo.12588359).

[^2] JOURNAL PAPER: Ruszczak, B., Kotowski. K., Evans, D., Nalepa, J.: The OPS-SAT benchmark for detecting anomalies in satellite telemetry, 2024, [preprint arXiv:5555.6666](https://arxiv.org/abs/5555.6666).

[^3] CONFERENCE PAPER: Ruszczak, B., Kotowski. K., Andrzejewski, J., et al.: (2023). Machine Learning Detects Anomalies in OPS-SAT Telemetry. Computational Science – ICCS 2023. LNCS, vol 14073. Springer, Cham.  [DOI:10.1007/978-3-031-35995-8_21](https://doi.org/10.1007/978-3-031-35995-8_21).