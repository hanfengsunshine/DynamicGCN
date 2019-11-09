## DynamicGCN
Source code for paper "[Learning Dynamic Context Graphs for Predicting Social Events](https://dl.acm.org/citation.cfm?id=3330919 "Learning Dynamic Context Graphs for Predicting Social Events")".

### Datasets
- [ICEWS event data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/28075 "ICEWS event data") is available online.
- ICEWS news data has not been released publicly.

### Libraries
- **PyTorch >= 1.0**
- **sklearn**
- **pytorch_sparse** Refer to [the official website](https://github.com/rusty1s/pytorch_sparse "this page") to install.

### Docker Environment
- **start the container sad_morse**
- **yank the new dataset into DynamicGCN/data/NEW_DATA_FOLDER/** Pay attention to the naming convention.
- **put word embedding into DynamicGCN/data/**
- **modify train.py for the new dataset**
