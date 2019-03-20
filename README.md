[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

# The Vichalana Anomaly Benchmark
This repository contains a time-series, multivariate dataset with a benchmark which can be used in performance anomaly detection in API Gateways. 
Vichalana Anomaly Benchmark can be used for evaluating anomaly detection algorithms. It comprises with 25 features and total of 
~50,000 datapoints. This dataset is synthetically generated using a industry standard setup of API Gateway.

Final anomaly dataset can be found in /combined_dataset
The individual parts of the normal dataset can be found in /normal_datasets
The anomalous datasets can be found in /anomalous_datasets

Details of  anomalous datasets are given below

scenario 1: High CPU usage due to mediation (Type 1)
scenario 2: High Memory usage due to mediation (Type 2)
scenario 3: High disk I/O due to mediation (Type 3)
scenario 4: Increased load  (numbers of users) (Type 4)
scenario 5: Increased load (throughput) (Type 4)
scenario 6: Long response time in back-end services  (Type 5)
scenario 7: Increased message size (Type 6)
scenario 8: Failure in back-end services (Type 7)
scenario 9: Increased load (throughput) (Type 4)
scenario 10: Increased message size (Type 6)

## Scoreboard
The Vichalana Anomaly Benchmark scores are normalized in such a way that the score for perfect detctor is 100.0 and the score for null detector is 0.0

Technique | Score
------------ | -------------
Box plot Analysis | 4.92
LSTM |
