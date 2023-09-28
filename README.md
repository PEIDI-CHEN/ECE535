# ECE535
<font size=3>Pr1oject Proposal:</font> 
Analyzing TartanVO Performance Across Diverse Datasets
Introduction:
Our project aims to comprehensively understand and evaluate the performance of TartanVO, a state-of-the-art learning-based Visual Odometry (VO) system. We will conduct a thorough investigation, encompassing literature review, algorithm understanding, implementation, and in-depth evaluation to provide valuable insights into its efficacy across diverse datasets.
Phase1: Research
1a. Literature Review:
We will delve into the research paper "TartanVO: A Generalizable Learning-based VO" to gain a deep understanding of the methodology, architecture, and the core findings of TartanVO.
1b. Existing Algorithm Overview:
Next, we will meticulously analyze the TartanVO GitHub repository to grasp its code structure, dependencies, and existing functionalities. Verifying the setup with sample data will ensure a solid foundation for the implementation phase.
Phase 2: Implementation
2a. Data Preparation:
To prepare for the implementation, we will procure essential datasets, including EuRoC, KITTI, and HoloSet. Data preprocessing will be performed to align with TartanVO's specific input requirements, ensuring a consistent format and structure.
2b. Model Training:
If required, we will initiate model training on the datasets. This entails configuring the training loop, fine-tuning hyperparameters, and ensuring convergence for optimal performance.
2c. Tracking Implementation:
Utilizing the trained TartanVO model, we will implement pose tracking and map generation on both EuRoC and KITTI datasets. Emphasis will be placed on modularity to facilitate seamless experimentation and effective debugging.
Phase 3: Evaluation
3a. Benchmarking:
Our evaluation will encompass a detailed benchmarking of TartanVO on the EuRoC and KITTI datasets, recording critical metrics such as accuracy, robustness, and computational efficiency.
3b. Comparison:
A comprehensive comparison of TartanVO's performance across these datasets will be conducted, employing both quantitative metrics and qualitative visual analysis. We will meticulously document performance variations and any observed discrepancies.
Phase 4: Analysis
4a. Reasoning & Hypotheses:
This phase involves a deep dive into understanding potential performance discrepancies across datasets. Factors like scene complexity, lighting conditions, and inherent data nature will be examined. We will consult relevant literature and the research paper to derive insightful hypotheses regarding these differences.
