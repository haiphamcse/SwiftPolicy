# SwiftPolicy: Accelerated Visuomotor Policies via Score Distillation Sampling

## 📖 Overview

Diffusion Policy (DP) has established a new state-of-the-art in robotic manipulation by modeling policies as conditional denoising processes. However, the iterative nature of DP creates a significant latency bottleneck, requiring tens of network evaluations to generate a single action.

**SwiftPolicy** is a surprisingly simple distillation scheme to accelerate Diffusion Policy -> Achieving a **50x reduction** in neural network evaluations (NFE) 

## 📚 Resources

### 📄 Paper
The full project report is available as a PDF: [MVA_Robots_25.pdf](assets/MVA_Robots_25.pdf)

### 🎥 Demo Video

![Teacher vs Student policy running within the same time constraint](assets/download.gif)

*Teacher vs Student policy running within the same time constraint*

## 🚀 Quick Start

The entire training and evaluation pipeline is self-contained in a Google Colab notebook. You can run the code directly in your browser without any local setup.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sW_0gh0vuMX1heYdfT6FceVNEQ6L-6Fh?usp=drive_link)

**Click the badge above to open the notebook.**

## 🚧 Todo & Future Work

We are actively looking to improve SwiftPolicy. Current roadmap includes:
- [ ] Run on a real robot (if you have a robot we can borrow, please reach out!)
- [ ] Improving stability during training
- [ ] Scale to different datasets


## ✍️ Authors

* **Duc-Hai Pham** (duchai1092002 at gmail dot com) - *ENS Paris-Saclay*
* **Ianis Hammani** (ianis.hammani1712 at gmail dot com) - *ENS Paris-Saclay*

This project was developed as part of the **MVA Master's program** (Robotics course).

## 📝 Citation

If you find this code or work useful in your research, please cite the following:

```bibtex
@software{Pham_SwiftPolicy_Accelerated_Visuomotor_2025,
author = {Pham, Duc-Hai and Hammani, Ianis},
month = jan,
title = {{SwiftPolicy: Accelerated Visuomotor Policies via Score Distillation Sampling}},
url = {https://github.com/yourusername/swiftpolicy},
version = {1.0.0},
year = {2025}
}
