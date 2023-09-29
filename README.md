# Efficient-Large-Scale-Deployment-of-LLM-Models-Across-Heterogeneous-Hardware-Architecture

The influence of transformer models in natural language processing and various other domains has been profound, revolutionizing the landscape of AI applications. From language models such as GPT and BERT to innovations like vision transformers, these models have ushered in a new era of capabilities. However, as the demand for real-time, low-power, and low-latency processing continues to grow, a significant challenge emerges: the efficient deployment of these models on high-speed hardware architectures. Field-Programmable Gate Arrays (FPGAs) have emerged as a particularly promising platform for deploying deep learning algorithms, thanks to the inherent dataflow characteristics of these algorithms. FPGAs have already demonstrated their effectiveness in deploying Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and recommender systems through a body of research [1-9]. While there have been limited efforts to accelerate Large Language Model (LLM) deployment on FPGAs [10-12], these endeavors often rely on model compression and quantization, which can compromise inference quality. Recent trends indicate a growing interest in deploying larger models across heterogeneous hardware architectures, including multiple FPGAs, CPUs, and GPUs, interconnected in a pipeline configuration leveraging high-speed 100GBps TCP/IP links [7,9, 13,14,15]. This approach harnesses the strengths of diverse accelerators to tackle the heterogeneity present in deep learning models, both in terms of computation and memory requirements. Building upon the promising results of these endeavors, we propose an extensive benchmarking study. Our objective is to evaluate the performance of various open-source LLM models such as BERT, GPT-2, T5, Bloom, LLama2, and others, when deployed across heterogenous hardware (including multiple FPGAs) interconnected in a pipeline configuration. This research aims to illuminate the feasibility and efficiency of large-scale LLM deployments, offering valuable insights into their practical applicability in real-world scenarios.

 

1. https://ieeexplore.ieee.org/document/9724104
2. https://ieeexplore.ieee.org/document/9761744
3. https://github.com/Xilinx/Vitis-AI-Tutorials
4. https://dl.acm.org/doi/10.1145/3503465
5.https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119857891.ch11
6. https://ieeexplore.ieee.org/document/8966676
7. fleetrec: https://dl.acm.org/doi/10.1145/3447548.3467139
8. HeteroRec: https://dl.acm.org/doi/abs/10.1145/3564121.3564134
9. niser: https://dl.acm.org/doi/abs/10.1145/3489525.3511692
10. FTRANS: https://arxiv.org/abs/2007.08563
11. EFA-Trans: https://www.mdpi.com/2079-9292/11/21/3550
12. https://dl.acm.org/doi/10.1145/3564606
13. https://dl.acm.org/doi/fullHtml/10.1145/3432816
14. https://ieeexplore.ieee.org/document/10137117
15. https://arxiv.org/pdf/2102.01343.pdf#:~:text=Therefore%2C%20because%20of%20the%20high,the%20tested%20multi%2D%20board%20setup.

## Contributors
Rekha Singhal           rekha.singhal@tcs.com <br>
Manoj Nambiar           m.nambiar@tcs.com
