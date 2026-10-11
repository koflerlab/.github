<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/ededb4cb-3328-4777-83e0-c6be379d5e66" />

# 👋 Welcome to the koflerlab

**Quantitative Biomedical Image Analysis** · [Hertie Institute for AI in Brain Health](https://www.hertie.ai/independent-research-groups/research-groups/about/quantitative-biomedical-image-analysis), University of Tübingen

We work at the interface of **AI, medicine, and experimental psychology**. In a nutshell, our research runs in both directions between people and machines: we **bring human expert knowledge into machine learning models**, and we **bring machine learning models into human workflows**.

Many AI systems look great on benchmarks but stumble on a new scanner, a new hospital, or a question that matters to the expert using them. We want AI that augments human expertise rather than replacing it, so we build expert perception, clinical knowledge, and uncertainty directly into how models are trained, evaluated, and deployed.

Our projects range from "ivory tower" methods research to applied work in the clinic and the biology lab. Much of what we do is about building bridges between the two, and many of these bridges are open-source software, documented in software papers.

## 🔬 Research

### 👁️ Human-aligned evaluation
Do our metrics reflect what experts actually see? Using psychophysics and eye-tracking, we study how experts judge image and segmentation quality, build surrogate models that predict their ratings, and treat label noise and annotation uncertainty as a signal rather than a nuisance.
- [Are we using appropriate segmentation metrics? Identifying correlates of human expert perception for CNN training beyond rolling the DICE coefficient](https://doi.org/10.59275/j.melba.2023-dg1f) (MELBA 2023)
- [Deep Quality Estimation: Creating Surrogate Models for Human Quality Ratings](https://doi.org/10.1007/978-3-031-33842-7_1) (BrainLes 2022)
- [Approaching Peak Ground Truth](https://doi.org/10.1109/ISBI53787.2023.10230497) (ISBI 2023)

### 🧠 Segmentation, metrics & losses
We build robust segmentation models that hold up across institutions, scanners, and protocols, along with the training objectives and evaluation tools to make sure they get right what matters. Examples include [blob loss](https://github.com/neuronflow/blob_loss) for small, clinically relevant structures, [panoptica](https://github.com/BrainLesion/panoptica) for instance-wise evaluation, and [PeTu](https://github.com/BrainLesion/PeTu), our pipeline for pediatric brain tumors trained on data from the Children's Hospital Zurich. Applications range from brain metastases in multicenter studies to cells in 3D microscopy.
- [blob loss: Instance Imbalance Aware Loss Functions for Semantic Segmentation](https://doi.org/10.1007/978-3-031-34048-2_58) (IPMI 2023)
- [Panoptica: instance-wise evaluation of 3D semantic and instance segmentation maps](https://arxiv.org/abs/2312.02608)
- [Redefining Instance Matching: A Unified Framework for Part-Aware Matching in Panoptic Segmentation Evaluation](https://arxiv.org/abs/2605.31094) (2026)
- [Development and external validation of an MRI-based neural network for brain metastasis segmentation in the AURORA multicenter study](https://doi.org/10.1016/j.radonc.2022.11.014) (Radiotherapy and Oncology 2023)
- [Enhancing efficiency in paediatric brain tumour segmentation using a pathologically diverse single-center clinical dataset](https://arxiv.org/abs/2507.22152) (2025)

### 🎨 Image synthesis
Generative models that respect anatomy and pathology, such as diffusion-based 3D inpainting of healthy brain tissue, used to stress-test downstream models before they reach the clinic. We are also working out how to evaluate synthetic images in ways that match expert perception.
- [The BraTS Challenge: Local Synthesis of Healthy Brain Tissue via Inpainting](https://arxiv.org/abs/2305.08992)
- [Denoising Diffusion Models for 3D Healthy Brain Tissue Inpainting](https://arxiv.org/abs/2403.14499) (MICCAI DGM 2024)
- [fastWDM3D: Fast and Accurate 3D Healthy Tissue Inpainting](https://arxiv.org/abs/2507.13146) (MICCAI DGM 2025)

### 🧰 Open & scalable translation
Modular, reproducible tooling for preprocessing, segmentation, and benchmarking, plus decentralized approaches that let institutions collaborate without moving sensitive patient data.
- [BrainLesion Suite: A flexible and user-friendly framework for modular brain lesion image analysis](https://arxiv.org/abs/2507.09036)
- [BraTS Orchestrator: Democratizing and disseminating state-of-the-art brain tumor image analysis](https://arxiv.org/abs/2506.13807)
- [BraTS Toolkit: Translating BraTS Brain Tumor Segmentation Algorithms Into Clinical and Scientific Practice](https://doi.org/10.3389/fnins.2020.00125) (Frontiers in Neuroscience 2020)

### 🔬 Beyond radiology
Deep learning for 3D microscopy and whole-organ imaging, together with biology labs.
- [Virtual reality-empowered deep-learning analysis of brain cells](https://doi.org/10.1038/s41592-024-02245-2) (Nature Methods 2024)
- [Spatial proteomics in three-dimensional intact specimens](https://doi.org/10.1016/j.cell.2022.11.021) (Cell 2022)

Our applications center on brain health, including adult and pediatric brain tumors, metastases, stroke, lesion assessment, and PET imaging, across MRI, CT, and microscopy. 📚 Full publication list: [Google Scholar](https://scholar.google.com/citations?user=1ZLJyJ4AAAAJ&hl=en)

We believe in open science: we share our code, benchmark methods through international challenges, and publish our tools so others can build on them.

---

## 🧠 Projects

### Our repositories

Code, tools, and research projects from the lab live right here in this organization: 👉 [**browse all koflerlab repositories**](https://github.com/orgs/koflerlab/repositories)

### Community initiatives

Some of our efforts have grown into larger collaborations with partners around the world, so they have their own GitHub organizations:

| Initiative | Description |
|---|---|
| [**BrainLesion**](https://github.com/BrainLesion) | A flexible open-source suite for modular brain lesion image analysis, from preprocessing to segmentation and evaluation, including BraTS Orchestrator, panoptica, and PeTu. |
| [**BraTS Inpainting Challenge**](https://github.com/BraTS-inpainting) | The international BraTS challenge we lead, benchmarking methods that synthesize healthy brain tissue in lesioned regions. |

---

## 🎓 Teaching

We enjoy teaching at the meeting point of medicine, computer science, and the life sciences, with a focus on critical AI literacy and hands-on work.

The whole team is involved in the **Health Innovation Lab** at the University of Tübingen, where medical and computer science students team up on clinically motivated AI projects. We helped shape the course concept and contribute through lectures and project mentoring.

---

## 📰 Stay up to date

- 💼 **News & updates:** we share new papers, software releases, challenges, and open positions on [Florian's LinkedIn](https://www.linkedin.com/in/florian-kofler/)
- 📚 **Publications:** the full, continuously updated list lives on [Google Scholar](https://scholar.google.com/citations?user=1ZLJyJ4AAAAJ&hl=en)
- ⭐ **Code:** watch or star our repositories here and in the [BrainLesion](https://github.com/BrainLesion) organization to follow new releases

---

## 👤 Group Lead: Florian Kofler

[![GitHub](https://img.shields.io/badge/GitHub-neuronflow-181717?logo=github)](https://github.com/neuronflow)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Florian%20Kofler-0A66C2?logo=linkedin)](https://www.linkedin.com/in/florian-kofler/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=1ZLJyJ4AAAAJ&hl=en)
[![X](https://img.shields.io/badge/X-@neuronflow-000000?logo=x)](https://x.com/neuronflow)

---

## 📬 Applications

Interested in joining us? **We will open a mailing list soon.** Stay tuned and follow Florian on [LinkedIn](https://www.linkedin.com/in/florian-kofler/) for announcements.


Interested in joining us? **We will open a mailing list soon.** Stay tuned and follow Florian on [LinkedIn](https://www.linkedin.com/in/florian-kofler/) for announcements.
