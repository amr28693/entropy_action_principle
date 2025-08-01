# CE Action Principle: Unifying Entropy, Quantum, and Spacetime via Collapse-Emergence

# For preprint and supplementary materials, see [arxiv_CE_action_preprint_DRAFT1.pdf](arxiv_CE_action_preprint_DRAFT1.pdf)


# Overview

CE Action Principle is a unified framework synthesizing thermodynamics, quantum mechanics, and spacetime geometry from a new 
information-theoretic action based on entropy-driven collapse events. 

This project includes all core code and numerical experiments supporting the preprint:

> Action Principle for Entropy: A Synthesis Generating Thermodynamics, Quantum Structures, and Spacetime Geometry from a Delta-Supported Collapse Surface

This repository provides full, reproducible Jupyter walkthroughs for all published figures and results.

To reproduce the results and figures of the associated preprint, simply run the scripts in order. They are labelled in a manner corresponding
with their respective sections in the Appendices.

---

## Contents

- `arxiv_CE_action_preprint_DRAFT1.pdf`  
  The full draft of the preprint (arXiv-ready).

- `full_CE_Appendix_C_walkthrough_suite.ipynb`  
  Numerical simulations of the CE Action Principle, reproducing all results in Appendix C.

- `CE_Appendix_D_walkthroughsuite.ipynb`  
  Information-theoretic Bell correlations and no-Hilbert-space quantum logic, reproducing results in Appendix D:

  Appendix D implements an information-theoretic collapse logic to demonstrate how quantum-like correlations can emerge from global feedback between system, measurement choices, and environment at each collapse event ($t_0$). In this model, free choice and physical randomness are real and active within the feedback loop. At each $t_0$, a global information constraint “closes the loop” and enforces conservation, but does not predetermine outcomes or deny local freedom. The resulting correlations do not require action-at-a-distance or classical superdeterminism—instead, they arise from the participatory, dynamically evolving context in which every measurement, environment, and collapse event co-define the outcome. The script illustrates this principle by producing only perfectly correlated outputs (00 or 11), emphasizing the role of global information closure rather than local randomness or nonlocal influence.

  While Appendix D’s script appears almost absurdly simple--always outputting only perfectly correlated outcomes--this is precisely the point. Over the course of the preprint the point is made that the model’s depth lies in its global perspective: each outcome is not determined locally or randomly, but emerges from the dynamic feedback loop of system, observer, and environment, all “closing the loop” at every collapse event (every ($t_0$)). This apparent simplicity is actually a signature of the theory’s elegance, showing that the strange quantum correlations can arise naturally from the structure of information itself, without the need for hidden variables or 'spooky' action-at-a-distance.

---

# Quick Start

1. Clone the repository

bash
git clone https://github.com/yourusername/ce-action-principle.git
cd ce-action-principle

2. Install dependencies
All simulations use Python 3.x and standard scientific libraries.

Install with:

pip install -r requirements.txt

Typical dependencies:
numpy
scipy
matplotlib
jupyter

All required packages are listed in each notebook's first cell; no obscure dependencies are used.

3. Run the notebooks
Launch Jupyter:

bash
Copy
Edit
jupyter notebook
Open and run:

full_CE_Appendix_C_walkthrough_suite.ipynb

CE_Appendix_D_walkthroughsuite.ipynb

Each notebook is annotated with clear section headers matching the corresponding appendix of the preprint.


If you'd like to use or build on this work please cite the associated preprint:
@article{Rodriguez_CE_Action_Principle_2025,
  title={Action Principle for Entropy: A Synthesis Generating Thermodynamics, Quantum Structures and Spacetime Geometry from a Delta-Supported Collapse Surface},
  author={Anderson M. Rodriguez},
  journal={arXiv preprint},
  year={2025},
  url={https://arxiv.org/abs/6670643}
  Orcid={0009-0007-5179-9341}
}
