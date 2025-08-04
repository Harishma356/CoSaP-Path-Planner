# CoSaP: Cognitive Sampling-based Potential-driven Online Planner

This repository accompanies the submission of the paper:

**"Cognitive Sampling-based Potential-driven Online Planner (CoSaP) for Autonomous Mobile Robots"**  
Author: Harishma Prakash  
Affiliation: Chennai Institute of Technology, India

---

## 🧭 Overview

**CoSaP** is a novel path planning algorithm designed to operate efficiently in **completely unknown environments**. It intelligently samples nodes in the space using cognitive based goal-biased heuristics, deriving potential field paths for local goal opted from sampled nodes in iteration until the goal is reached.

> 🚫 **Note**: The core pseudocode and implementation details are withheld due to current journal review. This repository provides validated results and context for review purposes only.

---

## 🎯 Key Highlights

- Efficient global path planner in both **unknown** and **known** environments
- Works without prior maps, compatible with SLAM/local planners like DWA
- Demonstrates better performance than classical planners; RRT, D* Lite, A*, Bug2 (As per the benchmark results) in:
  - ⏱️ Time to goal
  - 📏 Path optimality
  - 💾 Memory and computation cost

---

## 📊 Benchmark Results

This repository includes:

- 📈 Performance comparison graphs
- 🧪 Simulation snapshots from Matplotlib-based planner
- 🧮 Environment setups used for evaluation (grid maps)

Please see the [`/benchmark_results`](./benchmark_results) folder for plots and benchmark graphs.

---

## 🔐 License

This work is shared under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.  
You may view and share, but **not reuse or modify** the contents.

[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

### Dataset / Benchmark Map

The map (map_clean.png) used for benchmarking CoSaP were obtained from the Moving AI Lab's pathfinding benchmark suite:

> N. Sturtevant, “Benchmarks for grid-based pathfinding,” Moving AI Lab, [Online]. Available: [https://movingai.com/benchmarks/dao/index.html](https://movingai.com/benchmarks/dao/index.html). Accessed on: Jul. 15, 2025.

Please refer to their site for reuse policies and citation requirements.

---

## 📬 Contact

For academic inquiries, feel free to reach out:

**Harishma Prakash**  
Undergraduate Researcher  
Chennai Institute of Technology, India  
GitHub: [@Harishma356](https://github.com/Harishma356)  
Email: *[harishmaprakash.2006@gmail.com]*

---

