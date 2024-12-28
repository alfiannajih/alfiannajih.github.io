---
title: "ReviceGraph"
excerpt: "Implementation of G-Retriever Framework to resume reviewer.<br/><img src='/images/revice-graph.png'>"
collection: portfolio
---

## Overview
A submission for the final stage of Compfest 16 AIC, held by Universitas Indonesia. This Project implemented a G-Retriever Framework, combining LLM and Knowledge Graph, to reduce its hallucination and to assist in resume review by determining whether a candidate’s resume matches the current job market need, which is represented as a Knowledge Graph.

High level view of how the model generated a response can be seen in image below:
![model-overview](/images/revice-graph.png)

## Tools Used
1. MLflow
2. Neo4j Database
3. PyTorch
4. Pytorch Geometric
5. Transformers


## Dataset
1. The knowledge graph was constructed from tabular data sourced from [Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings), which was originally scraped from job postings on LinkedIn.
2. The resume and feedback dataset was synthetically generated using GPT-4o.

## Reference
1. Bienstock, Daniel, et al. ”A note on the prize collecting traveling salesman problem.” Mathematical programming 59.1 (1993): 413-420. [[Paper](https://math.mit.edu/~goemans/PAPERS/BienstockGSW-1993-PrizeCollecting.pdf)]
2. He, Xiaoxin, et al. ”G-retriever: Retrieval-augmented generation for textual graph understanding and question answering.” arXiv preprint arXiv:2402.07630 (2024). [[Paper](https://arxiv.org/abs/2402.07630)][[Code](https://github.com/XiaoxinHe/G-Retriever/)]
3. Li, Zehan, et al. ”Towards general text embeddings with multi-stage contrastive learning.” arXiv preprint arXiv:2308.03281 (2023). [[Paper](https://arxiv.org/abs/2308.03281)][[Code](https://huggingface.co/thenlper/gte-base)]
4. Veliˇckovi´c, Petar, et al. ”Graph attention networks.” arXiv preprint arXiv:1710.10903 (2017). [[Paper](https://arxiv.org/abs/1710.10903)]
5. Wang, Yizhong, et al. ”Self-instruct: Aligning language models with self-generated instructions.” arXiv preprint arXiv:2212.10560 (2022) [[Paper](https://arxiv.org/abs/2212.10560)]
