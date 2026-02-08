<div align="center">

# BioCodec: Biosignal Tokenization Module

Official implementation for the paper "Neural Codecs as Biosignal Tokenizers".

</div>

We recommend a conda environment with ``Python >= 3.12`` :

```bash
conda create -n biocodec python=3.12
conda activate biocodec
```

Install the dependencies:

```bash
cd BioCodec
pip install -r requirements.txt
```

You can run BioCodec on a random sample:

```bash
python -m biocodec.model
```

## Acknowledgements

In this study we made use of the following repositories:

* [encodec-pytorch](https://github.com/ZhikangNiu/encodec-pytorch)

## Citation

If you use BioCodec in your work, please consider citing the original study:
```
@article{avramidis2025neural,
  title={Neural Codecs as Biosignal Tokenizers},
  author={Avramidis, Kleanthis and Feng, Tiantian and Jeong, Woojae and Lee, Jihwan and Cui, Wenhui and Leahy, Richard M and Narayanan, Shrikanth},
  journal={arXiv preprint arXiv:2510.09095},
  year={2025}
}
```
