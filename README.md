# Deep Learning-Based Action Recognition for Joining and Welding Processes of Dissimilar Materials

This repository contains the code and models for a novel deep learning-based framework designed for action recognition in joining and welding tasks involving dissimilar materials. The proposed model, Multi-Scale Spatiotemporal Attention Network (MS-STAN), leverages advanced feature extraction techniques and attention mechanisms to analyze complex welding processes in real-time.

## Abstract

Joining and welding processes for dissimilar materials present unique challenges due to the need for precise monitoring and analysis of complex physical and chemical interactions. These processes are influenced by variations in material behavior, dynamic changes in process parameters, and environmental factors, making real-time action recognition a critical tool for ensuring consistent quality, efficiency, and reliability. Traditional methods for analyzing such processes often fail to effectively capture the multi-scale spatiotemporal dependencies and adapt to the inherent variability of these operations.

To address these limitations, we propose the MS-STAN framework. It captures fine-grained spatiotemporal patterns across varying scales and suppresses irrelevant or noisy regions within the input data. The framework integrates adaptive frame sampling and lightweight temporal modeling to ensure computational efficiency, making it suitable for real-time applications without sacrificing accuracy. Domain-specific knowledge is embedded to enhance interpretability and improve the model's generalizability across various welding scenarios.

## Keywords

- Action Recognition
- Dissimilar Materials
- Joining and Welding
- Spatiotemporal Modeling
- Deep Learning

## Features

- **Multi-Scale Spatiotemporal Attention Network (MS-STAN)**: A deep learning framework designed for action recognition in welding and joining tasks.
- **Real-time Monitoring**: Capable of processing dynamic, complex welding actions in real-time with high accuracy.
- **Adaptive Frame Sampling**: Ensures efficiency while maintaining model performance.
- **Interpretability and Generalization**: Domain-specific knowledge improves the model's ability to generalize across different joining and welding scenarios.

## Installation

To use the code in this repository, clone it and install the necessary dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Deep-Learning-Welding-Action-Recognition.git
   cd Deep-Learning-Welding-Action-Recognition
