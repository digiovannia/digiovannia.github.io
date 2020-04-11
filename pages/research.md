---
layout: page
title: Research
description: Anthony DiGiovanni's research
---

Reinforcement learning is a highly general framework for automated sequential decision-making in pursuit of certain objectives ("rewards"). AlphaZero showed the power of reinforcement learning to discover solutions to complex tasks with minimal hard-coding of human heuristics. But as stunning as AlphaZero is, board games have clearly and unambiguously designed rewards based on a "win" or "loss" state. In the real world, the desirability of different world-states is an immensely complex function of our psychology, such that if we tried to hand-design a reward function for such states and deploy an RL system to maximize this reward, the results would likely be dangerous.

My research focuses on a potential solution to this problem: inverse reinforcement learning (IRL). Using data on attempts by human demonstrators to solve certain tasks, an IRL algorithm uses a model of these demonstrators' behavior to infer the rewards motivating such behavior. Given that the goal is to automate these tasks in a way that surpasses the demonstrators, however, scalable IRL algorithms will require models of these demonstrators that accurately account for their irrationalities. Currently I am designing an IRL model that flexibly represents the variation of each demonstrator's expertise across different states.

Another significant challenge for IRL is that of learning from demonstrations in multi-agent systems. RL agents deployed in the real world will have to account for the interactions between multiple people's latent reward functions, and IRL algorithms for learning such functions will require models of humans' process of predicting and reacting to each other's actions, beyond the dynamics of the environment. I am surveying game theory literature as a foundation for these models.

## Publications

1. DiGiovanni, S., Demanelis, K., Tong, L., Argos, M., Shinkle, J., Jasmine, F., Sabarinathan, M., Rakibuz-Zaman, M., Sarwar, G., Islam, M.T., Shahriar, H., Islam, T., Rahman, M., Yunus, M., Graziano, J., Gamble, M.V., Ahsan, H., Pierce, B.L. (2020) "Assessing the impact of arsenic metabolism efficiency on DNA methylation using Mendelian randomization," *Environmental Epidemiology*, 4 (2), e083.

<!-- Note: this is how to write a comment in HTML. Everything in here won't show up on your webpage.-->

<!--
To increase the size of the title, use fewer # in front of the paper title.
To decrease the size of the title, use more #. 
To remove the italics, remove the * before and after the description
To remove the underline from the title, remove the <u> tags (<u> and </u>)
-->