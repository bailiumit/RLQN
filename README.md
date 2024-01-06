# RLQN: Server Allocation Simulation

This notebook provides the simulation code for Section 5.1, focusing on Server Allocation (Two Nodes), from my research paper titled [RL-QN: A Reinforcement Learning Framework for Optimal Control of Queueing Systems](https://arxiv.org/pdf/2011.07401.pdf).

## Notes

* The notebook is designed to be self-contained. However, please note that I haven't tested it since 2021, so compatibility with current systems may vary.

* I utilized [mdptoolbox](https://pymdptoolbox.readthedocs.io/en/latest/api/mdptoolbox.html) for implementing the truncated MDP solution for convenience. The library aims to find the policy optimizing cumulative discounted rewards, rather than average rewards. In this simple setting, the results should remain consistent.

* The primary value of the paper lies in its theoretical analysis, with simulations serving to validate this analysis. The provided code aids in comprehending the theoretical aspects but should not be regarded as a practical product.

* This research was conducted during the early stages of my Ph.D. I successfully graduated in 2022 and transitioned to an industry role. Please be aware that I cannot guarantee ongoing maintenance of the code or answer related questions.
