# post-training-primer-examples


## Notebooks

- [01. REINFORCE on a bandit](notebooks/01-reinforce-bandit.ipynb)
- [02. Discounted REINFORCE on CartPole](notebooks/02-reinforce-cartpole.ipynb)
- [03. Small-model supervised fine-tuning](notebooks/03-sft-small-model.ipynb) — Qwen2.5-0.5B, 256 synthetic demonstrations, LoRA, and held-out before/after comparisons. Use a Colab GPU; training is configured for 96 updates and has not been benchmarked here.

- [04. Small-model DPO](notebooks/04-dpo-small-model.ipynb) — 256 synthetic preference pairs, a fixed reference, explicit DPO loss, and held-out generation scores before and after training. Use a Colab GPU.
