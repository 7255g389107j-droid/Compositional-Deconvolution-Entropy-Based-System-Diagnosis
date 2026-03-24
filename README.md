# Compositional-Deconvolution-Entropy-Based-System-Diagnosis
Itagaki-Chaos-Engine (V7.0/V8.0): Triple-Metric System for Compositional Deconvolution and Entropy-Based Chaos Scoring in R. Overcoming Aitchison’s limit via Poisson-Aitchison-Ohta Triple Stability Metrics.
# Itagaki-Chaos-Engine (V8.0) 🚀
**Ultimate Compositional Deconvolution & Entropy-Based System Diagnosis**

Developed by **Tatsuki Itagaki**, this framework addresses the **"Compositional Closure"** problem. It reconstructs absolute scaling factors (Basis Data) from relative abundance and quantifies system collapse (Chaos) when no stable anchors exist.

## ⚖️ Scientific Philosophy
> "Physical standards are often sources of noise. The true reference exists within the data—the ensemble of components that remain statistically and physically motionless. When this motionlessness disappears, the system itself is in a state of 'Chaos'."

## 🛠 Key Features
- **Triple-Metric Validation**: Proves "immovability" through Physics (Poisson), Geometry (Aitchison), and Statistics (Ohta).
- **Automated Anchor Selection**: Dynamic Elbow-Cliff Logic identifies the optimal number of anchors.
- **Chaos Scoring (V8.0)**: Quantifies the "Depth of Chaos" (System Entropy) when invariant components are lost.
- **Pure Base R Implementation**: Zero external dependencies. Designed for reproducibility.
- **Publication-Ready Output**: Integrated diagnostic reports and staggered labeling for complex plots.

## 📊 The Chaos Metrics (V8.0)
When the system exceeds the **Critical Point**, standard deconvolution fails. This engine then shifts to **Chaos Diagnostics**:
1. **Physical Chaos ($S_p$)**: Measures deviation from the Poisson Noise Floor (External Disturbance).
2. **Geometric Chaos ($S_g$)**: Measures loss of structural coherence in the Simplex (System Disintegration).
3. **Statistical Chaos ($S_s$)**: Measures the absence of a dominant reference (Anarchy/Reference Loss).

## 🚀 Quick Start

1. **Prepare Data**: Load your proportion matrix (Samples as Rows, Taxa as Columns).
2. **Run Deconvolution (V7.0)**: Estimate absolute total mass and invariant anchors.
3. **Run Chaos Diagnosis (V8.0)**: Use `diagnose_chaos_v8()` to identify system collapse.

## 📦 Requirements
- **Language**: R (Base R only)
- **Input**: Non-negative numeric matrix/dataframe (`Dataset`).

## 📜 License
MIT License - Copyright (c) 2026 Tatsuki Itagaki

## 🎓 Academic Citation & Credits

This research and implementation are the original works of **Tatsuki Itagaki**. If you use this software, its logic, or the Chaos Scoring system in your research, please cite the following:

1. **Methodology & Implementation (Basis idea)**:
   Itagaki, T. (2026). *Deciphering Compositional Chaos Identifying Invariant Anchors and System Perturbations using Physics, Geometry, and Statistics*. 
   **DOI: 10.13140/RG.2.2.21953.93284**
   [ResearchGate Method Page](https://www.researchgate.net/publication/403086762_Deciphering_Compositional_Chaos_Identifying_Invariant_Anchors_and_System_Perturbations_using_Physics_Geometry_and_Statistics)

2. **Theoretical Anchor (Mathematical Basis)**:
   Ohta, T. (2011). *Identification of the Unchanging Reference Component of Compositional Data from the Properties of the Coefficient of Variation*. Mathematical Geosciences, 43, 223–244. 
   DOI: 10.1007/s11004-011-9332-y

---
**Author:** Tatsuki Itagaki  
**Copyright (c) 2026 Tatsuki Itagaki. All rights reserved.**  
**License:** MIT License (Software) / CC BY 4.0 (Logic/Text)


---
*"Even if it is an inconvenient truth, convey it as it is." — Tatsuki Itagaki*
