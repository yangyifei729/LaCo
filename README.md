# LaCo: Large Language Model Pruning via Layer Collapse
Official implementation for EMNLP 2024 Findings paper "[LaCo: Large Language Model Pruning via Layer Collapse](https://arxiv.org/pdf/2402.11187)"



## Requirements
- python >= 3.7.9
- torch >= 1.7.1
- transformers >= 4.25.1
- scikit-learn >= 1.0
- tqdm >= 4.49.0
- numpy >= 1.20.2


## Usage
The implementations of LaCo on Llama2 and Baichuan2 can be referred to `laco_llama-13b.ipynb` and `laco-baic-13B.ipynb`, respectively.

> [!NOTE]  
> This is just a preliminary version of the code. We will continue to update it and package it into a more general format as a .py file in the future.



## Citation

If you find our work helpful, please consider citing:

```
@article{yang2024laco,
  title={Laco: Large language model pruning via layer collapse},
  author={Yang, Yifei and Cao, Zouying and Zhao, Hai},
  journal={arXiv preprint arXiv:2402.11187},
  year={2024}
}
```