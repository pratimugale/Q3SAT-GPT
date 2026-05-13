# Q3SAT-GPT

This repository points to the repositories containing the implementation of [Q3SAT-GPT: A Generative Model for Discovering Quantum Circuits for the 3-SAT Problem](https://arxiv.org/abs/2604.27324).

1. The MosaicADAPT-QAOA algorithm used to generate a rich dataset of optimized circuits to serve as training data, is implemented at [https://github.com/pratimugale/MosaicADAPT-QAOA](https://github.com/pratimugale/MosaicADAPT-QAOA). An example of using MosaicADAPT-QAOA is at [MosasicADAPT-QAOA/test/mosaicadapt_qaoa.jl](https://github.com/pratimugale/MosaicADAPT-QAOA/blob/main/test/mosaicadapt_qaoa.jl)
2. While the above repository contains the implementation of the core algorithms, the code for the experiment that generates a dataset of Max3SAT instances and compares performance of MosaicADAPT-QAOA against TETRIS-QAOA and ADAPT-QAOA is provided at [MosaicADAPT-QAOA-Experiments](https://github.com/pratimugale/MosaicADAPT-QAOA-Experiments)
3. For Q3SAT-GPT code, i.e. the code that generates a large scale dataset of 50k Max3SAT instances, runs MosaicADAPT-QAOA on each instance and trains QAOA-GPT for prediction on unseen test set instances, please see [https://github.com/pratimugale/TETRIS-QAOA-GPT](https://github.com/pratimugale/TETRIS-QAOA-GPT). Note that the repository was named TETRIS-QAOA-GPT for legacy reasons and will be updated soon.

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
