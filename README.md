# [ICLR 2023] Conditional Positional Encodings for Vision Transformers
[![ICLR](https://img.shields.io/badge/ICLR2023-3KWnuT--R1bh-%238c1b13)](https://openreview.net/forum?id=3KWnuT-R1bh)

We propose a conditional positional encoding (CPE) scheme for vision Transformers. Unlike previous fixed or learnable positional encodings, which are pre-defined and independent of input tokens, CPE is dynamically generated and conditioned on the local neighborhood of the input tokens. As a result, CPE can easily generalize to the input sequences that are longer than what the model has ever seen during training. Besides, CPE can keep the desired translation-invariance in the image classification task, resulting in improved classification accuracy. CPE can be effortlessly implemented with a simple Position Encoding Generator (PEG), and it can be seamlessly incorporated into the current Transformer framework. Built on PEG, we present Conditional Position encoding Vision Transformer (CPVT). We demonstrate that CPVT has visually similar attention maps compared to those with learned positional encodings. Benefit from the conditional positional encoding scheme, we obtain state-of-the-art results on the ImageNet classification task compared with vision Transformers to date

![compared with DeiT](figures/w-deit.png)

![compared with DeiT](figures/sota-comparison.png)

# Updates

- 2023-1-21 Accepted by ICLR 2023.
- 2021-5-12 Note: Code is released along with our latest work [Twins](https://github.com/Meituan-AutoML/Twins).


## Citation

```
@inproceedings{chu2023CPVT,
	title={Conditional Positional Encodings for Vision Transformers},
	author={Xiangxiang Chu and Zhi Tian and Bo Zhang and Xinlong Wang and Chunhua Shen},
	booktitle={ICLR 2023},
	url={https://openreview.net/forum?id=3KWnuT-R1bh},
	year={2023}
}
```
