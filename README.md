# QNEAT
QNEAT: Natural Evolution of Variational Quantum Circuit Architecture

Authors: Alessandro Giovagnoli, Yunpu Ma, Volker Tresp

Here we focus on variational quantum circuits (VQC), which emerged as the most promising candidates for the quantum counterpart of neural networks in the noisy intermediate-scale quantum (NISQ) era. Although showing promising results, VQCs can be hard to train because of different issues, e.g., barren plateau, periodicity of the weights, or choice of architecture. This paper focuses on this last problem for finding optimal architectures of variational quantum circuits for various tasks. To address it, we propose a gradient-free algorithm inspired by natural evolution to optimize both the weights and the architecture of the VQC. In particular, we present a version of the well-known neuroevolution of augmenting topologies (NEAT) algorithm and adapt it to the case of variational quantum circuits. We refer to the proposed architecture search algorithm for VQC as QNEAT. We test the algorithm with different benchmark problems of classical fields of machine learning i.e. reinforcement learning and combinatorial optimization.

Please use this BitTex for citation:
@inproceedings{giovagnoli2023qneat,
  title={Qneat: Natural evolution of variational quantum circuit architecture},
  author={Giovagnoli, Alessandro and Tresp, Volker and Ma, Yunpu and Schubert, Matthias},
  booktitle={Proceedings of the Companion Conference on Genetic and Evolutionary Computation},
  pages={647--650},
  year={2023}
}
