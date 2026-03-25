<div align="center">

<h2>WildWorld: A Large-Scale Dataset for Dynamic World Modeling<br>with Actions and Explicit State toward Generative ARPG</h2>

[![project page](https://img.shields.io/badge/Project-Page-2ea44f)](https://shandaai.github.io/wildworld-project/)&nbsp;
[![arXiv](https://img.shields.io/badge/arXiv%20paper-2603.23497-b31b1b.svg)](https://arxiv.org/abs/2603.23497)&nbsp;
[![YouTube](https://badges.aleen42.com/src/youtube.svg)](https://www.youtube.com/watch?v=9vcSg553r2g)&nbsp;

</div>

This repo contains the dataset and benchmark code used in

> [**WildWorld: A Large-Scale Dataset for Dynamic World Modeling with Actions and Explicit State toward Generative ARPG**](https://arxiv.org/abs/2603.23497)
>
> Zhen Li, Zian Meng, Shuwei Shi, Wenshuo Peng, Yuwei Wu, Bo Zheng, Chuanhao Li, Kaipeng Zhang
>
> 
>
> Alaya Studio, Shanda AI Research Tokyo; Beijing Institute of Technology; Shanghai Innovation Institute

## 🔥Update

- [2026.03.25] We have released our paper — discussions and feedback are warmly welcome!

## 🧠Introduction

![pipeline](./assets/framework-arxiv.png)

**TL;DR** We present **WildWorld**, a large-scale action-conditioned world modeling dataset with explicit state annotations, automatically collected from a photorealistic AAA action role-playing game. It features:

- 🎬 **108M+ frames** with **per-frame annotations**: character skeletons, actions & states (HP, animation, etc.), camera poses, and depth maps
- ⚔️ **450+ semantically meaningful actions** including movement, attacks, and skill casting
- 🐉 **Diverse content**: 29 monster species, 4 player characters, 4 weapon types, 5 distinct stages
- 🕒 **Long-horizon sequences**: clips spanning up to 30+ minutes of continuous gameplay
- 📝 **Hierarchical captions**: both action-level and sample-level natural language descriptions

## 📦TODO

- [ ] Release WildWorld dataset and WildBench benchmark.

## 📄License

See [LICENSE](./LICENSE).

## 📖Citation

If you find this project helpful, please consider citing:

```bibtex
@misc{li2026wildworldlargescaledatasetdynamic,
      title={WildWorld: A Large-Scale Dataset for Dynamic World Modeling with Actions and Explicit State toward Generative ARPG}, 
      author={Zhen Li and Zian Meng and Shuwei Shi and Wenshuo Peng and Yuwei Wu and Bo Zheng and Chuanhao Li and Kaipeng Zhang},
      year={2026},
      eprint={2603.23497},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2603.23497}, 
}
```
