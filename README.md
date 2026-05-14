# XAI-GNN for Heart Disease Prediction

This repository contains a graph neural network (GNN) approach for predicting heart disease using clinical patient features.

## Project Contents

- `GNN_Medical_Prediction.ipynb` - Main notebook with preprocessing, graph construction, model definition, training, and evaluation.
- `benchmark.xlsx` - Dataset used for training and testing the model.
- `requirements.txt` - Python dependencies required to run the notebook.

## Usage

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `GNN_Medical_Prediction.ipynb` in Jupyter or VS Code.
3. Run the notebook cells in order.

## Notes

- Graphs are constructed from feature correlations.
- The model trains on patient graphs and evaluates classification performance.
- The notebook currently uses `torch_geometric` and PyTorch for model implementation.

## License

This repository does not include a license file. Add one if required for sharing or reuse.
