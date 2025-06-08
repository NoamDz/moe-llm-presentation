# Mixture-of-Experts LLM Presentation

This repository accompanies a presentation on the usage of Mixture of Experts (MoE) techniques for large language models. It includes slides, illustrative figures and example code for experimenting with MoE layers.

## Contents

- **presentation.ipynb** – Jupyter notebook that outlines the concepts behind MoE, covering both Switch Transformers and PEER (Parameter Efficient Expert Retrieval).
- **peer_main** – minimal implementation of PEER training on the WikiText‑103 dataset, along with example loss plots.
- **plots** and **switch_plots** – figures used in the presentation.
- Various PNG images referenced from the notebook.

## Quick Start

To experiment with the PEER implementation:

```bash
cd peer_main
python main.py
```

By default the script downloads a subset of WikiText‑103 and trains a small PEER language model. See `peer_main/README.md` for details and citations.

## License

This material is provided for educational purposes and does not include pretrained models.
