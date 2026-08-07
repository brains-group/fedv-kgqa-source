# FedV-KGQA: Vertical Federated Learning for Knowledge Graph Question Answering

This repository contains the source code for the vertical federated knowledge graph question answering experiments.

## Repository Structure

```text
anonymous-kgqa-source-code/
├── 2-hop-experiments/
├── 3-hop-experiments/
├── ablation-study/
├── baseline-comparison/
├── robustness-experiments/
└── README.md
```

## Dataset

The datasets are provided separately due to file-size constraints:

https://drive.google.com/drive/folders/1Jqmu5D9SBdFNt4q4NrM51bplTHTUf4Xd?usp=sharing

After downloading, place the datasets according to the instructions in the corresponding experiment folder.

## How to Run

Each experiment folder contains a file named `run.tex`.

The `run.tex` file explains how to run that specific experiment, including the required commands, input files, and expected outputs.

Before running any experiment, open the relevant `run.tex` file and follow its instructions.

## Experiment Groups

- `2-hop-experiments/`: 2-hop KGQA experiments.
- `3-hop-experiments/`: 3-hop KGQA experiments.
- `ablation-study/`: component ablation experiments.
- `baseline-comparison/`: adapted baseline experiments.
- `robustness-experiments/`: robustness experiments.

## Note

This repository is prepared for anonymous review. The interactive demo and model checkpoint instructions are provided separately in the anonymized demo repository.

## Citation

If you use this source code in your research, please cite the following paper:

```bibtex
@inproceedings{khan2026FedVKGQA,
    author = {Md Saikat Islam Khan Bappy and Oshani Seneviratne},
    title = {{FedV-KGQA: Multi-Hop Question Answering over Vertically Partitioned Knowledge Graphs}},
    year = {2026},
    booktitle = {Proceedings of the International Semantic Web Conference (ISWC)},
}
```

