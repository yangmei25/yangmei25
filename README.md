# Yangmei Li, Ph.D.

I am a computational biologist and microbiologist building reproducible bioinformatics workflows and rigorously evaluated AI systems for biomedical research. My work connects experimental biology, sequencing, biological data analysis, foundation models, and scientific failure analysis.

## Featured work

### [ESM-2 Protein Localization](https://github.com/yangmei25/esm2-protein-localization)

An end-to-end protein language-model project spanning biological and classical baselines, frozen embeddings, multi-seed fine-tuning, homology-filtered external evaluation, subtype failure analysis, long-protein inference, and a tested FastAPI service.

- Fine-tuned ESM-2 150M achieved **0.936 validation F1** and **0.982 ROC-AUC** across three seeds.
- External evaluation identified peripheral membrane proteins as the main failure mode.
- Subtype-aware modeling improved peripheral-protein recall from **0.325 to 0.549**.
- Delivered with **FastAPI, Docker, GitHub Actions, and 40 automated tests**.

### [scGPT–Scanpy NSCLC Single-Cell Benchmark](https://github.com/yangmei25/scgpt-scanpy-nsclc-single-cell-demo)

A patient- and sample-aware comparison of conventional Scanpy/PCA and frozen scGPT representations across **29,614 NSCLC cells from 10 metastatic lymph-node samples**.

- scGPT improved broad-cell sample-held-out kNN accuracy from **0.832 to 0.923**.
- The evaluation also found stronger platform separation and weaker performance for some fine-grained CD8 T-cell states.
- Sample-level analysis compared cell composition, functional programs, and scGPT pooling without presenting the small cohort as a validated clinical predictor.

## Technical focus

- **Bioinformatics:** single-cell RNA-seq, microbial and viral genomics, metagenomics, genome assembly, comparative genomics, sequencing QC
- **AI and machine learning:** PyTorch, Hugging Face Transformers, scGPT, ESM-2, scikit-learn, fine-tuning, embeddings, model benchmarking, error analysis
- **Scientific software:** Python, R, Bash, Linux/HPC, Git, automated testing, GitHub Actions, FastAPI, Docker

## Current direction

I am focused on scientific AI and computational biology roles where biological domain knowledge, reproducible analysis, and rigorous evaluation are essential to building trustworthy systems.

[LinkedIn](https://www.linkedin.com/in/yangmei-li-9a04b03a5/) · [GitHub](https://github.com/yangmei25)
