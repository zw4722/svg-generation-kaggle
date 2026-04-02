# svg-generation-kaggle
DL Spring 2026 Kaggle SVG Generation project using LoRA and Qwen2.5 code    Zekun Wang

## Reproducibility

All experiments were conducted in Google Colab with an A100 GPU.

### Steps to reproduce

1. Clone this repository or open the notebook in Google Colab.
2. Install the required packages from `requirements.txt`.
3. Mount Google Drive.
4. Place the competition files in the correct directory:
   - `train.csv`
   - `test.csv`
   - `sample_submission.csv`
5. Update the data path in the notebook if needed:
   ```python
   base = "/content/drive/MyDrive/svg_competition"
