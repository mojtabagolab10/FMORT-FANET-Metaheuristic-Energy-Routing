# FMORT: Energy-Optimized Meta-Heuristic Routing Framework for UAV-based FANET (2024)
Hybrid meta-heuristic routing framework for energy consumption and execution-time optimization in UAV-based FANET networks (FMORT, 2024).

## 🔗 DOI
https://doi.org/10.1016/j.comnet.2024.110869

Published in: Computer Networks (Elsevier)

---

# 🌍 Executive Summary

Unmanned Aerial Vehicles (UAVs) operate under strict constraints:

- Limited onboard energy  
- High mobility in 3D space  
- Rapid topology changes  
- Real-time routing requirements  
- Network instability risk  

Traditional MANET and VANET routing protocols fail under aerial mobility dynamics.

FMORT introduces a hybrid meta-heuristic routing framework for Flying Ad Hoc Networks (FANETs) that simultaneously optimizes:

• Energy Consumption  
• Real Execution Time  
• Network Lifetime  
• Packet Delivery Ratio (PDR)  
• End-to-End Delay  
• Re-clustering Overhead  

---

# 🚨 The Core Challenge

FANET routing is significantly more complex than terrestrial ad-hoc networks because:

- UAV nodes move in 3D with high velocity  
- Connectivity is highly dynamic  
- Frequent re-clustering increases overhead  
- Energy depletion leads to network fragmentation  

Existing methods often optimize only one objective (e.g., delay or energy).

FMORT performs multi-objective hybrid optimization.

---

# 💡 FMORT Innovation

FMORT integrates two swarm-intelligence algorithms:

### 1️⃣ Sparrow Optimization Algorithm  
### 2️⃣ Dragonfly Algorithm  

These operate simultaneously for:

- Intelligent cluster-head selection  
- Energy-balanced routing path determination  
- Mobility-aware re-clustering  
- Redundancy reduction  

---

# 🧠 Sensitivity-Driven Architecture

The framework introduces:

### ✔ Intelligent Threshold Detection
Dynamic thresholding based on:

- Node energy
- Sensitivity rate
- Network density
- Mobility state

Prevents overloading and underloading.

---

### ✔ Euclidean Distance-Based Scoring

Cluster heads are selected using:

- Average Euclidean distance  
- Node connectivity  
- Residual energy  
- Sensitivity classification  

This reduces unnecessary packet retransmissions.

---

### ✔ Hybrid Vision Range Regulation

FMORT integrates upper and lower vision ranges in aerial networking, balancing:

- Coverage stability  
- Isolation risk  
- Energy expenditure  

---

# 🔬 Experimental Setup

Simulation Tools:

- OPNET  
- MATLAB  

Network Scale:

40 – 160 UAV nodes  

Metrics Evaluated:

- Energy Consumption  
- Network Lifetime  
- Transmission Delay  
- Packet Delivery Ratio  
- Re-cluster Lifetime  
- Routing Overhead  

---

# 📊 Performance Gains

Compared to MWCRSF and other benchmark algorithms:

• 0.73% reduction in energy consumption  
• 2.23% increase in network lifetime  
• 1.35% reduction in re-cluster construction time  
• 0.11% improvement in re-cluster lifetime  

Performance becomes more stable under:

- High mobility  
- Large swarm density  
- Dynamic workload transmission  

---

# 🌱 Sustainability & Operational Impact

Energy reduction in UAV swarms directly impacts:

- Mission duration  
- Recharge cycles  
- Carbon footprint  
- Operational cost  

FMORT improves aerial swarm endurance and routing stability.

---

# 🛠 Technical Pipeline

1. Node classification via sensitivity rate  
2. Hybrid Sparrow–Dragonfly optimization  
3. Cluster head determination  
4. Threshold-based mobility regulation  
5. Dynamic re-clustering  
6. Load-balanced routing  

---

# 🛰 Real-World Applications

- Military UAV swarm coordination  
- Disaster management  
- Smart agriculture monitoring  
- Surveillance systems  
- Search & rescue missions  
- Remote sensing networks  

---

# 📄 Publication Details

Title:
FMORT: The Meta-Heuristic Routing Method by Integrating Index Parameters to Optimize Energy Consumption and Real Execution Time Using FANET

Authors:
Arash Ghorbannia Delavar  
Zahra Jormand  

Journal:
Computer Networks  

Year:
2024  

DOI:
10.1016/j.comnet.2024.110869  

---

# 📚 Citation (APA)

Ghorbannia Delavar, A., & Jormand, Z. (2024). FMORT: The meta-heuristic routing method by integrating index parameters to optimize energy consumption and real execution time using FANET. Computer Networks. https://doi.org/10.1016/j.comnet.2024.110869

---

# 📚 Citation (BibTeX)

@article{FMORT2024,
  title={FMORT: The Meta-Heuristic Routing Method by Integrating Index Parameters to Optimize Energy Consumption and Real Execution Time Using FANET},
  author={Ghorbannia Delavar, Arash and Jormand, Zahra},
  journal={Computer Networks},
  year={2024},
  doi={10.1016/j.comnet.2024.110869}
}

---

# 🏫 Affiliation

Department of Computer Science  
Payame Noor University, Tehran, Iran  

---

# ⚖ License

This repository is created for academic indexing, discoverability, and research visibility purposes.  
All publication rights belong to the journal publisher.

---

# ⭐ Research Optimization Series (2022–2025)

This repository is part of a structured research line focused on:

• Energy-Aware Networking  
• Hybrid Meta-Heuristic Optimization  
• Sensitivity-Driven Resource Allocation  
• Load Balancing in Dynamic Systems  
• Sustainable Distributed Networks  
