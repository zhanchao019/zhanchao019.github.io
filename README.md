# MuseV [English](README.md) [中文](README-zh.md)

<font size=5>MuseV: Infinite-length and High Fidelity Virtual Human Video Generation with Visual Conditioned  Parallel Denoising
</br>
Zhiqiang Xia <sup>\*</sup>,
Zhaokang Chen<sup>\*</sup>,
Bin Wu<sup>†</sup>,
Chao Li,
Kwok-Wai Hung,
Chao Zhan,
Yingjie He, 
Wenjiang Zhou
(<sup>*</sup>co-first author, <sup>†</sup>Corresponding Author, benbinwu@tencent.com)
</font>

**[github](https://github.com/TMElyralab/MuseV)**    **[huggingface](https://huggingface.co/TMElyralab/MuseV)**  **[HuggingfaceSpace](https://huggingface.co/spaces/AnchorFake/MuseVDemo)**  **[project](comming soon)**    **Technical report (comming soon)**


We have setup **the world simulator vision since March 2023, believing diffusion models can simulate the world**. `MuseV` was a milestone achieved around **July 2023**. Amazed by the progress of Sora, we decided to opensource `MuseV`, hopefully it will benefit the community. Next we will move on to the promising diffusion+transformer scheme.

We will soon release `MuseTalk`, a real-time high quality lip sync model, which can be applied with MuseV as a complete virtual human generation solution. Please stay tuned! 

# What is MuseV
`MuseV` is a diffusion-based virtual human video generation framework, which 
1. supports **infinite length** generation using a novel **Visual Conditioned Parallel Denoising scheme**.
2. checkpoint available for virtual human video generation trained on human dataset.
3. supports Image2Video, Text2Image2Video, Video2Video.
4. compatible with the **Stable Diffusion ecosystem**, including `base_model`, `lora`, `controlnet`, etc. 
5. supports multi reference image technology, including `IPAdapter`, `ReferenceOnly`, `ReferenceNet`, `IPAdapterFaceID`.
6. training codes (comming very soon).

# News
- [03/27/2024] release `MuseV` project and trained model `musev`, `muse_referencenet`.
- [03/30/2024] add huggingface space gradio to generate video in gui

