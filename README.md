[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

# Vichalana Anomaly Benchmark
This repository contains a time-series, multivariate dataset which can be used in performance anomaly detection in API Gateways. 
Vichalana Anomaly Benchmark can be used for evaluating anomaly detection algorithms. It comprises with 25 features and total of 
~50,000 data points. This dataset is generated using a industry standard setup of API Gateway.

Merged anomaly dataset can be found in `/combined_dataset`
The individual parts of the normal dataset can be found in `/normal_datasets`
The anomalous dataset can be found in `/anomalous_datasets`

Details of  anomalous dataset are given below

1.  `Scenario 01`: High CPU usage due to mediation (`Type 1`)
2.  `Scenario 02`: High Memory usage due to mediation (`Type 2`)
3.  `Scenario 03`: High disk I/O due to mediation (`Type 3`)
4.  `Scenario 04`: Increased load  (numbers of users) (`Type 4`)
5.  `Scenario 05`: Increased load (throughput) (`Type 4`)
6.  `Scenario 06`: Long response time in back-end services  (`Type 5`)
7.  `Scenario 07`: Increased message size (`Type 6`)
8.  `Scenario 08`: Failure in back-end services (`Type 7`)
9.  `Scenario 09`: Increased load (throughput) (`Type 4`)
10. `Scenario 10`: Increased message size (`Type 6`)
