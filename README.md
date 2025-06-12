# Cross-frame Representation Alignment for Fine-tuning Video Diffusion Models

⏳ The code will be released soon!

[Paper](https://arxiv.org/abs/2506.09229) | [Project page](https://crepavideo.github.io)

> [Sungwon Hwang\*](https://deepshwang.github.io), [Hyojin Jang\*](https://github.com/Whit3Snow), [Kinam Kim](https://kinam0252.github.io/), [Minho Park](https://pmh9960.github.io/) and [Jaegul Choo](https://sites.google.com/site/jaegulchoo/)  
> KAIST
> 
> arXiv 2025. (\* indicate equal contribution)

> **Abstract:**
> Fine-tuning Video Diffusion Models (VDMs) at the user level to generate videos that reflect specific attributes of training data presents notable challenges, yet remains underexplored despite its practical importance. 
> Meanwhile, recent work such as Representation Alignment (REPA) has shown promise in improving the convergence and quality of DiT-based image diffusion models by aligning, or assimilating, its internal hidden states with external
> pretrained visual features, suggesting its potential for VDM fine-tuning. 
> In this work, we first propose a straightforward adaptation of REPA for VDMs and empirically show that, while effective for convergence, it is suboptimal in preserving semantic consistency across frames. 
> To address this limitation, we introduce Cross-frame Representation Alignment (CREPA), a novel regularization technique that aligns hidden states of a frame with external features from neighboring frames. 
> Empirical evaluations on large-scale VDMs, including CogVideoX-5B and Hunyuan Video, demonstrate that CREPA improves both visual fidelity and cross-frame semantic coherence when fine-tuned with parameter-efficient methods such as
> LoRA.
> We further validate CREPA across diverse datasets with varying attributes, confirming its broad applicability. 
