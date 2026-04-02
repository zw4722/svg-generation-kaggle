# svg-generation-kaggle
DL Spring 2026 Kaggle SVG Generation project using LoRA and Qwen2.5 code    Zekun Wang

Due to competition rules, the dataset is not included in this repository.

Please download the following files from Kaggle and place them in your working directory:

- train.csv  
- test.csv  

## Reproducibility

All experiments were conducted in Google Colab with an A100 GPU.
Random Seed: 42

### Steps to reproduce

1. Clone this repository or open the notebook in Google Colab.
2. Install required dependencies:
```bash
pip install -r requirements.txt
```


---

The notebook will:

- preprocess the dataset
- fine-tune the LoRA adapter
- save model weights
- generate SVG predictions for the test set
- export the final submission file

Final output: 
submission_final3.csv
