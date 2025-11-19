# SOFAI-LM: A Cognitive Architecture for Efficient Reasoning

[![AAAI Accepted](https://img.shields.io/badge/AAAI-Lab%20Accepted-blue)](https://aaai.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Ollama](https://img.shields.io/badge/Served%20with-Ollama-white)](https://ollama.com/)

**Official website and notebook repository for the AAAI Lab: "SOFAI-LM: A Cognitive Architecture for Building Efficient and Reliable Reasoning Systems with LLMs".**

> **Website:** [https://sofai-lm-aaailab.github.io/](https://sofai-lm-aaailab.github.io/)

## 📖 Overview

This lab teaches participants how to build reliable, compute-efficient reasoning systems by instantiating **SOFAI-LM**, a cognitive architecture that guides a fast LLM (System 1) with a training-free metacognitive feedback loop and selectively falls back to a slower LRM (System 2) only when needed.

This repository hosts the **Lab Website** and the **Interactive Notebooks** used during the session. The core `sofailm` library code is installed externally within the notebooks.

## 📂 Repository Structure

```text
sofailm-lab/
├── index.html           # Lab Landing Page (Website)
├── notebooks/           # Interactive Lab Notebooks
│   ├── 01_setup.ipynb            # Environment setup & model pulling
│   ├── 02_graph_coloring.ipynb   # Case Study A: Graph Coloring
│   └── 03_debug_bench.ipynb      # Case Study B: DebugBench
├── images/              # Website assets
└── README.md            # This documentation
````

## 🚀 Getting Started

Participants can access the lab materials in two ways:

### 1\. Via the Website (Recommended)

Visit the [Lab Website](https://sofai-lm-aaailab.github.io/) to view all the information.

### 2\. Running Locally

If you prefer to run the notebooks on your local machine, clone this repository:

```bash
git clone [https://github.com/khvedant/sofailm-lab.git](https://github.com/khvedant/sofailm-lab.git)
cd sofailm-lab/notebooks
```

*Note: You will need [JupyterLab](https://jupyter.org/) or VS Code installed to run the `.ipynb` files.*

## 📅 Lab Schedule (Quarter Day)

| Time | Segment | Lead |
|------|---------|------|
| **0-20 min** | Welcome, objectives, and success criteria | Francesca Rossi |
| **20-40 min** | Environment Setup & Sanity Checks | Vishal Pallagani |
| **40-50 min** | **Hands-on A:** Graph Coloring (Evaluator $C(y)$, Feedback) | Vedant Khandelwal |
| **50-75 min** | **Hands-on B:** DebugBench (Test Harness, PO/BA/FH) | Keerthiram Murugesan |
| **75-85 min** | LRM Fallback Demo & Model Swapping | Vedant Khandelwal |
| **85-105 min**| Wrap-up, Failure Modes & Q\&A | Lior Horesh |

## 👥 Organizers

  * **Vedant Khandelwal** (University of South Carolina)
  * **Francesca Rossi** (IBM Research)
  * **Vishal Pallagani** (University of South Carolina)
  * **Keerthiram Murugesan** (IBM Research)
  * **Lior Horesh** (IBM Research)

## 📚 References

1.  **SOFAI-LM:** Khandelwal et al. (2025). *Language Models Coupled with Metacognition Can Outperform Reasoning Models.* arXiv preprint.
2.  **Thinking Fast and Slow in AI:** Ganapini et al. (2022). *The Role of Metacognition.*
3.  **Plan-SOFAI:** Fabiano et al. (2023). *A Neuro-Symbolic Planning Architecture.*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
