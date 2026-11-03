# Earlier & Adjacent Notes / 早期与邻近内容归档

This page keeps useful blog notes that are outside the current core of the Post-Training Atlas. The main map focuses on modern LLM-era post-training: **RL, reward, SFT × RL, distillation, and distribution alignment**.

Items here are grouped by mechanism and historical role. They do not participate in the core paper index, track structure, or chronological deep-dive timeline.

## Personal RL × NLP Historical Anchors

These works mattered personally before the modern LLM post-training map took shape. The longer reflection is in [《通向 AGI 的技术路径：多模态、强化学习与新架构的交汇点》](https://yam.gift/2026/01/25/AI/2026-01-25-AI-Future-Framework/): *“22 年 RL4LMs 出来后我兴奋的晚上觉都没睡着，第一时间就读了他们的代码。”*

- [RL4LMs / NLPO](http://arxiv.org/abs/2210.01241) ([GitHub](https://github.com/allenai/rl4lms)) — the first moment RL × NLP felt like it could really land.
- [Fine-Tuning Language Models from Human Preferences](http://arxiv.org/abs/1909.08593) ([GitHub](https://github.com/openai/lm-human-preferences)) — OpenAI's earliest RLHF experiment.
- [Quark](http://arxiv.org/abs/2205.13636) ([GitHub](https://github.com/GXimingLu/Quark)) — controllable generation through reinforced unlearning.
- [Decision Transformer](https://arxiv.org/abs/2106.01345) ([GitHub](https://github.com/kzl/decision-transformer)) — the parallel “RL as sequence modeling” branch.

## Pre-LLM Representation & Fine-Tuning

- [Sentence-BERT](https://yam.gift/2020/12/27/Paper/2020-12-27-Sentence-Bert/) — siamese/triplet objectives for sentence representation.
- [SimCSE](https://yam.gift/2021/07/10/Paper/2021-07-10-SimCSE/) — dropout views and contrastive representation learning.
- [R-Drop](https://yam.gift/2021/08/18/Paper/2021-08-18-R-Drop/) — bidirectional-KL consistency between dropout subnetworks.
- [NLP Data Augmentation](https://yam.gift/2021/11/28/Paper/2021-11-28-DataAugmentation/) — paraphrase-, noise-, and sampling-based augmentation.
- [Debiasing Techniques for Pre-Trained Language Models](https://yam.gift/2021/11/18/Paper/2021-11-18-Debiasing/) — CDA, Self-Debias, and representation projection.
- [Putting Humans in the NLP Loop](https://yam.gift/2023/01/21/Paper/2023-01-21-Human-in-Loop/) — a general NLP/HCI feedback-loop survey rather than modern LLM post-training.

## Prompting & Early Instruction Tuning

- [Prompt Methods Survey](https://yam.gift/2021/12/04/Paper/2021-12-04-Prompt/) — hard prompts, soft prompts, and answer engineering.
- [MetaICL](https://yam.gift/2021/11/01/Paper/2021-11-01-MetaICL/) — meta-training models to recover tasks from demonstrations.
- [T0 / Multitask Prompted Training](https://yam.gift/2021/12/25/Paper/2021-12-25-MLT-Promote/) — task and prompt diversity for zero-shot transfer.
- [FLAN](https://yam.gift/2022/08/28/Paper/2022-08-28-FLAN/) — instruction tuning as a bridge to zero-shot task following.
- [ChatGPT Prompt Engineering](https://yam.gift/2023/01/25/NLP/2023-01-25-ChatGPT-Prompt-Engineering/) — practical inference-time behavior shaping.

## Transitional Reflections

- [Think About LLM](https://yam.gift/2023/10/15/NLP/2023-10-15-Think-About-LLM/) — SFT data, LoRA, distillation, and an early return to RL.
- [Think About AI](https://yam.gift/2024/12/20/NLP/2024-12-20-Think-About-AI-and-Related/) — RL, inference-time scaling, and learning through generated context.

## Speech & Multimodal Adaptation

- [OMNI Papers 2024](https://yam.gift/2024/12/31/Paper/MM/2024-12-31-OMNI-Papers-2024/) — staged speech alignment, frozen-backbone adaptation, and full-duplex training.
- [SLM Papers 2024](https://yam.gift/2024/12/31/Paper/MM/2024-12-31-SLM-Papers/) — instruction tuning and PEFT for speech-capable language models.
- [OMNI Papers 2025](https://yam.gift/2025/03/08/Paper/MM/2025-03-08-OMNI-Papers-2025/) — modality-specific LoRA, multimodal SFT, DPO, and RLHF recipes.
- [Voila](https://yam.gift/2025/05/14/MM/2025-05-14-Voila-and-OMNI/) — speech/text alignment and response-only SFT around an LLM backbone.

These are valid post-training cases, but they do not add a new mechanism beyond staged SFT, PEFT, or preference alignment, so they remain outside the core map.
