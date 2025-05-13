# EnsembleGold: Modifying Marigold’s for Improved Monocular Depth Estimation

**Satyam Sharma | CS 280 Final Project**

_Please note: this page is a work in progress_

[![Open in Colab](https://img.shields.io/badge/Open_-_Colab-orange?style=flat-square&logo=googlecolab)](https://colab.research.google.com/gist/satshar07/ad32fb482bb7be10b0a83e4d635369f3/280_final_project___satyam_sharma.ipynb)


## 🚀 Overview  
**EnsembleGold** is an enhanced monocular depth estimation pipeline built on the Marigold/Stable Diffusion backbone. It delivers:  

1. **Ensemble Consensus Sampling** — combines multiple denoising trajectories with “mean + re-noise” to reduce variance
2. **Per-Scene Affine Alignment** — solves a least-squares scale & shift to match ground‐truth distributions
3. **Optimized DDIM Schedule** — increases inference steps for finer detail

On NYU-Depth V2, our method achieves **AbsRel 0.0856**, **RMSE 0.3250**, and **SiLog 12.40** on 15 test scenes, using 20 denoising steps and an ensemble size of 5, slightly outperforming Marigold's performance in the same context.

| Original Sample Data | Marigold DepthMap | EnsembleGold DepthMap |
| :------------------: | :---------------: | :-------------------: |
|<img width="300" alt="Screenshot 2025-05-12 at 11 52 51 PM" src="https://github.com/user-attachments/assets/74067a71-e49a-4be0-a37f-b8d90416428e" /> | <img width="300" alt="Screenshot 2025-05-12 at 11 53 12 PM" src="https://github.com/user-attachments/assets/90afb15b-88e1-4938-b0be-37f43da44b05" /> | <img width="300" alt="Screenshot 2025-05-12 at 11 53 50 PM" src="https://github.com/user-attachments/assets/be92de56-ac04-441e-9658-c5ae0a633372" /> |
|<img width="300" alt="Screenshot 2025-05-12 at 11 55 39 PM" src="https://github.com/user-attachments/assets/9e3cb620-d4d3-4e0d-9d20-86ffc04ecee1" /> | <img width="300" alt="Screenshot 2025-05-12 at 11 56 16 PM" src="https://github.com/user-attachments/assets/0dbb8968-3a88-41b9-9ab1-d26c7fe16c14" /> | <img width="310" alt="Screenshot 2025-05-12 at 11 57 36 PM" src="https://github.com/user-attachments/assets/7c30b6c9-2368-4a7c-ae88-072c962d043f" /> | 
| <img width="300" alt="Screenshot 2025-05-13 at 12 15 36 AM" src="https://github.com/user-attachments/assets/4d573d3e-8437-4d13-8a9d-e2bbfc79774e" /> | <img width="300" alt="Screenshot 2025-05-13 at 12 15 56 AM" src="https://github.com/user-attachments/assets/3c1b2ead-7bb3-46a5-8bb7-636a8fd98de8" /> | <img width="300" alt="Screenshot 2025-05-13 at 12 16 54 AM" src="https://github.com/user-attachments/assets/dbe3840c-f39e-420c-8616-068c8275245d" /> | 







## How you


## 🤝 Acknowledgements
Special thanks to Prof. Kanazawa, Rahul Ravishankar, and Aarav Shah for helping with direction, feedback and advice for this project.





