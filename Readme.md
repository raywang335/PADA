# PADA: Pluralistic Aging Diffusion Autoencoder (ICCV 2023)

## Code Comming Soon!
> Face aging is an ill-posed problem because multiple plausible aging patterns may correspond to a given input. Most existing methods often produce one deterministic estimation. This paper proposes a novel CLIP-driven Pluralistic Aging Diffusion Autoencoder (PADA) to enhance the diversity of aging patterns. First, we employ diffusion models to generate diverse low-level aging details via a sequential denoising reverse process. Second, we present Probabilistic Aging Embedding (PAE) to capture diverse high-level aging patterns, which represents age information as probabilistic distributions in the common CLIP latent space. A text-guided KL-divergence loss is designed to guide this learning. Our method can achieve pluralistic face aging conditioned on open-world aging texts and arbitrary unseen face images. Qualitative and quantitative experiments demonstrate that our method can generate more diverse and high-quality plausible aging results.

<img src="./docs/header.png" height="100%" width="100%" >

## Description
Official Implementation of our Pluralistic Aging Diffusion Autoencoder (PADA) paper for both training and evaluation. PADA allows modeling flexible and diverse face aging conditioned on texts and images.

<img src="./docs/fig.jpg" height="75%" width="75%" >


## TODO
- [ ] Release the pretrained model and inference code.
- [ ] Release the training code.
- [ ] Add jupyter notebooks demo.

## Acknowledgments
Our code borrows from [SAM](https://github.com/yuval-alaluf/SAM) and [DiffAE](https://github.com/phizaz/diffae). We would like to express our gratitude for their generosity in sharing their work.

## Citations
If you use this code for your research, please cite our paper [Pluralistic Aging Diffusion Autoencoder](https://arxiv.org/abs/2303.11086):
```latex
@misc{li2023pluralistic,
      title={Pluralistic Aging Diffusion Autoencoder}, 
      author={Peipei Li and Rui Wang and Huaibo Huang and Ran He and Zhaofeng He},
      year={2023},
      eprint={2303.11086},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

