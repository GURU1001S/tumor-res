# VarDRP

VarDRP is a research-oriented machine learning project for predicting variant-specific drug responses with a heterogeneous graph neural network. It combines mutation profiles, drug chemistry, and multi-objective ranking to identify promising therapeutics while also explaining the evidence behind each prediction.

## Folder structure
- data/: raw and processed datasets for GDSC2, TCGA, and D3EGFRdb.
- src/: data loaders, model implementations, explainability utilities, training logic, and shared helpers.
- experiments/: YAML configs, runnable scripts, results, checkpoints, logs, and figures.
- notebooks/: exploratory and analysis notebooks for graph inspection and model interpretation.
- paper/: publication figures, tables, and project notes.
- tests/: unit tests for graph construction, models, and metrics.

## Setup
Install the project dependencies with:

```bash
pip install -r requirements.txt
```
