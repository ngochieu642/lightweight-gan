## 'Lightweight' GAN (wip)

Implementation of an extremely <a href="https://openreview.net/forum?id=1Fqg133qRaI">'lightweight' GAN</a> proposed in ICLR 2021, in Pytorch. The main contributions of the paper is a skip-layer excitation in the generator, paired with autoencoding self-supervised learning in the discriminator. Quoting the one-line summary "converge on single gpu with few hours' training, on 1024 resolution sub-hundred images".

## Citations

```bibtex
@inproceedings{
    anonymous2021towards,
    title={Towards Faster and Stabilized {\{}GAN{\}} Training for High-fidelity Few-shot Image Synthesis},
    author={Anonymous},
    booktitle={Submitted to International Conference on Learning Representations},
    year={2021},
    url={https://openreview.net/forum?id=1Fqg133qRaI},
    note={under review}
}
```
