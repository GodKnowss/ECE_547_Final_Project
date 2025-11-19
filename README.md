# ECE 547 Final Project (Heuristic vs Greedy Comparison)

## Overview
This project systematically compares heuristic and greedy Age of Information (AoI) scheduling policies through simulation. 
We analyze their performance under various network conditions to determine when simple greedy approaches are sufficient versus when more sophisticated heuristics are justified.

## What is Age of Information (AoI)?
The age of Information measures the freshness of data in communication systems. 
It quantifies how old the most recently received Information is, 
making it critical for time-sensitive applications like sensor networks and real-time monitoring systems.

## Project Goals
- Implement and simulate both greedy and heuristic AoI scheduling algorithms
- Measure average and peak AoI under varying network conditions
- Identify performance trade-offs between algorithmic complexity and scheduling effectiveness
- Provide practical insights on algorithm selection based on network characteristics

## Hypothesis
We expect the greedy algorithm to:
- Perform comparably to heuristics under light traffic loads
- Experience sharp performance degradation as network load increases
- Struggle with complex traffic patterns where heuristic methods excel

## Methodology
- Simulation-based performance evaluation
- Testing across multiple network scenarios (varying load, topology, traffic patterns)
- Metrics: Average AoI, Peak AoI, computational overhead

## Progress

### Implementation
- [x] Kadota 2019 simulation
- [x] Tripathi 2019 simulation
- [x] Greedy age algorithm implementation
- [ ] Heuristic algorithm implementation
- [ ] Performance comparison framework

### Analysis & Results
- [ ] Light traffic scenario results
- [ ] Heavy traffic scenario results
- [ ] Performance graphs and visualizations

### Deliverables
- [ ] Simulation report
- [ ] Project poster
- [ ] Final paper
- [ ] Presentation video

### Documentation
- [x] GitHub repository setup
- [x] README
- [ ] Code documentation