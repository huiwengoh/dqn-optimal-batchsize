## An Empirically Optimal Batch Size for DQN playing Cart Pole

*Authors:* Hui Wen Goh, Yara Kyrychenko and Eion Tyacke.

### Abstract

Deep Q Learning has proven to be a great algorithm for achieving human-level performance on many tasks. However, training a Deep Q Network (DQN) successfully is tricky since it requires proper hyper-parameters. When hyper-parameters are not properly optimized, similarly performing models can take drastically different times to train. In this paper, we focus on one such hyper-parameter -- the batch size. We build on the work done by Choi 2019 to find an empirically optimal batch size for more complicated network architecture and the cart-pole task. Based on metrics such as the average rewards obtained, the training time taken per episode and completion rate, the optimal batch size we obtained in our analysis is around 32 to 64, which confirms Choi's results.
