
Secure Cloud-Native Security Platform for AWS Distributed Workloads

## Overview

**Quantum Computing Exploration for Drug Discovery on AWS** is an open-source solution that allows researchers and quantum computing advocates to design and run computational studies in the field of drug discovery.

With this solution, you can access quantum computers via the **Amazon Braket** service. The **Amazon Braket Hybrid Job** feature allows you to use both classical and quantum computing resources to evaluate experiment values such as **cost, time, and performance**.

The solution comes with **built-in sample code** for certain drug discovery problems, such as:

* Molecular docking
* Protein folding
* RNA folding
* Retrosynthetic planning

This helps you get started with quantum computing in the field of drug discovery.

The overall architecture is shown below:

*![image](https://github.com/user-attachments/assets/e6b416cf-e2f4-46aa-acf4-fb94110c22c6)*

For a detailed description of the architecture, refer to the **[Architecture Page]**.

This solution deploys an **Amazon CloudFormation template** in your AWS Cloud account and provides the URL for **Notebook Experiments** about drug discovery problems.

---

## Pre-built Examples for Drug Discovery

| Problem Name            | Method                         | Reference                                                                                               |
| ----------------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------- |
| Molecular Unfolding     | QUBO                           | Quantum Molecular Unfolding (2021)                                                                      |
| RNA Folding             | QUBO                           | RNA Folding Using Quantum Computers (2022) – QHack 2022 Winner                                          |
| Protein Folding         | Quantum Walk                   | QFold: Quantum Walk and Deep Learning to Solve Protein Folding (2022) – Roberto Campos's Implementation |
| Protein Folding         | VQE – Grover's Algorithm       | Quantum Speedup for Protein Structure Prediction (2022) – Renata Wong's Implementation                  |
| Retrosynthetic Planning | Quantum Reinforcement Learning | Learning Retrosynthetic Planning through Simulated Experience (2019)                                    |

> More examples will be added continuously with updates.

---

## File Structure

After cloning the repository, the directory structure will look like this:

```
CHANGELOG.md
CODE_OF_CONDUCT.md
CONTRIBUTING.md
LICENSE
NOTICE
README.md

docs/
├── en/
├── zh/
├── index.html
├── mkdocs.base.yml
├── mkdocs.en.yml
└── mkdocs.zh.yml

source/
├── README.md
├── cdk.json
├── package-lock.json
├── package.json
├── tsconfig.jest.json
├── tsconfig.json
├── version.json
├── src/
│   ├── cdk/
│   └── notebook/
│       └── healthcare-and-life-sciences/
│           ├── a-1-molecular-unfolding-quadratic-unconstrained-binary-optimization/
│           ├── b-1-folding-quadratic-unconstrained-binary-optimization/
│           ├── c-1-rna-folding-quadratic-unconstrained-binary-optimization/
│           ├── c-2-protein-folding-variational-quantum-eigensolver/
│           ├── c-3-protein-folding-grover-search/
│           └── d-1-retrosynthetic-planning-quantum-reinforcement-learning/
└── test/
```

## Resources

* **Readme**
* **License:** Apache-2.0
* **Code of Conduct**
* **Contributing Guide**

---

## Languages

* **Jupyter Notebook:** 99.5%
* **Other:** 0.5%

---

