# Physics-Informed Neural Networks: Non-unique, uncorrelated trained weights 

This repository contains the implementation and datasets associated with the paper:

**"Deep Neural Networks as Discrete Dynamical Systems: Implications for Physics-Informed Learning"**

---


## 📌 Overview

Physics-Informed Neural Networks (PINNs) mostly exhibit **highly non-unique weight structures** after training, owing to the underconstrained inverse problem of learning.
Compared to traditional numerical methods, these weight matrices contain no low-level structures associated with the PDE in question.
This project investigates:
- Correlational properties of trained PINN weights over several independent runs for 3 different problems  
- A link to **Discrete Dynamical Systems** model for modelling deep neural network learning   

---


## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/abhishekganguly808/degeneracy-in-pinns.git
cd randomness-in-PINNs
```

## 📂 Structure

- `weights/` → Run-wise saved trained PINN weights (inviscid Burgers / viscous Burgers / Eikonal equation).
- `weights/PINN_1dburgers_riemann.ipynb`→ PINN code for inviscid Burgers' equation.
- `weights/PINN_1dburgers_sine.ipynb`→ PINN code for viscid Burgers' equation.
- `weights/eikonal_PINN.ipynb`→ PINN code for Eikonal equation.
- `burgers_chain_riemann.ipynb` → Statistical analysis of trained PINN weights for inviscid Burgers.
- `burgers_chain_sine.ipynb` → Statistical analysis of trained PINN weights for viscid Burgers.
- `eikonal_chain.ipynb` → Statistical analysis of trained PINN weights for Eikonal equation.
---

## ▶️ Usage

### 1. Analyze PINN Weights

Open and run any of the following:

```bash
burgers_chain_riemann.ipynb
burgers_chain_sine.ipynb
eikonal_chain.ipynb
```

## 📖 Citation
## arXiv version:
```bash
@misc{ganguly2026deepneuralnetworksdiscrete,
      title={Deep Neural Networks as Discrete Dynamical Systems: Implications for Physics-Informed Learning}, 
      author={Abhisek Ganguly and Santosh Ansumali and Sauro Succi},
      year={2026},
      eprint={2601.00473},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2601.00473}, 
}
```


## 📬 Contact
```bash
abhishekganguly808@gmail.com
```
