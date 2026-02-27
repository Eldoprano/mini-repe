# Steering Vector Translation

We test if steering vectors extracted from one model can be translated and applied to another model.

Works well for refusal, happiness, formality and confidence behaviours.\
Can be improved with better steering vector extraction (Here we attempt a very universal way

- The [universal translation](https://github.com/Eldoprano/mini-repe/blob/main/universal_translation.ipynb) notebook shows it working surprisingly well for refusal extraction and translation
- [Multi concept steering](https://github.com/Eldoprano/mini-repe/blob/main/multi_concept_steering.ipynb) tries to extract them in a more general way, working different behaviours.
- And [PoC](https://github.com/Eldoprano/mini-repe/blob/main/poc.ipynb) is a messy notebook. There I tried different ideas before doing the other two ones.

---

> Inspired by [Steering Vector Transfer via Orthonormal Transformations and Semantic Pairing
](https://openreview.net/forum?id=iD8uUeCBy5) and\
> [Cross-model Transferability among Large Language Models on the Platonic Representations of Concepts](https://arxiv.org/abs/2501.02009)
