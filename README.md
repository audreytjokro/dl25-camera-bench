# dl25-camera-bench
This repository contains all the code for the paper: "Enhancing Video Vision-Language Models for Camera and Scene Understanding" written for the Deep Learning course at Cornell Tech, Fall 2025.


## Reproducing the Experiments

### 1. Generate Captions

Run the notebooks in `caption-generation-notebooks/`:

### 2. Evaluate BERTScore and LLM-as-Judge

Run the notebooks in the `evaluation-notebooks/`:

---

## Prompts

All prompt templates used in the experiments (both unified dual-task and separate
camera/scene prompts) are defined in the paper’s Appendix for reference.

---

## Data

We use the **CameraBench** dataset:

- CameraBench test split (N ≈ 1,071 videos) for evaluation.
- Please refer to the official CameraBench repository for data access
  and licensing details.

This repository does **not** redistribute the dataset. You must download it
separately and update the data paths in the notebooks.

---

## Attribution and External Code

Parts of this repository were adapted from:

- Official CameraBench code and examples (data loading, evaluation utilities).
- Qwen2.5-VL-7B example scripts.
- The use of AI to assist in building out the caption generation and evaluation pipelines.

We acknowledge these sources in accordance with the course instructions.

---

## Paper

If you refer to this project, please cite the course report:

> S. Dong, W. Li, A. Tjokro. “Enhancing Video Vision-Language Models for Camera and Scene Understanding.” Deep Learning, Cornell Tech, 2025.