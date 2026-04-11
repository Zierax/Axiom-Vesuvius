# Axiom-Vesuvius

### "Efficiency is the highest form of intelligence."

This repository presents the results of a **Non-Brute-Force Reconstruction** of the Herculaneum papyri. While the current industry standard relies on massive GPU clusters and redundant neural layers to "guess" ink patterns through statistical probability, I approached the ink-detection bottleneck as a pure **Symbolic Logic** problem.

## Visual Proof & Data Integrity
The reconstruction focuses on absolute clarity. We are not "generating" what we think the ink looks like; we are isolating it.

* **Fragment 1 Overview:** [View Performance Chart](https://github.com/Zierax/Axiom-Vesuvius/blob/main/Benchmark/charts/Frag1_overview.png)
* **Ink Mask Result:** [View Isolated Ink](https://github.com/Zierax/Axiom-Vesuvius/blob/main/Benchmark/per_fragment/Frag1/ink_mask.png)
* * **The What (Mathimatical way to reach the same results without showing the Source Code):** [View](https://github.com/Zierax/Axiom-Vesuvius/blob/main/Logic.md)

## The Metrics (Hardware-Agnostic Precision)
These results were achieved in a **single 4-hour window** on a standard 8GB RAM laptop. Unlike traditional methods that compensate for weak algorithms with massive compute power, this is the result of **Mathematical Intuition** applied to carbonized telemetry.

| Metric | Value |
| :--- | :--- |
| **F1-Score** | **0.9661** |
| **Precision** | **0.9685** |
| **Recall** | **0.9638** |
| **Total Ink Pixels** | 83,612 |
| **Predicted Pixels** | 83,205 |
| **Total coding Time Start2End** | 17 hour |
| **Inference Time** | **200 minutes** |
| **Environment** | **Consumer Laptop (8GB RAM)** |


**Architect’s Note:** The 3,030 False Negatives are a conscious architectural choice. In forensic reconstruction, **Verifiable Integrity** is paramount. I have no interest in "AI hallucinations" or probabilistic filler that looks good but lacks historical truth. I leave the "predictive guessing" to those with more GPUs than logic.

## The "Insiders" on Performance
* **Zero Resource Penalty:** While others discuss VRAM limitations, the Axiom engine operates within the noise floor of a standard OS. If your algorithm requires a cluster to see ink, the problem isn't the data—it's the architecture.
* **Deterministic vs. Stochastic:** This engine doesn't "learn" to see; it is programmed to **understand** the physical constraints of ink on papyrus. Complexity is not an excuse for inefficiency.

## Operational Constraints
This research is currently on hold due to environmental, not algorithmic, factors:

1.  **Infrastructure Latency:** Operating from Egypt involves navigating severe data caps. Downloading 3TB+ of raw CT scans is a logistical joke, not a technical challenge.
2.  **Academic Obligations:** I am finishing my **Senior Year** of high school (graduation in 3 months). Briefly entertaining the local educational system is a necessary pause before returning to higher-level logic.

## Status: Paused
I will resume the reconstruction of the remaining scrolls once I am in an environment that respects the bandwidth requirements of high-fidelity data acquisition. Until then, these metrics stand as a proof that **Algorithmic Elegance** will always outperform raw compute.

---

**"Computational power is often used as a mask for inefficient logic."**

**Date:** April 8, 2026  
**Researcher:** Ziad Salah
