# LLMs Under Attack: Understanding the Adversarial Mindset

**Presenter:** Bryan E. Tuck · University of Houston · [ORCID](https://orcid.org/0009-0002-3739-9708)  
**Event:** 11th ACM International Workshop on Security and Privacy Analytics (IWSPA ’25) — 6 June 2025, Pittsburgh, PA, USA  
**Slides:** [`LLMs Under Attack.pdf`](LLMs%20Under%20Attack.pdf)  
**Tutorial Notebook:** [`iwspa25_tutorial.ipynb`](iwspa25_tutorial.ipynb)

> **Abstract**  
> With Large Language Models (LLMs) powering critical applications, adversarial threats present urgent challenges to their safety and reliability. This tutorial explores adversarial threats against LLMs by covering foundational concepts, identifying key security implications, examining specific attack vectors (such as data poisoning, evasion techniques, and prompt-engineering vulnerabilities), and highlighting LLMs' dual roles as both targets and enablers of malicious activity. We critically assess current defensive approaches, discuss recent criticisms regarding detection reliability and ethical considerations, and outline key open research challenges. Attendees will gain practical insights into anticipating and mitigating adversarial threats to secure the deployment and application of LLM systems.

---

## Table of Contents

- [Tutorial Outline](#tutorial-outline)  
- [Prerequisites](#prerequisites)  
- [How to Use the Notebook](#how-to-use-the-notebook)  
- [Resources](#resources)  
- [Citation](#citation)  
- [Contact](#contact)  

---

## Tutorial Outline

| Section | Topics |
|---------|--------|
| **1. Introduction & Motivation** | LLMs’ dual usage in security; value of adversarial perspective |
| **2. Background & Foundations** | Pretraining, fine tuning, reinforcement learning with human feedback (RLHF), limitations & considerations |
| **3. Prompt Engineering & Alignment** | Zero/Few-shot, instruction tuning, RLHF; prompt-based threats |
| **4. Security Threat Landscape** | Data poisoning, evasion attacks, malicious-content generation |
| **5. Case Studies** | Jailbreaks, censorship side-effects |
| **6. Criticisms & Open Challenges** | Detection limits, evaluation gaps, ethics of LLM security research |

---

## Prerequisites

* Working knowledge of machine learning and basic NLP.  
* Familiarity with Transformers (attention, tokenization, pre-training).  
* Helpful, but not required, background in adversarial ML or security.

---

## How to Use the Notebook

1. Clone or download this repo.  
2. Create a fresh virtual environment.  
3. Launch Jupyter or VS Code.  
4. Open `iwspa25_tutorial.ipynb` and follow the cells sequentially.  

---

## Resources

<details>
<summary><strong>Foundational Architecture & Alignment</strong></summary>

| Year | Reference |
|------|-----------|
| 2017 | Vaswani *et al.* — “[Attention Is All You Need](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)” |
| 2020 | Brown *et al.* — “[Language Models Are Few-Shot Learners](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf)” |
| 2022 | Ouyang *et al.* — “[Training LMs to Follow Instructions with Human Feedback](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf)” |
| 2023 | OpenAI — “[GPT-4 Technical Report](https://cdn.openai.com/papers/gpt-4.pdf)” |
</details>

<details>
<summary><strong>Classical Adversarial ML</strong></summary>

| Year | Reference |
|------|-----------|
| 2013 | Szegedy *et al.* — “[Intriguing Properties of Neural Networks](https://arxiv.org/pdf/1312.6199)” |
| 2014 | Goodfellow *et al.* — “[Explaining & Harnessing Adversarial Examples](https://arxiv.org/pdf/1412.6572)” |
</details>

<details>
<summary><strong>LLM-Specific Threats & Defenses</strong></summary>

| Year | Reference |
|------|-----------|
| 2022 | Xu *et al.* — “[Exploring the Universal Vulnerability of Prompt-based Learning Paradigm](https://aclanthology.org/2022.findings-naacl.137.pdf)” |
| 2023 | Wei *et al.* — “[Jailbroken: How Does LLM Safety Training Fail?](https://proceedings.neurips.cc/paper_files/paper/2023/file/fd6613131889a4b656206c50a8bd7790-Paper-Conference.pdf)” |
| 2023 | Xue *et al.* — “[TrojLLM: A Black-box Trojan Prompt Attack on Large Language Models](https://proceedings.neurips.cc/paper_files/paper/2023/file/cf04d01a0e76f8b13095349d9caca033-Paper-Conference.pdf)” |
| 2023 | Wan *et al.* — “[Poisoning Language Models During Instruction Tuning](https://proceedings.mlr.press/v202/wan23b/wan23b.pdf)” |
| 2024 | Rao *et al.* — “[Tricking LLMs into Disobedience: Formalizing, Analyzing, and Detecting Jailbreaks.](https://aclanthology.org/2024.lrec-main.1462.pdf)” |
| 2024 | Abdali *et al.* — “[Securing Large Language Models: Threats, Vulnerabilities and Responsible Practices](https://arxiv.org/pdf/2403.12503)” |
| 2024 | Yao *et al.* — “[A survey on large language model (LLM) security and privacy: The Good, The Bad, and The Ugly](https://www.sciencedirect.com/science/article/pii/S266729522400014X)” |
</details>

---

## Citation

If you use these materials, please cite the tutorial abstract:

```bibtex
@inproceedings{tuck2025llms,
  title     = {LLMs Under Attack: Understanding the Adversarial Mindset},
  author    = {Bryan E. Tuck},
  booktitle = {Proceedings of the 11th ACM International Workshop on Security and Privacy Analytics (IWSPA '25)},
  year      = {2025},
  pages     = {33--35},
  publisher = {ACM},
  doi       = {10.1145/3716815.3729018}
}
```

## Contact

For questions or feedback about this tutorial, please contact Bryan E. Tuck ([betuck@uh.edu](mailto:betuck@uh.edu)). 
