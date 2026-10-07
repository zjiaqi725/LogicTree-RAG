# LogicTree-RAG
Logic Tree-guided Retrieval-Augmented Generation for Long-form Patent Drafting

<p align="center">
<img src="https://github.com/zjiaqi725/LogicTree-RAG/blob/main/archv-overview.png" width="1000">  
</p>

In this work, we propose LogicTree-RAG, a logic tree-guided retrieval-augmented generation framework that induces a hierarchical logic tree as a global organizational backbone to organize and ground technical disclosures, without relying on expert-defined drafting priors. Each node in the logic tree represents a technical element and is constructed through evidence-guided recursive generation. A hybrid traversal mechanism then maps the logic tree into patent sections, enabling controllable and section-balanced generation.

To support transparency and reproducibility, we provide:
- A public demo illustrating the end-to-end workflow;
- Detailed algorithm descriptions and hyperparameter settings in the paper;
- Supplementary materials that document the core design choices.

Due to intellectual property constraints, the full implementation of LogicTree-RAG cannot be released at this time. We plan to release additional components of the codebase when permitted.

## 📝 Citation

```bibtex
@article{zhu2026logictree,
  title={LogicTree-RAG: Logic Tree-guided Retrieval-Augmented Generation for Long-form Patent Drafting},
  author={Zhu, Jiaqi and Xing, Naili and Pan, Hexiang and Gao, Haotian and Yin, Jianwei and Xiao, Xiaokui and Ooi, Beng Chin},
  journal={arXiv preprint arXiv:2609.30943},
  year={2026}
}
