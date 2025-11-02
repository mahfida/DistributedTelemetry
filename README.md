Target field: EXP_TYPE
Bottlenecks Profiles and Experiments

This document summarizes the set of bottleneck scenarios and corresponding experiments conducted to evaluate network performance under varying stress and congestion conditions. The experiments are divided into Single Bottleneck and Composite Bottleneck categories based on the complexity and interaction of network stressors.

🧩 Single Bottleneck Experiments

These experiments isolate and evaluate the impact of a single source of network stress or congestion.
Each experiment (EX3–EX15) targets one bottleneck component at a time to assess its effect on system throughput, latency, and reliability.

Bottleneck	Experiment ID
S1U Congestion	EX3
SGi Congestion	EX4
S1U–SGi Congestion	EX5
SPGWU Stress	EX6
FlexRAN Stress	EX7
SPGWU – 1% Loss	EX8
SPGWU – 5% Loss	EX9
Interference	EX14
Low SPGWU Stress	EX15
⚙️ Composite Bottleneck Experiments

Composite bottlenecks combine multiple concurrent stress factors to simulate more realistic or extreme network conditions.
These scenarios help in identifying how simultaneous network degradations interact and amplify performance issues.

Composite Bottleneck	Experiment ID
SPGWU Stress + FlexRAN Stress	EX10
S1U Congestion + FlexRAN Stress	EX11
S1U Congestion + SPGWU – 5% Loss	EX12
SPGWU Stress + SPGWU – 5% Loss	EX13

🧩If you use this dataset in your research, please cite the following paper:

M.-R. Fida, A. H. Ahmed, T. Dreibholz, A. F. Ocampo, A. Elmokashfi, and F. I. Michelinakis,
“Bottleneck Identification in Cloudified Mobile Networks Based on Distributed Telemetry,”
IEEE Transactions on Mobile Computing, vol. 23, no. 5, pp. 5660–5676, May 2024.
DOI: 10.1109/TMC.2023.3312051

Keywords: Monitoring, Telemetry, Degradation, Cloud computing, Computer architecture, Servers, Mobile computing, Anomaly, Bottleneck, Classification, Congestion, Mobile cloud network, Telemetry.
