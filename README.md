# Multi-Agent LLMs as Ethics Advocates for AI-Based Systems (MALEA)

[![arXiv](https://img.shields.io/badge/arXiv-2507.08392-b31b1b.svg)](https://arxiv.org/abs/2507.08392)
[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/downloads/)

This repository hosts the **data** and **code** for the paper:

> **Multi-Agent LLMs as Ethics Advocates for AI-Based Systems**  
> Asma Yamani, Malak Baslyman, and Moataz Ahmed  
> [arXiv:2507.08392](https://arxiv.org/abs/2507.08392)

---

## 📖 Overview

Incorporating ethics into the requirements engineering process is often challenging due to the need for diverse stakeholder input and the resource intensity of manual elicitation. To address this, we introduce **MALEA** (Multi-Agent LLM Ethics Advocate), a framework that leverages multiple large language model (LLM) agents to draft and critique ethics-related requirements.

MALEA includes four agents:
- **Requirements Engineer Agent** – generates initial ethics requirements.
- **Quality Assurance Agent** – checks atomicity, minimality, and clarity.
- **Ethics Advocate Agent** – critiques requirements from an ethical perspective.
- **Documentation Agent** – consolidates and finalizes requirements.

We evaluate MALEA on two AI applications (a **Fake Review Detection System** and a **Saudi Sign Language Translation App**) and show that it captures most human-elicited ethics requirements while adding relevant new ones. Importantly, it highlights the role of **human-in-the-loop oversight** in ensuring cultural, contextual, and ethical validity.

---


## ⚙️ Code

We provide a Colab Notebook. 
---

## 📊 Data

We provide:
- **Human-elicited ethics requirements** (from domain experts).
- **LLM-generated requirements** (single LLM baseline vs. multi-agent).

---

## ✨ Key Contributions

- Propose **MALEA**, a multi-agent LLM framework with an embedded **ethics advocate agent**.  
- Demonstrate effectiveness on **two real-world case studies**.  
- Show that MALEA achieves higher recall than single-LLM baselines and surfaces **additional relevant ethical requirements**.  
- Highlight the importance of **human oversight** to mitigate reliability issues.  

---

## 📜 Citation

If you use this repository in your research, please cite:

```bibtex
@misc{yamani2025multiagentllmsethicsadvocates,
      title={Multi-Agent LLMs as Ethics Advocates for AI-Based Systems}, 
      author={Asma Yamani and Malak Baslyman and Moataz Ahmed},
      year={2025},
      eprint={2507.08392},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2507.08392}, 
}
```

---

## 🙏 Acknowledgments

This work was supported by the **Saudi Data and AI Authority (SDAIA)** and **King Fahd University of Petroleum and Minerals (KFUPM)** under the SDAIA-KFUPM Joint Research Center for Artificial Intelligence (Grant no. JRC-AI-RG-12).

---

## 📬 Contact

For questions or collaborations, please contact:  
**Asma Yamani** – g201906630@kfupm.edu.sa  
