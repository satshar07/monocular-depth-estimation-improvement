# EnsembleGold: Modifying Marigold’s for Improved Monocular Depth Estimation

**Satyam Sharma | CS 280 Final Project**

_Please note: this page is a work in progress_

[![Open in Colab](https://img.shields.io/badge/Open_-_Colab-orange?style=flat-square&logo=googlecolab)](https://colab.research.google.com/gist/satshar07/ad32fb482bb7be10b0a83e4d635369f3/280_final_project___satyam_sharma.ipynb)


## 🚀 Overview  
**Marigold-Align** is an enhanced monocular depth estimation pipeline built on the Marigold/Stable Diffusion backbone. It delivers:  

1. **Ensemble Consensus Sampling** — combines multiple denoising trajectories with “mean + re-noise” to reduce variance
2. **Per-Scene Affine Alignment** — solves a least-squares scale & shift to match ground‐truth distributions
3. **Optimized DDIM Schedule** — increases inference steps for finer detail

On NYU-Depth V2, our method achieves **AbsRel 0.0856**, **RMSE 0.3250**, and **SiLog 12.40** on 15 test scenes, using 20 denoising steps and an ensemble size of 5, outperforming Marigold's performance in the same context.

## How you


## 🤝 Acknowledgements
Special thanks to Prof. Kanazawa, Rahul Ravishankar, and Aarav Shah for helping with direction, feedback and advice for this project.





