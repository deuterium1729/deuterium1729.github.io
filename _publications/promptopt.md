---
title: "Prompt Optimization with Logged Bandit Data"
collection: publications
permalink: /publication/promptopt
excerpt: 'Haruka Kiyohara, Yuta Saito, Daniel Yiming Cao, Thorsten Joachims'
venue: 'ICLR 2024'
date: January 2024
---
[paper]([https://arxiv.org/abs/2211.03989](https://openreview.net/forum?id=Byj8MMJmoL&referrer=%5Bthe%20profile%20of%20Haruka%20Kiyohara%5D(%2Fprofile%3Fid%3D~Haruka_Kiyohara1)))



# abstract:
We study how to use naturally available user feedback, such as clicks, to optimize
a prompt policy for generating sentences with large language models (LLMs).
Naive approaches, including regression-based and importance sampling-based
ones, suffer either from bias in the log data or variance caused by the large action
space of prompts. To circumvent these challenges, we propose a way to leverage
similarity and smoothness in the generated sentence embedding, substantially
reducing variance in the policy gradient estimation while maintaining a small bias.
Initial experiments on synthetic data demonstrate the effectiveness of our approach.
We also plan to publish the benchmark and simulator as open-source software.
