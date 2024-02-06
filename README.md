# Image Generator using Stable Diffusion with Evaluation Metrics

## Overview

This project leverages the power of Stable Diffusion for image generation, enhanced with evaluation metrics including CLIP Score, PickScore, and Aesthetic Score. These metrics provide insights into the similarity between generated images and prompts, aesthetic quality, and alignment with human preferences.

### Key Components:
1. **Stable Diffusion Image Generation**: Utilizes [Stable Diffusion](https://huggingface.co/stabilityai/stable-diffusion-2-1) for generating high-quality images based on textual descriptions.
2. **CLIP Score**: Measures the similarity between generated images and prompts, as proposed by Radford et al., 2021. More details can be found [here](https://huggingface.co/yuvalkirstain/PickScore_v1).
3. **Aesthetic Score**: Evaluates the aesthetic quality of individual images following the methodology of Schuhmann et al., 2022. Implementation details are available on [GitHub](https://github.com/LAION-AI/aesthetic-predictor).
4. **PickScore**: A metric developed by Kirstain et al., 2023, trained to align with human preferences in image quality.

