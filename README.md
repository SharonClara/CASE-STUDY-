# CASE-STUDY-
## Name :   Sharon Clara A
## Reg no : 212224040310

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

Problem 1: Encryption Time Calculation

A company uses AES-256 encryption to secure its data before uploading it to the cloud. It takes 0.05 seconds to encrypt 1 MB of data.

Q: How long will it take to encrypt 2 TB of data before upload?
```
ANS : Binary TB 1 TB = 1024 GB, 1 GB = 1024 MB
• MB count: 2 X 1024 x 1024 = 2,097,152 MB
• Time: 2,097,152 X 0.05 s/MB = 104,857.6 seconds.
• Convert to hours/min/sec:
o Hours = 104,857.6 / 3600 = 29 Hours.
o Remainder seconds = 104,857.6 - 29 X 3600 = 459.6 s.
o Minutes = 459.6/60 = 7 minutes.
o Seconds = 459.6 - 7 X 60 = 39.6s
• Result: 29 hours, 7 minutes, 39.6 seconds (≈ 29.13 hours).

```
Problem 2:CPU Utilization Efficiency

A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.

Q: What is the CPU utilization efficiency?
```
 ANS: Formula: Efficiency = used vCPUs / allocated vCPUs.
 Calculation: 5.5÷8=0.68755.5
 Result: 68.75% CPU utilization efficiency.

```
Problem 3: Network Throughput Efficiency

A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only uses 600 Mbps.

Q: What is the network throughput efficiency?
```
ANS: Formula: Efficiency: actual throughput / maximum bandwith.
Calculation: 600Mbps / 1000Mbps = 0.6
• Result: 60% network throughput efficiency.
```
Problem 4:Energy Efficiency

Two cloud setups process the same workload:

Setup A uses 500W for 2 hours. Setup B uses 300W for 3.5 hours. Q: Which setup is more energy-efficient?

```
ANS: Setup A: 500W X 2h = 1000Wh = 1.00kWh.
• Setup B: 300 W X 3.5h = 1050 Wh = 1.05kWh.
• Conclusion: Setup A uses 1.00 kWh vs Setup B 1.05 kWh for the same workload, so
Setup A is more energy-efficient (it uses less total energy).
```

Problem 5:

CPU Utilization Efficiency

A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 75%.

Q: What is the maximum number of VMs that can be efficiently hosted?
```
ANS: Server cores: 16.
• Cores per VM: 2 → theoretical max VMs = 16 / 2 = 8
• But optimal utilization is 75%, so allowable cores = 16×0.75=1216 =12 cores for
efficient operation.
• Max VMs at 75%: 12÷2 =6 VMs (must be a whole number).
• Result: 6 VMs can be efficiently hosted at 75% optimal CPU utilization.
```
