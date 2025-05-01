# awesome-diffusion-noise
A collection of noise-aware algorithms in diffusion models.

Please find more details on [this page](https://diffusion-noise.mpi-inf.mpg.de/), including our Eurographics 2025 tutorial slides.


## Gassian (white) noise for image diffusion

- **Denoising diffusion probabilistic models (NeurIPS 2020)** [[code](https://github.com/hojonathanho/diffusion)] [[webpage](https://hojonathanho.github.io/diffusion/)]
- **Denoising Diffusion Implicit Models (ICLR 2021)** [[code](https://github.com/ermongroup/ddim)]
- **Improved denoising diffusion probabilistic models (ICML 2021)** [[code](https://github.com/openai/improved-diffusion)] [[webpage](https://proceedings.mlr.press/v139/nichol21a.html)]
- **SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations (ICLR 2022)** [[code](https://github.com/ermongroup/SDEdit)] [[webpage](https://sde-image-editing.github.io/)]
- **RePaint: Inpainting using Denoising Diffusion Probabilistic Models (CVPR 2022)** [[code](https://github.com/andreas128/RePaint)]
- **High-Resolution Image Synthesis with Latent Diffusion Models (CVPR 2022)** [[code](https://github.com/CompVis/latent-diffusion)]







## Correlated noise for image diffusion

- **Blue noise for diffusion models (SIGGRAPH 2024)** [[code](https://github.com/xchhuang/bndm)] [[webpage](https://xchhuang.github.io/bndm/)]
- **Edge-preserving noise for diffusion models (ICLR 2025 DeLTa workshop)** [[code](https://github.com/Jentuuh/edge-preserving-diffusion/)] [[webpage](https://edge-preserving-diffusion.mpi-inf.mpg.de/)]
- **Factorized Diffusion: Perceptual Illusions by Noise Decomposition (ECCV 2024)** [[code](https://github.com/dangeng/visual_anagrams)] [[webpage](https://dangeng.github.io/factorized_diffusion/)]
- **An Edit Friendly DDPM Noise Space: Inversion and Manipulations (CVPR 2024)** [[code](https://github.com/inbarhub/DDPM_inversion)] [[webpage](https://inbarhub.github.io/DDPM_inversion/)]
- **Multi-Resolution Noise for Diffusion Model Training** [[blogpost](https://wandb.ai/johnowhitaker/multires_noise/reports/Multi-Resolution-Noise-for-Diffusion-Model-Training--VmlldzozNjYyOTU2)]
- **A Traveler’s Guide to the Latent Space (section regarding Perlin noise init)** [[blogpost](https://sweet-hall-e72.notion.site/A-Traveler-s-Guide-to-the-Latent-Space-85efba7e5e6a40e5bd3cae980f30235f)]



## Optimized noise for image diffusion

- **Inference-Time Alignment of Diffusion Models with Direct Noise Optimization (ICML 2024 SPIGM workshop)** [[code](https://github.com/TZW1998/Direct-Noise-Optimization)] [[webpage](https://openreview.net/forum?id=Dqpa8rbL39)]
- **ReNO: Enhancing One-step Text-to-Image Models through Reward-based Noise Optimization (NeurIPS 2024)** [[code](https://github.com/ExplainableML/ReNO)]
- **InitNO: Boosting Text-to-Image Diffusion Models via Initial Noise Optimization (CVPR 2024)** [[code](https://github.com/xiefan-guo/initno)] [[webpage](https://xiefan-guo.github.io/initno/)]
- **A Noise is Worth Diffusion Guidance (2024)** [[code](https://github.com/cvlab-kaist/NoiseRefine)] [[webpage](https://cvlab-kaist.github.io/NoiseRefine/)]
- **Golden Noise for Diffusion Models: A Learning Framework (2024)** [[code](https://github.com/xie-lab-ml/Golden-Noise-for-Diffusion-Models)]


## Task-specfic noise for image diffusion

- **Relay Diffusion: Unifying diffusion process across resolutions for image synthesis (ICLR 2024)** [[code](https://github.com/THUDM/RelayDiffusion)]
- **NoiseCollage: A Layout-Aware Text-to-Image Diffusion Model Based on Noise Cropping and Merging (ICLR 2024)** [[code](https://github.com/univ-esuty/noisecollage)]


## Optimized/correlated noise for motion diffusion

- **Optimizing Diffusion Noise Can Serve As Universal Motion Priors (CVPR 2024)** [[code](https://github.com/korrawe/Diffusion-Noise-Optimization)] [[webpage](https://korrawe.github.io/dno-project/)]
- **Nonisotropic Gaussian Diffusion for Realistic 3D Human Motion Prediction (CVPR 2025)** [[code](https://github.com/Ceveloper/SkeletonDiffusion/tree/main)] [[webpage](https://ceveloper.github.io/publications/skeletondiffusion/)]




## Gaussian (white) noise for video diffusion

- **Video Diffusion Models (NeurIPS 2022)** [[unofficial code](https://github.com/lucidrains/video-diffusion-pytorch)] [[webpage](https://video-diffusion.github.io/)]
- **Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models (CVPR 2023)** [[webpage](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)]




## Correlated noise for video generation

- **How I Warped Your Noise: a Temporally-Correlated Noise Prior for Diffusion Models (ICLR 2024)** [[webpage](https://warpyournoise.github.io/)]
- **Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models (ICCV 2023)** [[webpage](https://research.nvidia.com/labs/dir/pyoco/)]
- **Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators (ICCV 2023)** [[code](https://github.com/Picsart-AI-Research/Text2Video-Zero)] [[webpage](https://text2video-zero.github.io/)]
- **Go-with-the-Flow: Motion-Controllable Video Diffusion Models Using Real-Time Warped Noise (CVPR 2025)** [[code](https://github.com/Eyeline-Research/Go-with-the-Flow)] [[webpage](https://eyeline-research.github.io/Go-with-the-Flow/)]



## Correlated noise for 3D generation

- **MultiDiff: Consistent Novel View Synthesis from a Single Image (CVPR 2024)** [[webpage](https://sirwyver.github.io/MultiDiff/)]
- **Consistent Flow Distillation for Text-to-3D Generation (ICLR 2025)** [[code](https://github.com/runjie-yan/ConsistentFlowDistillation)] [[webpage](https://runjie-yan.github.io/cfd/)]




## Citation

If you find this useful please consider citing:
```
@article{singh2025demystifying,
  author    = {Singh, Gurprit and Huang, Xingchang and Vandersanden, Jente and Öztireli, Cengiz and Mitra, Niloy},
  title     = {Demystifying noise: The role of randomness in generative AI},
  journal   = {Computer Graphics Forum},
  year      = {2025}
}
```







