# Reinforcement-Learning-Project

- Jacopo Tedeschi 1882789
- Giordano Pagano 2077179


In this project is implemented the method introduced in the paper Policy Consolidation for Continual Reinforcement Learning (https://arxiv.org/pdf/1902.00255).

We propose a method for tackling catastrophic forgetting in deep reinforcement learning that is agnostic to the timescale of changes in the distribution of experiences, does not require knowledge of task boundaries, and can adapt in continuously changing environments. In our policy consolidation model, the policy network interacts with a cascade of hidden networks that simultaneously remember the agent’s policy at a range of timescales and regularise the current policy by its own history, thereby improving its ability to learn without forgetting. We find that the model improves continual learning relative to PPO baselines on an alternating two-task problem.


