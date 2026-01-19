I like to train deep neural nets that reason and don't forget.

My research interests span:

- **Reinforcement Learning**
  - Core contributor of [Reasoning Gym](https://github.com/open-thought/reasoning-gym) where I built dozens of RL environments, as well as ran the zero-shot, external benchmark, and curriculum learning experiments for our publication.
  - Wrote several sections in the [RLHF Book](https://rlhfbook.com), where I I derived the [policy gradient objective](https://github.com/natolambert/rlhf-book/pull/136) and [Bradley-Terry loss](https://github.com/natolambert/rlhf-book/pull/97), as well as provided intuitions for the [PPO gradient dynamics](https://github.com/natolambert/rlhf-book/pull/139).
- **Continual Learning**
  - Worked on mitigating catastrophic forgetting in foundation models based on continual weight interpolation, [demonstrating](https://arxiv.org/abs/2211.03186) performance close to the upper bound of jointly training on all data.
- **Evaluation**
  - Contributed several datasets to EleutherAI’s Evaluation Harness (e.g. [Lambada Translations](https://github.com/EleutherAI/lm-evaluation-harness/pull/1897), [Paloma](https://github.com/EleutherAI/lm-evaluation-harness/pull/1928), [LegalBench](https://github.com/EleutherAI/lm-evaluation-harness/pull/1878)), as well as implemented [higher-is-better indicators](https://github.com/EleutherAI/lm-evaluation-harness/pull/1893) and tests for [output table consistency](https://github.com/EleutherAI/lm-evaluation-harness/pull/1916).
 
My publications include:
- <ins>Zafir Stojanovski</ins>, Oliver Stanley*, Joe Sharratt*, Richard Jones*, Abdulhakeem Adefioye, Jean Kaddour, Andreas Köpf: [“Reasoning Gym: Reasoning Environments for RL with Verifiable Rewards”](https://arxiv.org/abs/2505.24760). **<ins>NeurIPS 2025 (Spotlight)</ins>**
- <ins>Zafir Stojanovski</ins>, Karsten Roth*, Zeynep Akata: [“Momentum-based Weight Interpolation of Strong Zero-Shot Models for Continual Learning”](https://arxiv.org/abs/2211.03186). Interpolate workshop @ **<ins>NeurIPS 2022 (Best Paper Award)</ins>**
