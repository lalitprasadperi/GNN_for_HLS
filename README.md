# GNN_for_HLS
### Title
Graph Neural Networks for congestion prediction and logic optimization for synthesis of system-on-chips.

### Contributions
Lalit Prasad Peri, Benjamin Rice, Wilson Smith
mailto: {lalitprasad, bsrice33 ,wsmit22}@vt.edu

### Abstract
Abstract. As transistor scaling continues, the ability to accurately predict congestion during early design stages, particularly during logic synthesis, is essential for reducing the design cycle and enhancing System-on-Chip (SoC) performance. Congestion caused by inefficient logic combinations can lead to suboptimal physical implementations, increased development costs, and longer design times. Traditional manual optimization techniques in Very-Large-Scale Integration (VLSI) design rely heavily on expert intuition and iterative methods, which are both timeconsuming and unsuitable for the complexity of modern SoC designs.

In this project, we explore the application of Graph Neural Networks (GNNs) for logic optimization in SoC design. GNNs offer significant advantages by embedding prior knowledge and incorporating inductive biases relevant to VLSI tasks, making them well-suited for physics-informed optimization. These biases differ from those commonly applied in GNNs used for other structured data types, such as social or citation networks. Our approach involves predicting congestion through direct learning of embeddings from netlist designs using matrix factorization techniques and inductive biasing, a distinct improvement over classical optimization methods. By integrating these predictions, we aim to improve key design tasks, such as floor-plan congestion, timing, and parasitic estimation, earlier in the design process. Our framework builds upon design automation tools like OPENROAD[1] and DREAMPLACE[2], and seeks to automate critical stages of SoC design, ultimately reducing design cycles and optimizing logic synthesis for improved performance.

### References

1. OpenRoads Project https://theopenroadproject.org/
2. Y. Lin et al., "DREAMPlace: Deep Learning Toolkit-Enabled GPU Acceleration for Modern VLSI Placement," in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, vol. 40, no. 4, pp. 748-761, April 2021
3. Guyue Huang. et al., "Machine Learning for Electronic Design Automation: A Survey". ACM Transactions on Design Automation of Electronic Systems, 2021.
4. Brucek Khailany, Haoxing Ren, Steve Dai, Saad Godil, Ben Keller, Robert Kirby, Alicia Klinefelter, Rangharajan Venkatesan, Yanqing Zhang, Bryan Catanzaro, William J. Dally."Accelerating Chip Design With Machine Learning". IEEE Micro, 2020. paper
5. Yuzhe Ma, Zhuolun He, Wei Li, Lu Zhang, Bei Yu., "Understanding Graphs in EDA: From Shallow to Deep Learning" International Symposium on Physical Design (ISPD), 2020. paper
6. Daniela Sanchez Lopera, Lorenzo Servadei, Gamze Naz Kiprit, Souvik Hazra, Robert Wille, Wolfgang Ecker. "Survey of Graph Neural Networks for Electronic Design Automation" ACM/IEEE Workshop on Machine Learning for CAD (MLCAD), 2021. 
7. Daniela Sánchez Lopera, Lorenzo Servadei, Gamze Naz Kiprit, Robert Wille, Wolfgang Ecker. "A Comprehensive Survey on Electronic Design Automation and Graph Neural Networks: Theory and Applications." ACM Transactions on Design Automation of Electronic Systems, 2022.0. 
6. Haoxing Ren, Siddhartha Nath, Yanqing Zhang, Hao Chen, Mingjie Liu. "Why are Graph Neural Networks Effective for EDA Problems?". IEEE/ACM International Conference On Computer Aided Design (ICCAD) , 2022.0. 
7. Nan Wu, Hang Yang, Yuan Xie, Pan Li, Cong Hao "High-Level Synthesis Performance Prediction using GNNs: Benchmarking, Modeling, and Advancing." ACM/IEEE Design Automation Conference (DAC), 2022.0.
8. Daniela Sánchez Lopera, Wolfgang Ecker. "GNNs for EDA Behavioral and Logic Design Applying GNNs to Timing Estimation at RTL" IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2022.
9. Ecenur Ustun, Chenhui Deng, Debjit Pal, Zhijing Li, Zhiru Zhang "Accurate Operation Delay Prediction for FPGA HLS Using Graph Neural Networks." IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2020.
10. Nan Wu, Yuan Xie, Cong Hao. "IRONMAN: GNN-assisted Design Space Exploration in High-Level Synthesis via Reinforcement Learning." Proceedings of the 2021 Great Lakes Symposium on VLSI (GLSVLSI), 2021.
11. Robert Kirby, Saad Godil, Rajarshi Roy, Bryan Catanzaro. "CongestionNet: Routing Congestion Prediction Using Deep Graph Neural Networks." IFIP/IEEE 27th International Conference on Very Large Scale Integration (VLSI-SoC), 2019. paper
12. Amur Ghose, Vincent Zhang, Yingxue Zhang, Dong Li, Wulong Liu, Mark Coates. "Generalizable Cross-Graph Embedding for GNN-based Congestion Prediction." IEEE/ACM International Conference On Computer Aided Design (ICCAD), 2021. paper
13. Yi-Chen Lu, Siddhartha Nath, Vishal Khandelwal, Sung Kyu Lim. "RL-Sizer: VLSI Gate Sizing for Timing Optimization using Deep Reinforcement Learning." 58th ACM/IEEE Design Automation Conference (DAC), 2021. paper
14. Azalia Mirhoseini, Anna Goldie, Mustafa Yazgan, Joe Wenjie Jiang, Ebrahim Songhori, Shen Wang, Young-Joon Lee, Eric Johnson, Omkar Pathak, Azade Nazi, Jiwoo Pak, Andy Tong, Kavya Srinivasa, William Hang, Emre Tuncer, Quoc V. Le, James Laudon, Richard Ho, Roger Carpenter, Jeff Dean. "A graph placement methodology for fast chip design" Nature, 2021. 
15. Zhiyao Xie, Rongjian Liang, Xiaoqing Xu, Jiang Hu, Yixiao Duan, Yiran Chen. "Net2: A Graph Attention Network Method Customized for Pre-Placement Net Length Estimation" Proceedings of the 26th Asia and South Pacific Design Automation Conference (ASPDAC), 2021.
16. Yi-Chen Lu, Sai Pentapati, Sung Kyu Lim. "The Law of Attraction: Affinity-Aware Placement Optimization using Graph Neural Networks" Proceedings of the 2021 International Symposium on Physical Design (ISPD), 2021.
17. Anthony Agnesina, Kyungwook Chang, Sung Kyu Lim. "VLSI placement parameter optimization using deep reinforcement learning" Proceedings of the 39th International Conference on Computer-Aided Design (ICCAD), 2020.
18. Zizheng Guo, Mingjie Liu, Jiaqi Gu, Shuhan Zhang, David Z. Pan, Yibo Lin. "A timing engine inspired graph neural network model for pre-routing slack prediction" Proceedings of the 59th ACM/IEEE Design Automation Conference (DAC), 2022.
19. Ruoyu Cheng, Junchi Yan. "On Joint Learning for Solving Placement and Routing in Chip Design" Neural Information Processing Systems (NeurIPS), 2021.
20. RISC-V MegaBoom CPU [https://github.com/The-OpenROAD-Project/megaboom]
