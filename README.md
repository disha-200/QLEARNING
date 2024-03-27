# QLEARNING
Implemented QLearning and computed the value function of the greedy policy: vˆ(s) = max_a qˆ(s, a).
Analysed based on various design decisions: (i) which value of α(discount) to use; (ii) how to initialize the q-function; you may, e.g., initialize it with zeros, with random values, or optimistically (iii) how to explore; ε-greedy exploration or softmax action selection; and (iv) how to control the exploration rate over time; keep the exploration parameter (e.g., ε) fixed over time, or have it decay as a function of the number of episodes.
