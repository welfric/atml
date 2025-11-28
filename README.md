# CS 6304 – Advanced Topics in Machine Learning (ATML)

This repository contains all materials for **CS 6304: Advanced Topics in Machine Learning**, taught by **Dr. Muhammad Tahir in Fall 2025**. The course is structured around hands-on experimentation with modern research-driven themes in machine learning, emphasizing the design of models robust to real-world constraints such as domain shifts, resource limitations, and decentralized data.

Throughout the course, students work through individual **modules**, each focused on a key challenge in contemporary ML. These include **Domain Adaptation & Generalization**, **Model Compression**, and **Federated Learning**, among others. Each module deepens theoretical understanding while reinforcing applied skills through implementation-focused assignments and final project reports.

---

## Repository Structure

The repository is organized modularly to align with the course structure:

```
├── Module_X/
│   ├── Manual + Report/
|        ├── Manual.pdf
|        ├── Report.pdf
│   ├── Task_1/
│   ├── .
│   └── Task_X/
```

- **Each module folder** corresponds to a specific topic covered in the course.
- **Task notebooks** contain code implementations, experimentation, and evaluation.
- **Manuals** define the module objectives, theoretical background, and assignment steps.
- **Reports** summarize findings, insights, and reflections on results achieved.

---

## Module Overview

Below is a brief description of each module included in the repository:

- Deep Representation Learning (DRL)

- **Domain Adaptation (DA) & Domain Generalization (DG):**
  Explores how to make ML models robust to distribution shifts by aligning feature spaces or learning domain-invariant representations. Covers techniques ranging from unsupervised adaptation to robust optimization strategies for unseen domains.

- **Model Compression:**
  Investigates strategies for deploying models under resource constraints, focusing on **Pruning**, **Quantization**, and **Knowledge Distillation**. Emphasizes the balance between efficiency and performance in real-time and edge computing scenarios.

- **Federated Learning:**
  Examines decentralized learning without data centralization, highlighting the effect of non-IID client distributions and introducing advanced optimization strategies such as FedProx, FedDyn, SCAFFOLD, and FedSAM.

Additional modules may be included depending on the progression of the course and final project direction.

This repository serves as both a record of course work and a reference for implementing state-of-the-art ML techniques in settings where robustness, scalability, and practicality are essential.
