# DiffiT: Diffusion Vision Transformers for Image Generation

An implementation of **DiffiT**, a novel approach combining Vision Transformers (ViTs) with diffusion models for high-quality image generation. This repository includes training/evaluation code and pre-trained models for CIFAR-10 and Tiny ImageNet.

![Generated Samples](https://raw.githubusercontent.com/alighasemi78/DiffiT-Diffusion-Vision-Transformers-for-Image-Generation/main/images/diff_model.png)

## Key Features
- **Time-dependent Multihead Self Attention (TMSA)**: Novel attention mechanism adapting to diffusion timesteps
- **Parameter Efficiency**: Outperforms Transformer-based diffusion models with fewer parameters
- **Dual Support**: Includes both latent space and pixel space implementations
- **Benchmark Ready**: Preconfigured for CIFAR-10 and Tiny ImageNet datasets
- **Flexible Architecture**: Easily adjustable hyperparameters (image size, timesteps, model dimensions)

## How to Run

1. Open the DiffiT.ipynb file (preferably with colab).
2. If you want to train from scratch, comment the **Load Models** section in the **Visualization** part, and click **Run all**.
3. If you want to use the pretrained models, comment the **Training & Testing** Section in the **Image Space DiffiT Model** part, and click **Run all**.

## References
1. Ho et al. [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
2. Dosovitskiy et al. [An Image is Worth 16x16 Words: Transformers for Image Recognition](https://arxiv.org/abs/2010.11929)
3. Hatamizadeh et al. [DiffiT: Diffusion Vision Transformers For Image Generation](https://arxiv.org/abs/2312.02139)
