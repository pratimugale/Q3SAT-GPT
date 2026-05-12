# Q3SAT-GPT

This repository points to the repositories containing the implementation of [Q3SAT-GPT: A Generative Model for Discovering Quantum Circuits for the 3-SAT Problem](https://arxiv.org/abs/2604.27324).

1. The MosaicADAPT-QAOA algorithm used to generate a rich dataset of optimized circuits to serve as training data, is implemented at [https://github.com/pratimugale/MosaicADAPT-QAOA](https://github.com/pratimugale/MosaicADAPT-QAOA). An example of using MosaicADAPT-QAOA is at [MosasicADAPT-QAOA/test/mosaicadapt_qaoa.jl](https://github.com/pratimugale/MosaicADAPT-QAOA/blob/main/test/mosaicadapt_qaoa.jl)
2. For Q3SAT-GPT code, please see [https://github.com/pratimugale/TETRIS-QAOA-GPT](https://github.com/pratimugale/TETRIS-QAOA-GPT)

## Citation

If you found our work useful, please cite [arXiv preprint](https://arxiv.org/abs/2604.27324):
```
@misc{ugale2026q3satgptgenerativemodeldiscovering,
      title={Q3SAT-GPT: A Generative Model for Discovering Quantum Circuits for the 3-SAT Problem}, 
      author={Pratim Ugale and Ilya Tyagin and Karunya Shirali and Kien X. Nguyen and Ilya Safro},
      year={2026},
      eprint={2604.27324},
      archivePrefix={arXiv},
      primaryClass={quant-ph},
      url={https://arxiv.org/abs/2604.27324}, 
}
```
