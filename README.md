# CoSaP: Cognitive Sampling-based Potential-driven Online Planner

This repository accompanies the submission of the paper:

**"Cognitive Sampling-based Potential-driven Online Planner (CoSaP) for Autonomous Mobile Robots"**  
Submitted to: *IEEE Transactions on Robotics (T-RO)*  
Author: Harishma Prakash  
Affiliation: Chennai Institute of Technology, India

---

## 🧭 Overview

**CoSaP** is a novel path planning algorithm designed to operate efficiently in **completely unknown environments**. It intelligently samples the navigation space using goal-biased heuristics, moving towards the final goal by drawing chunks of potential gradient to pave a smooth path.

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
- 📝 Complexity analysis overview

Please see the [`/benchmark_results`](./benchmark_results) folder for plots and benchmark graphs.

---

## 🔐 License

This work is shared under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.  
You may view and share, but **not reuse or modify** the contents.

[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---


## 📬 Contact

For academic inquiries, feel free to reach out:

**Harishma Prakash**  
Undergraduate Researcher  
Chennai Institute of Technology, India  
GitHub: [@Harishma356](https://github.com/Harishma356)  
Email: *[harishmaprakash.2006@gmail.com]*

---

