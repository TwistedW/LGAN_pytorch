# LGAN
This is the project for the following technical report:

**Guo-Jun Qi, Liheng Zhang, Hao Hu. Global versus Localized Generative Adversarial Nets. arXiv: 1711.06020 [[pdf](https://arxiv.org/pdf/1711.06020.pdf)]**

## Requirements
- Python == 2.7 or 3.5+
- Pytorch == 0.4.1

## Train LGAN

```bash
python train.py
```
## Test LGAN

```bash
python test.py
```

## Result
After 20 epochs training. We can adjust noise z to control the output.In each row,the images are generated in one direction of a local coordinate.

<p align="center">
    <img src="/images/result.png">
</p>

## Acknowledge
Parts of codes are reused from Localized-GAN at https://github.com/z331565360/Localized-GAN
