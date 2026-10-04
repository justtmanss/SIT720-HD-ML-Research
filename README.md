# SIT720 HD Machine Learning Research

## Paper
An efficient stacking-based ensemble technique for early heart attack prediction.

## Dataset
Heart disease dataset used for reproduction.

## How to run
1. Install Python 3.10+
2. Install dependencies:
   pip install -r requirements.txt
3. Open HD_SIT720.ipynb in Google Colab or Jupyter.
4. Run all cells from top to bottom.

## Experiments
Part 1 reproduces the models from the selected paper.

Part 2 evaluates:
- Baseline
- Ablation with feature engineering
- Proposed tuned OOF stacking model

The experiments use repeated stratified cross-validation on the deduplicated dataset.

## Results
The notebook automatically generates the result CSV files and figures in the results/ directory.
