# TP_Bert — Financial Phrase Classification

This repository contains a practical assignment (TP) that experiments with BERT-based models for sentiment classification on the FinancialPhraseBank dataset.

## Project structure
- `tp_bert.ipynb` — main Jupyter notebook for the TP (data preprocessing, model, training, evaluation).
- `FinancialPhraseBank-v1.0/` — dataset folder (includes `License.txt`, `README.txt`, and several `Sentences_*.txt` files).

## Dataset
The dataset is FinancialPhraseBank (v1.0). See `FinancialPhraseBank-v1.0/README.txt` and `FinancialPhraseBank-v1.0/License.txt` for license and citation information.


## Usage
1. Open the notebook `tp_bert.ipynb` in Google colab or VS Code.
2. Run the notebook cells in order. The notebook loads data from the `FinancialPhraseBank-v1.0/` folder.

## Notes
- If you prefer using a GPU, ensure `torch` is installed with CUDA support and the runtime provides a GPU.
- The notebook is self-contained; adapt model/learning-rate settings inside the notebook as needed for experiments.
