# 🔥 Awesome Controllable Generative Models

A curated and continuously updated collection of **recent (2023–2025)** research papers on **controllable generative models**, with a special focus on both **UNet-based diffusion models** and **Transformer-based diffusion architectures**.

This list emphasizes core advances in:

- 🧭 **Control mechanisms** – including condition injection, adapters, multi-modal control
- 👁️ **Attention interpretation** – revealing what diffusion models focus on
- 🎛️ **Frequency-based control** – using spectral domain knowledge to guide generation
- 🔁 **Alignment & knowledge transfer** – enabling more coherent, faithful, and data-efficient synthesis
- 🧑‍🎨 **Image-to-image (I2I) editing** – flexible, structure-preserving transformation across domains

> 💡 Our goal is not only to track the state-of-the-art in controllable generation, but also to offer a **well-organized knowledge map** for newcomers and researchers building on top of diffusion models.

---

## 🧭 Control Mechanism

| Paper | Venue | Links |
|-------|-------|-------|
| OminiControl: Minimal and Universal Control for Diffusion Transformer | ICCV 2025 (Highlight) | [Paper](https://arxiv.org/abs/2411.15098) \| [Code](https://github.com/Yuanshi9815/OminiControl) |
| Rectified Diffusion Guidance for Conditional Generation | CVPR 2025 | [Paper](https://arxiv.org/abs/2410.18737) \| [Code](#) |
| FlexControl: Computation-Aware Conditional Control with Differentiable Router | ICML 2025 (Poster) | [Paper](https://arxiv.org/abs/2502.10451) \| [Code](https://github.com/Daryu‑Fan/FlexControl) |
| CTRL-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model | ICLR 2025 (Oral) | [Paper](https://openreview.net/forum?id=ny8T8OuNHe) \| [Code](https://github.com/HL-hanlin/Ctrl-Adapter) |
| Ctrl-U: Robust Conditional Image Generation via Uncertainty-aware Reward Modeling | ICLR 2025 | [Paper](https://arxiv.org/abs/2410.11236) \| [Code](https://github.com/grenoble-zhang/Ctrl-U) |
| ConceptCtrl: Concept Control of Zero-shot Personalized Image Generation | arXiv 2025 | [Paper](https://arxiv.org/abs/2503.06568) \| [Code](https://github.com/QY-H00/Conceptrol) |
| Is Noise Conditioning Necessary for Denoising Generative Models? | arXiv 2025 | [Paper](https://arxiv.org/abs/2502.13129) \| [Code](#) |
| Ctrl‑X: Controlling Structure and Appearance Without Guidance | NeurIPS 2024 | [Paper](https://arxiv.org/abs/2406.07540) \| [Code](https://github.com/genforce/ctrl-x) |
| ControlNet++: Improving Conditional Controls with Efficient Consistency Feedback | ECCV 2024 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72667-5_8) \| [Code](#) |
| ControlNet-XS: Rethinking the Control of Text-to-Image Diffusion Models as Feedback-Control Systems | ECCV 2024 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-73223-2_20) \| [Code](#) |
| SmartControl: Enhancing ControlNet for Handling Rough Visual Conditions | ECCV 2024 (Poster) | [Paper](https://arxiv.org/abs/2404.06451) \| [Code](https://github.com/liuxiaoyu1104/SmartControl) |
| PIXART-δ: Fast and Controllable Image Generation with Latent Consistency Models | ICML 2024 Workshop | [Paper](https://openreview.net/forum?id=Dyi0hXiQ9R) \| [Code](https://github.com/PixArt-alpha/PixArt-alpha) |
| Layout-to-Image Generation with Localized Descriptions using ControlNet with Cross-Attention Guidance | WACV 2024 | [Paper](https://arxiv.org/abs/2402.13404) \| [Code](#) |
| Controllable Generation with Text-to-Image Diffusion Models: A Survey | T-PAMI 2024 | [Paper](https://arxiv.org/abs/2403.04279) \| [Code](#) |
| Edify Image: High-Quality Image Generation with Pixel Space Laplacian Diffusion Models | arXiv 2024 | [Paper](https://arxiv.org/abs/2411.07126) \| [Code](https://github.com/NVIDIA/Edify-Image) |
| Cocktail : Mixing Multi-Modality Controls for Text-Conditional Image Generation | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2306.00964) \| [Code](https://github.com/mhh0318/Cocktail) |
| T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2302.08453) \| [Code](https://github.com/TencentARC/T2I-Adapter) |
| Uni-ControlNet: All-in-One Control to Text-to-Image Diffusion Models | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2305.16322) \| [Code](https://github.com/ShihaoZhaoZSH/Uni-ControlNet) |
| Adding Conditional Control to Text-to-Image Diffusion Models | ICCV 2023 | [paper](https://arxiv.org/abs/2302.05543) \| [Code](https://github.com/lllyasviel/ControlNet) |
| GLIGEN: Open-Set Grounded Text-to-Image Generation | CVPR 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Li_GLIGEN_Open-Set_Grounded_Text-to-Image_Generation_CVPR_2023_paper.html) \| [Code](https://github.com/gligen/GLIGEN) |
| MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation | CVPR 2023 | [Paper](https://arxiv.org/abs/2302.08113) \| [Code](https://github.com/omriav/MultiDiffusion) |
| UniControl: A Unified Diffusion Model for Controllable Visual Generation In the Wild | CVPR 2023 | [Paper](https://arxiv.org/abs/2305.11147) \| [Code](https://github.com/salesforce/UniControl) |
| Composer: Creative and Controllable Image Synthesis with Composable Conditions | ICML 2023 | [Paper](https://arxiv.org/abs/2302.09778) \| [Code](https://github.com/ali-vilab/composer?tab=readme-ov-file) |
| More Control for Free! Image Synthesis with Semantic Diffusion Guidance | WACV 2023 | [Paper](https://arxiv.org/abs/2112.05744) \| [Code](https://xh-liu.github.io/sdg/) |
| IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models | arXiv 2023 | [Paper](https://arxiv.org/abs/2308.06721) \| [Code](https://github.com/tencent-ailab/IP-Adapter) |
| Sketch-Guided Text-to-Image Diffusion Models | arXiv 2022 | [Paper](https://arxiv.org/abs/2211.13752) \| [Code](https://github.com/ogkalu2/Sketch-Guided-Text-To-Image-Diffusion) |
| Generative Modeling by Estimating Gradients of the Data Distribution | NeurIPS 2019 | [Paper](https://arxiv.org/abs/1907.05600) \| [Code](#) |

> 🧠 These papers push the boundary of **how we guide generation**, whether through minimal prompts, learned adapters, or uncertainty-aware mechanisms.


---

## 👁️ Attention & Interpretability

| Paper | Venue | Links |
|-------|-------|-------|
| ConceptAttention: Diffusion Transformers Learn Highly Interpretable Features | ICML 2025 (Oral) | [Paper](https://arxiv.org/abs/2502.04320) \| [Code](https://github.com/helblazer811/ConceptAttention) |
| ToMA: Token Merge with Attention for Diffusion Models | ICML 2025 (Poster) | [Paper](https://openreview.net/forum?id=xhtqgW5b93) \| [Code](#) |
| Attention in Diffusion Model: A Survey | arXiv 2025 | [Paper](https://arxiv.org/abs/2504.03738) \| [Code](#) |
| Attention Distillation: A Unified Approach to Visual Characteristics Transfer | CVPR 2025 | [Paper](https://arxiv.org/abs/2502.20235) \| [Code](https://github.com/xugao97/AttentionDistillation) |
| What the DAAM: Interpreting Stable Diffusion Using Cross Attention | ACL 2024 (Oral) | [Paper](https://arxiv.org/abs/2302.12243) \| [Code](https://github.com/zhudilin/DAAM) |

> 🔬 Interpretability is **not just analysis** — it's a step toward **transparent and editable generative pipelines**.

---

## 🎛️ Frequency Domain Control

| Paper | Venue | Links |
|-------|-------|-------|
| DiffFNO: Diffusion Fourier Neural Operator for Arbitrary-Scale Super-Resolution | CVPR 2025 (Oral) | [Paper](https://arxiv.org/abs/2411.09911) \| [Code](#) |
| PTDiffusion: Free Lunch for Generating Optical Illusion Hidden Pictures with Phase-Transferred Diffusion | CVPR 2025 (Poster) | [Paper](https://arxiv.org/abs/2503.06186) \| [Code](https://github.com/XiangGao1102/PTDiffusion) |
| Diffusion-based Adversarial Purification from the Perspective of the Frequency Domain | ICML 2025 (Spotlight Poster) | [Paper](https://arxiv.org/abs/2505.01267) \| [Code](#) |
| Frequency Autoregressive Image Generation with Continuous Tokens | arXiv 2025 | [Paper](https://arxiv.org/abs/2503.05305) \| [Code](https://github.com/yuhuUSTC/FAR) |
| FreeDiff: Progressive Frequency Truncation for Image Editing with Diffusion Models | ECCV 2024 (Poster) | [Paper](https://arxiv.org/abs/2404.11895) \| [Code](https://github.com/thermal-dynamics/freediff) |
| FreeU: Free Lunch in Diffusion U-Net | CVPR 2024 | [Paper](https://arxiv.org/abs/2309.11497) \| [Code](https://github.com/ChenyangSi/FreeU) |
| Frequency-Controlled Diffusion Model for Versatile Text-Guided Image-to-Image Translation | AAAI 2024 | [Paper](https://arxiv.org/abs/2407.03006) \| [Code](https://github.com/XiangGao1102/FCDiffusion) |
| ResDiff: Combining CNN and Diffusion Model for Image Super-Resolution | AAAI 2023 | [Paper](https://arxiv.org/abs/2303.08714) \| [Code](https://github.com/LYL1015/ResDiff) |

> 📡 Spectral and signal-level control provides **low-level but powerful levers** for generative consistency, resolution, and robustness.

---

## 🔁 Alignment & Knowledge Transfer

| Paper | Venue | Links |
|-------|-------|-------|
| When Model Knowledge meets Diffusion: Data-free Synthesis with Domain-Class Alignment | ICML 2025 | [Paper](https://arxiv.org/abs/2506.15381) \| [Code](#) |

> 🧬 These works align **discrete symbolic knowledge** with **continuous generative priors**, aiming for controllability in low-data or zero-shot regimes.

---

You may also consider including some notable **image-to-image (I2I） editing methods** in your collection.

## Image Editing

| Paper | Venue | Links |
|-------|-------|-------|
| In-Context Edit: Enabling Instructional Image Editing with In-Context Generation in Large Scale Diffusion Transformer | NeurIPS 2025 | [Paper](https://arxiv.org/abs/2504.20690) \| [Code](https://github.com/River-Zhang/ICEdit) |
| AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea | CVPR 2025 (Oral) | [Paper](https://arxiv.org/abs/2411.15738) \| [Code](https://github.com/DCDmllm/AnyEdit) |
| Stable Flow: Vital Layers for Training-Free Image Editing | CVPR 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Avrahami_Stable_Flow_Vital_Layers_for_Training-Free_Image_Editing_CVPR_2025_paper.html) \| [Code](https://github.com/snap-research/stable-flow) |
| UniReal: Universal Image Generation and Editing via Learning Real-world Dynamics | CVPR 2025 | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_UniReal_Universal_Image_Generation_and_Editing_via_Learning_Real-world_Dynamics_CVPR_2025_paper.html) \| [Code](#) |
| Taming Rectified Flow for Inversion and Editing | ICML 2025 | [Paper](https://openreview.net/forum?id=uDreZphNky) \| [Code](https://github.com/wangjiangshan0725/RF-Solver-Edit) |
| Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations | ICLR 2025 | [Paper](https://openreview.net/forum?id=Hu0FSOSEyS) \| [Code](https://github.com/LituRout/RF-Inversion) |
| Diffusion Model-Based Image Editing: A Survey | TPAMI 2025 | [Paper](https://arxiv.org/abs/2402.17525) \| [Code](https://github.com/SiatMMLab/Awesome-Diffusion-Model-Based-Image-Editing-Methods) |
| ChronoEdit: Towards Temporal Reasoning for Image Editing and World Simulation | arXiv 2025 | [Paper](https://arxiv.org/abs/2510.04290) \| [Code](#) |
| SAEdit: Token-level control for continuous image editing via Sparse AutoEncoder | arXiv 2025 | [Paper](https://arxiv.org/abs/2510.05081) \| [Code](#) |
| UltraEdit: Instruction-based Fine-Grained Image Editing at Scale | NeurIPS 2024 | [Paper](https://openreview.net/forum?id=9ZDdlgH6O8#discussion) \| [Code](https://github.com/HaozheZhao/UltraEdit) |
| SmartEdit: Exploring complex instruction-based image editing with multimodal large language models | CVPR 2024 | [Paper](http://openaccess.thecvf.com//content/CVPR2024/papers/Huang_SmartEdit_Exploring_Complex_Instruction-based_Image_Editing_with_Multimodal_Large_Language_CVPR_2024_paper.pdf) \| [Code](https://github.com/TencentARC/SmartEdit) |
| Direct Inversion: Boosting Diffusion-based Editing with 3 Lines of Code | ICLR 2024 | [Paper](https://arxiv.org/abs/2310.01506) \| [Code](https://github.com/cure-lab/PnPInversion) |
| MagicBrush: A Manually Annotated Dataset for Instruction-Guided Image Editing | NeurIPS 2023 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/64008fa30cba9b4d1ab1bd3bd3d57d61-Abstract-Datasets_and_Benchmarks.html) \| [Code](https://github.com/OSU-NLP-Group/MagicBrush) |
| NULL-text inversion for editing real images using guided diffusion models | CVPR 2023 | [Paper](http://openaccess.thecvf.com//content/CVPR2023/papers/Mokady_NULL-Text_Inversion_for_Editing_Real_Images_Using_Guided_Diffusion_Models_CVPR_2023_paper.pdf) \| [Code](https://github.com/google/prompt-to-prompt) |
| Imagic: Text-based real image editing with diffusion models | CVPR 2023 | [Paper](http://openaccess.thecvf.com//content/CVPR2023/papers/Kawar_Imagic_Text-Based_Real_Image_Editing_With_Diffusion_Models_CVPR_2023_paper.pdf) \| [Code](https://github.com/kawar2020/imagic) |
| InstructPix2Pix: Learning To Follow Image Editing Instructions | CVPR 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Brooks_InstructPix2Pix_Learning_To_Follow_Image_Editing_Instructions_CVPR_2023_paper.html) \| [Code](https://github.com/timothybrooks/instruct-pix2pix) |
| Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation | CVPR 2023 (Poster) | [Paper](https://arxiv.org/abs/2211.12572) \| [Code](https://github.com/MichalGeyer/plug-and-play) |
| DiffEdit: Diffusion-based semantic image editing with mask guidance | ICLR 2023 | [Paper](https://openreview.net/forum?id=3lge0p5o-M-) \| [Code](#) |
| Prompt-to-Prompt Image Editing with Cross Attention Control | ICLR 2023 | [Paper](https://arxiv.org/abs/2208.01626) \| [Code](https://github.com/google/prompt-to-prompt) |
| Zero-shot Image-to-Image Translation (pix2pix-zero) | SIGGRAPH 2023 | [Paper](https://arxiv.org/abs/2302.03027) \| [Code](https://github.com/pix2pixzero/pix2pix-zero) |
| RePaint: Inpainting using Denoising Diffusion Probabilistic Models | CVPR 2022 | [Paper](https://arxiv.org/abs/2201.09865) \| [Code](https://github.com/andreas128/RePaint) |

> ✏️ Editing is arguably **where controllability matters most** — precision, structure preservation, and user intent must all align.

---

## 📬 Contribute

💡 Know a paper we missed? Working on a new controllable generation method?  
Feel free to **submit a pull request** or **open an issue** — contributions are welcome!
