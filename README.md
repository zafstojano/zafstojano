I like to train deep neural nets that reason without forgetting.

## 👨🏻‍🔬 Research Interests

**Reinforcement Learning**
- Core contributor of [Reasoning Gym](https://github.com/open-thought/reasoning-gym) where I built dozens of RL environments, as well as ran the zero-shot, external benchmark, and curriculum learning experiments for our NeurIPS publication.
- Wrote several sections of the [RLHF Book](https://rlhfbook.com), where I derived the [policy gradient objective](https://github.com/natolambert/rlhf-book/pull/136) and [Bradley-Terry loss](https://github.com/natolambert/rlhf-book/pull/97), as well as provided intuitions for the [PPO gradient dynamics](https://github.com/natolambert/rlhf-book/pull/139).

**Continual Learning**
- Worked on mitigating catastrophic forgetting in foundation models based on continual weight interpolation, [demonstrating](https://arxiv.org/abs/2211.03186) performance close to the upper bound of jointly training on all data in our NeurIPS workshop publication.
  
**Evaluation**
- Contributed several datasets to EleutherAI’s Evaluation Harness (e.g. [Lambada Translations](https://github.com/EleutherAI/lm-evaluation-harness/pull/1897), [Paloma](https://github.com/EleutherAI/lm-evaluation-harness/pull/1928), [LegalBench](https://github.com/EleutherAI/lm-evaluation-harness/pull/1878)), as well as implemented [higher-is-better indicators](https://github.com/EleutherAI/lm-evaluation-harness/pull/1893) and tests for [output table consistency](https://github.com/EleutherAI/lm-evaluation-harness/pull/1916).

## 📄 Publications

My work is used by AI labs such as DeepMind [[1](https://arxiv.org/abs/2401.12187), [2](https://arxiv.org/abs/2406.16768), [3](https://arxiv.org/abs/2411.15099), [4](https://arxiv.org/abs/2408.14471)], Meta [[5](https://arxiv.org/abs/2212.10445), [6](https://arxiv.org/abs/2306.04488), [7](https://arxiv.org/abs/2508.13141)], NVIDIA [[8](https://arxiv.org/abs/2507.12507), [9](https://arxiv.org/abs/2510.01180)], Mila [[10](https://arxiv.org/abs/2509.26626), [11](https://arxiv.org/abs/2505.24273), [12](https://arxiv.org/abs/2505.14970)], and Prime Intellect [[13](https://www.primeintellect.ai/blog/synthetic-2])]:
- **<ins>Zafir Stojanovski</ins>**, Oliver Stanley*, Joe Sharratt*, Richard Jones*, Abdulhakeem Adefioye, Jean Kaddour, Andreas Köpf: [“Reasoning Gym: Reasoning Environments for RL with Verifiable Rewards”](https://arxiv.org/abs/2505.24760). **<ins>NeurIPS 2025 (Spotlight)</ins>**
- **<ins>Zafir Stojanovski</ins>**, Karsten Roth*, Zeynep Akata: [“Momentum-based Weight Interpolation of Strong Zero-Shot Models for Continual Learning”](https://arxiv.org/abs/2211.03186). Interpolate workshop @ **<ins>NeurIPS 2022 (Best Paper Award)</ins>**
