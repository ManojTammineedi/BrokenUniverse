# Bio-Physical Inconsistency Detection in Diffusion-Generated Videos

## Overview

This repository accompanies the research paper:

**_Bio-Physical Inconsistency Detection in Diffusion-Generated Videos_**

The work proposes a **theoretical detection framework** for identifying state-of-the-art diffusion-generated videos by analyzing violations of **physical, biological, and geometric invariants**, rather than relying on appearance-based artifacts or supervised classifiers.

The core thesis is that modern generative video models are **masters of visual plausibility, not simulators of reality**. As a result, they inevitably produce subtle but measurable inconsistencies that violate the laws governing real biological and physical systems.

> **You are not looking for a fake person; you are looking for a broken universe.**

---

## Key Contributions

This framework introduces five complementary detection principles:

1. **Latent Trajectory Incoherence**  
   Detects phase drift and micro-stutter in latent dynamics caused by stochastic diffusion sampling.

2. **Spatio-Temporal Spectral Gaps**  
   Identifies unnatural temporal frequency spikes via 3D FFT analysis, violating biological 1/f motion statistics.

3. **Biometric Volumetric Inconsistency (rPPG)**  
   Exploits the absence of coherent cardiovascular dynamics and subsurface scattering in synthetic skin.

4. **Projective Geometry Violations**  
   Measures depth drift and reprojection errors that violate rigid-body and epipolar constraints.

5. **Occlusion Boundary Entropy**  
   Detects failures in physical occlusion modeling via boundary entropy and PSF inconsistencies.

Together, these signals form a **Bio-Physical Inconsistency Score** that is model-agnostic and architecture-independent.

---

## Repository Status

⚠️ **Important Note on Implementation**

This repository currently focuses on the **theoretical framework, mathematical formulation, and system architecture**.

**I do not currently have access to a GPU capable of running large-scale video diffusion models or performing high-throughput empirical evaluation.**

As a result:

- This work is presented as a **theoretical and conceptual foundation**
- No large-scale experimental benchmarks are included
- The framework is intended to **guide future empirical implementations** by researchers with suitable compute resources

This limitation is **explicitly acknowledged** as part of the research scope.

---

## Intended Use

This work is suitable for:

- PhD proposals and qualifying exams  
- Position papers and theory papers (CVPR / ICCV / NeurIPS workshops)  
- Foundations for future empirical deepfake detection systems  
- Research into physics-based and biology-aware AI safety methods  

---

## Future Work

Planned extensions (compute permitting):

- Empirical validation on real vs diffusion-generated video datasets  
- Quantitative evaluation of each invariant signal  
- Robustness analysis against adversarially physics-aware generators  
- Integration with differentiable physics and biological simulators  

---

## Disclaimer

This project is **not a trained classifier** and is **not intended for production deployment** in its current form.  
It is a **research framework** designed to reframe deepfake detection as a **computational physics problem**, not a perceptual one.

---

## Citation

If you build upon this work, please cite:

