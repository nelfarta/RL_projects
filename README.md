# RL Projects

Contains all the Reinforcement learning projects I did.

## Projects

### Project 1: Does LayerNorm in the critic reduce overestimation? DDPG and TD3 on LunarLander-v3
- **Authors:** Matteo Nizard, Norman El Fartass
- **Summary:** Tests whether LayerNorm in the critic reduces overestimation bias in DDPG and TD3 (LunarLander-v3, 10 seeds per condition). TD3 already removes the bias and LN changes nothing. Without clipped double Q-learning, LN halves the bias in TD3 but increases it in DDPG.
- **Report:** [layernorm_td3_ddpg.pdf](https://github.com/nelfarta/RL_projetcs/blob/main/layernorm_td3_ddpg.pdf)
- **Code:** [matleniz/ddpg-td3-layernorm-bias](https://github.com/matleniz/ddpg-td3-layernorm-bias)
